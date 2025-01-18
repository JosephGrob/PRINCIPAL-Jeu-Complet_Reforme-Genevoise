# Jeu interactif sur la Réforme protestante genevoise (XVIème siècle)

## Introduction

Le projet **Jeu interactif sur la Réforme genevoise au XVIème siècle** est une expérience éducative numérique qui invite les utilisateurs à explorer l'histoire et les lieux de la Réforme protestante à Genève à travers une série de mini-jeux interactifs. Ces jeux sont intégrés dans une carte interactive qui sert de point de départ pour découvrir divers aspects culturels, religieux et historiques liés à la Réforme.

Ce jeu est conçu pour être inclus dans une **borne tactile ou sur des tablettes disponibles au public dans un musée** consacré à la Réforme protestante à Genève. L'objectif est de fournir un moyen ludique et immersif de découvrir ou d'approfondir les connaissances sur cette période clé de l'histoire genevoise. 

Nous partons de l'idée que les utilisateurs auront déjà acquis quelques connaissances contextuelles grâce à l'exposition principale du musée. Ainsi, le jeu sert à deux objectifs principaux :
- Pour les visiteurs curieux ou réfractaires aux approches traditionnelles du musée, le jeu constitue un **point d'entrée ludique** pour découvrir la Réforme.
- Pour les visiteurs désireux d'en apprendre davantage, il agit comme un **outil d'approfondissement**, mettant en lumière des aspects complémentaires de l'exposition.

Grâce à sa conception interactive et pédagogique, le jeu s'intègre harmonieusement dans l'expérience muséale et offre une alternative engageante à l'apprentissage passif, tout en restant fidèle au contenu historique du musée.

---

## Objectifs et Public Cible

### Objectifs
- **Sensibilisation historique :** Faire découvrir l’histoire de la Réforme protestante à Genève au XVIème et son impact culturel et religieux.
- **Engagement par le jeu :** Rendre l'apprentissage captivant et ludique grâce à des mini-jeux variés. Tous les mini-jeux sont interconnectés : chaque victoire dans un mini-jeu permet à l'utilisateur de gagner une **lettre**. Ces lettres, une fois réunies, composent l'adresse d'un **lieu secret** à découvrir. Cette mécanique de récompense maintient la motivation de l'utilisateur, l'incitant à explorer tous les mini-jeux lui permettant ainsi d'acquérir les connaissances nécessaires sur cet événement historique.
- **Apprentissage interactif :** Offrir une alternative aux supports traditionnels des musées, adaptée à un public recherchant une expérience plus dynamique.
- **Approfondissement des connaissances :** Permettre aux utilisateurs ayant déjà quelques notions sur la Réforme, acquises grâce à l’exposition du musée, d'approfondir leur compréhension à travers des jeux contextuels.

### Public cible

Le jeu est conçu pour être inclus dans le contexte d'un musée dédié à la Réforme protestante à Genève, et s'adresse à un public diversifié, comprenant :

- **Tous les âges :** Que ce soit des enfants, des adolescents, des adultes ou des seniors, chacun peut participer grâce à des mini-jeux adaptés à différents niveaux de complexité.
- **Tous les niveaux de connaissances :** 
  - **Débutants :** Les visiteurs peu familiers avec la Réforme peuvent explorer et apprendre les bases historiques et culturelles de manière ludique.
  - **Intermédiaires :** Ceux ayant déjà des notions générales sur la Réforme, souvent acquises lors de leur visite au musée, peuvent approfondir leurs connaissances grâce aux jeux interactifs.
  - **Experts :** Les amateurs d’histoire ou les visiteurs aguerris peuvent tester leurs connaissances en explorant des aspects moins connus ou anecdotiques.
- **Groupes scolaires et familles :** Le jeu constitue une activité éducative et collaborative idéale à faire en groupe, permettant aux groupes de visiteurs de partager une expérience immersive tout en découvrant l’histoire de la Réforme.

En tant qu’outil numérique intégré à des bornes tactiles ou à des tablettes disponibles dans le musée, ce jeu s'adapte parfaitement à un large éventail de visiteurs, rendant l'exposition plus dynamique et interactive.


---

## Construction et organisation du jeu répondant aux objectifs et aux publics cibles

Le jeu est structuré en plusieurs mini-jeux, chacun expliqué dans des fichiers .md distincts. Cette organisation facilite la reconstruction du jeu complet, étape par étape, en suivant les explications détaillées de chaque fichier markdown et en consultant les codes correspondants. Le jeu complet repose sur 14 fichiers .html, regroupés en 8 catégories principales en fonction du type de mini-jeu auquel ils appartiennent :

### Pour tester le jeu au complet, vous pouvez utiliser l'URL suivant : 

https://stellular-seahorse-46e01a.netlify.app/index.html

### Si vous voulez observer chaque mini-jeu indépendamment, 
### cliquez sur les liens suivants qui redirigent vers un dépôt GitHub dédié au mini-jeu contenant à la fois un fichier .md explicatif du code et de la façon dont le code a été construit et le(s) fichier(s) .html (le code utilisé) : 

#### Quizz interactif sous la forme de QCM
- [Lien vers le répo Git pour le quizz interactif QCM](https://github.com/JosephGrob/MINI-JEU1-Quizz-Interactif-QCM)

#### Questions-Réponses interactives à relier
- [Lien vers le répo Git pour les questions-réponses interactives](https://github.com/JosephGrob/MINI-JEU2-Questions-Reponses-Relier)

#### Labyrinthe interactif
- [Lien vers le répo Git pour le labyrinthe interactif](https://github.com/JosephGrob/MINI-JEU3-Labyrinthe-Interactif)

#### Ligne temporelle interactive 
- [Lien vers le répo Git pour la ligne temporelle interactive](https://github.com/JosephGrob/MINI-JEU4-Ligne-Temporelle-Jeu)

#### Puzzle interactif statique (sans mouvement des pièces)
- [Lien vers le répo Git pour le puzzle statique interactif](https://github.com/JosephGrob/MINI-JEU5-Puzzle-Statique-Interactif)

#### Puzzle interactif par mouvement des pièces
- [Lien vers le répo Git pour le puzzle interactif dynamique](https://github.com/JosephGrob/MINI-JEU6-Puzzle-Dynamique)

#### Jeu de mémoire interactif
- [Lien vers le répo Git pour le jeu de mémoire interactif](https://github.com/JosephGrob/MINI-JEU7-Memory-Interactif)

#### Jeu de parcours interactif
- [Lien vers le répo Git pour le jeu de parcours interactif](https://github.com/JosephGrob/MINI-JEU8-Parcours-Questions)


---

# 1. Explications Techniques : Réalisation et Fonctionnement de `index.html`

## Introduction de "Index.html" : Fonctionnement global des mini-jeux

Le fichier `index.html` constitue le cœur de l'expérience de jeu, reliant tous les mini-jeux interactifs autour du thème de la Réforme genevoise. À travers une carte interactive basée sur **Leaflet.js**, l'utilisateur peut explorer divers lieux historiques de Genève, chacun associé à un mini-jeu. Une fois les mini-jeux résolus, l'utilisateur débloque des lettres qui composent l'adresse d'un lieu secret, maintenant son engagement tout en favorisant l'apprentissage.

La structure et les fonctionnalités de `index.html` sont conçues pour :

1. Offrir une navigation intuitive via une carte interactive.
2. Gérer les connexions entre les mini-jeux et les lettres débloquées.
3. Suivre les progrès des utilisateurs avec des indicateurs visuels.
4. Présenter un mot mystère final, révélant l'adresse du lieu secret.

---

## Fonctionnalités principales et sections du code "index.html"

### 1. Initialisation de la carte interactive

La carte interactive est le point central de `index.html`. Elle est créée avec la bibliothèque **Leaflet.js** et affiche des marqueurs représentant les lieux historiques. Chaque marqueur est ensuite associé à un mini-jeu.

#### Fonctionnalités principales
- Centrage initial sur Genève et sa vieille ville, le coeur de la Réforme protestante.
- Affichage des marqueurs pour chaque lieu, avec des icônes personnalisées, grâce à leurs URL.
- Association de chaque marqueur à un mini-jeu via un lien.

#### codes utilisés : 

1. Affichage du fond de carte grâce à la bibliothèque **Leaflet.js**:
<div style="border: 1px solid #ddd; padding: 10px; margin: 10px 0;">

```javascript
    var map = L.map('map', {
        zoomControl: true, // Ajout des contrôles de zoom
        maxZoom: 18,       // Niveau de zoom maximum
        minZoom: 10        // Niveau de zoom minimum
    }).setView([46.201959880626424, 6.14730078708044], 17); // Centrage initial sur Genève

    // Ajout d'un calque de tuiles pour afficher les cartes
    L.tileLayer('https://{s}.basemaps.cartocdn.com/light_all/{z}/{x}/{y}{r}.png', {
        attribution: '© CARTO' // Crédits pour le fournisseur de tuiles
    }).addTo(map);

    </div>
```
</div>

2.  Ajouter les marqueurs à la carte (les lieux de la Réforme ici), ajout des popups pour chaque marqueur avec le lien vers le mini-jeu et recentrage de la carte après fermeture des popups:

<div style="border: 1px solid #ddd; padding: 10px; margin: 10px 0;">

```javascript
    function addMarkers(waypoints) {
                // Création d'un marqueur pour un waypoint spécifique et ajout à la carte
                var marker = L.marker(waypoint.coordinates, { icon: icon }).addTo(map);

                // Déterminer le lien vers le mini-jeu pour chaque waypoint
                var miniJeuUrl;
                switch (waypoint.name) {
                    case "Le site archéologique de la Cathédrale Saint-Pierre":
                        miniJeuUrl = 'quizz.html';
                        break;
                    case "La Tour du Molard":
                        miniJeuUrl = 'Sortie_puzzle.html';
                        break;
                    case "La Maison Tavel":
                        miniJeuUrl = 'Europe_Calvin.html';  
                        break;
                    ...
                        
                }

                // Contenu du popup incluant le nom et un lien vers le mini-jeu
                var popupContent = `
                    <div>
                        <strong>${waypoint.name}</strong><br>
                        <a href="${miniJeuUrl}" target="_self">Accès au mini-jeu</a>
                    </div>
                `;

                // Associe le popup au marqueur
                marker.bindPopup(popupContent);

                // Gère l'ouverture du popup lorsque l'utilisateur clique sur le marqueur
                marker.on('click', function() {
                    marker.openPopup();
                });

                // Fonction pour recentrer la carte après la fermeture d'un popup
                map.on('popupclose', function () {
                    // Recentrer la carte sur la position initiale 
                    map.setView([46.201959880626424, 6.14730078708044], 17);
                });
            };

    </div>
```
</div>

3. Les lieux historiques (nos icones) et leurs informations (coordonnées, URL des icônes, etc.) sont définis dans un tableau de données:

<div style="border: 1px solid #ddd; padding: 10px;margin: 10px 0;"> 

```javascript
        // Données des marqueurs avec des icônes personnalisées
        var waypoints = [
            { name: "La fontaine de l'Escalade", coordinates: [46.20374005005952, 6.14376619916994], iconUrl: 'https://cdn-icons-png.flaticon.com/512/382/382316.png' },
            { name: "Le Musée Tatiana Zoubov", coordinates: [46.20169750116412, 6.1445213669340175], iconUrl: 'https://cdn-icons-png.flaticon.com/512/3936/3936764.png' },
            { name: "Le Monument international de la Réformation", coordinates: [46.20021323907556, 6.145877866790115], iconUrl: 'https://cdn-icons-png.flaticon.com/128/5985/5985359.png' },
            { name: "Hôtel de Ville", coordinates: [46.20082826849649, 6.14685899892906], iconUrl: 'https://cdn-icons-png.flaticon.com/512/4797/4797110.png' },
            { name: "L'Ancien Arsenal", coordinates: [46.20118262528934, 6.1470305989292005], iconUrl: 'https://cdn-icons-png.flaticon.com/512/2144/2144733.png' },
            { name: "La Maison Tavel", coordinates: [46.201439880626424, 6.14730078708044], iconUrl: 'https://cdn-icons-png.flaticon.com/512/3936/3936764.png' },
            { name: "La Place du Bourg-de-Four", coordinates: [46.20009574069345, 6.1490588877031715], iconUrl: 'https://cdn-icons-png.flaticon.com/512/9732/9732185.png' },
            { name: "Le Musée international de la Réforme", coordinates: [46.20142631586874, 6.148557910985599], iconUrl: 'https://cdn-icons-png.flaticon.com/512/3936/3936764.png' },
            { name: "La Cathédrale Saint-Pierre", coordinates: [46.20123740229765, 6.1482750374787365], iconUrl: 'https://cdn-icons-png.flaticon.com/512/4313/4313544.png' },
            { name: "Le site archéologique de la Cathédrale Saint-Pierre", coordinates: [46.201085840345335, 6.147888138975222], iconUrl: 'https://cdn-icons-png.flaticon.com/512/3936/3936764.png' },
            { name: "Auditoire de Calvin", coordinates: [46.20085503585228, 6.148318004371298], iconUrl: 'https://cdn-icons-png.flaticon.com/512/9061/9061938.png' },
            { name: "Le Collège Calvin", coordinates: [46.2008686039396, 6.151007748107211], iconUrl: 'https://cdn-icons-png.freepik.com/512/4729/4729436.png' },
            { name: "Eglise Evangélique luthérienne de Genève", coordinates: [46.20097696309722, 6.149556623691599], iconUrl: 'https://cdn-icons-png.flaticon.com/512/9061/9061938.png' },
            { name: "La Tour du Molard", coordinates: [46.20387914429126, 6.148108876482555], iconUrl: 'https://cdn-icons-png.flaticon.com/256/993/993612.png' },
        ];

    </div>

```
</div>

### 2. Gestion des mini-jeux et progression

Chaque mini-jeu est associé à une clé dans `localStorage` pour suivre son état de complétion. Lorsqu'un mini-jeu est terminé, une lettre est débloquée et une icône "OK" s'affiche sur le marqueur correspondant. Une fois tous les mini-jeux complétés, le joueur découvre un lieu secret.

#### Fonctionnalités principales
- **Suivi de progression** : Gestion des états de complétion des mini-jeux à l'aide de `localStorage`.
- **Déblocage des lettres** : Lorsqu'un mini-jeu est terminé, une lettre est ajoutée à une position spécifique pour former l'adresse du lieu secret.
- **Révélation du lieu secret** : Une fois tous les mini-jeux complétés, un marqueur spécial apparaît sur la carte, révélant le lieu final.

#### Codes utilisés

1. Suivi de la progression: 
   Le script vérifie constamment si tous les mini-jeux ont été complétés grâce à un écouteur d'événements sur `storage` et une vérification des clés dans `localStorage`.

<div style="border: 1px solid #ddd; padding: 10px; margin: 10px 0;">

```javascript
   document.addEventListener('DOMContentLoaded', function() {
       checkAllGamesCompleted(); // Vérifie au chargement de la page si tous les jeux sont complétés
       window.addEventListener('storage', function() {
           checkAllGamesCompleted(); // Vérifie dynamiquement si un jeu est terminé
       });
   });

   function checkAllGamesCompleted() {
       const games = [
           'puzzleCompleted',
           'quizCompleted',
           'labyrintheCompleted',
           'reformationGameCompleted',
           'reformationMuseumCompleted',
           'cathedralePuzzleCompleted',
           'europeCalvinCompleted',
           'escaladeGameCompleted',
           'auditoireGameCompleted',
           'bourgDeFourGameCompleted',
           'lutherianQuizCompleted',
           'hotelDeVilleQuizCompleted',
           'collegeCalvinCompleted',
           'tatianaZoubovPuzzleCompleted'
       ];

       // Vérifie si toutes les clés indiquent que les jeux sont terminés
       const allCompleted = games.every(game => localStorage.getItem(game) === 'true');

       if (allCompleted) {
           afficherLieuSecret(); // Affiche le lieu secret si tous les jeux sont terminés
       }
   }

   </div>
```
</div>

2. Déblocage des lettres: 
    Affichage des lettres débloquées lorsqu'un mini-jeu est terminé (via le localStorage), une lettre est placée à une position spécifique pour former l'adresse secrète: 

<div style="border: 1px solid #ddd; padding: 10px; margin: 10px 0;">

```javascript
        // Événement déclenché au chargement de la page
        document.addEventListener('DOMContentLoaded', function() {
            loadAllLetters(); // Charge les lettres
            checkAllGamesCompleted(); // Vérifie si tous les jeux sont terminés
            // Vérifiez si chaque mini-jeu a été complété et placez les lettres correspondantes à la bonne position
            const puzzleCompleted = localStorage.getItem('puzzleCompleted');
            if (puzzleCompleted === 'true') {
                placeLetterAtPosition(2, 'E');
            }

            const quizCompleted = localStorage.getItem('quizCompleted');
            if (quizCompleted === 'true') {
                placeLetterAtPosition(3, 'D');
            }

            const labyrintheCompleted = localStorage.getItem('labyrintheCompleted');
            if (labyrintheCompleted === 'true') {
                placeLetterAtPosition(1, 'U');
            }

            ... 

            </div>

        <div style="border: 1px solid #ddd; padding: 10px; background-color: #f9f9f9; margin: 10px 0;">
        // Place une lettre à une position donnée dans l'affichage
        function placeLetterAtPosition(position, letter) {
            const letterDisplay = document.getElementById(`letter-display-${position}`);
            if (letterDisplay) {
                letterDisplay.textContent = letter;
            } else {
                console.error(`Le conteneur de la lettre à la position ${position} est introuvable.`);
            }
        }

        </div>
```
</div>

3. Clignotement des lettres débloquées:
    Pour rendre l'apparition des lettres plus dynamique et captivante, un effet de clignotement a été ajouté. Cet effet est déclenché lorsqu'une lettre débloquée entre en contact avec un carré transparent placé au-dessus de sa ligne correspondante. Cela permet de renforcer visuellement la progression de l'utilisateur:

<div style="border: 1px solid #ddd; padding: 10px; margin: 10px 0;">

```javascript
        // Vérifie en permanence les chevauchements entre les lettres et les carrés transparents
        function detectOverlap() {
            for (let i = 0; i < 14; i++) {
                const letterDisplay = document.getElementById(`letter-display-${i}`);
                const squareElement = document.getElementById(`transparent-square-${i}`);

                if (!letterDisplay || !squareElement) continue;

                // Récupère les positions des éléments dans la fenêtre
                const letterRect = letterDisplay.getBoundingClientRect();
                const squareRect = squareElement.getBoundingClientRect();

                // Vérifie si les deux éléments se chevauchent
                if (
                    letterRect.left < squareRect.right &&
                    letterRect.right > squareRect.left &&
                    letterRect.top < squareRect.bottom &&
                    letterRect.bottom > squareRect.top
                ) {
                    triggerBlinkAndHide(letterDisplay, squareElement, i);
                }
            }
        }

        </div>

        <div style="border: 1px solid #ddd; padding: 10px; margin: 10px 0;">
        // Ajoute un effet visuel (clignotement) et masque le carré après chevauchement
        function triggerBlinkAndHide(letterDisplay, squareElement, index) {
            if (letterDisplay) {
                letterDisplay.classList.add('blink');
                if (squareElement) {
                    squareElement.style.display = 'none';
                    localStorage.setItem(`square-${index}`, 'hidden');
                }
                setTimeout(() => {
                    letterDisplay.classList.remove('blink');
                }, 3000);

                console.log(`Carré ${index} supprimé et lettre clignotante.`);
            }
        }

        </div>

        <div style="border: 1px solid #ddd; padding: 10px; background-color: #f9f9f9; margin: 10px 0;">
        // Vérifie les chevauchements toutes les 100ms
        setInterval(detectOverlap, 100); 

        // Charge toutes les lettres sauvegardées depuis localStorage
        function loadAllLetters() {
            const linesContainer = document.getElementById('lines-container');

            for (let i = 0; i < 14; i++) {
                const letter = localStorage.getItem(`letter-${i}`);
                if (letter) {
                    const letterDisplay = document.getElementById(`letter-display-${i}`);
                    if (letterDisplay) {
                        letterDisplay.textContent = letter; 
                    }
                }
            }
        }

        </div>
```
</div>

4. A chaque fois qu'un mini-jeu est complété, un "OK" apparait sur l'icone en question. Ceci permet une meilleur expérience utilisatrice, permettant ainsi d'indiquer à l'utilisateur quels mini-jeu sont complétés et ceux qu'il doit encore effectuer. Nous utilisons encore le "localStorage" pour avoir le suivi des jeux complétés: 

<div style="border: 1px solid #ddd; padding: 10px; margin: 10px 0;">

```javascript
        // Fonction pour créer une nouvelle icône "OK" avec l'icône d'origine légèrement transparente pour montrer qu'un mini-jeu est terminé
        function createOkIcon(waypoint) {
            return L.divIcon({
                html: `
                    <div style="position: relative; width: 40px; height: 40px;">
                        <!-- Icône d'origine, légèrement transparente -->
                        <img src="${waypoint.iconUrl}" style="width: 100%; height: 100%; opacity: 0.5;">
                        <!-- Texte "OK" par-dessus -->
                        <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; display: flex; align-items: center; justify-content: center; color: green; font-weight: bold; font-size: 20px;">
                            OK
                        </div>
                    </div>
                `,
                className: 'custom-ok-icon',
                iconSize: [80, 80],  
                iconAnchor: [20, 20] 
            });
        }

        </div>

        <div style="border: 1px solid #ddd; padding: 10px; background-color: #f9f9f9; margin: 10px 0;">
        // Fonction pour ajouter des marqueurs sur la carte
        function addMarkers(waypoints) {
            waypoints.forEach(function(waypoint) {
                let icon;

                // Vérifiez si le mini-jeu de la Tour du Molard est terminé et placer le "OK" sur l'icone
                if (waypoint.name === "La Tour du Molard" && localStorage.getItem('puzzleCompleted') === 'true') {
                    icon = createOkIcon(waypoint); // Icône OK pour la Tour du Molard
                } 
                // Vérifiez si le mini-jeu de la Maison Tavel est terminé et placer le "OK" sur l'icone
                else if (waypoint.name === "La Maison Tavel" && localStorage.getItem('europeCalvinCompleted') === 'true') {
                    icon = createOkIcon(waypoint); // Icône OK pour la Maison Tavel
                } 

                ...

        </div>
```
</div>


5. Révélation du lieu secret
    Une fois que tous les jeux ont été complétés et que toutes les lettres ont été correctement placées, le lieu secret apparait sur la carte. Pour se faire, nous créons un nouveau marqueur qui apparait uniquement lorsque tous les jeux ont été complétés (via le LocalStorage). Ce marqueur apparait ainsi sur la carte et nous ouvrons automatiquement le popup correspondant au marqueur pour que l'utilisateur puisse prendre connaissance de sa récompense. 

<div style="border: 1px solid #ddd; padding: 10px; margin: 10px 0;">

```javascript        
        // Affiche un marqueur pour le lieu secret une fois tous les mini-jeux complétés
        function afficherLieuSecret() {
            const icon = L.divIcon({
                html: `
                    <div style="position: relative; width: 60px; height: 60px; animation: blink 2s 3;">
                        <img src="${lieuSecretIconUrl}" style="width: 100%; height: 100%; border-radius: 50%;">
                    </div>
                `,
                className: '',
                iconSize: [60, 60], 
                iconAnchor: [30, 30], 
            });

            const marker = L.marker(lieuSecretCoordinates, { icon: icon }).addTo(map);

            // Contenu du popup affichant le message final
            const popupContent = `
                <div style="font-family: Arial, sans-serif; text-align: center; display: flex; align-items: center; gap: 15px; padding: 10px;">
                    <!-- Image -->
                    <div style="flex: 1; text-align: center;">
                        <img src="https://www.delcampe.net/static/img_large/auction/000/928/607/614_001.jpg" 
                            alt="Passage Secret du Monetier" 
                            style="max-width: 100%; height: auto; border: 1px solid #ddd; border-radius: 8px; max-height: 150px;">
                    </div>
                    <!-- Texte -->
                    <div style="flex: 2; text-align: left;">
                        <h2 style="color: #2d2d86; font-size: 18px; margin-bottom: 10px;">🎉 Bravo !</h2>
                        <p style="font-size: 14px; line-height: 1.6; color: #333;">
                            Vous avez découvert le passage secret très étroit de <strong>Monetier</strong>, utilisé par les Genevois pour défendre la ville durant la Réforme et durant l'Escalade. Vous pouvez aller le découvrir !
                        </p>
                        <p style="font-size: 14px; color: #2d2d86; font-weight: bold; margin-top: 10px;">
                            Cliquez sur "Recommencer le jeu" pour les prochains utilisateurs!
                        </p>
                    </div>
                </div>
            `;

            marker.bindPopup(popupContent, {
                maxWidth: 600, 
                minWidth: 200, 
            });
            marker.openPopup(); 
        }

        </div>

        <div style="border: 1px solid #ddd; padding: 10px; background-color: #f9f9f9; margin: 10px 0;">
        // Ajoute un observateur pour détecter les changements dans localStorage (au cas où les jeux seraient complétés dynamiquement)
        document.addEventListener('DOMContentLoaded', function() {
            checkAllGamesCompleted();
            window.addEventListener('storage', function() {
                checkAllGamesCompleted();
            });
        });

        </div>
```
</div>

## 3. Optimisation de l'expérience utilisateur

Pour garantir une navigation fluide et intuitive, des éléments ont été ajoutés pour améliorer le confort et la convivialité de l'interface. Cela inclut la gestion de l'inactivité avec un **overlay de rappel**, ainsi que des boutons pratiques pour recentrer la carte ou recommencer le jeu. Ces fonctionnalités permettent de maintenir l'engagement de l'utilisateur tout en lui offrant des options claires pour interagir avec le jeu.

### 3.1 Gestion de l'inactivité avec un overlay

Un système de détection d'inactivité a été implémenté pour éviter que la session reste inutilisée trop longtemps. Lorsqu'aucune interaction n'est détectée, un **overlay** s'affiche pour notifier l'utilisateur et lui offre un bouton pour prolonger la session. Si aucune action n'est prise, le jeu est automatiquement réinitialisé et un nouvel utilisateur peut commencer le jeu sans être "spoilé" par l'avancement du l'utilisateur précédent. 

#### Code utilisé :

1. Affichage de l'overlay et démarrage du compte à rebours :

<div style="border: 1px solid #ddd; padding: 10px; margin: 10px 0;">

```javascript
            // Fonction pour afficher l'overlay et démarrer le compte à rebours
        function showInactivityOverlay() {
            const overlay = document.getElementById('inactivityOverlay');
            const countdownTimer = document.getElementById('countdownTimer');
            let countdown = 60;

            overlay.style.display = 'flex'; // Afficher l'overlay
            countdownTimer.textContent = countdown;

            // Démarrer le compte à rebours
            countdownInterval = setInterval(() => {
                countdown--;
                countdownTimer.textContent = countdown;

                if (countdown === 0) {
                    clearInterval(countdownInterval);
                    resetGame(); 
                }
            }, 1000);

            // Planifier la réinitialisation après 30 secondes si "Continuer le jeu en cours" n'est pas cliqué
            resetTimeout = setTimeout(() => {
                overlay.style.display = 'none'; 
                resetGame();
            }, 30000);
        }

    </div>
```
```javascript
        <div style="border: 1px solid #ddd; padding: 10px; background-color: #f9f9f9; margin: 10px 0;">

        // Fonction pour masquer l'overlay et annuler la réinitialisation si l'utilisateur clique sur "Continuer le jeu en cours"
        function cancelReset() {
            const overlay = document.getElementById('inactivityOverlay');
            overlay.style.display = 'none'; 
            clearTimeout(resetTimeout); 
            clearInterval(countdownInterval); 
            resetOnInactivity(); 
        }

        // Réinitialisation si l'utilisateur reste inactif (sans interaction ou clic sur "Continuer")
        function resetOnInactivity(timeout = 30000) { 
            clearTimeout(inactivityTimeout); 

            inactivityTimeout = setTimeout(() => {
                showInactivityOverlay(); 
            }, timeout);
        }

        // Ajout d'événements uniquement pour surveiller le clic sur "Continuer"
        document.addEventListener('DOMContentLoaded', () => {
            resetOnInactivity(); 

            // Gérer le clic sur le bouton "Continuer"
            document.getElementById('continueButton').addEventListener('click', cancelReset);
        });

        </div>
```
</div>

2. Réinitialisation automatique en cas d'inactivité :

<div style="border: 1px solid #ddd; padding: 10px; margin: 10px 0;">

```javascript
    function resetOnInactivity(timeout = 30000) { 
        clearTimeout(inactivityTimeout); 

        inactivityTimeout = setTimeout(() => {
            showInactivityOverlay(); 
        }, timeout);
    }

    </div>

    <div style="border: 1px solid #ddd; padding: 10px; background-color: #f9f9f9; margin: 10px 0;">
    document.addEventListener('DOMContentLoaded', () => {
        resetOnInactivity(); 

        // Gérer le clic sur le bouton "Continuer"
        document.getElementById('continueButton').addEventListener('click', cancelReset);
    });
    </div>
```
</div>

3. Annulation de la réinitialisation lorsque l'utilisateur reprend la session :

<div style="border: 1px solid #ddd; padding: 10px; margin: 10px 0;">

```javascript
    function cancelReset() {
        const overlay = document.getElementById('inactivityOverlay');
        overlay.style.display = 'none'; 
        clearTimeout(resetTimeout); 
        clearInterval(countdownInterval); 
        resetOnInactivity(); 
    }
    </div>
```
</div>

---

### 3.2 Bouton pour recentrer la carte

Un bouton dédié permet de recentrer la carte sur les coordonnées initiales (la Maison Tavel) pour faciliter l'exploration en cas de désorientation.

#### Code utilisé :
<div style="border: 1px solid #ddd; padding: 10px; margin: 10px 0;">

    ```javascript
    function centerMap() {
        map.setView([46.201959880626424, 6.14730078708044], 17); // Recentre sur Genève
        }

</div>

</div>
```
### 3.3 Bouton pour recommencer le jeu 

Un Bouton dédié permet de recommencer le jeu. Ceci est particulièrement utile pour permettre à l'utilisateur, soit de ré-initialiser le jeu à la fin pour le prochain utilisateur, soit de recommencer volontairement le jeu durant sa partie. Pour faire ceci, nous ré-initialisons le localStorage grâce à la fonction suivante. 

#### Code utilisé : 

    ```javascript
    function resetGame() {
        // Supprime toutes les entrées liées aux mini-jeux
        localStorage.clear();

        // Recharge la page pour réinitialiser l'interface
        location.reload();
    }

    </div>



