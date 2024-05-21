Обновление ядра ubuntu на версию 6.2

vagrant@kernel-update:~$ history
    1  mkdir downloads
    2  cd downloads/
    3  wget https://kernel.ubuntu.com/mainline/v6.2/amd64/linux-headers-6.2.0-060200-generic_6.2.0-060200.202302191831_amd64.deb https://kernel.ubuntu.com/mainline/v6.2/amd64/linux-headers-6.2.0-060200_6.2.0-060200.202302191831_all.deb https://kernel.ubuntu.com/mainline/v6.2/amd64/linux-image-unsigned-6.2.0-060200-generic_6.2.0-060200.202302191831_amd64.deb https://kernel.ubuntu.com/mainline/v6.2/amd64/linux-modules-6.2.0-060200-generic_6.2.0-060200.202302191831_amd64.deb
    4  dpkg -i linux-headers* linux-image* linux-modules*
    5  sudo dpkg -i linux-headers* linux-image* linux-modules*
    6  uname -r
    7  vagrant reload
    8  sudo shutdown now
    9  uname -r
   10  history
vagrant@kernel-update:~$
