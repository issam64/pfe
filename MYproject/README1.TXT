premierement pour que le site web marche il faut ajoute database (database.txt) dans phpMYadmin .
pour application remote :
  Premiérement il faut que vous téléchargez Pyton2.7 et le mettre dans le path.

  Deuxiément il faut que vous changer les adresses ip dans les fichiers suivant par 
  votre propre adresse IP:  SERVER => DISPLAY.HTML => line : 19.
                          CLIENT => APP.JS       => line : 06.

  cote server :
      1/ Ouvrir votre terminal bash.
      2/ Taper les commande suivante: 
      cd remote-desktop-master/server;
      npm install 
   
      3/  Taper la commande suivante: 'node index.js' => à ce niveau là, la partie seveur
       sera lancer, et donc le boutton de contrôle dans l'application web sera accessible.
      
      !!! pour la line 6 du fichier display.html au niveau du style (width,height) il faut faire 
      la resolution du pc que vous voulez controler . 
       
     
  cote client :
     1/ Ouvrir votre terminal bash.
     2/ Taper les commande suivante: 
      cd remote-desktop-master/client ;
      npm install elctron ;
      npm install ocket.io-client ;
      npm install screenshot-desktop;
      npm install uuid   
     3/ pour ouvrir application logiciel entrer commande : 
        ->npm start; 