# Syskit
Collection d'outils système Bash pour Linux.
## Fonctionnalités
 1. disk_usage : affiche l'espace disaue trier par taille
 2. top_processes : affiche les processus les plus gourmand en CPU
 3. find_large_files : cherche les fichiers volumineux 
 4. .. et ... : navigation rapide dans les dossiers 
## Prérequis
- Linux (Ubuntu, Debian, Arch...)
- Bash >= 4.0
## Installation
```bash
git clone https://github.com/<elyseekulukiswahili>/syskit.git
cd syskit
bash install.sh
source ~/.bashrc
```
## Utilisation
Vérifier le disque : Tape simplement disk_usage.


Voir les 5 processus les plus lourds : top_processes 5.

Trouver les fichiers de plus de 50Mo dans le dossier actuel : find_large_files . 50.


Remonter de deux niveaux : ....
## Structure du projet
syskit/
├── lib/                # Répertoire contenant les bibliothèques 
│   ├── functions.sh    # Définition des fonctions système 
│   └── aliases.sh      # Liste des alias personnalisés 
├── install.sh          # Script d'installation automatique 
├── README.md           # Documentation du projet (ce fichier) 
└── ANSWERS.md          # Réponses aux questions de compréhension 
## Auteur
Votre Nom — [GitHub]elyseekulukiswahili-stack
kulu kiswahili elysee 
