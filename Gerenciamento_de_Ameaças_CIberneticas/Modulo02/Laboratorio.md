# Comandos

laptop 192.168.50.3

DNS Server 10.2.0.125

------------------------------------
Armario
ipv4 192.168.99.9          submask 255.255.255.0



------------------------------------
HQ-Edge
Enter // para habilitar os comandos
"show ip route | begin Gateway"

Verifica se foi configurado se não vai esta 0.0.0.0


show run | begin ip route

"GigabiteEthernet0/0/0" configurado prá isso 

----------------------------------------

CDP (Cisco Discovery Protocol)
Descobrir o endereço IP do Roteador 
 
show cdp neighbors detail
IP address : 10.0.0.49

Port ID (outgoing port): GigabitEthernet1/0 - portas conectadas


IOS (tm) PT1000 Software (PT1000-I-M), Version 12.2(28), RELEASE SOFTWARE (fc5) - versão IOS no 
roteador - Device ID: ISP

----------------------------------------

Ping (Endereço)<br>
ping 10.0.0.49

----------------------------------------

show arp<br>
Internet  10.0.0.49         -       43  0060.2FE1.903B  ARPA   GigabitEthernet0/0/0<br>
Internet  10.0.0.50         -     -   0000.0C99.CB04  ARPA   GigabitEthernet0/0/0<br>
Internet  192.168.99.10     -     43  0090.2B03.46D1  ARPA   GigabitEthernet0/0/1.99<br>

----------------------------------------

