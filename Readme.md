# EXPLORE-NFC-WW ELEMENT 14
## Enable Spi on your RBP 3
1. Open Terminal
2. Interfacing options (5)
3. SPI (P4)
4. Enable
5. Reboot your pi

## Download Cmake
1. Open terminal
2. `sudo apt-get update && sudo apt-get install cmake`

## Drivers - Docs - example project can be found on the NXP website
nxp-website: https://www.nxp.com/products/identification-and-security/nfc/nfc-reader-ics/explore-nfc-exclusive-from-element14:PNEV512R 
(Make sure to create an account to get access to the software)

## We will use nxppy
1. navigate to the nxppy github page: https://github.com/svvitale/nxppy
2. Follow the installation process over there

### Possible errors
1. Can't find module when trying to import in your python file: find the 'setup.py' file in source and run `sudo python setup.py build install`
2. module 'nxppy' has no attribute 'mifire': run `pip install nxppy` in your folder where your python file is (the one you are working on)

