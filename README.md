# Installation

sudo dpkg -i libopenni2-0_2.2.0.33+dfsg-4_<ARCH>.deb
sudo dpkg -i libopenni2-dev_2.2.0.33+dfsg-4_<ARCH>.deb

#Read resolution from config file [option]

Default resolution for depth and color is 640x480, 
percipio openni2 will read resolution from Percipio.ini if /etc/openni2/Percipio.ini exist,
example config file located in root directory of this sdk.

# Note
Percipio openni2 depends on camport2, so you should correctly install camport2 before above commands.


