antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder$ gh repo clone cecilev-axe/tp-bachelor
Command 'gh' not found, but can be installed with:
snap install gh       # version 2.6.0-15-g1a10fd5a, or
apt  install gh       # version 2.4.0+dfsg1-2
apt  install gitsome  # version 0.8.0+ds-6ubuntu1
See 'snap info gh' for additional versions.
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder$ git clone https://github.com/cecilev-axe/tp-bachelor.gitCloning into 'tp-bachelor'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 10 (delta 0), reused 10 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (10/10), done.
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder$ cd tp-bachelor/
antoinegouet@ip-172-31-18-235:~/sites/UE3antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ g       tantoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ git init
Reinitialized existing Git repository in /home/antoinegouet/sites/UE3/github/New Folder/tp-bachelor/.git/
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ git commit -m "first commit"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ git branch -M main
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ git remote add origin https://github.com/PoseurDeBombe/Ue3TP.giterror: remote origin already exists.
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bacheloantoinegouet@ip-172-31-antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ git remote add origin https://github.com/PoseurDeBombe/Ue3TP.giterror: remote origin already exists.
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ remote origin
Command 'remote' not found, but can be installed with:
snap install remote
Please ask your administrator.
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ git remote add origin https://github.com/PoseurDeBombe/Ue3TP.git
error: remote origin already exists.
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ git push -u origin main
Username for 'https://github.com': PoseurDeBombe
Password for 'https://PoseurDeBombe@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/cecilev-axe/tp-bachelor.git/'
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ 
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ git remote -v
origin  https://github.com/cecilev-axe/tp-bachelor.git (fetch)
origin  https://github.com/cecilev-axe/tp-bachelor.git (push)
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ git remote remove origin
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ git remote add origin https://github.com/antoine/ue3tp.git
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ git remote remove origin git remote add origin https://github.com/PoseurDeBombe/Ue3TP.git
usage: git remote remove <name>

antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ git remote -v
origin  https://github.com/antoine/ue3tp.git (fetch)
origin  https://github.com/antoine/ue3tp.git (push)
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ git remote -v                          
origin  https://github.com/antoine/ue3tp.git (fetch)
origin  https://github.com/antoine/ue3tp.git (push)
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ git remote remove origin
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ git remote remove origin git remote add origin https://github.com/PoseurDeBombe/Ue3TP.git
usage: git remote remove <name>

antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ 
antoinegouet@ip-172-31-18-235:~/sites/UE3/github/New Folder/tp-bachelor$ 


   ## Changement de l'origine (remote)
   ```bash
   git remote remove origin
   git remote add origin https://github.com/antoine/ue3tp.git
   git remote -v
   ```

   ## Vérification du remote
   ```bash
   git remote -v
   ```

   ## Ajout d'une nouvelle fonctionnalité
   - Ajoutez une quatrième image et un dot supplémentaire.
   - Vérifiez que tout fonctionne.

   ## Mise à jour du dépôt distant
   ```bash
   git add .
   git commit -m "Ajout d'une nouvelle fonctionnalité"
   git push origin main
   ```

   ## Gestion d'un conflit
   - **Sur GitHub** : Modifiez la taille des dots de 15px à 20px.
   - **En local** : Modifiez la taille des dots de 15px à 25px.
   ```bash
   git add .
   git commit -m "Modification de la taille des dots à 25px en local"
   git pull origin main
   ```

   - Résolvez le conflit et enregistrez les modifications :
   ```bash
   git add .
   git commit -m "Résolution du conflit de taille des dots"
   git push origin main
   ```

   ## Vérification de l'état du dépôt
   ```bash
   git status
   git log
   ```








