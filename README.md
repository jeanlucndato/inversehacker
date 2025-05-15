# Bug Bounty & Penetration Testing Toolkit - Docker Image

![Image](inversehacker.png)

## Pourquoi utiliser cette boîte à outils Docker ?

L'objectif de cette image Docker est de fournir aux chercheurs en sécurité, aux pentesters et aux bug hunters un environnement portable et préconfiguré, intégrant un ensemble d'outils et de frameworks populaires couramment utilisés dans leurs engagements.

Elle offre une base de travail cohérente et rapide à déployer, éliminant le besoin d'installations manuelles fastidieuses et de configurations complexes. Que vous travailliez sur Linux, macOS ou Windows (via Docker Desktop), cette boîte à outils est prête à l'emploi.

## Outils Inclus

Cette image Docker contient les outils suivants, installés dans le répertoire `/root/toolkit` :

- sqlmap - Un outil puissant pour détecter et exploiter les vulnérabilités d'injection SQL.
- dirb - Un scanner de répertoires web conçu pour découvrir les chemins et fichiers cachés.
- dnsenum - Un outil d'audit DNS pour recueillir des informations sur les domaines et les serveurs DNS.
- wfuzz - Un fuzzer HTTP pour identifier les vulnérabilités des applications web.
- knock - Un outil de découverte de ports pour identifier les ports ouverts sur un système cible.
- massdns - Un résolveur DNS à haute performance pour le balayage DNS à grande échelle.
- wafw00f - Un outil pour identifier et détecter les pare-feu d'applications web (WAF).
- wpscan - Un scanner de vulnérabilités pour les sites web WordPress.
- commix - Un outil d'exploitation de vulnérabilités de commande à distance dans les applications web.
- masscan - Un scanner de ports réseau extrêmement rapide.
- altdns - Un outil pour générer des permutations et des mutations de sous-domaines et tenter de les résoudre.
- teh_s3_bucketeers - Un outil pour trouver des buckets Amazon S3 mal configurés.
- Recon-ng - Un framework modulaire pour la reconnaissance web open source.
- XSStrike - Une suite d'outils pour la détection et l'exploitation des vulnérabilités Cross-Site Scripting (XSS).
- theHarvester - Un outil pour la collecte d'informations à partir de diverses sources publiques.
- CloudFlair - Un outil pour trouver les adresses IP d'origine derrière Cloudflare.
- joomscan - Un scanner de sécurité pour les systèmes de gestion de contenu Joomla.
- gobuster - Un outil de découverte de répertoires et de fichiers web basé sur la force brute.
- virtual-host-discovery - Un outil pour identifier les hôtes virtuels hébergés sur un serveur web.
- bucket_finder - Un autre outil pour la découverte de buckets S3 exposés.
- dirsearch - Un outil avancé de découverte de répertoires web.
- s3recon - Un outil pour l'énumération et l'analyse des buckets S3.
- subfinder - Un outil rapide pour la découverte de sous-domaines.
- zsh - Un shell puissant avec de nombreuses fonctionnalités avancées.
- dotdotpwn - Un fuzzer pour découvrir les vulnérabilités de traversée de répertoire.
- whatweb - Un outil pour identifier les technologies utilisées par un site web.
- fierce - Un scanner de ports réseau rapide.
- amass - Un moteur de reconnaissance de réseau actif et passif.
- S3Scanner - Un outil pour scanner les configurations de sécurité des buckets S3.
- droopescan - Un scanner pour identifier les vulnérabilités dans les CMS basés sur PHP.
- subjack - Un outil pour détecter les sous-domaines susceptibles d'être détournés.
- SubOver - Un autre outil pour la prise de contrôle de sous-domaines.
- ffuf - Un fuzzer web rapide pour la découverte de contenu.
- httprobe - Un outil pour sonder une liste d'hôtes HTTP et HTTPS actifs.
- gitGraber - Un outil pour aider à localiser les informations sensibles potentiellement exposées dans les référentiels `.git` publics.
- waybackurls - Un outil pour extraire toutes les URLs connues pour un domaine donné à partir des archives du Wayback Machine.
- Katoolin - Un outil pour installer des outils Kali Linux sur d'autres distributions Linux.

## Utilisation du Conteneur

Pour démarrer le conteneur, exécutez la commande Docker suivante :

```bash
docker run -it --rm inversehacker/bug-bounty-toolkit
```
