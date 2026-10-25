Bonjour, moi c'est Ange 👋

Étudiant en 3ᵉ année de BUT Informatique, parcours DACS (Déploiement d'Applications Communicantes et Sécurisées) à l'IUT de Metz. Je m'intéresse surtout aux réseaux et à la cybersécurité : concevoir une infrastructure, la durcir, la superviser, puis la documenter.

🎯 Je recherche un stage en réseaux ou en cybersécurité du 22 février au 11 juin 2027.

🛠️ Projets
Projet	En bref	Site
net-toolkit	Calculateur IPv4 et VLSM, et générateur de configurations Cisco IOS (VLAN, trunk 802.1Q, Rapid PVST+, Port Security, DHCP), validées dans Packet Tracer. 224 tests, aucune dépendance.	reseau.ange-bonkoski.fr
simulateur-but	Simulateur de moyennes du BUT (UE, compétences, note à viser) qui lit les relevés PDF de l'ENT dans le navigateur, sans rien envoyer ni stocker. 249 tests.	notes.ange-bonkoski.fr
blog	Le journal de mon homelab et mes write-ups : incidents réels, diagnostics, retours d'expérience. Site Hugo sans JavaScript, avec une CI qui bloque toute fuite (IP, jetons, EXIF).	journal.ange-bonkoski.fr

Les trois sont des sites statiques publiés par GitHub Actions, uniquement si tous les tests passent, avec une CSP stricte et un modèle de menace documenté dans leur SECURITY.md.

🏠 Mon homelab

Un PC portable recyclé devenu serveur, géré comme une petite infrastructure de production :

Zéro port ouvert sur la box : le site public passe par un tunnel Cloudflare, tout le reste uniquement par VPN (Tailscale).
Services en Docker Compose derrière un reverse proxy (Nginx Proxy Manager, certificats Let's Encrypt).
Bastion d'accès Apache Guacamole avec TOTP, détection d'intrusions avec CrowdSec.
Supervision Uptime Kuma et alertes Discord, sauvegardes chiffrées restic planifiées par timers systemd.
Un dossier d'exploitation de plus de 40 pages, et les incidents racontés sur le blog.
🧰 Ce que j'utilise

Réseau : TCP/IP, VLSM, VLAN, Spanning Tree, Cisco IOS, Packet Tracer, DNS, DHCP, Modbus TCP Systèmes : Linux (Debian, Ubuntu), Windows Server, Active Directory, VMware ESXi, Docker Sécurité : Cloudflare, Tailscale, CrowdSec, TLS, durcissement, sauvegardes 3-2-1 Outils : Git, GitHub Actions, Bash, PowerShell, Python

📫 Portfolio · LinkedIn

<sub>🇬🇧 Third-year Computer Science student (networks & cybersecurity) in Metz, France. Looking for a networking or cybersecurity internship, Feb–June 2027.</sub>
