# Vocale convoluée

<p align="center">
  <a href="https://github.com/Jerboas86/astrone-feedback/blob/master/examples/convolved_speech/lang/en">🇬🇧 English</a> |
  <span>🇫🇷 Français</span>
</p>

## Description

Un fichier audio est joué dans un espace acoustique. L'espace acoustique est représenté par sa réponse impulsionnelle.\
Vous pouvez controler:

- Le volume du bruit à bande étroite à l'aide du slider `Volume`

Vous pouvez trouver des enregistrements de réponses impulsionnelles pour différents lieux, et en libre accès.\
La réponse impulsionnelle `church_ir.wav` utilisée dans cet exemple provient d'une base de donnée de l'université de York ([openair](https://www.openair.hosted.york.ac.uk/))

## Utilisation

- Télécharger le fichier `convolved_speech.astrone` présent dans ce dossier
- Télécharger le fichier audio `monolog.mp3` présent dans le dossier accelerated_speech
- Télécharger le fichier audio `church_ir.wav` présent dans ce dossier
- Importer ce fichier dans le [playground](https://www.astrone.app/playground)
- Ajouter le fichier audio `church_ir.wav` dans la buffer du noeud `Convolver`
- Et ajouter le fichier audio `monolog.mp3` dans la playlist du noeud `AudioPlayer`
