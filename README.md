@@ -4,12 +4,12 @@

- this modified version of udpxy with secured status page, you can now enter status page both ways, only from specific IP or from everywhere. defined by enviroment variable UDPXY_MNGIP

# install instructions as root (if not, use sudo):
- apt-get install build-essentials
# install instructions:
- sudo apt-get install build-essentials
- git clone https://github.com/astrit/udpxy-1.0.23-9.git
- cd udpxy-1.0.23-9
- make
- make install
- sudo make install

# usage example:
##### udpxy help usage
