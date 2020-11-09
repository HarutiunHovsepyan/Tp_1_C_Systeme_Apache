Harutiun
Hovsepyan
3ICS

# TP 1 - Service Web


## 2 - Désactivation de SELinux

**[2A] A quoi sert ce composant ?**

rep : SELinux est un mécanisme de sécurité qui améliore de manière la sécurité des serveurs sur lesquels il est déployé en apportant une couche supplémentaire aux traditionnels droits d’accès aux fichiers Unix.


**[2B] Comment peut on le désactiver momentanément (Il existe au moins 2 moyens)**

rep : Pour désactiver temporairement SElinux on peut entrer la commande `setenforce 0` ou la commande `echo "0" > /selinux/enforce`.


**[2C] Comment peut-on le désactiver de façon permanente ?**

rep : Pour désactiver Selinux de façon permanente, il faut entrer dans le fichier avec la commande `nano /etc/selinux/config`. Il faut ensuite editer `SELINUX=enforcing` en `SELINUX=permissive`.

---

## 3 - Désactivation permanente du pare-feu.

**[3A] Quelle commande vous permet de désactiver temporairement le firewall, le temps deprocéder a la configuration de la machine ?**

rep : Pour désactiver temporairement le firewall il faut entrer la commande `systemctl stop firewalld`.


**[3B] Quelle commande vous permet d’avoir la certitude que le firewall est bien inactif ?**

rep : La commande `systemctl is-active firewalld` nous permet d’avoir la certitude que le firewall est bien inactif. Si il nous renvoie `inactive`, alors tout est bon.

---

## 4 - Installation du service Apache (La configuration réseau avancé viendra par la suite)
**[4A] Quels sont les trois principaux serveurs WEB disponible sous Linux**

rep :


**[4B] La commande dnf (ou anciennement yum) permet d’installer les packages.**

rep :


**-Quelle commande permet de retrouver le nom du package contenant le serveur Apache ?**

rep :


**-Quelle commande permet d’installer le serveur Apache ?**

rep :


**[4C] Démarrage du service Apache**

**-Quelle commande permet de démarrer le service Apache ?**

rep :


**[4D] Quelle commande vous permet d’avoir la certitude que le service Apache est fonctionnel ?**

rep :


**[4E] Quelles informations essentielles vous sont fournies par cette commande ?**

rep :

---

## 5 - Configuration du service Apache

**[5A] Ou se trouvent les fichiers de configuration de Apache ?**

rep : 


**[5B] Quelle est la structure de ce répertoire ?**

rep : 


**[5C] Ou se trouve le fichier de configuration principal ?**

rep : 


**[5D] Que contient (du point de vue logique) le répertoire conf.d**

rep : 


**[5E] Que contient le répertoire conf.modules.d**

rep : 


**[5F] Qu’est-ce qu’un module ?**

rep : 


**[5G] Ou sont-ils stockés ?**

rep : 


**[5H] Ou sont stockés les log de Apache ?**

rep : 



