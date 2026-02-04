ubuntu@ip-172-31-34-254:~$ uname -a
Linux ip-172-31-34-254 6.14.0-1018-aws #18~24.04.1-Ubuntu SMP Mon Nov 24 19:46:27 UTC 2025 x86_64 x86_64 x86_64 GNU/Linux

ubuntu@ip-172-31-34-254:~$ cat /etc/os-release
PRETTY_NAME="Ubuntu 24.04.3 LTS"
NAME="Ubuntu"
VERSION_ID="24.04"
VERSION="24.04.3 LTS (Noble Numbat)"
VERSION_CODENAME=noble
ID=ubuntu
ID_LIKE=debian
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
UBUNTU_CODENAME=noble
LOGO=ubuntu-logo

Tasks: 112 total,   1 running, 111 sleeping,   0 stopped,   0 zombie
%Cpu(s):  0.5 us,  0.2 sy,  0.0 ni, 99.3 id,  0.0 wa,  0.0 hi,  0.0 si,  0.0 st 
MiB Mem :    914.2 total,    292.3 free,    333.4 used,    449.8 buff/cache     
MiB Swap:      0.0 total,      0.0 free,      0.0 used.    580.8 avail Mem 

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                                                            
      1 root      20   0   22540  13952   9648 S   0.0   1.5   0:02.16 systemd                                                            
      2 root      20   0       0      0      0 S   0.0   0.0   0:00.00 kthreadd                                                           
      3 root      20   0       0      0      0 S   0.0   0.0   0:00.00 pool_workqueue_release                                             
      4 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-rcu_gp                                                   
      5 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-sync_wq                                                  
      6 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-kvfree_rcu_reclaim                                       
      7 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-slub_flushwq                                             
      8 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-netns                                                    
     10 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/0:0H-events_highpri                                        
     11 root      20   0       0      0      0 I   0.0   0.0   0:00.19 kworker/0:1-events                                                 
     12 root      20   0       0      0      0 I   0.0   0.0   0:00.17 kworker/u8:0-events_power_efficient                                
     13 root       0 -20       0      0      0 I   0.0   0.0   0:00.00 kworker/R-mm_percpu_wq         

ubuntu@ip-172-31-34-254:~$ df -h 
Filesystem       Size  Used Avail Use% Mounted on
/dev/root        6.8G  1.8G  5.0G  27% /
tmpfs            458M     0  458M   0% /dev/shm
tmpfs            183M  876K  182M   1% /run
tmpfs            5.0M     0  5.0M   0% /run/lock
efivarfs         128K  3.6K  120K   3% /sys/firmware/efi/efivars
/dev/nvme0n1p16  881M   89M  730M  11% /boot
/dev/nvme0n1p15  105M  6.2M   99M   6% /boot/efi
tmpfs             92M   12K   92M   1% /run/user/1000
ubuntu@ip-172-31-34-254:~$ du -sh
48K     .
