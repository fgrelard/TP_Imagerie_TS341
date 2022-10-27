# TP - Outils d'imagerie pour la robotique 

Commencez par cloner le dépôt:
    
        git clone https://github.com/fgrelard/TP_Imagerie_TS341.git
        
Les TPs se font via des notebooks Jupyter, c'est-à-dire des applications Web où l'on peut exécuter du code Python. 

Suivez l'option ci-dessous qui correspond à votre cas de figure. On recommande d'utiliser un environnement virtuel:
1. [Environnement virtuel sur les machines de l'ENSEIRB](#enseirb)
2. [Environnement virtuel sur vos machines perso](#perso)
3. [Sans environnement virtuel](#novirtual)

## 1. <a name="enseirb"></a> Utilisation d'un environnement virtuel sur les machines de l'ENSEIRB

1. Activation de l'environnement virtuel
        
        source ~xxxxxxxxx/tp-image/bin/activate
        
A ce stade, vous devriez voir votre ligne de terminal être préfixée par (tp-image).

2. Création d'un kernel propre à l'environnement virtuel

        ipython kernel install --user --name=venv

3. Création d'un point d'accès aux notebooks:

        jupyter notebook
        
4. Après l'exécution de la commande précédente, copier/coller l'adresse renvoyée dans votre navigateur préféré. L'url est de la forme 127.0.0.1:8888 suivi du token d'authentification.

Vous pouvez désormais exécuter le code Python dans votre navigateur. 

5. Cliquez sur le fichier "0_notebooks_python". 

6. Sélectionner le kernel créé à l'étape 4. Dans le menu Kernel > Change kernel > venv.

        
## 2. <a name="perso"></a> Utilisation d'un environnement virtuel sur vos machines perso 

1. Création d'un environnement virtuel

        python3 -m venv venv 
    
2. Activation de l'environnement virtuel

        source ./venv/bin/activate
    
A ce stade, vous devriez voir votre ligne de terminal être préfixée par (venv).

3. Installation des dépendances

        pip3 install -r requirements.txt
        
4. Création d'un kernel propre à l'environnement virtuel

        ipython kernel install --user --name=venv

5. Création d'un point d'accès aux notebooks:

        jupyter notebook
        
6. Après l'exécution de la commande précédente, copier/coller l'adresse renvoyée dans votre navigateur préféré. L'url est de la forme 127.0.0.1:8888 suivi du token d'authentification.

Vous pouvez désormais exécuter le code Python dans votre navigateur. 

7. Cliquez sur le fichier "0_notebooks_python". 

8. Sélectionner le kernel créé à l'étape 4. Dans le menu Kernel > Change kernel > venv.

## 3. <a name="novirtual"></a> Sans environnement virtuel sur vos machines perso (plus court)

1. Installation des dépendances

        pip3 install -r requirements.txt
        
2. Création d'un point d'accès aux notebooks:

        jupyter notebook
        
3. Après l'exécution de la commande précédente, copier/coller l'adresse renvoyée dans votre navigateur préféré. L'url est de la forme 127.0.0.1:8888 suivi du token d'authentification.

Vous pouvez désormais exécuter le code Python dans votre navigateur. 
