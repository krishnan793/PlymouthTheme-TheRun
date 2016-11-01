# PlymouthTheme-TheRun
This is a Plymouth theme created that can be used in Linux Distributions. Credits to Joel Roset for the FX animation.

[![Video](https://github.com/krishnan793/PlymouthTheme-TheRun/blob/master/images/PlymouthTheme-TheRun.gif?raw=true)](https://youtu.be/yNW1hTyDe5U)


[Video] https://youtu.be/yNW1hTyDe5U

[Blog] http://eionix.blogspot.in/2016/11/this-is-another-theme-i-created-for.html

# Installation

    cd /usr/share/plymouth/themes/

Clone this repository.

    sudo git clone https://github.com/krishnan793/PlymouthTheme-TheRun.git
    
Install the theme.

    sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/PlymouthTheme-TheRun/PlymouthTheme-TheRun.plymouth 100

Select the default theme.

    sudo update-alternatives --config default.plymouth

Update the initramfs image.

    sudo update-initramfs -u

Now reboot.

If you want to install this on < Ubuntu 16.04, change the path from /usr/share/plymouth to /lib/plymouth/ . You need to do this on the eionix-cat.plymouth file also.
