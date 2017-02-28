Faille 1: VSFTPD 2.3.4 backdoor
----------------
![vsftpd](https://github.com/gregorylony/metaspoitable/blob/master/vsftpd.PNG?raw=true)

Cette faille donne un accès root à un serveur ftp sous linux.

**FIX**
La distrib metaspoitable 2 tourne sur une ancienne version de debian, il est difficile de la mettre à jour.
Il faut télécharger les sources de vsftpd:

     1. wget https://security.appspot.com/downloads/vsftpd-3.0.3.tar.gz
        --no-check-certificate
     2. tar -xzvf vsftpd-3.0.3.tar.gz
     3. cd vsftpd-3.0.3
     4. make
     5. make install

Faille 2: Unreal IRCD
![enter image description here](https://github.com/gregorylony/metaspoitable/blob/master/ircd.png?raw=true)

**Fix**
Il faut mettre à jour le programme puisque c'est un backdoor présent sur une ancienne version.

Faille 3: java_rmi_server
--------
![javarmi](https://github.com/gregorylony/metaspoitable/blob/master/rmi.PNG?raw=true)


----------
Grégory LONY, Freddy RAZAFILAZAMAHAZO
