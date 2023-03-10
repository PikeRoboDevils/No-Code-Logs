# Command Outputs

### `ls -la /home/lvuser`

```lvuser@roborio-1018-FRC:~$ ls -la /home/lvuser
total 10364
drwxrwsr-x    6 lvuser   ni           12288 Dec 14 19:42 ./
drwxr-xr-x    5 admin    administ      4096 Dec 21 13:38 ../
-rw-r--r--    1 lvuser   ni             389 Sep 29 02:50 .bashrc
-rw-r--r--    1 lvuser   ni             241 Sep 29 02:50 .profile
-rwxr-xr-x    1 lvuser   ni         5432212 Mar  5 14:02 FRC-2023-Software.jar*
-rw-r--r--    1 lvuser   ni         2237000 Mar  8 19:56 FRC_20230309_004936.wpilog
-rw-r--r--    1 lvuser   ni         2278181 Mar  8 20:03 FRC_20230309_005748.wpilog
-rw-r--r--    1 lvuser   ni           82761 Dec 14 19:43 FRC_TBD_bcc0c6daea157976.wpilog
lrwxrwxrwx    1 lvuser   ni              42 Dec 21 13:38 FRC_UserProgram.log -> /var/local/natinst/log/FRC_UserProgram.log
lrwxrwxrwx    1 admin    ni              22 Jul  1  2021 README_File_Paths.txt -> /README_File_Paths.txt
drwxrwxrwx    2 lvuser   ni            4096 Mar  5 14:02 deploy/
drwxr-xr-x    4 lvuser   ni            4096 Dec 21 13:38 frc/
---x--x--x    1 lvuser   ni          506888 Feb 28 21:46 frcUserProgram*
drwxrwsr-x    2 lvuser   ni            4096 Dec 14 19:09 frc_install/
drwxrwxr-x    4 lvuser   ni            4096 Dec 21 13:38 natinst/
-rw-r--r--    1 lvuser   ni               3 Feb 25 20:02 networktables.json
-rwxr-xr-x    1 lvuser   ni             234 Mar  5 14:02 robotCommand*
```

### `ps -a`

```
lvuser@roborio-1018-FRC:~$ ps -a
PID   USER     TIME   COMMAND
    1 admin      0:00 init [5]
    2 admin      0:00 [kthreadd]
    4 admin      0:00 [kworker/0:0H]
    6 admin      0:00 [kswork]
    7 admin      0:00 [mm_percpu_wq]
    8 admin      0:03 [ksoftirqd/0]
    9 admin      0:01 [ktimersoftd/0]
   10 admin      0:00 [rcu_preempt]
   11 admin      0:00 [rcu_sched]
   12 admin      0:00 [rcuop/0]
   13 admin      0:00 [rcuos/0]
   14 admin      0:00 [rcub/0]
   15 admin      0:00 [rcuc/0]
   16 admin      0:00 [kswork]
   17 admin      0:00 [posixcputmr/0]
   18 admin      0:00 [migration/0]
   19 admin      0:00 [cpuhp/0]
   20 admin      0:00 [cpuhp/1]
   21 admin      0:00 [migration/1]
   22 admin      0:00 [posixcputmr/1]
   23 admin      0:00 [rcuc/1]
   24 admin      0:01 [ktimersoftd/1]
   25 admin      0:03 [ksoftirqd/1]
   27 admin      0:00 [kworker/1:0H]
   28 admin      0:00 [rcuop/1]
   29 admin      0:00 [rcuos/1]
   30 admin      0:00 [kdevtmpfs]
   31 admin      0:00 [kworker/0:1]
   32 admin      0:00 [oom_reaper]
   33 admin      0:00 [writeback]
   34 admin      0:00 [crypto]
   35 admin      0:00 [kblockd]
   36 admin      0:00 [kauditd]
   37 admin      0:00 [kswapd0]
   38 admin      0:00 [cifsiod]
   39 admin      0:00 [cifsoplockd]
   68 admin      0:00 [irq/45-f8003000]
   69 admin      0:00 [irq/46-f8003000]
   70 admin      0:00 [irq/47-f8003000]
   71 admin      0:00 [irq/48-f8003000]
   72 admin      0:00 [irq/49-f8003000]
   73 admin      0:00 [irq/72-f8003000]
   74 admin      0:00 [irq/73-f8003000]
   75 admin      0:00 [irq/74-f8003000]
   76 admin      0:00 [irq/75-f8003000]
   77 admin      0:00 [kworker/1:1]
   78 admin      0:00 [irq/58-e0006000]
   79 admin      0:00 [spi0]
   80 admin      0:00 [irq/81-e0007000]
   81 admin      0:00 [spi1]
   84 admin      0:00 [irq/64-e000b000]
   85 admin      0:00 [irq/57-cdns-i2c]
   86 admin      0:00 [irq/96-niwatchd]
   87 admin      0:00 [irq/80-cdns-i2c]
   88 admin      0:00 [irq/65-81000000]
   89 admin      0:00 [irq/79-mmc0]
   90 admin      0:00 [irq/79-s-mmc0]
   91 admin      0:00 [mmcqd/0]
   92 admin      0:00 [kworker/1:1H]
   93 admin      0:00 [jbd2/mmcblk0p3-]
   94 admin      0:00 [ext4-rsv-conver]
  101 admin      0:00 [jbd2/mmcblk0p1-]
  102 admin      0:00 [ext4-rsv-conver]
  103 admin      0:00 [kworker/0:1H]
  104 admin      0:00 [jbd2/mmcblk0p2-]
  105 admin      0:00 [ext4-rsv-conver]
  115 admin      0:01 /usr/sbin/jitterentropy-rngd
  193 admin      0:00 /sbin/udevd -d
  214 admin      0:00 [kworker/1:2]
  215 admin      0:00 [irq/53-e0002000]
  217 admin      0:00 [ci_otg]
  219 admin      0:01 [irq/76-e0003000]
  469 admin      0:00 [nibds]
  470 admin      0:00 [nibds]
  471 admin      0:00 [nibds]
  472 admin      0:00 [nibds]
  473 admin      0:00 [nibds]
  474 admin      0:00 [irq/61-atomiczy]
  485 admin      0:00 [cfg80211]
  599 admin      0:00 /usr/sbin/rtctld
  787 admin      0:00 {ifplugd} /bin/busybox.nosuid /usr/sbin/ifplugd -i usb0 -fI -u0 -d0 -a -m auto -M -l
  793 messageb   0:00 /usr/bin/dbus-daemon --system
  820 admin      0:00 {ifplugd} /bin/busybox.nosuid /usr/sbin/ifplugd -i eth0 -fI -u0 -d0 -a -m auto -M -l
  853 admin      0:07 [irq/54-eth0]
 1059 admin      0:00 /usr/local/natinst/share/NIAuth/niauth_daemon -start -timeout 30
 1135 admin      0:00 [ipv6_addrconf]
 1137 admin      0:00 sshd: /usr/sbin/sshd [listener] 0 of 10-100 startups
 1143 admin      0:00 /usr/sbin/syslog-ng --process-mode=background
 1148 admin      0:00 lldpd: monitor.
 1151 lldpd      0:00 lldpd: no neighbor.
 1171 admin      0:00 {nipalps} /bin/bash /usr/sbin/nipalps /dev/nipalk /var/lib/nipal/nipalps.bin
 1174 admin      0:00 {cat} /bin/busybox.nosuid /bin/cat /dev/nipalk
 1182 lvuser     0:00 /usr/bin/nirioserver
 1194 avahi      0:00 avahi-daemon: running [roborio-1018-FRC.local]
 1195 avahi      0:00 avahi-daemon: chroot helper
 1205 webserv    0:00 {NI WSD Watchdog} /usr/local/natinst/share/NIWebServer/SystemWebServer -timeout 50 -child-timeout 20 -system
 1206 webserv    0:00 /usr/local/natinst/share/NIWebServer/SystemWebServer -timeout 50 -child-timeout 20 -system
 1215 webserv    0:00 NIWebServiceContainer {87447B86-7CDA-11ED-B01E-00802F33C793} 11
 1229 admin      0:00 /usr/local/natinst/bin/nirtmdnsd
 1237 webserv    0:00 NIWebServiceContainer {875E8613-7CDA-11ED-B01E-00802F33C793} 11
 1250 webserv    0:00 NIWebServiceContainer {87814DB4-7CDA-11ED-B01E-00802F33C793} 11
 1257 webserv    0:00 NIWebServiceContainer {87A5B325-7CDA-11ED-B01E-00802F33C793} 11
 1264 webserv    0:00 NIWebServiceContainer {87AF833C-7CDA-11ED-B01E-00802F33C793} 11
 1271 webserv    0:00 NIWebServiceContainer {87BF5F8F-7CDA-11ED-B01E-00802F33C793} 11
 1317 admin      0:00 /usr/sbin/vsftpd
 1335 admin      0:00 {S88FRCNetComm} /bin/sh /etc/rc5.d/S88FRCNetComm start
 1336 admin      0:00 /bin/su - -- lvuser -l -c /usr/local/frc/bin/FRC_NetCommDaemon
 1343 lvuser     0:14 /usr/local/frc/bin/FRC_NetCommDaemon
 1346 admin      0:00 /usr/sbin/crond
 1373 admin      0:00 /sbin/getty 38400 tty2
 1374 admin      0:00 /sbin/getty 38400 tty1
 1506 admin      0:00 {udhcpc} /bin/busybox.nosuid /sbin/udhcpc -a -b -x hostname:roborio-1018-FRC -i eth0 -r 10.10.18.2 -s /etc/natinst/networking/udhcpc.script -p /var/run/udhc
 1854 admin      0:00 {udhcpc} /bin/busybox.nosuid /sbin/udhcpc -a -b -x hostname:roborio-1018-FRC -i usb0 -r 172.22.11.2 -s /etc/natinst/networking/udhcpc.script -p /var/run/udh
 1892 admin      0:00 sshd: lvuser [priv]
 1896 lvuser     0:01 sshd: lvuser@pts/0
 1897 lvuser     0:00 -sh
 1918 admin      0:00 [kworker/u4:2]
 2081 admin      0:00 [kworker/u4:0]
 2155 admin      0:00 [kworker/0:2]
 2922 admin      0:00 [kworker/u4:1]
 2947 lvuser     0:00 {ps} /bin/busybox.nosuid /bin/ps -a
```

### Checking nirtcfg YouOnlyLiveOnce

```
lvuser@roborio-1018-FRC:~$ /usr/local/natinst/bin/nirtcfg  -g section=Startup,token=YouOnlyLiveTwice
FALSE
```
