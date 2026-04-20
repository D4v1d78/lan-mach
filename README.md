lan-mach 
 LAN síť – Packet Tracer


David Mach


192.168.25.0 /24


M(77) + A(65) + C(67) + H(72) = 281  
281 mod 256 = 25
 
  Topologie
- S1, S2 (switch)
- PC1 (statická IP)
- PC2 (DHCP)
- SRV1 (DHCP + DNS)
- SRV2 (WEB)

Nastavení
- PC1: 192.168.25.100
- PC2: DHCP
- SRV1: 192.168.25.10
- SRV2: 192.168.25.20

DNS
mach.cz → 192.168.25.20

Testování
- ipconfig (PC1)
- ping 192.168.25.20
- ping mach.cz

 

