# PlymouthTheme-Cat
This is a Plymouth theme created for Ubuntu 16.04 (can be also used in other Linux Distributions).

# Installation
    cd /usr/share/plymouth/themes/

Clone this repository.

    git clone https://github.com/krishnan793/PlymouthTheme-Cat.git
    
Install the theme.

    sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/lib/plymouth/themes/PlymouthTheme-Cat/eionix-cat.plymouth 100

Select the default theme.

    sudo update-alternatives --config default.plymouth

Update the initramfs image.

    sudo update-initramfs -u

Now reboot.

If you want to install this on < Ubuntu 16.04, change the path from /usr/share/plymouth to /lib/plymouth/ . You need to do this on the eionix-cat.plymouth file also.
