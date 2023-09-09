
<h1>Installing open office in Ubuntu </h1>

<h3>First uninstall libre office using the following command:</h3> 
<b>sudo apt remove libreoffice-base-core libreoffice-impress libreoffice-calc libreoffice-math libreoffice-common libreoffice-ogltrans libreoffice-core libreoffice-pdfimport libreoffice-draw libreoffice-style-breeze libreoffice-gnome libreoffice-style-colibre libreoffice-gtk3 libreoffice-style-elementary libreoffice-help-common libreoffice-style-tango libreoffice-help-en-us libreoffice-writer</b>

<h3>Then Download Apache OpenOffice from this link:</h3>
https://www.openoffice.org/download/index.html

<h3>Note:</h3> 
1. The format should be "Linux 64 bit (x86-64) (DEB)" for a 64 bit Ubuntu system  
2. You can also check the important hints link to know more: https://www.openoffice.org/download/platform_hints.html  

<h3>Setting Up Open-Office</h3>
1. Open terminal  
2. Type cd Downloads  
3. Type tar -xvf Apache_OpenOffice_4.1.14_Linux_x86-64_install-deb_en-GB.tar.gz  
   It will Extract the files.  
4. Type cd en-GB/DEBS/  
5. Type sudo dpkg -i *.deb  
   It will install the Packages on the system  
6. Desktop integration:  
    Type cd desktop-integration/  
    Type sudo dpkg -i *.deb  
    It installs the icons of open office
