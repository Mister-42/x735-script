# x735-script
This is the safe shutdown script for x735;

NOTE:

We tested this shell script with the official Raspbian '2019-09-26-raspbian-buster-lite.img' image.

How to use?

* step 1:
> wget https://raw.githubusercontent.com/Thoulah/x735-script/master/x735.sh

> chmod +x x735.sh

> sudo bash x735.sh

* step 2:

> printf "%s\\n" "alias x735off='sudo /usr/local/sbin/x735shutdown.sh'" >> ~/.bashrc

* step 3:
> sudo reboot
