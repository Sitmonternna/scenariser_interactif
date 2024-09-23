# Levana  - Sitmonternna Yi

## Idée générale
### Concept
Les visiteurs sont invités à poser leurs mains sur une boule interactive, où ils pourront observer une illustration générée par une intelligence artificielle, reflétant leur énergie. Les couleurs et les formes abstraites, également créées par l'IA, viendront enrichir cette expérience visuelle unique.

### Objectif
Ce projet vise à offrir aux visiteurs une interaction humaine enrichie par la technologie. Il s’agit également d’une activité conviviale pouvant rassembler de larges groupes, favorisant ainsi le renforcement des liens humains grâce à l’innovation technologique.

### Motivation créative
Ce projet a pour objectif de rassembler les proches tout en démontrant l'utilisation artistique de l'intelligence artificielle, accessible à tous, même à ceux qui n'ont aucune connaissance de cette technologie. Il cherche à dissiper les stéréotypes associés à l'IA, en montrant qu'elle peut enrichir les interactions humaines et favoriser des moments de partage et de connexion authentiques, même à l’ère numérique.

## Scénario intéractif
### Logigramme de l'intéractivité
```mermaid
flowchart TD
    A[Entrer] -->|Observation d'un stand| B(Placer ses mains par dessus la boules)
    B --> C{Observation de projection}
    C -->|Continuer| D[Jouer avec la boule pour bouger projection]
    C -->|Fini| E[Sortir]
    D -->F[Sortir]
```
<br>

### Narratif
Il n' y a pas de contexte narratif dans ce projet.

### Expérience intéractive
1. Installation de la Boule Interactif : Les participants sont invités à s'approcher d'une grande boule lumineuse. En plaçant leurs mains dessus, ils déclenchent une réponse visuelle unique.

2. Visualisation de l'Énergie : À mesure qu'ils interagissent avec la boule, une illustration dynamique générée par l’intelligence artificielle apparaît sur un écran nearby, représentant leur énergie sous forme de couleurs et de formes abstraites. Chaque interaction est différente, rendant chaque expérience personnelle et unique.

3. Partage et Discussion : Après avoir exploré l’illustration, les visiteurs sont encouragés à partager leurs ressentis avec les autres. Des espaces de discussion sont aménagés pour favoriser les échanges sur leurs expériences respectives.

Cette expérience immersive vise à démontrer que la technologie, loin de nous isoler, peut servir de pont pour des interactions humaines enrichissantes.

## Ambiance - moodboard
### Moodboard visuelle
<img src="img/moodboard_visuelle.jpg" >
source images: https://www.lucent-design.co.jp/en/artworks/kaleido-circle/ 
               https://www.teamlab.art/fr/ew/spiral_fireonice/mifuneyama_lamp/
               <br>
               https://meowwolf.com/?gad_source=1&gclid=Cj0KCQjwgL-3BhDnARIsAL6KZ6-_l05LL7f-E_inxbu-6laeTKFXHXHRIVCcIxjQvGWuGWk8kVr1d8EaAlh-EALw_wcB

### Moodboard sonore
[Sonore 1](https://pixabay.com/fr/music/meditation-spirituel-heavenly-energy-188908/)

<br>

[Sonore 2](https://pixabay.com/fr/music/ambiant-ambiant-relax-sounds-10621/)

<br>

[Sonore 3](https://pixabay.com/fr/music/ambiant-lost-in-the-forest-236236/)

<br>

[Sonore 4](https://pixabay.com/fr/music/meditation-spirituel-cave-of-solitude-187589/)


### Références artistiques
<img src="img/reference_artistique.jpg" >
source images: https://www.lucent-design.co.jp/en/artworks/kaleido-circle/ 
               https://www.teamlab.art/fr/ew/spiral_fireonice/mifuneyama_lamp/

## Éléments et technologies nécessaire
### Support médiatique
Utilisation de lumières, audio, vidéo en temps réel et capteur de détection.
### Matériel
Boule Interactive : Un dispositif sensible au toucher capable de détecter les mains des utilisateurs et de générer des réponses visuelles.
<br>
Écran de Projection : Un écran pour afficher les illustrations générées par l’IA.
<br>
Ordinateur : Un PC ou un Mac équipé de logiciels de création visuelle et de programmation d'IA.

### Logiciels
Touch Designer: Création de vidéo, gérer lumières et audio
Arduino: Configuration du capteur
Logiciels d’IA - Ebsynth(animation)  AIVA(music)  : Personnalisation de l' animation, couleur de lumières et sons. 



