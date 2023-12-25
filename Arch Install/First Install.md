1. check the Wi-fi connection:

~~~
$ rfkill

$ rfkill unblock wifi

$ iwctl
~~~

2. go into the iwd then setup network:

~~~
[iwd] station wlan0 scan

[iwd] station get-networks

[iwd] station wlan0 show

[iwd] exit
~~~

3. check the disk arrangement:

~~~
$ fdisk -l

$ fdisk /dev/ <your chosen partition>


~~~