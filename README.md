# Moose

Dans ce fichier, vous trouverez les différentes étapes à suivre pour (1) lancer une image Moose  et (2) charger votre modèle.


## 1. Lancer une image Moose

Dans un premier temps, télécharger et installer le pharo launcher en suivant les étapes décrites sur cette page : [Downloading Pharo Launcher](https://pharo-project.github.io/pharo-launcher/installation/).

<img src="https://pharo-project.github.io/pharo-launcher/images/pharo-launcher.png" alt="Pharo Launcher" style="width:550px;"/>

Une fois le pharo launcher lancé, suivre ces étapes pour exécuter une image Moose :
1. Cliquer sur le bouton **Import** <img src="images/Import_image.png" alt="Import button" style="width:20px;"/> et séléctionner la première option. <br/> <img src="images/wwyltd.png" alt="What would you like to do?" style="width:350px;">
2. Sélectionner l'image (fichier avec extension *.image*) sur le disque. <br/> <img src="images/importpharoimage.png" alt="Import from disk window" style="width:350px;">
3. Séléctionner l'image dans la liste et cliquer sur le bouton **Launch** <img src="images/launchbutton.png" alt="Launch button" style="width:20px;">.
4. L'image Moose est lancée. <br/> <img src="images/MooseImage.png" alt="Moose image" style="width:350px">


## 2. Charger le modèle

Dans une image Moose ouverte, suivre les étapes suivantes afin de charger un modèle : 

1. Ouvrir le **Models browser** à partir du menu; **Moose** > **Models browser** <br/><img src="images/Menu_ModelBrowser.png" alt="drawing" style="width:350px;"/>
2. Dans le Models browser cliquer sur le bouton **File** <img src="images/fileButton.png" alt="File button" style="width:20px;"> pour importer le fichier contenant le modèle. <br/> <img src="images/Models_browser.png" alt="drawing" style="width:350px;"/>
3. Dans la fenêtre d'import, choisir le type de modèle (**FamixCppModel** pour un modèle C++) dans la liste déroulante du champs **Model type**.  <br/> <img src="images/Import_model_from_file.png" alt="drawing" style="width:350px;"/>
4. Choisir le chemin vers le fichier contenant le modèle (avec extension .mse, .ref ou .json) à l'aide du champs **File path**.
5. (Étape optionnelle) Il est possible de lier le modèle avec le code source pour pouvoir utiliser les outils qui nécessitent le code source. Pour cela, choisir le dossier raçine du projet dans le champs **Root folder**.
6. Cliquer sur le bouton **Import**. L'importation peut prendre plusieurs minutes.



## Conseils

- Sauvegarder régulièrement l'image Moose quand c'est nécessaire, afin de ne pas perdre les changements en cas de disfonctionnement de la machine ou de l'image.
- La fonction "Freeze" permet de ne pas écraser l'état d'un browser après la propagation d'entités à partir d'un autre browser. Àprès l'ouverture d'un browser, il est conseillé de le "Freeze", après lui avoir propagé les entités qui l'intéressent.