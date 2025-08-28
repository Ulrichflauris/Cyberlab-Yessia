# Cyberlab-Yessia
# Projet : Lab de cybersécurité avec pfSense
## Description
- Configuré un lab VirtualBox avec pfSense (firewall/router), Kali Linux (LAN, 10.0.0.0/24), et Ubuntu (DMZ, 172.16.0.0/24).
- Configuré WAN (pont) pour accès internet, NAT/DHCP pour LAN/DMZ.
- Résolu problème "no route to host" via configuration passerelle/DNS.
- Testé connectivité (ping 8.8.8.8, google.com), inter-réseaux (Nmap), et règles firewall (blocage port 80).
- Validé avec serveur Apache sur Ubuntu.
- Scanné la machine Ubuntu avec Nmap pour récupérer la clé ssh et tenter une connection avec Putty depuis ma machine hôte.
## Surveillance réseau avec Wazuh
- Installé Wazuh SIEM/XDR sur Ubuntu (DMZ) et agent sur Kali (LAN).
- Résolu erreur due à lien invalide avec nouveau téléchargement.
- Configuré accès dashboard via pfSense (port 443).

## Preuves
- [Dashboard Pfsense](pfsense_dashboard.png)
- [Connectivité entre réseaux](ping_ubuntu.png)
- [Règles firewall LAN sur Pfsense](rules_LAN_pfsense.png)
- [Règles firewall DMZ sur Pfsense](rules_DMZ_pfsense.png)
- [Règles NAT sur Pfsense](nat_pfsense.png)
- [Scan Nmap de la machine Ubuntu avec récupération de la clé SSH](scan_nmap_ubuntu.png)
- [Connexion en SSH à Ubuntu via Putty sur Windows(machine hôte)](putty_ubuntu.png)
- [Security Events de Wazuh]()
