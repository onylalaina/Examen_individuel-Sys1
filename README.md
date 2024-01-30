# Examen_individuel-Sys1
WeChall Training: Warchall-The begining
Pour commencer à faire ce challenge, il faut d'abord cliquer et entrer dans le lien https://www.wechall.net/challenge/warchall/begins/index.php. 
Pour se faire, il faut s'authentifier ou s'identifier en remplissant sur le formulaire à droite de la page d'accueil: saisir le prénom et le mot de passe de l'utilisateur; pour que l'on soit enregistrer, on doit aller vers la gauche du page d'accueil en complètant ses demandes par:
-Pseudo:....
-Mot de passe:...
-E-mail:....
-Cliquer sur la case concernant l'accepte des termes d'utilisation
-Nom inverse du site: Llahcew
-Réécrire le captcha qu'il a donné précédemment
-Cliquez sur enregistrer pour commencer
-Recevoir un message de notification en vert pour la validation sinon veuillez recommencer ces étapes si le message de notification est en rouge juste en haut de la case d'enregistrement
-Consulter l'adresse e-mail saisi précédemment pour vérifier le message venant le support de ce challenge; cliquer sur nouveau lien dont il a donné.

En débutant Warcall-ChapterI(Warcall begins), on a besoin de se connecter sur un compte ssh et ce compte est déjà censé donner après avoir saisi le mot de passe lors de l'enregistrement du compte de l'utilisateur: ssh -p 19198 user@warchall.net

Voici les commandes linux qui peuvent nous aider(utiles) à capturer le drapeau!
cd       :change directory
ls -a    :afficher un contenu
cat      :lire un fichier 
chmod +r :recevoir la permission de lire

## Niveau 0: welcome
cd /home/level
ls -a
cd 00-welcom
ls -a
cat README.md

## Niveau 1:  choice_tree
cd /home/level
ls -a
cd -choise tree
ls -a
cd blue
cd hats
cd grey
cat solution.txt

## Niveau 2
cd /home/level
ls -a
cd 02
ls -a
cd .prob
ls -a
cat solution

## Niveau 3
cd /home/level
ls -a
cd 03
ls -a
cat .bash_history

## Niveau 4: kwisatz
cd /home/user/username/level
ls -a
cd 04-kwisat
ls -a
chmod +r README.md
cat README.md

## Niveau 5: privacy
cd /home/level
ls -a
cd 05-privacy
ls -a
cat README.md

## Niveau 7: tropical_fruits
cd/home/level/topic/7
ls
bin
cat fichier.bin
validation

## Niveau 8: sshz
cd/home/level
10-no-sleep-ssh.sh into /etc/pm/sleep
sshlocalhost
-I INPUT -s 192.168.1.100/24 -p tcp --dport ssh -j ACCEPT
-cmd --direct --add-rule ipv4 filter INPUT 1 -m tcp --source 192.168.1.100 -p tcp --dport 22 -j ACCEPT 


