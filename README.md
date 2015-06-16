# arduino-hello-world
this repository is more a reminder of the compilation process

# installation on debian based distributions

sudo apt-get install arduino arduino-mk
cd MY_PROJECT
echo -e "BOARD_TAG = uno\nARDUINO_LIBS = \ninclude /usr/share/arduino/Arduino.mk" > Makefile
make && make upload
