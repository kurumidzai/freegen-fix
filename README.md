<h2 align="center"> 🛠️ Freegen Fix 🛠️ </h2> 


<h3 align="center">
💻 Version épurée de Freegen avec exe.io, prête à l'emploi. Importez votre jeton exe.io, profitez-en. Base de données allégée. Téléversez et appréciez. Merci à Unfair ! 💻/a> 
</h3>

## 🔭 Configuration de la template
- Déployez le code source sur votre serveur.
- Connectez votre base de données dans le fichier config.php (inc/config.php) à la ligne 22 et au-delà.

## 📱 Configuration des captchas V2
- Rendez-vous sur <a href="https://www.google.com/recaptcha/admin/">le panel d'administration des captchas Google</a>
- Cliquez sur +
  ![image](https://github.com/kurumidzai/freegen-fix/assets/79694235/08218fd8-4db2-4f66-a49c-fadf2aaf7c27)

- ⚠️ Choisissez la version 2 des captchas Google lors du remplissage de vos informations :
  ![image](https://github.com/kurumidzai/freegen-fix/assets/79694235/e4a37638-c76c-430a-ae87-7618750396ff)
- Conservez la clé publique et secrète.
- Insérez votre clé publique dans les balises suivantes :
    <div class="form-group" align="center">
                <div class="g-recaptcha" data-theme="dark" data-sitekey="METTEZ LA CLE ICI"></div>
            </div>
- Vous trouverez cette balise dans ces fichiers et par conséquent Vous devez la mettre dans les     fichiers suivants :
  connexion.php
  inscription.php
  captcha.php
  
- Faites de même pour votre clé secrète dans le fichier :
  inc/fonctions.php
  $secret = 'TA CLé CAPTCHA SECRET';

  
## 🧘‍♂️ Configuration de exe.io  (QUASI RIEN A FAIRE JAI TOUT FAIT)
- Rendez-vous sur <a href="https://exe.io/">exe.io</a>
- Créez votre compte et récupérez votre jeton dans la section <a href="https://exe.io/member/tools/api">API </a>
- Placez-le dans index.php à la ligne $token exe io.


  ### Voilà, c'est fini. Ensuite, partout où il est écrit "freegen" dans les fichiers, remplacez-le par le nom de votre gen, et chaque fois qu'il y a un lien vers le site de Freegen, remplacez-le par le vôtre.


Pour toutes question ajoutez 64a sur discord!
