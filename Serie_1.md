Série d'exercices HTML/CSS

Voici une série d'exercices progressifs pour pratiquer HTML et CSS. Chaque exercice est conçu pour vous faire travailler des concepts spécifiques.

Exercice 1 : Structure de base et sélecteurs simples

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercice 1</title>
    <style>
        /* 1. Changez la couleur de fond de la page en #f0f0f0 */
        
        /* 2. Faites en sorte que tous les h1 soient centrés et de couleur bleue */
        
        /* 3. Donnez une bordure noire de 1px aux paragraphes */
        
        /* 4. Changez la police de tous les éléments en Arial */
    </style>
</head>
<body>
    <h1>Mon premier exercice CSS</h1>
    <p>Ceci est un paragraphe avec du texte.</p>
    <p>Un autre paragraphe pour pratiquer.</p>
    <div>
        <p>Paragraphe dans un div.</p>
    </div>
</body>
</html>

Exercice 2 : Classes et IDs

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercice 2</title>
    <style>
        /* 1. Donnez une couleur rouge à l'élément avec l'ID "special" */
        
        /* 2. Les éléments avec la classe "important" doivent être en gras */
        
        /* 3. Les éléments avec la classe "note" doivent avoir un fond jaune */
        
        /* 4. Créez une classe "hidden" qui masque les éléments */
    </style>
</head>
<body>
    <p id="special">Ce paragraphe est spécial.</p>
    <p class="important">Ceci est très important!</p>
    <div class="note">Ceci est une note à retenir.</div>
    <p class="important note">Ceci est à la fois important et une note.</p>
    <div class="hidden">Ceci ne devrait pas être visible.</div>
</body>
</html>

Exercice 3 : Modèle de boîte (Box Model)

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercice 3</title>
    <style>
        /* 1. Créez une boîte de 200x200px avec bordure, marge et padding */
        
        /* 2. Centrez cette boîte horizontalement dans la page */
        
        /* 3. Ajoutez un espace de 20px entre chaque boîte */
        
        /* 4. Faites en sorte que la bordure soit incluse dans les dimensions */
    </style>
</head>
<body>
    <div class="box">Boîte 1</div>
    <div class="box">Boîte 2</div>
    <div class="box">Boîte 3</div>
</body>
</html>

Exercice 4 : Positionnement

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercice 4</title>
    <style>
        /* 1. Positionnez le header en fixed en haut de la page */
        
        /* 2. La sidebar doit faire 200px de large et être à gauche */
        
        /* 3. Le contenu principal doit s'adapter à l'espace restant */
        
        /* 4. Le footer doit toujours être visible en bas de la fenêtre */
    </style>
</head>
<body>
    <header>En-tête</header>
    <aside class="sidebar">Menu</aside>
    <main>Contenu principal</main>
    <footer>Pied de page</footer>
</body>
</html>

Exercice 5 : Flexbox

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercice 5</title>
    <style>
        /* 1. Utilisez flexbox pour centrer les éléments verticalement et horizontalement */
        
        /* 2. Les éléments doivent s'enrouler sur plusieurs lignes si nécessaire */
        
        /* 3. Chaque élément doit avoir une largeur de 100px et une hauteur de 100px */
        
        /* 4. Espacez les éléments de 10px */
    </style>
</head>
<body>
    <div class="container">
        <div class="item">1</div>
        <div class="item">2</div>
        <div class="item">3</div>
        <div class="item">4</div>
        <div class="item">5</div>
        <div class="item">6</div>
    </div>
</body>
</html>

Exercice 6 : Grid

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercice 6</title>
    <style>
        /* 1. Créez une grille de 3 colonnes égales */
        
        /* 2. Ajoutez un espace de 15px entre les éléments */
        
        /* 3. La première ligne doit faire 100px de haut, les autres 200px */
        
        /* 4. Faites en sorte que le 6ème élément prenne 2 colonnes */
    </style>
</head>
<body>
    <div class="grid-container">
        <div class="grid-item">1</div>
        <div class="grid-item">2</div>
        <div class="grid-item">3</div>
        <div class="grid-item">4</div>
        <div class="grid-item">5</div>
        <div class="grid-item">6</div>
        <div class="grid-item">7</div>
        <div class="grid-item">8</div>
        <div class="grid-item">9</div>
    </div>
</body>
</html>

Exercice 7 : Media Queries

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercice 7</title>
    <style>
        /* 1. Par défaut, la boîte est rouge et fait 200px */
        
        /* 2. Sur écran > 600px, elle devient bleue et 300px */
        
        /* 3. Sur écran > 900px, elle devient verte et 400px */
        
        /* 4. Sur impression, elle devient grise et 150px */
    </style>
</head>
<body>
    <div class="responsive-box">Je m'adapte à la taille de l'écran!</div>
</body>
</html>

Exercice 8 : Animations

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercice 8</title>
    <style>
        /* 1. Animez la boîte pour qu'elle tourne de 360deg en 3s en boucle */
        
        /* 2. Au survol, la boîte doit grossir et changer de couleur */
        
        /* 3. Ajoutez un délai de 0.5s avant le début de l'animation */
        
        /* 4. L'animation doit alterner entre sens normal et inverse */
    </style>
</head>
<body>
    <div class="animated-box"></div>
</body>
</html>

Exercice 9 : Transitions

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercice 9</title>
    <style>
        /* 1. Créez un bouton avec une transition de couleur de fond */
        
        /* 2. Au survol, le bouton doit changer de couleur et de taille */
        
        /* 3. La transition doit durer 0.3s avec un easing "ease-out" */
        
        /* 4. Ajoutez un effet d'ombre portée au survol */
    </style>
</head>
<body>
    <button class="btn">Survolez-moi!</button>
</body>
</html>

Exercice 10 : Variables CSS

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercice 10</title>
    <style>
        /* 1. Déclarez des variables pour les couleurs principales */
        
        /* 2. Utilisez ces variables pour styliser la page */
        
        /* 3. Changez les valeurs des variables dans une media query */
        
        /* 4. Créez une variable pour l'espacement et utilisez-la partout */
    </style>
</head>
<body>
    <header>En-tête</header>
    <main>
        <h1>Titre principal</h1>
        <p>Paragraphe de contenu.</p>
        <button>Bouton</button>
    </main>
    <footer>Pied de page</footer>
</body>
</html>

Pour chaque exercice, écrivez le CSS nécessaire dans les zones prévues à cet effet. Ces exercices couvrent les concepts fondamentaux de CSS et vous permettront de pratiquer les différentes fonctionnalités.

