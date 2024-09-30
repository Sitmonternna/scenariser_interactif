# Motus Animi (mouvements de l'esprit) - Sitmonternna Yi

## Idée générale
### Concept
Une immersion intéractive faite à l'aide de l'intelligence artificielle dans un dome accompagnée de musique et décoration lumineuse.

### Objectif
Ce projet vise à offrir aux visiteurs une interaction humaine enrichie par la technologie. Il s’agit également d’une activité conviviale pouvant rassembler de larges groupes, favorisant ainsi le renforcement des liens humains grâce à l’innovation technologique.

### Motivation créative
Ce projet a pour objectif de rassembler les proches tout en démontrant l'utilisation artistique de l'intelligence artificielle. Il cherche à dissiper les stéréotypes associés à l'IA, en montrant qu'elle peut enrichir les interactions humaines et favoriser des moments de partage et de connexion authentiques, même à l’ère numérique.

## Scénario intéractif
### Logigramme de l'intéractivité
```mermaid
flowchart TD
   A[Entrer dans la pièce] --> B(Avancer vers le présentoire)
    A[Entrer dans la pièce]  -->G[Sortir]
    B --> C{Scanné mains sur la boule}
    C -->D[Projection de l'animation]
    D -->F[Sortir]
    D -->E[Bouge les mains sur la boule]
    E -->G[Sortir]
```
<br>

### Narratif
Il n' y a pas de trame narrative, le projet est une immersion intéractive dans un dome.
#### Possibilités fixes
Placer les mains sur la boule pour enclencher la projection/animation.

### Expérience intéractive
#### Installation de la Boule Interactif 
Les participants sont invités à s'approcher d'une boule lumineuse. En plaçant leurs mains dessus, elle déclenche un visuel unique.

#### Scanne 
La boule scannera leur battement de coeur, leur biométrie ainsi que leur température afin de personnaliser leur animation la boule émettera une lumière pour indiquer son processus.

#### Visualisation de l'Énergie 
À mesure qu'ils interagissent avec la boule, une animation générée par l’intelligence artificielle est projetter sur toute la pièce et les lumières changeront de couleurs aussi, représentant leur énergie sous forme de couleurs et  formes abstraites. Chaque interaction est différente, rendant chaque expérience personnelle et unique.

#### Intéractivité avec la boule
À mesure que les visiteurs bouge leur mains l' animation bougera et les couleurs de lumières changeront aussi.

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
Lumières 
<br>
Audio
<br>
Vidéo en temps réel 
<br>
Projection
<br>
Capteurs

### Matériel
Mini Heart Rate Unit (MAX30100) Pulse Oximeter
<br>
Ordinateur
<br>
Lumière en forme de chandelles
<br>
Projecteur
<br>
Haut-parleur
<br>
Capteur de lumière
<br>
Boule semi-transpararente
<br>
Capteur de température et d'humidité numérique
<br>
Lecteur d'empreinte digital

### Logiciels
Touch Designer
<br>
Arduino
<br>
Ebsynth(animation)  
<br>
AIVA(music) 
