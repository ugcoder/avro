# Avro phonetic for Linux
Avro phonetic implementation for Linux in IBus.

# Installation & Usage

### *Ubuntu 14.04, 16.04, 16.10, 17.04, 17.10 (32/64-bit)*

 1. Please run these commands from the terminal. Never forget to be in relevant directory.
	```
	sudo apt install gjs gir1.2-ibus-1.0 libibus-1.0-5 libibus-1.0-dev ibus-gtk ibus-gtk3 ibus-clutter ibus-qt4 ibus
	```
	```
	wget "https://github.com/maateen/avro/releases/download/v2.1/avro_2.1-3_all.deb"
	```
	```
	sudo dpkg -i avro_2.1-3_all.deb
	```
	I hope, all is well now and the installation has been finished.

 2. Go to `System Settings -> Language Support` from _Unity Launcher_
 3. Look at the `Keyboard input method system`  
 4. Select __IBus__ and close the window.
 5. I believe that you need to restart __IBus__ to make everything work fine. Try the following command:
	```
	ibus restart
	```

 6. Now go to `System Settings -> Keyboard -> Text Entry`.
 7. Search and add __Avro Phonetic__ as input source. That's all.

## Contributors
 
__IBus Engine__ by __Sarim Khan__ <sarim2005@gmail.com>

[__Avro JavaScript Phonetic Library__](https://github.com/torifat/jsAvroPhonetic) by [__Rifat Nabi__](https://github.com/torifat)

__Avro Phonetic Dictionary Search Library__ by [__Mehdi Hasan Khan__](https://github.com/omicronlab)

__Ubuntu 16.04 LTS (multi-arch) Binary Package__ by [__Maksudur Rahman Maateen__](https://github.com/maateen)

_Licensed under Mozilla Public License 1.1 ("MPL"), an open source/free software license._
