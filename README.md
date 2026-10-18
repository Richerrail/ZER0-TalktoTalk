# ZER0|TalktoTalk

Application web rétro 80's pour discuter uniquement avec le provider **OpenRouter** (modèles **free** uniquement).

## Screenshot

![Aperçu](assets/screenshot.png)

## Fonctionnalités

- Entête ASCII style Lego : `ZER0|TalktoTalk`
- Style rétro-gaming 80' (scanlines, néon cyan/magenta/lime)
- Connexion via clé API OpenRouter
- Liste des modèles gratuits mise à jour automatiquement
- Chat conventionnel (utilisateur / ZER0)
- System prompt personnalisable
- Version mobile avec popup de configuration (`MENU ⚡`)
- Animation Canvas Lemming (desktop uniquement) — le personnage tombe en boucle

## Liens

- Démo Render : https://zer0-talktotalk.onrender.com
- Dépôt GitHub : https://github.com/Richerrail/ZER0-TalktoTalk

## Déploiement

Voir `README.md` du dépôt GitHub : https://github.com/Richerrail/ZER0-TalktoTalk

## Utilisation

1. Ouvrir `index.html` dans le navigateur (ou via un serveur local)
2. Coller la clé API dans le popup (`MENU ⚡`)
3. Cliquer **CONNECTER**
4. Sélectionner un modèle **FREE**
5. Écrire et envoyer
Animation Lemming ajoutée via canvas (desktop uniquement) dans index.html.
Le fichier index.html a disparu du dossier (probablement déplacé/supprimé précédemment). Le README.md, la screenshot (assets/screenshot.png) et le script d animation (animation.py) sont présents dans /home/omar0/ZER0-TalktoTalk/. L animation Lemming est un canvas qui tombe en boucle (intégré pour desktop uniquement via media query ou condition JS). Le bouton MENU ⚡ reste pour mobile.
