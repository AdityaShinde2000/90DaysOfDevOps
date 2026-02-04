ubuntu@ip-172-31-34-254:~$ ps aux 
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  3.2  1.4  22632 13832 ?        Ss   19:56   0:01 /sbin/init
root           2  0.0  0.0      0     0 ?        S    19:56   0:00 [kthreadd]
root           3  0.0  0.0      0     0 ?        S    19:56   0:00 [pool_workqueue_release]
root           4  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-rcu_gp]
root           5  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-sync_wq]
root           6  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-kvfree_rcu_reclaim]
root           7  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-slub_flushwq]
root           8  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-netns]
root           9  0.0  0.0      0     0 ?        I    19:56   0:00 [kworker/0:0-rcu_gp]
root          10  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/0:0H-events_highpri]
root          11  0.0  0.0      0     0 ?        I    19:56   0:00 [kworker/0:1-events]
root          12  0.1  0.0      0     0 ?        I    19:56   0:00 [kworker/u8:0-flush-259:0]
root          13  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-mm_percpu_wq]
root          14  0.0  0.0      0     0 ?        I    19:56   0:00 [rcu_tasks_rude_kthread]
root          15  0.0  0.0      0     0 ?        I    19:56   0:00 [rcu_tasks_trace_kthread]
root          16  0.0  0.0      0     0 ?        S    19:56   0:00 [ksoftirqd/0]
root          17  0.0  0.0      0     0 ?        I    19:56   0:00 [rcu_sched]
root          18  0.0  0.0      0     0 ?        S    19:56   0:00 [rcu_exp_par_gp_kthread_worker/0]
root          19  0.0  0.0      0     0 ?        S    19:56   0:00 [rcu_exp_gp_kthread_worker]
root          20  0.0  0.0      0     0 ?        S    19:56   0:00 [migration/0]
root          21  0.0  0.0      0     0 ?        S    19:56   0:00 [idle_inject/0]
root          22  0.0  0.0      0     0 ?        S    19:56   0:00 [cpuhp/0]
root          23  0.0  0.0      0     0 ?        S    19:56   0:00 [cpuhp/1]
root          24  0.0  0.0      0     0 ?        S    19:56   0:00 [idle_inject/1]
root          25  0.1  0.0      0     0 ?        S    19:56   0:00 [migration/1]
root          26  0.0  0.0      0     0 ?        S    19:56   0:00 [ksoftirqd/1]
root          27  0.0  0.0      0     0 ?        I    19:56   0:00 [kworker/1:0-events]
root          28  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/1:0H-events_highpri]
root          29  0.0  0.0      0     0 ?        S    19:56   0:00 [kdevtmpfs]
root          30  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-inet_frag_wq]
root          31  0.0  0.0      0     0 ?        S    19:56   0:00 [kauditd]
root          32  0.0  0.0      0     0 ?        S    19:56   0:00 [khungtaskd]
root          33  0.0  0.0      0     0 ?        I    19:56   0:00 [kworker/u8:1-flush-259:0]
root          34  0.0  0.0      0     0 ?        S    19:56   0:00 [oom_reaper]
root          35  0.0  0.0      0     0 ?        I    19:56   0:00 [kworker/u8:2-kvfree_rcu_reclaim]
root          36  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-writeback]
root          37  0.0  0.0      0     0 ?        S    19:56   0:00 [kcompactd0]
root          38  0.0  0.0      0     0 ?        SN   19:56   0:00 [ksmd]
root          39  0.0  0.0      0     0 ?        SN   19:56   0:00 [khugepaged]
root          40  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-kintegrityd]
root          41  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-kblockd]
root          42  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-blkcg_punt_bio]
root          43  0.0  0.0      0     0 ?        S    19:56   0:00 [irq/9-acpi]
root          44  0.0  0.0      0     0 ?        I    19:56   0:00 [kworker/1:1-events]
root          45  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-tpm_dev_wq]
root          46  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-ata_sff]
root          47  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-md]
root          48  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-md_bitmap]
root          49  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-edac-poller]
root          50  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-devfreq_wq]
root          51  0.0  0.0      0     0 ?        S    19:56   0:00 [watchdogd]
root          52  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/1:1H-kblockd]
root          53  0.0  0.0      0     0 ?        S    19:56   0:00 [kswapd0]
root          54  0.0  0.0      0     0 ?        S    19:56   0:00 [ecryptfs-kthread]
root          55  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-kthrotld]
root          56  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-acpi_thermal_pm]
root          57  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-nvme-wq]
root          58  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-nvme-reset-wq]
root          59  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-nvme-delete-wq]
root          60  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-nvme-auth-wq]
root          61  0.0  0.0      0     0 ?        I    19:56   0:00 [kworker/0:2-cgroup_destroy]
root          62  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-mld]
root          63  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-ipv6_addrconf]
root          70  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-kstrp]
root          72  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/u9:0]
root          85  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-charger_manager]
root          86  0.0  0.0      0     0 ?        S    19:56   0:00 [jbd2/nvme0n1p1-8]
root          87  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-ext4-rsv-conversion]
root          88  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/0:1H-kblockd]
root          89  0.0  0.0      0     0 ?        I    19:56   0:00 [kworker/1:2-cgroup_destroy]
root         128  0.4  1.4  42304 14008 ?        S<s  19:56   0:00 /usr/lib/systemd/systemd-journald
root         162  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-kmpathd]
root         163  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-kmpath_handlerd]
root         180  0.0  0.0      0     0 ?        I    19:56   0:00 [kworker/u8:3-events_unbound]
root         183  0.0  0.0      0     0 ?        I    19:56   0:00 [kworker/1:3]
root         184  0.0  0.0      0     0 ?        I    19:56   0:00 [kworker/1:4-events]
root         188  0.0  2.9 288952 27292 ?        SLsl 19:56   0:00 /sbin/multipathd -d -s
root         199  0.4  0.8  26480  8388 ?        Ss   19:56   0:00 /usr/lib/systemd/systemd-udevd
root         213  0.0  0.0      0     0 ?        S    19:56   0:00 [psimon]
root         236  0.0  0.0      0     0 ?        I    19:56   0:00 [kworker/u8:4-ext4-rsv-conversion]
root         253  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-cryptd]
root         255  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-ena]
root         264  0.0  0.0      0     0 ?        I    19:56   0:00 [kworker/0:3-events]
root         289  0.0  0.0      0     0 ?        S    19:56   0:00 [jbd2/nvme0n1p16-8]
root         290  0.0  0.0      0     0 ?        I<   19:56   0:00 [kworker/R-ext4-rsv-conversion]
systemd+     328  0.2  1.3  21592 13044 ?        Ss   19:56   0:00 /usr/lib/systemd/systemd-resolved
systemd+     531  0.0  1.0  22408  9828 ?        Ss   19:56   0:00 /usr/lib/systemd/systemd-networkd
root         593  0.0  0.2   2720  2008 ?        Ss   19:56   0:00 /usr/sbin/acpid
root         597  0.0  0.3   7224  2816 ?        Ss   19:56   0:00 /usr/sbin/cron -f -P
message+     598  0.2  0.6   9804  5628 ?        Ss   19:56   0:00 @dbus-daemon --system --address=systemd: --nofork --nopidfile --systemd
root         603  0.0  0.4  82920  4644 ?        Ssl  19:56   0:00 /usr/sbin/irqbalance
root         606  0.1  2.2  32416 20796 ?        Ss   19:56   0:00 /usr/bin/python3 /usr/bin/networkd-dispatcher --run-startup-triggers
polkitd      607  0.1  1.0 383704 10024 ?        Ssl  19:56   0:00 /usr/lib/polkit-1/polkitd --no-debug
root         613  1.1  4.2 1922672 39332 ?       Ssl  19:56   0:00 /usr/lib/snapd/snapd
root         615  0.1  0.9  17988  8880 ?        Ss   19:56   0:00 /usr/lib/systemd/systemd-logind
root         617  0.1  1.4 468996 13680 ?        Ssl  19:56   0:00 /usr/libexec/udisks2/udisksd
root         693  0.0  0.2   6148  2220 ttyS0    Ss+  19:56   0:00 /sbin/agetty -o -p -- \u --keep-baud 115200,57600,38400,9600 - vt220
top - 19:57:49 up 1 min,  1 user,  load average: 0.04, 0.02, 0.00
Tasks: 114 total,   1 running, 113 sleeping,   0 stopped,   0 zombie
%Cpu(s):  0.0 us,  0.0 sy,  0.0 ni,100.0 id,  0.0 wa,  0.0 hi,  0.0 si,  0.0 st 
MiB Mem :    914.2 total,    329.9 free,    374.2 used,    368.1 buff/cache     
MiB Swap:      0.0 total,      0.0 free,      0.0 used.    540.0 avail Mem 

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                                                            
      1 root      20   0   22632  13832   9648 S   0.0   1.5   0:01.63 systemd                                                            
      2 root      20   0       0      0      0 S   0.0   0.0   0:00.00 kthreadd                                                           
      3 root      20   0       0      0      0 S   0.0   0.0   0:00.00 pool_workqueue_release                                             
      4 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-rcu_gp                                                   
      5 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-sync_wq                                                  
      6 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-kvfree_rcu_reclaim                                       
      7 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-slub_flushwq                                             
      8 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-netns                                                    
      9 root      20   0       0      0      0 I   0.0   0.0   0:00.00 kworker/0:0-rcu_gp                                                 
     10 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/0:0H-events_highpri                                        
     11 root      20   0       0      0      0 I   0.0   0.0   0:00.03 kworker/0:1-events                                                 
     12 root      20   0       0      0      0 I   0.0   0.0   0:00.07 kworker/u8:0-events_power_efficient   


ubuntu@ip-172-31-34-254:~$ systemctl list-units --type=service
  UNIT                                           LOAD   ACTIVE SUB     DESCRIPTION                                                       >
  acpid.service                                  loaded active running ACPI event daemon
  apparmor.service                               loaded active exited  Load AppArmor profiles
  apport.service                                 loaded active exited  automatic crash report generation
  blk-availability.service                       loaded active exited  Availability of block devices
  chrony.service                                 loaded active running chrony, an NTP client/server
  cloud-config.service                           loaded active exited  Cloud-init: Config Stage
  cloud-final.service                            loaded active exited  Cloud-init: Final Stage
  cloud-init-local.service                       loaded active exited  Cloud-init: Local Stage (pre-network)
  cloud-init.service                             loaded active exited  Cloud-init: Network Stage
  console-setup.service                          loaded active exited  Set console font and keymap
  cron.service                                   loaded active running Regular background program processing daemon
  dbus.service                                   loaded active running D-Bus System Message Bus
  finalrd.service                                loaded active exited  Create final runtime dir for shutdown pivot root
  getty@tty1.service                             loaded active running Getty on tty1
  irqbalance.service                             loaded active running irqbalance daemon
  keyboard-setup.service                         loaded active exited  Set the console keyboard layout
  kmod-static-nodes.service                      loaded active exited  Create List of Static Device Nodes
lines 1-18

ubuntu@ip-172-31-34-254:~$ systemctl status cron.service
● cron.service - Regular background program processing daemon
     Loaded: loaded (/usr/lib/systemd/system/cron.service; enabled; preset: enabled)
     Active: active (running) since Wed 2026-02-04 19:56:32 UTC; 8min ago
       Docs: man:cron(8)
   Main PID: 597 (cron)
      Tasks: 1 (limit: 1008)
     Memory: 468.0K (peak: 2.0M)
        CPU: 18ms
     CGroup: /system.slice/cron.service
             └─597 /usr/sbin/cron -f -P

Feb 04 19:56:32 ip-172-31-34-254 systemd[1]: Started cron.service - Regular background program processing daemon.
Feb 04 19:56:32 ip-172-31-34-254 (cron)[597]: cron.service: Referenced but unset environment variable evaluates to an empty string: EXTRA>
Feb 04 19:56:32 ip-172-31-34-254 cron[597]: (CRON) INFO (pidfile fd = 3)
Feb 04 19:56:32 ip-172-31-34-254 cron[597]: (CRON) INFO (Running @reboot jobs)
Feb 04 20:05:01 ip-172-31-34-254 CRON[2261]: pam_unix(cron:session): session opened for user root(uid=0) by root(uid=0)
Feb 04 20:05:01 ip-172-31-34-254 CRON[2262]: (root) CMD (command -v debian-sa1 > /dev/null && debian-sa1 1 1)
Feb 04 20:05:01 ip-172-31-34-254 CRON[2261]: pam_unix(cron:session): session closed for user root

ubuntu@ip-172-31-34-254:~$ sudo systemctl stop cron.service
ubuntu@ip-172-31-34-254:~$ journalctl -u cron.service
Feb 04 19:56:32 ip-172-31-34-254 systemd[1]: Started cron.service - Regular background program processing daemon.
Feb 04 19:56:32 ip-172-31-34-254 (cron)[597]: cron.service: Referenced but unset environment variable evaluates to an empty string: EXTRA>
Feb 04 19:56:32 ip-172-31-34-254 cron[597]: (CRON) INFO (pidfile fd = 3)
Feb 04 19:56:32 ip-172-31-34-254 cron[597]: (CRON) INFO (Running @reboot jobs)
Feb 04 20:05:01 ip-172-31-34-254 CRON[2261]: pam_unix(cron:session): session opened for user root(uid=0) by root(uid=0)
Feb 04 20:05:01 ip-172-31-34-254 CRON[2262]: (root) CMD (command -v debian-sa1 > /dev/null && debian-sa1 1 1)
Feb 04 20:05:01 ip-172-31-34-254 CRON[2261]: pam_unix(cron:session): session closed for user root
Feb 04 20:08:49 ip-172-31-34-254 systemd[1]: Stopping cron.service - Regular background program processing daemon...
Feb 04 20:08:49 ip-172-31-34-254 systemd[1]: cron.service: Deactivated successfully.
Feb 04 20:08:49 ip-172-31-34-254 systemd[1]: Stopped cron.service - Regular background program processing daemon.
lines 1-10/10 (END)

