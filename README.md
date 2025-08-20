# Cyberlab-Yessia
# Projet : Lab de cybersécurité avec pfSense
- Configuré un lab VirtualBox avec pfSense (firewall/router), Kali Linux (LAN, 10.0.0.0/24), et Ubuntu (DMZ, 172.16.0.0/24).
- Configuré WAN (pont) pour accès internet, NAT/DHCP pour LAN/DMZ.
- Résolu problème "no route to host" via configuration passerelle/DNS.
- Testé connectivité (ping 8.8.8.8, google.com), inter-réseaux (Nmap), et règles firewall (blocage port 80).
- Validé avec serveur Apache sur Ubuntu.
- Scanné la machine Ubuntu avec Nmap pour récupérer la clé ssh et tenter une connection avec Putty depuis ma machine hôte.
