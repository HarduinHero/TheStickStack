# TheStackStick
PRA sur clé.<br>
Mettez votre infra sur clé. Créez et entretenez votre ``clé Red Tape`` pour vous préparer au pire.

## Cahier des charges scénarisé

### L'organisation :
- ABC sas est une entreprise commerciale exerceant dans un domaine quelconque.
- ABC sas stock des données personnelles des ses clients (nom, prénoms, adresses email) et de ses employés (nom, prénom, adresse postale, coordonées banquaires, numéro de sécurité sociale).
- ABC sas possede une infra virtualisée avec un annuaire ldap, des VLANs des services applicatifs.
### Préparation :
- ABC sas prend en comptes les risques cyber et met en place un PRA.
- Les application vitales sont identifiées et une infrastructure minimale est définie.
- Cette infrastructure minimale est crée et maintenue à jour (versions, configuration, données) sur une ``clé Red Tape`` grace à TheStackStick.
### L'attaque :
- ABC sas est victime d'une attaque par ransomware.
- Tout le réseau est touché, toutes les machines doivent êtres déverminé.
- ABC sas doit rapidement redmarer ceertains éléùents de son infrastructure (serveur de téléphonie, serveur de mail, serveur applicatif) afin de reprendre son activité mais aussi répondre à ses impératifs légaux (devoir d'alerte RGPD).
### La solution :
- ABC sas à pu obtenir en vietesse des ordinateurs / serveurs et un routeur.
- ABC sas utilise sa ``clé Red Tape`` pour :
  - Installer proxmox correctement configuré sur ses machines de pret.
  - Instancier et configurer automatiquement des VMs.
  - Installer ses applications vitales, et y charger les configurations et données nécessaires.
- ABC sas peut mieux gérer sa crise en utilisant son infra minimale.
