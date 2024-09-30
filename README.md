# Conception de réseau Projet hétérogène

Le projet à réaliser

Démonstration 1 : Infrastructure : Routage + DMZ + VPN (10%)
Lors de cette première démonstration au professeur, vous devrez démontrer le bon fonctionnement de l’infrastructure de votre réseau. À ce stade, cette dernière devrait comprendre les passerelles VPN, la zone DMZ, les différents réseaux et l’interconnexion entre les différents sites. Avant de faire cette démonstration, assurez-vous que tous les sites soient en mesure de communiquer entre eux par l’entremise d’un VPN.

Démonstration 2 : Active Directory + DNS (15%)
Lors de cette deuxième démonstration, vous devrez démontrer le bon fonctionnement de votre annuaire Active Directory (incluant le RODC et le contrôleur de domaine Linux), des services DNS. Avant de réaliser cette démonstration, porter une attention particulière au bon fonctionnement de la réplication de l’annuaire Active Directory et de votre service DNS.

Démonstration 3 : Utilisateurs : création, permissions, lecteurs réseaux, stations de travail (15%)
Lors de cette troisième démonstration, vous devrez démontrer que vous avez correctement créé les 200 utilisateurs du fichier utilisateurs.csv disponible sur Moodle. Vous devrez configurer correctement l’appartenance de ses utilisateurs aux différents groupes de sécurité, de même que les scripts de login nécessaire au mappage des différents lecteurs réseau lors de leur connexion. À cette étape, l’utilisation des langages Power Shell et Batch sont essentiels de même que l’utilisation de Samba.

Le serveur de fichier Samba doit être fonctionnel et les disques contenant les répertoires personnels des utilisateurs doivent être cryptés.

Démonstration 4 : Sécurité : Pare-feu, antivirus, sauvegardes, redondance des disques, surveillance (15%)
Pour cette quatrième vérification, tous les services de votre infrastructure devraient être fonctionnels. Celle-ci devrait aussi faire l’objet d’une protection antivirus et d’une stratégie de sauvegarde sur l’ensemble de ses serveurs. Tous les serveurs doivent utiliser le RAID pour leurs disques durs.

Tous les serveurs, services et éléments de l’infrastructure doivent être monitorés en utilisant les protocoles et les méthodes adéquats.

Démonstration 5 : Stockage, virtualisation (15%)
Pour cette dernière vérification, votre infrastructure de stockage doit être fonctionnelle, ceci inclut la réplication inter site. Les DNS des clients doivent pouvoir être créés sur exécution d’un simple script et doivent tous être identiques avec une configuration centralisée (les modifications se font à un seul endroit).

Les hyperviseurs accèdent aux cibles du SAN à l’aide d’une VIP, donc une seule cible est active à la fois. En cas de panne d’une cible, les hyperviseurs basculent vers la cible secondaire. Cette opération doit être automatique
