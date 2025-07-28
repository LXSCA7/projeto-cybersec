## Scan Corp:

Nmap 7.95 scan initiated Sun Jul 27 17:43:33 2025 as: /usr/lib/nmap/nmap -sV -O -p- -iL corp.txt -oN scan-corp.txt

Nmap scan report for WS_001.projeto_final_opcao_1_corp_net (10.10.10.10)
Host is up (0.000089s latency).
All 65535 scanned ports on WS_001.projeto_final_opcao_1_corp_net (10.10.10.10) are in ignored states.
Not shown: 65535 closed tcp ports (reset)
MAC Address: F2:FA:C6:4A:57:51 (Unknown)
Too many fingerprints match this host to give specific OS details
Network Distance: 1 hop

Nmap scan report for WS_002.projeto_final_opcao_1_corp_net (10.10.10.101)
Host is up (0.000031s latency).
All 65535 scanned ports on WS_002.projeto_final_opcao_1_corp_net (10.10.10.101) are in ignored states.
Not shown: 65535 closed tcp ports (reset)
MAC Address: CE:0F:04:B0:2D:D7 (Unknown)
Too many fingerprints match this host to give specific OS details
Network Distance: 1 hop

Nmap scan report for WS_003.projeto_final_opcao_1_corp_net (10.10.10.127)
Host is up (0.000029s latency).
All 65535 scanned ports on WS_003.projeto_final_opcao_1_corp_net (10.10.10.127) are in ignored states.
Not shown: 65535 closed tcp ports (reset)
MAC Address: 22:70:E8:F9:F4:52 (Unknown)
Too many fingerprints match this host to give specific OS details
Network Distance: 1 hop

Nmap scan report for WS_004.projeto_final_opcao_1_corp_net (10.10.10.222)
Host is up (0.000026s latency).
All 65535 scanned ports on WS_004.projeto_final_opcao_1_corp_net (10.10.10.222) are in ignored states.
Not shown: 65535 closed tcp ports (reset)
MAC Address: 7E:E9:F8:16:40:83 (Unknown)
Too many fingerprints match this host to give specific OS details
Network Distance: 1 hop

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .

Nmap done at Sun Jul 27 17:43:37 2025 -- 4 IP addresses (4 hosts up) scanned in 4.52 seconds

## Scan Guest:

Nmap 7.95 scan initiated Sun Jul 27 17:42:46 2025 as: /usr/lib/nmap/nmap -sV -O -p- -iL guest.txt -oN scan-guest.txt
Nmap scan report for ftp-server.projeto_final_opcao_1_infra_net (10.10.30.10)
Host is up (0.000070s latency).
Not shown: 65534 closed tcp ports (reset)
PORT   STATE SERVICE VERSION
21/tcp open  ftp     Pure-FTPd
MAC Address: 4E:A2:9E:5A:57:EA (Unknown)
Device type: general purpose
Running: Linux 4.X|5.X
OS CPE: cpe:/o:linux:linux_kernel:4 cpe:/o:linux:linux_kernel:5
OS details: Linux 4.15 - 5.19, OpenWrt 21.02 (Linux 5.4)
Network Distance: 1 hop

Nmap scan report for mysql-server.projeto_final_opcao_1_infra_net (10.10.30.11)
Host is up (0.000032s latency).
Not shown: 65533 closed tcp ports (reset)
PORT      STATE SERVICE VERSION
3306/tcp  open  mysql   MySQL 8.0.43
33060/tcp open  mysqlx  MySQL X protocol listener
MAC Address: F6:F7:DB:C4:C2:D6 (Unknown)
Device type: general purpose|router
Running: Linux 4.X|5.X, MikroTik RouterOS 7.X
OS CPE: cpe:/o:linux:linux_kernel:4 cpe:/o:linux:linux_kernel:5 cpe:/o:mikrotik:routeros:7 cpe:/o:linux:linux_kernel:5.6.3
OS details: Linux 4.15 - 5.19, OpenWrt 21.02 (Linux 5.4), MikroTik RouterOS 7.2 - 7.5 (Linux 5.6.3)
Network Distance: 1 hop

Nmap scan report for samba-server.projeto_final_opcao_1_infra_net (10.10.30.15)
Host is up (0.000049s latency).
Not shown: 65533 closed tcp ports (reset)
PORT    STATE SERVICE     VERSION
139/tcp open  netbios-ssn Samba smbd 4
445/tcp open  netbios-ssn Samba smbd 4
MAC Address: E6:64:04:5F:CE:3B (Unknown)
Device type: general purpose|router
Running: Linux 4.X|5.X, MikroTik RouterOS 7.X
OS CPE: cpe:/o:linux:linux_kernel:4 cpe:/o:linux:linux_kernel:5 cpe:/o:mikrotik:routeros:7 cpe:/o:linux:linux_kernel:5.6.3
OS details: Linux 4.15 - 5.19, OpenWrt 21.02 (Linux 5.4), MikroTik RouterOS 7.2 - 7.5 (Linux 5.6.3)
Network Distance: 1 hop

Nmap scan report for openldap.projeto_final_opcao_1_infra_net (10.10.30.17)
Host is up (0.000025s latency).
Not shown: 65533 closed tcp ports (reset)
PORT    STATE SERVICE  VERSION
389/tcp open  ldap     OpenLDAP 2.2.X - 2.3.X
636/tcp open  ldapssl?
MAC Address: 4A:74:A4:5B:54:FD (Unknown)
Device type: general purpose
Running: Linux 4.X|5.X
OS CPE: cpe:/o:linux:linux_kernel:4 cpe:/o:linux:linux_kernel:5
OS details: Linux 4.15 - 5.19
Network Distance: 1 hop

Nmap scan report for zabbix-server.projeto_final_opcao_1_infra_net (10.10.30.117)
Host is up (0.000065s latency).
Not shown: 65532 closed tcp ports (reset)
PORT      STATE SERVICE             VERSION
80/tcp    open  http                nginx
10051/tcp open  ssl/zabbix-trapper?
10052/tcp open  unknown
MAC Address: 46:39:5B:48:2E:27 (Unknown)
Device type: general purpose|router
Running: Linux 4.X|5.X, MikroTik RouterOS 7.X
OS CPE: cpe:/o:linux:linux_kernel:4 cpe:/o:linux:linux_kernel:5 cpe:/o:mikrotik:routeros:7 cpe:/o:linux:linux_kernel:5.6.3
OS details: Linux 4.15 - 5.19, OpenWrt 21.02 (Linux 5.4), MikroTik RouterOS 7.2 - 7.5 (Linux 5.6.3)
Network Distance: 1 hop

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .

Nmap done at Sun Jul 27 17:43:15 2025 -- 5 IP addresses (5 hosts up) scanned in 28.68 seconds

# Scan infra:

Nmap scan report for 10.10.50.1
Host is up (0.000095s latency).
Not shown: 65534 closed tcp ports (reset)
PORT     STATE SERVICE    VERSION
5432/tcp open  postgresql PostgreSQL DB 9.6.0 or later
MAC Address: B6:76:F1:F3:35:0A (Unknown)
Device type: general purpose
Running: Linux 4.X|5.X
OS CPE: cpe:/o:linux:linux_kernel:4 cpe:/o:linux:linux_kernel:5
OS details: Linux 4.15 - 5.19, OpenWrt 21.02 (Linux 5.4)
Network Distance: 1 hop

Nmap scan report for laptop-luiz.projeto_final_opcao_1_guest_net (10.10.50.2)
Host is up (0.000067s latency).
All 65535 scanned ports on laptop-luiz.projeto_final_opcao_1_guest_net (10.10.50.2) are in ignored states.
Not shown: 65535 closed tcp ports (reset)
MAC Address: B6:2B:E8:F4:BE:DB (Unknown)
Too many fingerprints match this host to give specific OS details
Network Distance: 1 hop

Nmap scan report for macbook-aline.projeto_final_opcao_1_guest_net (10.10.50.3)
Host is up (0.000031s latency).
All 65535 scanned ports on macbook-aline.projeto_final_opcao_1_guest_net (10.10.50.3) are in ignored states.
Not shown: 65535 closed tcp ports (reset)
MAC Address: B6:A8:D7:CB:A3:C9 (Unknown)
Too many fingerprints match this host to give specific OS details
Network Distance: 1 hop

Nmap scan report for laptop-vastro.projeto_final_opcao_1_guest_net (10.10.50.4)
Host is up (0.000027s latency).
All 65535 scanned ports on laptop-vastro.projeto_final_opcao_1_guest_net (10.10.50.4) are in ignored states.
Not shown: 65535 closed tcp ports (reset)
MAC Address: 2A:E5:A0:7B:D1:47 (Unknown)
Too many fingerprints match this host to give specific OS details
Network Distance: 1 hop

Nmap scan report for notebook-carlos.projeto_final_opcao_1_guest_net (10.10.50.5)
Host is up (0.000031s latency).
All 65535 scanned ports on notebook-carlos.projeto_final_opcao_1_guest_net (10.10.50.5) are in ignored states.
Not shown: 65535 closed tcp ports (reset)
MAC Address: 22:1D:48:58:02:8B (Unknown)
Too many fingerprints match this host to give specific OS details
Network Distance: 1 hop

Nmap scan report for fc6bd504ab03 (10.10.50.6)
Host is up (0.000058s latency).
All 65535 scanned ports on fc6bd504ab03 (10.10.50.6) are in ignored states.
Not shown: 65535 closed tcp ports (reset)
Too many fingerprints match this host to give specific OS details
Network Distance: 0 hops