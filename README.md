# CCNPv6
## NGN Networking Academy
### Default Config Router
#### enable
#### hostname R1
#### no ip domain-lookup
#### enable secret darkness
#### service password-en
#### line con 0
#### password hntu
#### logging synchronous
#### exec-timeout 1 0
#### login
#### exit
#### line vty 0 4
#### password hntu
#### logging synchronous
#### exec-timeout 1 0
#### login
#### exit
#### banner motd " Access for authorized users only. Please enter your username and  password. "