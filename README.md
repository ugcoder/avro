# Avro phonetic for Linux
Avro phonetic implementation for Linux in IBus.

# Installation & Usage

### *Ubuntu 16.04 (32/64-bit)*

 1. Please run these commands from the terminal. Never forget to be in relevant directory.
	```
	# Install GDebi, a helper tool for installing .deb files directly.
	sudo apt-get install gdebi
	```
	```
	wget "https://github.com/maateen/avro/releases/download/v2.0/avro_2.0-1_all.deb"
	```
	```
	sudo gdebi avro_2.0-1_all.deb
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
