bsd-fastboot
------------

collection aims to enhance the boot performance of FreeBSD by applying various patches that reduce startup time.

1. reduce boot delay

  add this line to `/boot/loader.conf`

  `autoboot_delay="0"`
  `boot_mute=YES`

2. silent start messages

  add this line to `/etc/rc.conf`

  `rc_startmsgs=NO`


