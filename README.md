# VMWare-BigSur
VMWare .vmx file, ready to install Mac OSX Big Sur. tested on VMWare workstation 16.1.1 on a Core i7 Linux host

Installing Mac OSX in VMWare often ends up with a freezed progress bar below the apple logo usually after the second reboot for completion of installation. I tried evey setting and recommendation on the Web but no luck. Beside i had a working machine that was installed in older versions of VMWare that was upgraded to latest VMWare. so copied that working machine's .vmx file and used it to make a new machine and voila... it worked.

Assuming you have a Big Sur installation bootable iso file.
From VMWare home, open a virtual machine, select this .vmx file. edit the machine and add a CD drive and a HDD by recomended settings. boot up by the iso file and continue regular installation.
