<h2 align="center"> 🛠️ Freegen Fix 🛠️ </h2> 

#

<h3 align="center">
💻 Voici la version épurée de Freegen avec exe.io utilisable. Vous pouvez l'utiliser simplement en important votre jeton exe.io. La base de données a été débarrassée de tout élément superflu. Il vous suffit de téléverser et de profiter. Merci à Unfair pour cela !💻</a> 
</h3>

## 🔭 Configuration de la template
- Déployez le code source sur votre serveur.
- Connectez votre base de donné dans le fichier config.php (inc/config.php) a la ligne 22 et le reste.

## 📱 Configuration des captchas V2
- Rendez vous sur <a href="https://www.google.com/recaptcha/admin/">le panel d'administration captcha google</a>
- Cliquez sur +
  ![image](https://github.com/kurumidzai/freegen-fix/assets/79694235/08218fd8-4db2-4f66-a49c-fadf2aaf7c27)

- ⚠️ Choisissez la v2 des googles captchas lors du remplissage de vos infos:
  ![image](https://github.com/kurumidzai/freegen-fix/assets/79694235/e4a37638-c76c-430a-ae87-7618750396ff)
- Gardez de cotez la  clé publique & secrete.
- Inserez votré clé publique dans les balises
    <div class="form-group" align="center">
                <div class="g-recaptcha" data-theme="dark" data-sitekey="METTEZ LA CLE ICI"></div>
            </div>
- Vous devez la mettre dans les fichiers suivants:
  connexion.php
  inscription.php
  captcha.php
  
- Faites de meme pour votre clé secrete dans le fichier:
  inc/fonctions.php
   $secret = 'TA CLé CAPTCHA SECRET';
