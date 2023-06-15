
# Déployer son site Hugo sur Clever Cloud

![Clever Cloud logo](../assets/clever-cool.png)

**Avant tout :** Accepter l'invitation à rejoindre l'organisation envoyée par mail

## 1. Depuis la Console Clever Cloud

1. [Ajouter une clé SSH à son compte](https://www.clever-cloud.com/doc/getting-started/ssh-keys/)
2. Cliquer sur l'organisation **Atelier Hugo**
3. Déclarer une app statique avec les variables d'environnement suivantes :

```shell
CC_CGI_IMPLEMENTATION="proxy_fcgi"
CC_COMPOSER_VERSION="2"
CC_PHP_VERSION="7"
CC_PRE_BUILD_HOOK="./hugo.sh"
CC_WEBROOT="/public"
HUGO_ENV="production"
HUGO_VERSION="0.104.3"
PORT="8080"
```

4. Copier la commande `git push`

## 2.À la racine du code

1. Ajouter le fichier `hugo.sh`
2. Enregistrer le travail avec Git :
   
   - `git add .`
   - `git commit -m "first commit"`
  
3. Coller la commande `git push` copiée depuis la console
