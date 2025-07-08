# Créez et personnalisez votre site avec Hugo et Go en 1h

<p align="center">
  <img src="assets/gopher.svg" alt="Gopher Logo" width="200">
</p>



Durée totale : 1 heure

Objectif de l'atelier :
L'objectif de cet atelier est de permettre aux participants de créer leur propre site web à l'aide de Hugo, un générateur de sites statiques, et de le personnaliser en utilisant Go, un langage de programmation. À la fin de l'atelier, les participants auront acquis les compétences nécessaires pour créer un site statique avec Hugo et pour personnaliser son apparence en utilisant Go.

## Déroulé détaillé :

### Introduction (5 minutes) :

- Présentation de l'atelier et des objectifs
- Présentation rapide de Hugo et Go
- Installation des prérequis (5 minutes) :
  - [Guide d'installation de Hugo](https://gohugo.io/installation/)
  - [Guide d'installation de Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - [Guide d'installation de Go](https://go.dev/dl/)

<details><summary>Guide détaillé pour l'installation de Go</summary>

  <details><summary>Windows</summary>

   1. Rendez-vous sur le site officiel de Go : <https://golang.org/dl/>
   2. Téléchargez le fichier d'installation correspondant à votre architecture (32 bits ou 64 bits).
   3. Une fois le téléchargement terminé, ouvrez le fichier d'installation (par exemple, go1.x.x.windows-amd64.msi).
   4. Suivez les instructions de l'assistant d'installation et acceptez les conditions de licence.
   5. Choisissez le répertoire d'installation (par défaut, C:\Go\).
   6. Sélectionnez les composants à installer (laissez les options par défaut si vous n'avez pas de préférences spécifiques).
   7. Cliquez sur le bouton "Next" (Suivant) et attendez la fin de l'installation.
   8. Une fois l'installation terminée, ouvrez une nouvelle fenêtre de terminal pour vérifier que Go est bien installé en exécutant la commande `go version`

   </details>

  <details><summary>macOS</summary>

  1. Installez [Homebrew](https://brew.sh/index_fr) sur votre machine si vous ne l'avez pas déjà : `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
  2. Installez Go avec la commande `brew install go`
  3. Vérifiez l'installation avec la commande `go version`

  </details>

  <details><summary>Linux</summary>
  
  1. Ouvrez un navigateur Web et accédez au site officiel de Go : https://golang.org/dl/
  2. Téléchargez le fichier d'archive correspondant à votre architecture Linux (par exemple, `go1.x.x.linux-amd64.tar.gz`)
  3. Ouvrez un terminal et accédez au répertoire où vous avez téléchargé le fichier d'archive.
  4. Extrayez le contenu de l'archive en utilisant la commande tar -xvf go1.x.x.linux-amd64.tar.gz. Remplacez go1.x.x par la version téléchargée.
  5. Déplacez le répertoire extrait vers un emplacement approprié en utilisant la commande sudo mv go /usr/local
  6. Configurez les variables d'environnement en ajoutant les lignes suivantes à votre fichier de configuration de profil (par exemple, ~/.profile, ~/.bash_profile ou ~/.bashrc):

```shell
export GOPATH=$HOME/go
export PATH=/usr/local/go/bin:$PATH
```
  </details>

 </details>

### Démo : création d'un site de base avec Hugo (15 minutes) :

- Explication des concepts de base de Hugo : contenu, modèles, thèmes
- Démonstration de la création d'un nouveau site Hugo
- Création de quelques pages de contenu de base (par exemple : accueil, à propos, contact)
- Aperçu du site généré par Hugo
- Personnalisation du site en utilisant Go et les modules Hugo (solution facile)
- Alternatives les sous-modules git (solution moins facile)

### Mise en pratique

#### 1. Démarrer

Consigne : Créez votre propre site Hugo,  ajoutez un thème et déployez-le en local.

**Ressources :**

- [Guide démarrage d'Hugo](https://gohugo.io/getting-started/quick-start/)
- [Répértoire de thèmes](https://themes.gohugo.io)

#### 2. Créer la page d'accueil

Trouvez le fichier `index.md` et personnalisez votre page d'accueil. Ajoutez  les éléméents suivants :

- une image
- un shortcode

**Ressources :**

- [Guide Markdown](https://www.markdownguide.org/tools/hugo/)
- [Fichiers statiques](https://gohugo.io/content-management/static-files/)
- [Les shortcodes](https://gohugo.io/content-management/shortcodes/)

#### 3. Déployer sur Clever Cloud



Temps pour répondre aux questions des participants
Conclusion (5 minutes) :

Récapitulation des concepts clés abordés pendant l'atelier
Ressources supplémentaires pour approfondir les connaissances sur Hugo et Go
Encouragement à continuer à explorer et à expérimenter avec Hugo et Go
