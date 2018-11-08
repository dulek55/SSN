ifconfig -a
 inet 10.0.2.15

nmap -sS 10.0.2.*

 Starting Nmap 7.25BETA2 ( https://nmap.org ) at 2018-11-08 05:45 EST
Nmap scan report for 10.0.2.2
Host is up (0.00034s latency).
Not shown: 993 closed ports
PORT     STATE SERVICE
22/tcp   open  ssh
25/tcp   open  smtp
631/tcp  open  ipp
902/tcp  open  iss-realsecure
2500/tcp open  rtsserv
3306/tcp open  mysql
8080/tcp open  http-proxy
MAC Address: 52:54:00:12:35:02 (QEMU virtual NIC)

Nmap scan report for 10.0.2.3
Host is up (0.00039s latency).
Not shown: 992 closed ports
PORT     STATE SERVICE
22/tcp   open  ssh
25/tcp   open  smtp
53/tcp   open  domain
631/tcp  open  ipp
902/tcp  open  iss-realsecure
2500/tcp open  rtsserv
3306/tcp open  mysql
8080/tcp open  http-proxy
MAC Address: 52:54:00:12:35:03 (QEMU virtual NIC)

Nmap scan report for 10.0.2.4
Host is up (0.00033s latency).
Not shown: 993 closed ports
PORT     STATE SERVICE
22/tcp   open  ssh
25/tcp   open  smtp
631/tcp  open  ipp
902/tcp  open  iss-realsecure
2500/tcp open  rtsserv
3306/tcp open  mysql
8080/tcp open  http-proxy
MAC Address: 52:54:00:12:35:04 (QEMU virtual NIC)

Nmap scan report for 10.0.2.15
Host is up (0.0000020s latency).
Not shown: 999 closed ports
PORT   STATE SERVICE
22/tcp open  ssh

Nmap done: 256 IP addresses (4 hosts up) scanned in 2.15 seconds



