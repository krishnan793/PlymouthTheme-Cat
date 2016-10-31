# PlymouthTheme-Cat
This is a Plymouth theme created for Ubuntu 16.04 (can be also used in other Linux Distributions).

[![Video](https://4.bp.blogspot.com/-gG0MBGjEE9M/WBYXrOGrVGI/AAAAAAAABVE/auGpLRYf7jor4hu3jurYGcjaVBapHyAVACLcB/s320/8998adc40112985a8f29cf414925d390.gif)](https://www.youtube.com/watch?v=c6f478VBhtE)


[Video] https://www.youtube.com/watch?v=c6f478VBhtE

[Blog] http://eionix.blogspot.in/2016/10/plymouth-theme-for-ubuntu.html

# Installation

    cd /usr/share/plymouth/themes/

Clone this repository.

    sudo git clone https://github.com/krishnan793/PlymouthTheme-Cat.git
    
Install the theme.

    sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/PlymouthTheme-Cat/eionix-cat.plymouth 100

Select the default theme.

    sudo update-alternatives --config default.plymouth

Update the initramfs image.

    sudo update-initramfs -u

Now reboot.

If you want to install this on < Ubuntu 16.04, change the path from /usr/share/plymouth to /lib/plymouth/ . You need to do this on the eionix-cat.plymouth file also.
