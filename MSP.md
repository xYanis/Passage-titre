# 1 Active Directory






# 2 Script PowerShell

# 3 Script Batch 

# 4 Linux


## Gestion utilisateurs

Les utilisateurs sont dans le fichier `/etc/passwd`

![2024-08-06 13_19_47-kali-linux-2024 2-virtualbox-amd64  En fonction  - Oracle VM VirtualBox](https://github.com/user-attachments/assets/c620fad2-8be7-457b-a8eb-2c4c2163663c)

Les mots de passe sont dans le fichier `/etc/shadow`


| Commande  | Définition                                                        | Exemple                                   |
|-----------|-------------------------------------------------------------------|-------------------------------------------|
| `passwd`  | Change le mot de passe d'un utilisateur.                          | `passwd utilisateur`                      |
| `adduser` | Ajoute un nouvel utilisateur au système.                          | `adduser nouvel_utilisateur`              |
| `deluser` | Supprime un utilisateur du système.                               | `deluser ancien_utilisateur`              |
| `usermod` | Modifie les informations d'un utilisateur.                        | `usermod -aG sudo utilisateur`            |
| `chfn`    | Change les informations sur le compte utilisateur (nom complet, etc.). | `chfn utilisateur`                        |
| `chsh`    | Change le shell par défaut d'un utilisateur.                      | `chsh -s /bin/bash utilisateur`           |
| `chage`   | Modifie les paramètres d'expiration du mot de passe d'un utilisateur. | `chage -l utilisateur`                   |
| `newusers`| Crée de nouveaux utilisateurs à partir d'un fichier.              | `newusers fichier_utilisateurs`           |
| `pwck`    | Vérifie l'intégrité des fichiers de mots de passe.                | `pwck`                                    |



## Gestions groupes

Les groupes sont dans le fichier `/etc/group`

![2024-08-06 13_38_47-kali-linux-2024 2-virtualbox-amd64  En fonction  - Oracle VM VirtualBox](https://github.com/user-attachments/assets/1464e85f-d70a-4a24-8a6e-ebc6a03ed284)




| Commande   | Définition                                                        | Exemple                                  |
|------------|-------------------------------------------------------------------|------------------------------------------|
| `newgrp`   | Change de groupe courant pour un utilisateur.                     | `newgrp nouveau_groupe`                  |
| `groupadd` | Ajoute un nouveau groupe au système.                              | `groupadd nouveau_groupe`                |
| `groupdel` | Supprime un groupe du système.                                    | `groupdel ancien_groupe`                 |
| `groupmod` | Modifie un groupe existant.                                       | `groupmod -n nouveau_nom ancien_groupe`  |
| `grpck`    | Vérifie l'intégrité des fichiers de groupes.                      | `grpck`                                  |

## Informations complémentaires

| Commande | Définition                                                        | Exemple           |
|----------|-------------------------------------------------------------------|-------------------|
| `id`     | Affiche l'identifiant utilisateur et les groupes d'un utilisateur. | `id`              |
| `whoami` | Affiche le nom de l'utilisateur actuel.                           | `whoami`          |
| `who`    | Affiche les utilisateurs actuellement connectés.                  | `who`             |
| `su`     | Permet de changer d'utilisateur dans une session.                 | `su - autre_utilisateur` |
| `sudo`   | Exécute une commande avec les privilèges d'un autre utilisateur (par défaut, superutilisateur). | `sudo commande`   |
| `exit`   | Quitte la session shell actuelle.                                 | `exit`            |
| `logout` | Déconnecte l'utilisateur de la session actuelle.                  | `logout`          |



# 5 TOIP
