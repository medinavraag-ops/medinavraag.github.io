<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>Harmonica - Mon carnet</title>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; -webkit-tap-highlight-color: transparent; }
  body { font-family: system-ui, sans-serif; background: #f5f0e8; }
  #root { min-height: 100vh; }
  textarea, input, button { font-family: inherit; }
  .loading { display:flex; flex-direction:column; align-items:center; justify-content:center; height:100vh; color:#8a7f70; font-family:monospace; gap:12px; padding:20px; text-align:center; }
  .err { color:#c84a6f; font-size:13px; max-width:340px; line-height:1.6; }
</style>
</head>
<body>
<div id="root"><div class="loading">Chargement...</div></div>

<script src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
<script src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>

<script>
function showError(){
  document.getElementById("root").innerHTML =
    '<div class="loading"><div>Impossible de charger l application</div>' +
    '<div class="err">Composants non telecharges. Verifie ta connexion internet et recharge. Une connexion est requise au premier lancement.</div></div>';
}
function loadFallback(cb){
  var s1 = document.createElement("script");
  s1.src = "https://cdn.jsdelivr.net/npm/react@18/umd/react.production.min.js";
  s1.onload = function(){
    var s2 = document.createElement("script");
    s2.src = "https://cdn.jsdelivr.net/npm/react-dom@18/umd/react-dom.production.min.js";
    s2.onload = cb; s2.onerror = showError;
    document.head.appendChild(s2);
  };
  s1.onerror = showError;
  document.head.appendChild(s1);
}
function startApp(){
  try {
    var useState = React.useState, useEffect = React.useEffect, useCallback = React.useCallback, useRef = React.useRef;
const LEXIQUE = [{
  cat: "Bases",
  color: "#2a7a52",
  terms: [{
    word: "Blow / Souffler",
    def: "Expirer à travers l'harmonica (↑). Les notes soufflées sont les notes 'naturelles' - l'instrument est conçu d'abord pour ça."
  }, {
    word: "Draw / Aspirer",
    def: "Inspirer à travers l'harmonica (↓). L'harmonica est l'un des seuls instruments qui produit des notes différentes en inspirant et en expirant. C'est ce qui le rend unique."
  }, {
    word: "Tab / Tablature",
    def: "Notation simplifiée : un numéro de trou + une flèche. ↑ = souffler. ↓ = aspirer. ↓' = bend. Ex : 4↓ = aspirer dans le trou 4."
  }, {
    word: "Accord / Chord",
    def: "Plusieurs notes jouées en même temps. Quand on met plusieurs trous en bouche sans chercher une note précise, on joue un accord. L'harmonica est conçu pour que les accords sonnent juste naturellement."
  }, {
    word: "Registre",
    def: "Zone de l'harmonica selon la hauteur. Bas = trous 1-3 (blues, bends profonds). Moyen = trous 4-6 (zone de confort). Haut = trous 7-10 (plus délicats)."
  }, {
    word: "Le Shift",
    def: "Le passage particulier entre trous 6 et 7. Partout ailleurs on alterne blow/draw en montant. Entre 6 et 7, on passe de draw 6 à draw 7 - deux aspirations de suite. Le seul endroit où ça arrive."
  }, {
    word: "Lick",
    def: "Courte phrase musicale caractéristique, réutilisable. Comme une 'expression toute faite' en musique. Yellow Bird, Shark Fin, Bendus Interruptus sont des licks d'entraînement au bend."
  }, {
    word: "Dynamique",
    def: "La variation de volume. Fort (forte) ou doux (piano), passage progressif (crescendo) ou brusque. Un jeu sans dynamique sonne mécanique."
  }]
}, {
  cat: "Corps & Souffle",
  color: "#c85a20",
  terms: [{
    word: "Fat pipe (gros tuyau)",
    def: "Image pour décrire la gorge ouverte - comme dans un bâillement. Un 'gros tuyau' laisse l'air circuler en silence et en quantité. C'est la base sonore de tout."
  }, {
    word: "Diaphragme",
    def: "Le muscle sous les poumons qui propulse le souffle. Quand le ventre bouge en respirant (et non la poitrine), c'est le diaphragme qui travaille."
  }, {
    word: "Glotte",
    def: "L'ouverture entre les cordes vocales. On peut la contracter légèrement pour 'découper' les notes. C'est le mécanisme du vibrato de gorge et du glottal stop."
  }, {
    word: "Colonne d'air",
    def: "La masse d'air en mouvement de tes poumons jusqu'à l'harmonica. Plus large et en mouvement, plus le son porte sans forcer."
  }, {
    word: "Articulation",
    def: "Donner un début net à chaque note (une 'attaque'). Sans articulation, les notes se fondent sans rythme. Avec T, K ou diaphragme, chaque note a un caractère."
  }]
}, {
  cat: "Bouche & Technique",
  color: "#4a5fa0",
  terms: [{
    word: "Embouchure",
    def: "La position de la bouche sur l'instrument. Sur harmonica : comment les lèvres sont posées sur les covers."
  }, {
    word: "Pucker",
    def: "Embouchure de base : avancer les lèvres comme pour un bisou, réduire l'ouverture pour isoler un seul trou. Méthode la plus simple pour jouer une note unique."
  }, {
    word: "Tongue block",
    def: "Poser la langue à plat sur les trous de gauche pour ne laisser qu'un seul trou ouvert à droite. Ouvre la porte à toutes les textures blues avancées."
  }, {
    word: "K-spot",
    def: "La zone de constriction de la langue contre le palais qui active le bend. Quand on dit 'k' (comme dans 'kuh'), la partie médiane de la langue se rapproche du palais. Ce point, en reculant, réaccorde la cavité buccale et fait descendre la note."
  }, {
    word: "Cup / Main cup",
    def: "Les deux mains formant une chambre autour de l'harmonica. En ouvrant et fermant, on contrôle le timbre (sombre/brillant). Le 'wah' vient d'une ouverture brusque pendant que la note sonne."
  }]
}, {
  cat: "Techniques avancées",
  color: "#8a4a98",
  terms: [{
    word: "Bend",
    def: "Faire descendre la hauteur d'une note en modifiant la forme de la cavité buccale via le K-spot. Pas souffler plus fort - réaccorder l'intérieur de la bouche. Le son caractéristique du blues harmonica."
  }, {
    word: "Bend draw / Bend blow",
    def: "Trous 1-6 : les bends se font en aspirant. Trous 7-10 : les bends se font en soufflant. Dans chaque trou, c'est la note la plus haute qui peut bender vers le bas."
  }, {
    word: "Overblow / Overdraw",
    def: "La note monte au-dessus de sa hauteur naturelle - l'opposé du bend. Rend l'harmonica diatonique capable de toutes les notes chromatiques. Nécessite un harmonica bien réglé."
  }, {
    word: "Vibrato",
    def: "Faire palpiter une note tenue à un rythme régulier. Ne pas s'arrêter et reprendre - juste onduler. Gorge (le plus utilisé en blues), diaphragme, langue ou mains."
  }, {
    word: "Tongue slap",
    def: "En tongue block : commencer avec un accord (langue levée), puis claquer la langue pour ne laisser que la note de mélodie. L'accord initial donne une attaque percussive 'chak-OOOH'."
  }, {
    word: "Split",
    def: "Jouer simultanément deux notes distantes (souvent une octave) en bloquant les trous intermédiaires avec la langue."
  }]
}, {
  cat: "Positions & Tonalités",
  color: "#c8960a",
  terms: [{
    word: "1ère position (straight harp)",
    def: "Jouer dans la tonalité de l'harmonica. Sur un harmonica en Do, on joue en Do. Utilisé pour le folk, les hymnes, les chansons populaires."
  }, {
    word: "2ème position (cross harp)",
    def: "Jouer 5 tons au-dessus. Sur un harmonica en Do, on joue en Sol. C'est LA position du blues. Le draw chord des trous 1-4 devient la note 'maison'."
  }, {
    word: "Blue note",
    def: "Note légèrement en dehors de la gamme, caractéristique du blues. Sur harmonica en Do joué en 2ème position, le Do soufflé crée une tension blues contre la tonalité de Sol."
  }]
}];

// --- DATA EXERCICES -----------------------------------------------------------

const PHASES = [{
  id: "p1",
  subtitle: "Fondations",
  num: "01",
  color: "#2a7a52",
  bg: "#e8f5ee",
  badge: "Jour 1",
  title: "Tenue, bouche, respiration",
  exercises: [{
    id: "p1e1",
    icon: "🤲",
    title: "Main chaude",
    tag: "sans harmonica",
    why: "L'harmonica a des languettes minuscules. Souffler trop fort les distord. Cet exercice calibre l'intensité correcte - tout le reste part de là.",
    steps: ["Tenir la paume à 3 cm de la bouche. Souffler doucement : sentir la chaleur, pas la force.", "Faire pareil en aspirant.", "C'est l'intensité à garder quand on joue."]
  }, {
    id: "p1e2",
    icon: "😮",
    title: "Gorge ouverte - le bâillement",
    tag: "sans harmonica",
    why: "Une gorge fermée étrangle le son. La gorge ouverte (comme dans un bâillement) crée le 'fat pipe' : un conduit d'air large qui amplifie naturellement.",
    steps: ["Bâiller vraiment 2-3 fois. Observer la sensation intérieure.", "Maintenir cette sensation avec la bouche presque fermée.", "Respirer en silence. Si on entend l'air siffler → la gorge s'est refermée. Re-bâiller mentalement."]
  }, {
    id: "p1e3",
    icon: "🎈",
    title: "Exercice du ballon - fermer le nez",
    tag: "sans harmonica",
    why: "Tout l'air doit passer dans l'harmonica, pas par le nez. Une fuite affaiblit le son.",
    steps: ["Fermer les lèvres et simuler le gonflement d'un ballon.", "Les joues se gonflent = nez bien fermé.", "Si les joues ne bougent pas : de l'air fuit par le nez."]
  }, {
    id: "p1e4",
    icon: "🎵",
    title: "Premier son libre",
    tag: "avec l'harmonica",
    why: "Avant de chercher une note précise, s'habituer à la sensation de l'harmonica en bouche et au son des accords naturels. Exploration sans pression.",
    steps: ["Tenir l'harmonica (numéros dessus), l'amener aux lèvres sans bouger la tête.", "Lèvres posées doucement sur les covers jusqu'aux coins.", "Aspirer → accord. Souffler → accord différent. Alterner 5 minutes sans objectif."]
  }, {
    id: "p1e5",
    icon: "🏊",
    title: "Natation douce - 4 temps continu",
    tag: "trous 1-4",
    why: "La respiration doit être un flux continu, pas des à-coups. Entraîne à maintenir un volume constant tout au long du souffle.",
    steps: ["Mettre trous 1-4 en bouche.", "Aspirer 4 temps à volume constant (ni pic, ni fondu).", "Enchaîner l'expiration SANS pause, même volume, 4 temps.", "Répéter 10 fois. Tout le corps reste détendu."]
  }, {
    id: "p1e6",
    icon: "🚂",
    title: "Imitation du train",
    tag: "trous 1-4 . rythme libre",
    why: "Le train transforme le souffle rythmique en jeu musical immédiatement. Pas de 'bonnes' notes - juste du rythme. Premier moment où on se sent vraiment jouer.",
    steps: ["Démarrage lent : aspirer-souffler en rythme sur trous 1-4. 'Chug-chug'. Accélérer comme un train qui démarre.", "À pleine vitesse : accélérer jusqu'au maximum confortable.", "Le sifflet : glisser vers trous 4-6, jouer 2 longues notes soufflées. Revenir sur 1-4.", "Ralentissement : réduire progressivement jusqu'à l'arrêt.", "L'ordre est libre - inventer son propre voyage."]
  }, {
    id: "p1e7",
    icon: "🌊",
    title: "Legato - connecter les notes",
    tag: "son fluide",
    why: "Au debut, presque tout le monde sonne hache : chaque note separee par un petit arret. En gardant le souffle continu quand tu changes de trou, tu sonnes deja mieux que 90% des debutants. C est la difference entre legato (connecte) et staccato (hache).",
    steps: ["Garder la bouche sur l harmonica en permanence - ne jamais la retirer entre les notes.", "Au lieu de : souffler trou 5, ARRETER, retirer la bouche, repositionner sur trou 6, souffler - fais plutot : souffler trou 5, glisser la bouche vers trou 6 SANS arreter le souffle.", "Le souffle doit etre un courant continu pendant tout le glissement, comme une seule respiration qui traverse plusieurs notes.", "S exercer sur une gamme simple (trous 4-5-6-7) en gardant l air qui coule sans interruption du debut a la fin."],
    tabs: [{
      label: "Gamme en legato (souffle continu)",
      notes: [{
        h: 4,
        d: "b"
      }, {
        gliss: true
      }, {
        h: 5,
        d: "b"
      }, {
        gliss: true
      }, {
        h: 6,
        d: "b"
      }, {
        gliss: true
      }, {
        h: 7,
        d: "b",
        beats: 2
      }],
      hint: "Le souffle ne s arrete jamais entre les notes. Glisser, pas sauter."
    }]
  }]
}, {
  id: "p2",
  subtitle: "Fondations",
  num: "02",
  color: "#2a7a52",
  bg: "#e8f5ee",
  badge: "1-3 jours",
  title: "Note unique - le pucker",
  exercises: [{
    id: "p2e1",
    icon: "💋",
    title: "Former le pucker",
    tag: "embouchure",
    why: "L'harmonica donne plusieurs notes à la fois par défaut. Le pucker est la méthode la plus directe pour isoler une seule note - indispensable pour jouer une mélodie.",
    steps: ["Ouvrir la bouche grand, lèvres décontractées.", "Amener l'harmonica jusqu'aux coins de la bouche.", "Laisser l'harmonica glisser légèrement vers l'avant. Rapprocher les coins des lèvres (comme faire la moue).", "Souffler/aspirer doucement. Moins de notes = le pucker fonctionne."],
    tabs: [{
      label: "Test du pucker - trou 4 isole",
      notes: [{
        h: 4,
        d: "b"
      }, {
        h: 4,
        d: "d"
      }, {
        h: 4,
        d: "b"
      }, {
        h: 4,
        d: "d",
        beats: 2
      }],
      hint: "Si tu entends une seule note claire a chaque fois (pas un accord), le pucker fonctionne."
    }]
  }, {
    id: "p2e2",
    icon: "🎯",
    title: "Trouver le trou 4 - Do/Ré",
    tag: "trou 4",
    why: "Le trou 4 est la note de référence centrale et le point de départ de presque tout - gammes, bends, licks blues. L'identifier à l'oreille et au toucher, sans regarder.",
    steps: ["Compter 4 trous depuis la gauche, numéros dessus.", "Trou 4 soufflé = Do. Trou 4 aspiré = Ré.", "Alterner aspiration/expiration en pucker 3 minutes."],
    schema: "harmonica-layout"
  }, {
    id: "p2e3",
    icon: "🚶",
    title: "Gamme Do - trous 4 à 7",
    tag: "registre médian",
    why: "Connaître les notes de la gamme de Do sur l'harmonica est la carte du territoire. Toutes les mélodies utilisent ces positions.",
    steps: ["Jouer chaque note lentement - attendre qu'elle soit propre avant de bouger.", "⚠ Le Shift trous 6-7 : deux aspirations de suite - seule exception au pattern.", "Redescendre la gamme dans l'autre sens."],
    tabs: [{
      label: "Gamme de Do (montante)",
      notes: [{
        h: 4,
        d: 'b'
      }, {
        h: 4,
        d: 'd'
      }, {
        h: 5,
        d: 'b'
      }, {
        h: 5,
        d: 'd'
      }, {
        h: 6,
        d: 'b'
      }, {
        h: 6,
        d: 'd'
      }, {
        h: 7,
        d: 'd'
      }, {
        h: 7,
        d: 'b'
      }],
      hint: "Do - Ré - Mi - Fa - Sol - La - Si - Do"
    }]
  }]
}, {
  id: "p3",
  subtitle: "Fondations",
  num: "03",
  color: "#2a7a52",
  bg: "#e8f5ee",
  badge: "1-2 sem.",
  title: "Déplacements et premières mélodies",
  exercises: [{
    id: "p3e1",
    icon: "👆",
    title: "Sauter sans entendre les notes entre",
    tag: "déplacement",
    why: "Quand on glisse pour sauter plusieurs trous, les notes intermédiaires s'entendent. Cette technique apprend à les masquer.",
    steps: ["Changer la direction du souffle en premier (avant de glisser).", "Glisser vers la note cible en écoutant quand on arrive.", "Réduire progressivement les notes entendues en accélérant le passage."]
  }, {
    id: "p3e2",
    icon: "🎵",
    title: "Frère Jacques",
    tag: "mélodie",
    why: "Mélodie connue de tous : si ce qu'on joue correspond à ce qu'on entend dans sa tête, on est sur la bonne voie - sans lire de partition.",
    steps: ["Apprendre phrase 1 seule, puis phrase 2, puis enchaîner.", "La 3ème phrase (les cloches) est plus rapide - la travailler séparément."],
    tabs: [{
      label: "Phrase 1 (×2)",
      notes: [{
        h: 4,
        d: 'b'
      }, {
        h: 4,
        d: 'd'
      }, {
        h: 5,
        d: 'b'
      }, {
        h: 4,
        d: 'b'
      }, {
        sep: true
      }, {
        h: 4,
        d: 'b'
      }, {
        h: 4,
        d: 'd'
      }, {
        h: 5,
        d: 'b'
      }, {
        h: 4,
        d: 'b'
      }]
    }, {
      label: "Phrase 2 (×2)",
      notes: [{
        h: 5,
        d: 'b'
      }, {
        h: 5,
        d: 'd'
      }, {
        h: 6,
        d: 'b'
      }, {
        sep: true
      }, {
        h: 5,
        d: 'b'
      }, {
        h: 5,
        d: 'd'
      }, {
        h: 6,
        d: 'b'
      }]
    }, {
      label: "Phrase 3 - les cloches (×2)",
      notes: [{
        h: 6,
        d: 'b'
      }, {
        h: 5,
        d: 'd'
      }, {
        h: 5,
        d: 'b'
      }, {
        h: 4,
        d: 'd'
      }, {
        sep: true
      }, {
        h: 6,
        d: 'b'
      }, {
        h: 5,
        d: 'd'
      }, {
        h: 5,
        d: 'b'
      }, {
        h: 4,
        d: 'd'
      }],
      hint: "Cette phrase est plus rapide"
    }]
  }, {
    id: "p3e3",
    icon: "⏱️",
    title: "Tenir le tempo même si note fausse",
    tag: "rythme avant tout",
    why: "S'arrêter pour corriger une note casse le rythme - c'est pire que la note fausse. Le tempo doit devenir un réflexe inconscient avant la précision.",
    steps: ["Jouer une mélodie simple avec un tempo stable.", "Ne pas s'arrêter si on manque une note. Continuer en maintenant le rythme.", "Travailler la note fausse séparément, hors contexte."]
  }]
}, {
  id: "p4",
  subtitle: "Fondations",
  num: "04",
  color: "#2a7a52",
  bg: "#e8f5ee",
  badge: "1-2 sem.",
  title: "Rythme & blues 12 mesures",
  exercises: [{
    id: "p4e1",
    icon: "🥁",
    title: "Les 3 rythmes blues",
    tag: "trous 1-4",
    why: "Le blues repose d'abord sur le rythme. Avec 3 patterns simples, on joue un blues complet à 12 mesures - même sans savoir bender.",
    steps: ["Rythme A : aspirer sur les temps forts (trous 1-4). Commence ET finit en aspirant.", "Rythme B : souffler sur les temps forts (trous 1-4). Commence ET finit en soufflant.", "Rythme C : même pattern que A mais glisser 1-2 trous vers la droite (trous 2-5).", "Blues 12 mesures : A-A-B-A-C-A (chaque rythme = 2 mesures).", "Travailler d'abord A↔B en alternance avant d'ajouter C."],
    schema: "three-rhythms",
    extraSchema: "twelve-bar"
  }, {
    id: "p4e2",
    icon: "🖐️",
    title: "Cup wah - ouvrir pendant la note",
    tag: "expression",
    why: "Le 'wah' est une des couleurs sonores les plus expressives. L'ouverture PENDANT la note (et non avant) est la clé.",
    steps: ["Mains fermées → jouer l'accord. Son sombre.", "Ouvrir la main droite (pivot sur le poignet) PENDANT que l'accord continue.", "L'ouverture doit se faire pendant la note, pas avant."],
    tabs: [{
      label: "Wah sur accord aspire",
      notes: [{
        h: [1, 2, 3],
        d: "d",
        beats: 4
      }],
      hint: "Tenir l'accord 4 temps. Mains fermees au debut, ouvrir progressivement vers la fin (le wah)."
    }]
  }, {
    id: "p4e3",
    icon: "🚂",
    title: "Train + wah",
    tag: "rythme + expression",
    why: "Le train avec cup wah combine rythme, dynamique et expression en un seul exercice. C'est souvent spectaculaire dès les premiers jours.",
    steps: ["Reprendre l'imitation du train avec le cup wah sur les temps forts.", "Pour le sifflet : aller sur trous 4-6 soufflés, appliquer le wah sur les deux longues notes.", "Expérimenter : changer la vitesse, ajouter des accélérations, inventer des arrêts."]
  }]
}, {
  id: "p5",
  subtitle: "Expression & Son",
  num: "05",
  color: "#c85a20",
  bg: "#fdf0e8",
  badge: "2-4 sem.",
  title: "Projection, dynamique, articulation",
  exercises: [{
    id: "p5e1",
    icon: "📢",
    title: "Auditeur qui recule - crescendo",
    tag: "dynamique",
    why: "Jouer fort sans distorsion est une compétence. Cet exercice apprend à trouver le volume maximum utilisable - celui où le son reste plein et beau.",
    steps: ["Jouer l'exercice de natation douce (trous 1-4, cycles 4 temps).", "Imaginer l'auditeur qui recule un pas à la fois.", "Augmenter légèrement le volume à chaque pas. S'arrêter au premier signe de distorsion."]
  }, {
    id: "p5e2",
    icon: "🤫",
    title: "Bébé qui dort - décrescendo",
    tag: "dynamique",
    why: "Jouer doucement sans perdre la qualité est aussi difficile que jouer fort. Un jeu expressif alterne les deux.",
    steps: ["Partir du volume maximum atteint.", "Réduire progressivement jusqu'au quasi-silence.", "Ne jamais s'arrêter de jouer pendant l'exercice."]
  }, {
    id: "p5e3",
    icon: "😈",
    title: "Rire du vilain - activer le diaphragme",
    tag: "articulation",
    why: "Le diaphragme bien activé donne une puissance et une profondeur au son qu'on ne peut pas obtenir autrement.",
    steps: ["Poser une main sur l'abdomen sous les côtes.", "Dire 'Hah!' en sentant le ventre rebondir vers l'extérieur.", "Enchaîner 'Hah-Hah-Hah-Hah' sur un souffle continu - comme le rire d'un vilain de film.", "Avec harmonica trou 4 : appliquer sur blow et draw."],
    tabs: [{
      label: "Rire du vilain - trou 4",
      notes: [{
        h: 4,
        d: "b"
      }, {
        h: 4,
        d: "b"
      }, {
        h: 4,
        d: "b"
      }, {
        h: 4,
        d: "b"
      }],
      hint: "Hah-Hah-Hah-Hah avec coup de ventre a chaque note. Meme note, 4 attaques distinctes."
    }]
  }, {
    id: "p5e4",
    icon: "👅",
    title: "Articulation T - attaque nette",
    tag: "articulation",
    why: "Sans articulation, les notes se fondent en bouillie. Le T donne une attaque précise à chaque note - comme les syllabes qui découpent les mots dans une phrase.",
    steps: ["Sans harmonica : 'Aaaa-Taaa-Taaa-Taaa' sur un souffle continu.", "Avec harmonica trou 4 aspiré : jouer une note longue et l'interrompre avec des T réguliers.", "Double tonguing rapide : 'Diddle-diddle' (T et L alternés)."],
    tabs: [{
      label: "Articulation T - trou 4 aspiré",
      notes: [{
        h: 4,
        d: "d"
      }, {
        h: 4,
        d: "d"
      }, {
        h: 4,
        d: "d"
      }, {
        h: 4,
        d: "d",
        beats: 2
      }],
      hint: "Une seule note longue interrompue par des T réguliers - comme TtTtTtTt."
    }]
  }]
}, {
  id: "p6",
  subtitle: "Expression & Son",
  num: "06",
  color: "#c85a20",
  bg: "#fdf0e8",
  badge: "2-4 sem.",
  title: "Vibrato - faire palpiter les notes",
  exercises: [{
    id: "p6e1",
    icon: "🎤",
    title: "Vibrato de gorge ★",
    tag: "à maîtriser en 1er",
    why: "Le vibrato transforme une note tenue en quelque chose de vivant. Le vibrato de gorge est le plus utilisé en blues - il crée le 'throb' des grands harmonicistes.",
    steps: ["Chuchoter '!Ah-!Ah-!Ah-!Ah' : pulsations séparées à la glotte.", "Connecter ces pulsations : flux continu avec pulsations douces, sans jamais couper l'air.", "Avec harmonica trou 4 aspiré : maintenir et appliquer les pulsations de gorge.", "⚠ L'abdomen ne doit PAS bouger - tout se passe à la glotte."],
    tabs: [{
      label: "Vibrato de gorge sur Draw 4",
      notes: [{
        h: 4,
        d: "d",
        beats: 4
      }],
      hint: "Une seule note tenue 4 temps avec pulsations de gorge régulières dessus."
    }]
  }, {
    id: "p6e2",
    icon: "🤏",
    title: "Vibrato de main - 3 niveaux",
    tag: "expression",
    why: "Le vibrato de main change le timbre en plus du volume - très utilisé en blues acoustique pour 'projeter' le son.",
    steps: ["Pinkie vibrato : lever/baisser le petit doigt. Très subtil.", "Wrist rock : pivoter le poignet pour ouvrir/fermer par les bords. Modéré.", "Elbow swing : pivoter tout l'avant-bras depuis le coude. Maximal."]
  }, {
    id: "p6e3",
    icon: "📐",
    title: "Synchroniser vibrato sur le temps",
    tag: "musicalité",
    why: "Un vibrato synchronisé sur le rythme sonne musical et intentionnel. C'est la différence entre un tremblement et une expression.",
    steps: ["Tenir Draw 4. Battre le pied sur le temps.", "Produire exactement 2 pulsations de gorge par battement de pied.", "Puis essayer 3 pulsations par temps."]
  }]
}, {
  id: "p7",
  subtitle: "Tongue Block",
  num: "07",
  color: "#4a5fa0",
  bg: "#eeeef8",
  badge: "2-6 sem.",
  title: "Tongue block - bases",
  exercises: [{
    id: "p7e1",
    icon: "👅",
    title: "Former le tongue block",
    tag: "trou 4",
    why: "Le tongue block donne accès à des textures sonores impossibles en pucker : accords + mélodie simultanés, slap, rake, shimmer, splits.",
    steps: ["Ouvrir la bouche pour trous 1-4 en bouche.", "Poser la langue à plat sur les trous 1, 2, 3. Trou 4 libre à droite.", "Souffler → Do. Aspirer → Ré. Note unique.", "Lever la langue → accord complet. Alterner 10 fois."],
    tabs: [{
      label: "Tongue block - trou 4 isole",
      notes: [{
        h: 4,
        d: "b"
      }, {
        h: 4,
        d: "d"
      }, {
        h: 4,
        d: "b"
      }, {
        h: 4,
        d: "d"
      }],
      hint: "Langue posee sur trous 1-2-3, seul le trou 4 sonne. Note unique, pas accord."
    }]
  }, {
    id: "p7e2",
    icon: "🐑",
    title: "Mary Had a Groovin' Little Lamb",
    tag: "mélodie + accords",
    why: "Premier exercice qui combine mélodie et accords simultanément. La mélodie sur le tempo fort, l'accord sur les temps faibles - c'est immédiatement le son du blues.",
    steps: ["Jouer 'Mary Had a Little Lamb' en tongue block note unique.", "Lever la langue sur les 2ème et 4ème temps de chaque mesure pour ajouter l'accord.", "Rythme : mélodie (langue posée) - accord (langue levée) - mélodie - accord."],
    tabs: [{
      label: "Mary Had a Little Lamb - version tongue block",
      notes: [{
        h: 5,
        d: 'b'
      }, {
        h: 4,
        d: 'd'
      }, {
        h: 4,
        d: 'b'
      }, {
        h: 4,
        d: 'd'
      }, {
        sep: true
      }, {
        h: 5,
        d: 'b'
      }, {
        h: 5,
        d: 'b'
      }, {
        h: 5,
        d: 'b'
      }, {
        sep: true
      }, {
        h: 4,
        d: 'd'
      }, {
        h: 4,
        d: 'd'
      }, {
        h: 4,
        d: 'd'
      }, {
        sep: true
      }, {
        h: 5,
        d: 'b'
      }, {
        h: 6,
        d: 'b'
      }, {
        h: 6,
        d: 'b'
      }],
      hint: "* = lever la langue (accord) sur les temps 2 et 4"
    }]
  }, {
    id: "p7e3",
    icon: "💥",
    title: "Tongue slap - attaque percussive",
    tag: "effet blues",
    why: "Le tongue slap donne de la percussivité à chaque note. On l'entend dans presque tous les grands enregistrements de blues Chicago.",
    steps: ["Jouer un accord (trous 1-4, mélodie à droite).", "Claquer la langue sur les trous de gauche, net et rapide.", "Résultat : 'chak-OOOH' - attaque chord + résolution sur la note seule."],
    tabs: [{
      label: "Tongue slap sur trou 4",
      notes: [{
        h: [1, 2, 3, 4],
        d: "d"
      }, {
        h: 4,
        d: "d",
        beats: 2
      }],
      hint: "Bref accord (langue levée) puis claquer la langue - seul le trou 4 reste audible."
    }]
  }]
}, {
  id: "p8",
  subtitle: "Bends",
  num: "08",
  color: "#c85a20",
  bg: "#fdf0e8",
  badge: "2-6 sem.",
  title: "Premier bend - Draw 4",
  exercises: [{
    id: "p8e1",
    icon: "👄",
    title: "Explorer le palais - trouver le K-spot",
    tag: "sans harmonica",
    why: "Le bend se passe à l'intérieur de la bouche. Avant de l'essayer avec l'harmonica, il faut cartographier cette zone à l'aveugle.",
    steps: ["Toucher la pointe de la langue aux dents du haut, la faire glisser vers l'arrière en sentant le palais.", "Dire 'kuh-kuh-kuh' doucement. Sentir où la langue touche le palais = K-spot.", "Chuchoter 'eee-ooh' avec lèvres en 'ooh'. Sentir la langue reculer de 'eee' vers 'ooh'. C'est le geste du bend."],
    schema: "bend-map"
  }, {
    id: "p8e2",
    icon: "🎯",
    title: "Activer le bend - Draw 4",
    tag: "trou 4 aspiré",
    why: "Le trou 4 aspiré est le point de départ idéal : amplitude d'un demi-ton seulement, plus facile à contrôler que les trous 2 et 3.",
    steps: ["Jouer Draw 4 en pucker. Maintenir la note.", "Rapprocher la langue du palais sans le toucher (K-spot) - sentir une légère succion.", "Faire glisser le K-spot vers l'arrière doucement. Si la note descend → c'est un bend.", "⚠ Ne jamais aspirer plus fort. C'est la langue qui fait le travail."],
    tabs: [{
      label: "Test du bend Draw 4",
      notes: [{
        h: 4,
        d: "d"
      }, {
        h: 4,
        d: "bd",
        b: 1
      }],
      hint: "Draw 4 normal, puis meme trou langue reculee doucement - la note doit descendre legerement."
    }]
  }, {
    id: "p8e3",
    icon: "🐦",
    title: "Lick Yellow Bird - bend et release",
    tag: "étape 1",
    why: "L'aller-retour 'normal → bendé → normal' est la base de toute expression blues. Le 'pleur' de l'harmonica vient de ce mouvement.",
    steps: ["Draw 4 normal → bend down → Draw 4 normal.", "Penser 'Eee-Ooh-Eee'.", "Pour un son qui pleure : fermer les mains au bend, les ouvrir au relâchement."],
    tabs: [{
      label: "Yellow Bird - trou 4",
      notes: [{
        h: 4,
        d: 'd'
      }, {
        h: 4,
        d: 'bd',
        b: 1
      }, {
        h: 4,
        d: 'd'
      }],
      hint: "Penser : Eee → Ooh → Eee . Faire ×3 avec les trous 5 et 6"
    }]
  }, {
    id: "p8e4",
    icon: "⏸️",
    title: "Bendus Interruptus - tenir et reprendre",
    tag: "étapes 2 et 3",
    why: "Bender n'est que la moitié du travail. Tenir la note baisssée et la reprendre depuis cette position permet de jouer les blue notes comme des notes normales.",
    steps: ["Étape 2 : Draw 4 → bend → STOP le souffle (sans relâcher la langue). La note reste baisssée.", "Étape 3 : reprendre le souffle sans bouger la langue → la note repart déjà baisssée.", "Penser 'Eee-Ooh! … Ooh-Eee'. Ne rien bouger quand on stoppe."],
    tabs: [{
      label: "Bendus Interruptus - trou 4",
      notes: [{
        h: 4,
        d: 'd'
      }, {
        h: 4,
        d: 'bd',
        b: 1
      }],
      hint: "STOP après le bend (silence) → reprendre Draw 4 bendé → relâcher jusqu'à Draw 4 normal"
    }]
  }]
}, {
  id: "p9",
  subtitle: "Bends",
  num: "09",
  color: "#c85a20",
  bg: "#fdf0e8",
  badge: "1-3 mois",
  title: "Bends trous 2 et 3 - cœur du blues",
  exercises: [{
    id: "p9e1",
    icon: "2️⃣",
    title: "Bend Draw 2 - 1 et 2 demi-tons",
    tag: "trou 2 aspiré",
    why: "Le Draw 2 bendé est l'une des notes les plus importantes du blues. Il donne le gémissement central de la 2ème position.",
    steps: ["Yellow Bird lick sur Draw 2. Écouter lequel arrive en premier : superficiel (1 demi-ton) ou profond (2 demi-tons).", "Travailler le premier obtenu avant de chercher l'autre.", "Bend profond : K-spot plus reculé, mâchoire légèrement baisssée. Penser 'eee-YOO'."],
    tabs: [{
      label: "Draw 2 - superficiel (1 demi-ton) et profond (2 demi-tons)",
      notes: [{
        h: 2,
        d: 'd'
      }, {
        h: 2,
        d: 'bd',
        b: 1
      }, {
        h: 2,
        d: 'd'
      }, {
        sep: true
      }, {
        h: 2,
        d: 'd'
      }, {
        h: 2,
        d: 'bd',
        b: 2
      }, {
        h: 2,
        d: 'd'
      }],
      hint: "' = 1 demi-ton . '' = 2 demi-tons . Identifier lequel arrive en premier"
    }]
  }, {
    id: "p9e2",
    icon: "3️⃣",
    title: "Bend Draw 3 - jusqu'à 3 demi-tons",
    tag: "trou 3 aspiré",
    why: "Le trou 3 est le plus large bend de l'harmonica. Il contient 3 notes bendées. C'est le trou le plus difficile mais aussi le plus riche.",
    steps: ["3 niveaux : superficiel (Sib), intermédiaire (La), profond (Lab).", "L'intermédiaire est le plus utilisé en blues. Identifier lequel arrive en premier.", "Lick Cool Juke : bend superficiel → bend intermédiaire → Draw 2."],
    tabs: [{
      label: "Draw 3 - les 3 niveaux de bend",
      notes: [{
        h: 3,
        d: 'd'
      }, {
        h: 3,
        d: 'bd',
        b: 1
      }, {
        h: 3,
        d: 'd'
      }, {
        sep: true
      }, {
        h: 3,
        d: 'd'
      }, {
        h: 3,
        d: 'bd',
        b: 2
      }, {
        h: 3,
        d: 'd'
      }, {
        sep: true
      }, {
        h: 3,
        d: 'd'
      }, {
        h: 3,
        d: 'bd',
        b: 3
      }, {
        h: 3,
        d: 'd'
      }],
      hint: "1 demi-ton = Sib . 2 demi-tons = La . 3 demi-tons = Lab . Commencer par le plus profond (le fond 'attire' la langue)"
    }]
  }, {
    id: "p9e3",
    icon: "🦈",
    title: "Shark Fin - enchaîner bend et blow",
    tag: "étape 4",
    why: "En blues, le bend doit s'enchaîner naturellement avec les autres notes. Le Shark Fin apprend à passer du bend au blow et retour sans note 'normale' accidentelle entre les deux.",
    steps: ["Blow 3 → Draw 3 bendé → Blow 3. Penser 'Hoo-Eee-Hoo'.", "Ne pas laisser la note Draw 3 normale s'entendre entre le bend et le blow.", "Baisser la langue juste assez pour le blow, la reprendre aussitôt."],
    tabs: [{
      label: "Shark Fin - trou 3",
      notes: [{
        h: 3,
        d: 'b'
      }, {
        h: 3,
        d: 'bd',
        b: 2
      }, {
        h: 3,
        d: 'b'
      }],
      hint: "Penser : Hoo → Eee → Hoo . Pas de Draw 3 normal entre les deux"
    }]
  }]
}, {
  id: "p10",
  subtitle: "Tongue Block",
  num: "10",
  color: "#4a5fa0",
  bg: "#eeeef8",
  badge: "2-4 mois",
  title: "Rake, shimmer, splits, corner switching",
  exercises: [{
    id: "p10e1",
    icon: "〰️",
    title: "Chord rake - balayage rythmique",
    tag: "texture blues",
    why: "Le rake est la texture rythmique de base du Chicago blues. Il donne ce son 'cliquetant' qu'on entend chez Little Walter.",
    steps: ["Tongue block sur trous 1-4, mélodie trou 4 (droite).", "Glisser la langue vers la droite : trou 1 libre à gauche.", "Alterner entre ces deux positions en rythme : droite-gauche-droite-gauche."],
    tabs: [{
      label: "Rake sur trous 1-4",
      notes: [{
        h: [1, 2, 3, 4],
        d: "d"
      }, {
        h: [1, 2, 3, 4],
        d: "d"
      }, {
        h: [1, 2, 3, 4],
        d: "d"
      }, {
        h: [1, 2, 3, 4],
        d: "d"
      }],
      hint: "Meme accord 4 fois, la langue alterne sa position de gauche a droite a chaque coup."
    }]
  }, {
    id: "p10e2",
    icon: "✨",
    title: "Shimmer - trémolo rapide",
    tag: "texture brillante",
    why: "Le shimmer crée un effet de trémolo brillant entre deux notes éloignées. Un ornement expressif qui rend une note plus vibrante.",
    steps: ["Deux notes distantes (ex. trous 1 et 4) dans la bouche simultanément.", "La langue passe très rapidement de l'un à l'autre - beaucoup plus vite que le rake.", "Commencer lentement pour bien séparer les deux sons, puis accélérer."],
    tabs: [{
      label: "Shimmer trous 1 et 4",
      notes: [{
        h: 1,
        d: "d"
      }, {
        h: 4,
        d: "d"
      }, {
        h: 1,
        d: "d"
      }, {
        h: 4,
        d: "d"
      }, {
        h: 1,
        d: "d"
      }, {
        h: 4,
        d: "d"
      }],
      hint: "Les deux notes dans la bouche en même temps, la langue alterne très vite."
    }]
  }, {
    id: "p10e3",
    icon: "↔️",
    title: "Corner switching - sauts larges propres",
    tag: "agilité",
    why: "Pour sauter rapidement de plusieurs trous sans entendre les notes intermédiaires.",
    steps: ["Mettre en bouche les deux trous du saut (ex. trous 1 et 4).", "Langue sur les trous du milieu : seul trou 4 (droite) ouvert. Jouer.", "Glisser langue à droite : seul trou 1 (gauche) ouvert. Jouer."],
    tabs: [{
      label: "Corner switching trous 1 et 4",
      notes: [{
        h: 1,
        d: "d"
      }, {
        h: 4,
        d: "d"
      }, {
        h: 1,
        d: "d"
      }, {
        h: 4,
        d: "d"
      }],
      hint: "Saut propre entre trou 1 et trou 4 sans entendre les trous entre les deux."
    }]
  }, {
    id: "p10e4",
    icon: "🎸",
    title: "Locked split - octaves en mouvement",
    tag: "harmonie",
    why: "Jouer en octaves simultanées donne une plénitude sonore et une puissance qu'une seule note ne peut pas atteindre.",
    steps: ["Ouvrir sur 4 trous, langue bloquant les 2-3 du milieu, notes aux deux coins.", "Glisser l'harmonica en conservant cet écart fixe.", "Blow en 4 trous d'écart = octaves propres."],
    tabs: [{
      label: "Split octave trous 1 et 5",
      notes: [{
        h: [1, 5],
        d: "b"
      }, {
        h: [1, 5],
        d: "b",
        beats: 2
      }],
      hint: "Les deux coins (trou 1 et trou 5) jouent en même temps - même note, une octave d écart."
    }]
  }]
}, {
  id: "p_flair",
  subtitle: "Ornements et Vitesse",
  num: "10+",
  color: "#c85a20",
  bg: "#fdf0e8",
  badge: "2-4 mois",
  title: "Ornements — flair et velocite",
  exercises: [{
    id: "pflair1",
    icon: "〰️",
    title: "Shake — le trille",
    tag: "ornement essentiel",
    why: "Le shake est l ornement blues le plus utilise. Il transforme une note ordinaire en texture vivante et expressive. On l entend dans presque tous les solos de blues et de rock.",
    steps: ["Choisir deux trous adjacents (ex. trous 4 et 5). Les deux doivent etre dans la meme direction (tous les deux aspires ou tous les deux souffles).", "Tenir l harmonica et faire pivoter le poignet droit rapidement d un trou a l autre. C est l harmonica qui bouge, pas la tete.", "Commencer lentement (2 allers-retours par seconde), puis accelerer progressivement.", "Le trou de gauche est la note principale, le trou de droite est la note ajoutee. Revenir toujours sur la gauche."],
    tabs: [{
      label: "Shake sur Draw 4-5",
      notes: [{
        h: 4,
        d: "d"
      }, {
        gliss: true
      }, {
        h: 5,
        d: "d"
      }, {
        gliss: true
      }, {
        h: 4,
        d: "d"
      }, {
        gliss: true
      }, {
        h: 5,
        d: "d"
      }, {
        gliss: true
      }, {
        h: 4,
        d: "d",
        beats: 2
      }],
      hint: "Alterner rapidement entre trou 4 et 5 aspires. La note principale est le trou 4."
    }, {
      label: "Shake sur Blow 5-6",
      notes: [{
        h: 5,
        d: "b"
      }, {
        gliss: true
      }, {
        h: 6,
        d: "b"
      }, {
        gliss: true
      }, {
        h: 5,
        d: "b"
      }, {
        gliss: true
      }, {
        h: 6,
        d: "b"
      }, {
        gliss: true
      }, {
        h: 5,
        d: "b",
        beats: 2
      }],
      hint: "Meme principe en soufflant. Son plus brillant."
    }]
  }, {
    id: "pflair2",
    icon: "🚀",
    title: "Rip — glisse d approche",
    tag: "ornement",
    why: "Le rip cree une approche dramatique vers une note cible. Au lieu d arriver directement sur la note, on glisse depuis plusieurs trous a gauche. Son caracteristique du jazz et du blues expressif.",
    steps: ["Choisir une note cible (ex. Blow 6).", "Partir de 3 ou 4 trous a gauche de la cible (ex. Blow 3).", "Glisser l harmonica rapidement vers la droite tout en soufflant (ou aspirant). Les notes intermediaires s entendent brievement.", "Atterrir sur la note cible et la tenir. Le rip ne dure qu une fraction de seconde."],
    tabs: [{
      label: "Rip vers Blow 6",
      notes: [{
        h: 3,
        d: "b"
      }, {
        gliss: true
      }, {
        h: 4,
        d: "b"
      }, {
        gliss: true
      }, {
        h: 5,
        d: "b"
      }, {
        gliss: true
      }, {
        h: 6,
        d: "b",
        beats: 3
      }],
      hint: "Glisser rapidement de Blow 3 vers Blow 6. Les notes intermediaires sont rapides, la note 6 est tenue."
    }, {
      label: "Rip vers Draw 4",
      notes: [{
        h: 1,
        d: "d"
      }, {
        gliss: true
      }, {
        h: 2,
        d: "d"
      }, {
        gliss: true
      }, {
        h: 3,
        d: "d"
      }, {
        gliss: true
      }, {
        h: 4,
        d: "d",
        beats: 3
      }],
      hint: "Glisser de Draw 1 vers Draw 4 en aspirant."
    }]
  }, {
    id: "pflair3",
    icon: "🎾",
    title: "Boing — rebond vers le haut",
    tag: "ornement",
    why: "Le boing quitte une note vers la droite (montant). Donne une impression de rebond ou de question sans reponse. Utilise en jazz et parfois en blues pour des fins de phrase insolites.",
    steps: ["Jouer une note cible (ex. Draw 4).", "Quitter vers la droite (trous 5-6-7) en maintenant l aspiration. Le son monte et s efface.", "Le mouvement est bref et fluide. La note cible est la note principale, le boing est la queue.", "Experimenter : la vitesse du boing change complètement l effet."],
    tabs: [{
      label: "Boing depuis Draw 4",
      notes: [{
        h: 4,
        d: "d",
        beats: 2
      }, {
        gliss: true
      }, {
        h: 5,
        d: "d"
      }, {
        gliss: true
      }, {
        h: 6,
        d: "d"
      }],
      hint: "Tenir Draw 4, puis glisser vers la droite en montant. Le son s evanouit vers le haut."
    }]
  }, {
    id: "pflair4",
    icon: "📉",
    title: "Fall-off — chute vers le bas",
    tag: "ornement",
    why: "Le fall-off quitte une note vers la gauche (descendant). Le son tombe et disparait. Tres utilise en blues et en jazz pour finir des phrases avec une couleur melancolique ou decontractee.",
    steps: ["Jouer une note cible (ex. Blow 6).", "Quitter vers la gauche (trous 5-4-3) en maintenant le souffle. Le son descend et s efface.", "Garder le meme type de souffle (blow ou draw). Le mouvement est fluide, pas hacjhe.", "La chute peut etre lente (dramatique) ou rapide (decontractee)."],
    tabs: [{
      label: "Fall-off depuis Blow 6",
      notes: [{
        h: 6,
        d: "b",
        beats: 2
      }, {
        gliss: true
      }, {
        h: 5,
        d: "b"
      }, {
        gliss: true
      }, {
        h: 4,
        d: "b"
      }, {
        gliss: true
      }, {
        h: 3,
        d: "b"
      }],
      hint: "Tenir Blow 6, puis glisser vers la gauche en descendant. Le son tombe et s evanouit."
    }]
  }, {
    id: "pflair5",
    icon: "✨",
    title: "Grace note — note d appui",
    tag: "ornement",
    why: "La grace note est une note tres breve jouee juste avant la note principale. Elle lui donne un accent percussif et du caractere. C est l equivalent d une consonne avant une voyelle en chant.",
    steps: ["Choisir la note principale (ex. Draw 4).", "Placer sur le trou adjacent (ex. trou 3 ou 5) une fraction de seconde avant.", "Bouger immediatement sur la note principale. La grace note doit etre quasi inaudible — just une impulsion.", "La note principale doit etre clairement plus longue et plus forte que la grace note."],
    tabs: [{
      label: "Grace note avant Draw 4",
      notes: [{
        h: 3,
        d: "d"
      }, {
        gliss: true
      }, {
        h: 4,
        d: "d",
        beats: 3
      }],
      hint: "Draw 3 breve (grace note) immediatement suivie de Draw 4 tenue. La 3 est un clin d oeil."
    }, {
      label: "Grace note avant Blow 6",
      notes: [{
        h: 5,
        d: "b"
      }, {
        gliss: true
      }, {
        h: 6,
        d: "b",
        beats: 3
      }],
      hint: "Blow 5 breve puis Blow 6 tenue."
    }]
  }, {
    id: "pflair6",
    icon: "⚡",
    title: "Developper la vitesse — 4 etapes",
    tag: "velocite",
    why: "La vitesse ne s obtient pas en essayant de jouer vite. Elle vient de la precision a tempo lent, repete jusqu a devenir automatique. C est comme apprendre a parler : d abord les sons, puis les mots, puis les phrases.",
    steps: ["Etape 1 — Commencer tres lentement : jouer chaque note en sachant exactement ou elle est, comment elle sonne, et comment y arriver. Si une note est incertaine, la travailler isolement.", "Etape 2 — Apprendre par petits blocs : decouper la sequence en morceaux de 2-3 notes. Maitriser chaque bloc seul avant de les assembler.", "Etape 3 — Accelerer progressivement : augmenter le tempo de 5 BPM a la fois. Ne jamais depasser le tempo ou les gestes deviennent imprecis.", "Etape 4 — Penser en phrases : quand les gestes sont automatiques, ne plus penser note par note mais en groupes de notes. Comme lire des mots entiers plutot que des lettres."]
  }]
}, {
  id: "p11",
  subtitle: "Positions",
  num: "11",
  color: "#8a4a98",
  bg: "#f8eef8",
  badge: "3-6 mois",
  title: "Splits avancés & 2ème position",
  exercises: [{
    id: "p11e1",
    icon: "🔄",
    title: "Trouver la 2ème position - draw chord home",
    tag: "cross harp",
    why: "La 2ème position est LA position du blues. Comprendre pourquoi elle sonne blues transforme l'improvisation.",
    steps: ["Aspirer les trous 1-4 ensemble. C'est le 'home' en 2ème position (accord de Sol).", "Jouer une phrase et revenir toujours terminer sur ce draw chord.", "Le Do soufflé crée une 'blue note' contre la tonalité de Sol - c'est le décalage volontaire du blues."],
    schema: "twelve-bar"
  }, {
    id: "p11e2",
    icon: "🎼",
    title: "Licks blues en 2ème position",
    tag: "improvisation",
    why: "Ces licks sont des 'briques' réutilisables. Les enchaîner et terminer les phrases sur le draw chord est le début de l'improvisation réelle.",
    steps: ["Apprendre chaque lick séparément, lentement.", "Terminer toujours sur Draw 1 ou Draw 2 - c'est la note de résolution.", "Improviser sur blues 12 mesures."],
    tabs: [{
      label: "Lick 1 - résolution classique",
      notes: [{
        h: 3,
        d: 'bd',
        b: 2
      }, {
        h: 2,
        d: 'd'
      }, {
        h: 2,
        d: 'b'
      }, {
        h: 1,
        d: 'd'
      }],
      hint: "Le bend intermédiaire du trou 3 → résolution sur Draw 1"
    }, {
      label: "Lick 2 - ligne descendante",
      notes: [{
        h: 4,
        d: 'd'
      }, {
        h: 3,
        d: 'bd',
        b: 2
      }, {
        h: 3,
        d: 'b'
      }, {
        h: 2,
        d: 'd'
      }, {
        h: 1,
        d: 'd'
      }],
      hint: "Draw 4 → bend trou 3 → Blow 3 → Draw 2 → Draw 1"
    }]
  }]
}, {
  id: "p12",
  subtitle: "Technique avancee",
  num: "12",
  color: "#c8960a",
  bg: "#fdf8e8",
  badge: "6 mois - 1 an+",
  title: "Overblows & overdraws",
  exercises: [{
    id: "p12e1",
    icon: "⚙️",
    title: "Prérequis - harmonica et oreille",
    tag: "avant de commencer",
    why: "Les overbends nécessitent un instrument bien réglé ET une oreille capable d'entendre si la note est juste. Sans ça, on peut passer des heures sans résultat.",
    steps: ["Maîtriser les 4 étapes de contrôle du bend sur trous 1-5.", "Être capable d'entendre si une note est juste ou fausse.", "Idéalement : harmonica dédié avec gap serré."]
  }, {
    id: "p12e2",
    icon: "⬆️",
    title: "Premier overblow - trou 5 ou 6",
    tag: "technique",
    why: "L'overblow donne accès à des notes qui n'existent pas sur l'harmonica diatonique standard. Avec eux, on peut jouer dans n'importe quelle tonalité.",
    steps: ["Former le K-spot comme pour un bend, mais en soufflant.", "Souffler doucement dans le trou 5 ou 6 avec cette position de langue.", "Chercher le point où la note 'saute' vers le haut.", "⚠ Jamais forcer."],
    tabs: [{
      label: "Tentative overblow trou 6",
      notes: [{
        h: 6,
        d: "b"
      }, {
        h: 6,
        d: "bd",
        b: 1
      }],
      hint: "Blow 6 normal, puis souffler avec la langue en position de bend - chercher le saut vers le haut."
    }]
  }, {
    id: "p12e3",
    icon: "🎵",
    title: "Intégrer les overbends dans le jeu",
    tag: "musical",
    why: "Un overbend isolé ne sert à rien musicalement. Il doit s'insérer dans une phrase - c'est ça qui le rend musical.",
    steps: ["Une fois répétables : les insérer dans les licks existants.", "Travailler les enchaînements vers l'overbend et depuis l'overbend.", "Les overdraws (aspirés qui montent) viennent après les overblows."]
  }]
}];
const SONGS = [{
  id: "s1",
  icon: "🎸",
  title: "Mannish Boy",
  artist: "Muddy Waters",
  style: "Blues",
  niveau: "Débutant",
  position: "2ème",
  bends: false,
  suggestedBpm: 60,
  bpmRange: [40, 120],
  timeSignature: 4,
  masteryLevels: ["Lis la tablature et reconnais le riff", "Joues les accords dans le bon ordre lentement", "Joues le riff en boucle a 60 BPM avec le metronome", "Joues fluide a 90 BPM avec cup wah", "Joues de memoire a 120+ BPM avec feeling blues"],
  color: "#c85a20",
  bg: "#fdf0e8",
  desc: "Le riff fondateur du blues de Chicago. Aucun bend requis  -  que des accords naturels de l'harmonica. En 2ème position, le draw chord (aspirer) est l'accord 'maison' (Sol). Le blow chord (souffler) est l'accord 'milieu' (Do).",
  tips: "Jouer fort et sec. L'espace entre les accords compte autant que les accords eux-mêmes. Utiliser le cup wah sur les draw chords.",
  tabs: [{
    label: "Riff principal  -  notation de Damien",
    notes: [{
      h: [1, 2, 3],
      d: 'd'
    }, {
      h: [4, 5, 6],
      d: 'b'
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      h: [4, 5, 6],
      d: 'd'
    }, {
      h: [1, 2, 3],
      d: 'd'
    }],
    hint: "-123 = aspirer trous 1-2-3 (accord Sol) · +456 = souffler trous 4-5-6 (accord Do) · -456 = aspirer trous 4-5-6"
  }, {
    label: "Structure d'un couplet (jouer le riff 4 fois)",
    notes: [{
      h: [1, 2, 3],
      d: 'd'
    }, {
      h: [4, 5, 6],
      d: 'b'
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      h: [4, 5, 6],
      d: 'd'
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      sep: true
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      h: [4, 5, 6],
      d: 'b'
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      h: [4, 5, 6],
      d: 'd'
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      sep: true
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      h: [4, 5, 6],
      d: 'b'
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      h: [4, 5, 6],
      d: 'd'
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      sep: true
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      h: [4, 5, 6],
      d: 'b'
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      h: [4, 5, 6],
      d: 'd'
    }, {
      h: [1, 2, 3],
      d: 'd'
    }],
    hint: "Chaque riff = 1 mesure. 4 mesures = 1 couplet. Puis chanter ou ré-enchaîner."
  }]
}, {
  id: "s2",
  icon: "🎻",
  title: "Ode à la joie",
  artist: "Beethoven",
  style: "Classique",
  niveau: "Débutant",
  position: "1ère",
  bends: false,
  suggestedBpm: 70,
  bpmRange: [40, 140],
  timeSignature: 4,
  masteryLevels: ["Lis la tablature et reconnais la melodie", "Joues les notes dans le bon ordre lentement", "Joues proprement a 70 BPM avec le metronome", "Joues fluide a 100 BPM sans regarder la tab", "Joues de memoire a 120 BPM avec expression"],
  color: "#2a7a52",
  bg: "#e8f5ee",
  desc: "Mélodie universellement connue. En 1ère position, registre médian (trous 4-6). Aucun bend. Parfaite pour travailler les changements de trou propres et le contrôle du souffle.",
  tips: "Tenir les notes longues vraiment longues. Ne pas se presser. La mélodie doit se reconnaître même jouée très lentement.",
  tabs: [{
    label: "Thème principal (×2)",
    notes: [{
      h: 5,
      d: 'b'
    }, {
      h: 5,
      d: 'b'
    }, {
      h: 5,
      d: 'd'
    }, {
      h: 6,
      d: 'b'
    }, {
      sep: true
    }, {
      h: 6,
      d: 'b'
    }, {
      h: 5,
      d: 'd'
    }, {
      h: 5,
      d: 'b'
    }, {
      h: 4,
      d: 'd'
    }, {
      sep: true
    }, {
      h: 4,
      d: 'b'
    }, {
      h: 4,
      d: 'b'
    }, {
      h: 5,
      d: 'b'
    }, {
      h: 5,
      d: 'b'
    }, {
      sep: true
    }, {
      h: 5,
      d: 'b'
    }, {
      h: 4,
      d: 'd',
      beats: 2
    }],
    hint: "Mi Mi Fa Sol | Sol Fa Mi Re | Do Do Re Mi | Mi Re(long)"
  }, {
    label: "Deuxième phrase",
    notes: [{
      h: 4,
      d: 'd'
    }, {
      h: 4,
      d: 'd'
    }, {
      h: 5,
      d: 'b'
    }, {
      h: 4,
      d: 'b'
    }, {
      sep: true
    }, {
      h: 4,
      d: 'd'
    }, {
      h: 5,
      d: 'b'
    }, {
      h: 5,
      d: 'd'
    }, {
      h: 5,
      d: 'b'
    }, {
      sep: true
    }, {
      h: 4,
      d: 'b'
    }, {
      h: 4,
      d: 'd'
    }, {
      h: 5,
      d: 'b'
    }, {
      h: 5,
      d: 'd'
    }, {
      sep: true
    }, {
      h: 5,
      d: 'b'
    }, {
      h: 4,
      d: 'd'
    }, {
      h: 4,
      d: 'b'
    }, {
      h: 4,
      d: 'b',
      beats: 2
    }],
    hint: "Re Re Mi Do | Re Mi Fa Mi | Do Re Mi Fa | Mi Re Do Do(long)"
  }]
}, {
  id: "s3",
  icon: "⛪",
  title: "When the Saints Go Marching In",
  artist: "Traditional",
  style: "Jazz / Gospel",
  niveau: "Débutant",
  position: "1ère",
  bends: false,
  suggestedBpm: 80,
  bpmRange: [40, 160],
  timeSignature: 4,
  masteryLevels: ["Lis la tablature et reconnais la melodie", "Joues les notes dans le bon ordre lentement", "Joues proprement a 80 BPM avec le metronome", "Joues fluide a 110 BPM avec swing", "Joues de memoire a 130 BPM avec energie"],
  color: "#4a5fa0",
  bg: "#eeeef8",
  desc: "Standard jazz incontournable. En 1ère position, registre médian. Aucun bend. Excellent pour travailler les sauts de notes et le jeu avec un tempo fort.",
  tips: "Accentuer les notes longues. Jouer avec conviction  -  cette chanson doit sonner joyeux et puissant. Essayer d'ajouter le cup wah sur les notes tenues.",
  tabs: [{
    label: "Refrain  -  Oh when the saints",
    notes: [{
      h: 4,
      d: 'b'
    }, {
      h: 5,
      d: 'b'
    }, {
      h: 5,
      d: 'd'
    }, {
      h: 6,
      d: 'b',
      beats: 3
    }, {
      sep: true
    }, {
      h: 6,
      d: 'b'
    }, {
      h: 5,
      d: 'b'
    }, {
      h: 6,
      d: 'b',
      beats: 2
    }, {
      sep: true
    }, {
      h: 6,
      d: 'b'
    }, {
      h: 5,
      d: 'd'
    }, {
      h: 5,
      d: 'b'
    }, {
      h: 5,
      d: 'd',
      beats: 2
    }, {
      sep: true
    }, {
      h: 6,
      d: 'b'
    }, {
      h: 5,
      d: 'b'
    }, {
      h: 4,
      d: 'b'
    }, {
      h: 4,
      d: 'd',
      beats: 3
    }],
    hint: "Do Mi Fa Sol(long) | Sol Mi Sol(long) | Sol Fa Mi Fa(long) | Sol Mi Do Re(long)"
  }, {
    label: "Suite  -  go marching in",
    notes: [{
      h: 5,
      d: 'b'
    }, {
      h: 5,
      d: 'b'
    }, {
      h: 5,
      d: 'd'
    }, {
      h: 5,
      d: 'b'
    }, {
      sep: true
    }, {
      h: 4,
      d: 'd'
    }, {
      h: 4,
      d: 'b'
    }, {
      h: 4,
      d: 'd'
    }, {
      h: 5,
      d: 'b'
    }, {
      sep: true
    }, {
      h: 5,
      d: 'd'
    }, {
      h: 6,
      d: 'b'
    }, {
      h: 6,
      d: 'b'
    }, {
      h: 5,
      d: 'b'
    }, {
      h: 4,
      d: 'b'
    }, {
      sep: true
    }, {
      h: 4,
      d: 'b',
      beats: 4
    }],
    hint: "Mi Mi Fa Mi | Re Do Re Mi | Fa Sol Sol Mi Do | Do(long)"
  }]
}, {
  id: "s4",
  icon: "🌻",
  title: "Oh! Susanna",
  artist: "Stephen Foster",
  style: "Folk",
  niveau: "Débutant",
  position: "1ère",
  bends: false,
  suggestedBpm: 75,
  bpmRange: [40, 150],
  timeSignature: 4,
  masteryLevels: ["Lis la tablature et reconnais la melodie", "Joues les notes dans le bon ordre lentement", "Joues proprement a 75 BPM avec le metronome", "Joues fluide a 100 BPM sans hesitation", "Joues de memoire a 130 BPM avec rythme"],
  color: "#c8960a",
  bg: "#fdf8e8",
  desc: "Mélodie folk américaine classique. Registre médian, aucun bend. Bonne pour travailler les changements rapides de souffle et les notes répétées.",
  tips: "Attention aux deux Ré (draw 4) consécutifs dans le couplet  -  ne pas se perdre. Marquer le tempo avec le pied avant de commencer.",
  tabs: [{
    label: "Couplet  -  Oh I come from Alabama",
    notes: [{
      h: 4,
      d: 'b'
    }, {
      h: 4,
      d: 'd'
    }, {
      h: 5,
      d: 'b'
    }, {
      h: 5,
      d: 'd'
    }, {
      sep: true
    }, {
      h: 6,
      d: 'b'
    }, {
      h: 5,
      d: 'd'
    }, {
      h: 4,
      d: 'b'
    }, {
      h: 4,
      d: 'd',
      beats: 2
    }, {
      sep: true
    }, {
      h: 4,
      d: 'b'
    }, {
      h: 4,
      d: 'b'
    }, {
      h: 4,
      d: 'd'
    }, {
      h: 5,
      d: 'b'
    }, {
      sep: true
    }, {
      h: 5,
      d: 'd'
    }, {
      h: 6,
      d: 'b',
      beats: 3
    }],
    hint: "Do Re Mi Fa | Sol Fa Mi Re(long) | Do Do Re Mi | Fa Sol(long)"
  }, {
    label: "Refrain  -  Oh! Susanna",
    notes: [{
      h: 6,
      d: 'b'
    }, {
      h: 6,
      d: 'd'
    }, {
      h: 6,
      d: 'b'
    }, {
      h: 5,
      d: 'd'
    }, {
      sep: true
    }, {
      h: 5,
      d: 'b'
    }, {
      h: 5,
      d: 'd'
    }, {
      h: 4,
      d: 'b'
    }, {
      h: 4,
      d: 'd',
      beats: 2
    }, {
      sep: true
    }, {
      h: 4,
      d: 'b'
    }, {
      h: 4,
      d: 'b'
    }, {
      h: 4,
      d: 'd'
    }, {
      h: 5,
      d: 'b'
    }, {
      sep: true
    }, {
      h: 5,
      d: 'd'
    }, {
      h: 4,
      d: 'b',
      beats: 3
    }],
    hint: "Sol La Sol Fa | Mi Fa Mi Re(long) | Do Do Re Mi | Fa Mi(long)"
  }]
}, {
  id: "s5",
  icon: "🌊",
  title: "Riff blues de base",
  artist: "2ème position",
  style: "Blues",
  niveau: "Débutant",
  position: "2ème",
  bends: false,
  suggestedBpm: 55,
  bpmRange: [30, 120],
  timeSignature: 4,
  masteryLevels: ["Comprends les 3 accords et leur position", "Joues le riff lentement a 55 BPM", "Joues le riff en shuffle fluide a 70 BPM", "Joues les 3 accords en enchainement a 90 BPM", "Improvises par-dessus avec feeling blues"],
  color: "#2a7a52",
  bg: "#e8f5ee",
  desc: "Le premier riff de blues à maîtriser. En 2ème position sur un harmonica en Do, on joue en Sol. Tous les accords viennent naturellement des trous 1-4. Aucun bend requis  -  c'est le point de départ de l'improvisation blues.",
  tips: "C'est la fondation de tout. Une fois ce riff dans les mains, on peut commencer à improviser dessus. Alterner avec le cup wah ouvert/fermé pour varier le son.",
  tabs: [{
    label: "Accord de base  -  draw chord (home Sol)",
    notes: [{
      h: [1, 2, 3, 4],
      d: 'd'
    }, {
      sep: true
    }, {
      h: [1, 2, 3, 4],
      d: 'd'
    }, {
      sep: true
    }, {
      h: [1, 2, 3, 4],
      d: 'd'
    }],
    hint: "L'accord 'maison' du blues en 2ème position. Aspirer trous 1-4 simultanément."
  }, {
    label: "Riff rythmique shuffle (2 mesures)",
    notes: [{
      h: [1, 2, 3],
      d: 'd'
    }, {
      h: [1, 2, 3],
      d: 'b'
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      sep: true
    }, {
      h: [1, 2, 3],
      d: 'b'
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      h: [1, 2, 3],
      d: 'b'
    }, {
      h: [1, 2, 3],
      d: 'b'
    }, {
      sep: true
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      h: [1, 2, 3],
      d: 'b'
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      h: [1, 2, 3],
      d: 'd'
    }],
    hint: "Jouer en shuffle : long-court, long-court. Ce groove est la base du blues et du rock."
  }, {
    label: "Passage IV  -  blow chord (Do)",
    notes: [{
      h: [1, 2, 3],
      d: 'b'
    }, {
      h: [1, 2, 3],
      d: 'd'
    }, {
      h: [1, 2, 3],
      d: 'b'
    }, {
      h: [1, 2, 3],
      d: 'b'
    }],
    hint: "L'accord IV. Souffler sur les mêmes trous = passage automatique à l'accord du milieu."
  }]
},, {
  id: "s6",
  icon: "🚂",
  title: "Kansas City",
  artist: "Wilbert Harrison",
  style: "Blues",
  niveau: "Debutant",
  position: "2eme",
  bends: false,
  suggestedBpm: 65,
  bpmRange: [40, 130],
  timeSignature: 4,
  masteryLevels: ["Lis les tabs", "Joues lentement", "65 BPM shuffle", "90 BPM enchainement", "120 BPM de memoire"],
  color: "#c85a20",
  bg: "#fdf0e8",
  desc: "Un des riffs blues les plus joues au monde. 2eme position, aucun bend.",
  tips: "Cle : le SHUFFLE, long-court. Ecouter Wilbert Harrison avant de jouer.",
  tabs: [{
    label: "Riff trous 1-2-3",
    notes: [{
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "b"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      sep: true
    }, {
      h: [1, 2, 3],
      d: "b"
    }, {
      h: [1, 2, 3],
      d: "d",
      beats: 2
    }],
    hint: "-123 +123 -123 : tes propres notes !"
  }, {
    label: "Riff trous 2-3-4",
    notes: [{
      h: [2, 3, 4],
      d: "d"
    }, {
      h: [2, 3, 4],
      d: "d"
    }, {
      h: [2, 3, 4],
      d: "b"
    }, {
      h: [2, 3, 4],
      d: "d"
    }, {
      sep: true
    }, {
      h: [2, 3, 4],
      d: "b"
    }, {
      h: [2, 3, 4],
      d: "d",
      beats: 2
    }],
    hint: "Meme pattern, 1 trou vers la droite."
  }, {
    label: "Melodie (sans bend)",
    notes: [{
      h: 4,
      d: "d"
    }, {
      h: 4,
      d: "d"
    }, {
      h: 3,
      d: "b"
    }, {
      h: 4,
      d: "d"
    }, {
      sep: true
    }, {
      h: 3,
      d: "d"
    }, {
      h: 2,
      d: "d"
    }, {
      h: 2,
      d: "b"
    }, {
      h: 1,
      d: "d",
      beats: 2
    }],
    hint: "Re Re Sol Re - Si Sol Mi Re"
  }]
}, {
  id: "s7",
  icon: "🎵",
  title: "Riff 5 variations",
  artist: "Blues 2eme position",
  style: "Blues",
  niveau: "Debutant",
  position: "2eme",
  bends: false,
  suggestedBpm: 60,
  bpmRange: [40, 120],
  timeSignature: 4,
  masteryLevels: ["Riff de base en boucle", "Variation 1 proprement", "Variations 1 a 3", "Les 5 variations enchainees", "Fluide a 90 BPM avec feeling"],
  color: "#2a7a52",
  bg: "#e8f5ee",
  desc: "Le riff principal (6 accords) repete 5 fois. A la fin de chaque repetition : 3 notes dont les 2 dernieres sont glissees. Chaque variation monte progressivement sur l harmonica.",
  tips: "Apprendre le riff de base d abord. Ajouter les conclusions une par une. Le / = glisse en maintenant le souffle et en faisant glisser l harmonica vers la droite.",
  tabs: [{
    label: "Riff de base - 6 accords",
    notes: [{
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "b"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "b"
    }, {
      h: [1, 2, 3],
      d: "d"
    }],
    hint: "6 accords. Jouer ce riff, puis enchaîner avec une des 5 conclusions."
  }, {
    label: "Variation 1 : -1, 2 / 3",
    notes: [{
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "b"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "b"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      sep: true
    }, {
      h: 1,
      d: "d"
    }, {
      h: 2,
      d: "b"
    }, {
      gliss: true
    }, {
      h: 3,
      d: "b"
    }],
    hint: "Draw 1, puis glisse blow 2 vers blow 3."
  }, {
    label: "Variation 2 : 3, -3 / -4",
    notes: [{
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "b"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "b"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      sep: true
    }, {
      h: 3,
      d: "b"
    }, {
      h: 3,
      d: "d"
    }, {
      gliss: true
    }, {
      h: 4,
      d: "d"
    }],
    hint: "Blow 3, puis glisse draw 3 vers draw 4."
  }, {
    label: "Variation 3 : -4, 5 / 6",
    notes: [{
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "b"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "b"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      sep: true
    }, {
      h: 4,
      d: "d"
    }, {
      h: 5,
      d: "b"
    }, {
      gliss: true
    }, {
      h: 6,
      d: "b"
    }],
    hint: "Draw 4, puis glisse blow 5 vers blow 6."
  }, {
    label: "Variation 4 : -1, -2 / -2",
    notes: [{
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "b"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "b"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      sep: true
    }, {
      h: 1,
      d: "d"
    }, {
      h: 2,
      d: "d"
    }, {
      gliss: true
    }, {
      h: 2,
      d: "d"
    }],
    hint: "Draw 1, puis glisse draw 2 vers draw 2 (vibrato de position)."
  }, {
    label: "Variation 5 : -2, -3 / -4",
    notes: [{
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "b"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      h: [1, 2, 3],
      d: "b"
    }, {
      h: [1, 2, 3],
      d: "d"
    }, {
      sep: true
    }, {
      h: 2,
      d: "d"
    }, {
      h: 3,
      d: "d"
    }, {
      gliss: true
    }, {
      h: 4,
      d: "d"
    }],
    hint: "Draw 2, puis glisse draw 3 vers draw 4. Conclusion finale."
  }]
}];
const STATUS = [{
  label: "A faire",
  emoji: "○",
  color: "#9a9080",
  bg: "#f0ece4",
  pct: 0
}, {
  label: "Decouverte",
  emoji: "◔",
  color: "#c8960a",
  bg: "#fdf8e8",
  pct: 25
}, {
  label: "En cours",
  emoji: "◑",
  color: "#c85a20",
  bg: "#fdf0e8",
  pct: 50
}, {
  label: "Assez bon",
  emoji: "◕",
  color: "#4a5fa0",
  bg: "#eeeef8",
  pct: 75
}, {
  label: "Maitrise",
  emoji: "●",
  color: "#2a7a52",
  bg: "#e8f5ee",
  pct: 100
}];

// ============================================================
// COMPOSANTS UI
// ============================================================

function TabNote({
  note,
  size = "md"
}) {
  if (note.sep) return /*#__PURE__*/React.createElement("div", {
    style: {
      width: 2,
      background: "#d0c8b8",
      margin: "0 5px",
      alignSelf: "stretch",
      borderRadius: 1
    }
  });
  if (note.gliss) return /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      flexDirection: "column",
      alignItems: "center",
      justifyContent: "center",
      padding: "0 2px",
      color: "#7a40a0",
      fontSize: size === "lg" ? 20 : 16,
      fontWeight: 700,
      lineHeight: 1,
      alignSelf: "stretch"
    }
  }, "/");
  const C = {
    b: {
      bg: "#e8f5ee",
      border: "#80c8a0",
      text: "#2a7a52",
      arrow: "↑"
    },
    d: {
      bg: "#fdf0e8",
      border: "#f0a070",
      text: "#c85a20",
      arrow: "↓"
    },
    bd: {
      bg: "#f0eaf8",
      border: "#c0a0d8",
      text: "#7a40a0",
      arrow: "↓"
    }
  };
  const col = C[note.d] || C.d;
  const apos = note.d === "bd" && note.b ? "'".repeat(note.b) : "";
  const isChord = Array.isArray(note.h);
  const hLabel = isChord ? note.h[0] + "-" + note.h[note.h.length - 1] : note.h;
  const lg = size === "lg";
  return /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      flexDirection: "column",
      alignItems: "center",
      gap: 2,
      padding: lg ? "7px 10px" : "5px 7px",
      background: col.bg,
      border: "1.5px solid " + col.border,
      borderRadius: isChord ? 8 : 6,
      minWidth: isChord ? lg ? 52 : 42 : lg ? 36 : 30,
      position: "relative"
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: lg ? 18 : 15,
      lineHeight: 1,
      color: col.text,
      fontWeight: 700
    }
  }, col.arrow, apos), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: isChord ? 12 : 11,
      fontFamily: "monospace",
      color: col.text,
      fontWeight: 700
    }
  }, hLabel), isChord && /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 8,
      color: col.text,
      opacity: 0.7
    }
  }, "accord"), note.beats > 1 && /*#__PURE__*/React.createElement("span", {
    style: {
      position: "absolute",
      top: -7,
      right: -4,
      fontSize: 9,
      background: col.border,
      color: "#fff",
      borderRadius: "50%",
      width: 14,
      height: 14,
      display: "flex",
      alignItems: "center",
      justifyContent: "center",
      fontWeight: 700
    }
  }, note.beats));
}
function TabBar({
  tab,
  size = "md"
}) {
  const lg = size === "lg";
  return /*#__PURE__*/React.createElement("div", {
    style: {
      marginBottom: 12
    }
  }, tab.label && /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      color: "#8a7f70",
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      marginBottom: 6
    }
  }, tab.label), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      flexWrap: "wrap",
      gap: lg ? 6 : 4,
      alignItems: "center",
      padding: lg ? "12px 14px" : "10px 12px",
      background: "#f8f5f0",
      borderRadius: 8,
      border: "1px solid #e0d8cc"
    }
  }, tab.notes.map((n, i) => /*#__PURE__*/React.createElement(TabNote, {
    key: i,
    note: n,
    size: size
  }))), tab.hint && /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 11,
      color: "#8a7f70",
      marginTop: 5,
      fontStyle: "italic",
      paddingLeft: 2
    }
  }, tab.hint));
}
function TabDisplay({
  tabs
}) {
  return /*#__PURE__*/React.createElement("div", {
    style: {
      marginTop: 12
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      color: "#4a5fa0",
      marginBottom: 8,
      display: "flex",
      gap: 10,
      flexWrap: "wrap"
    }
  }, /*#__PURE__*/React.createElement("span", null, "Tablature"), /*#__PURE__*/React.createElement("span", {
    style: {
      color: "#b0a090",
      fontWeight: 400
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      color: "#2a7a52"
    }
  }, "↑"), " souffler \xA0", /*#__PURE__*/React.createElement("span", {
    style: {
      color: "#c85a20"
    }
  }, "↓"), " aspirer \xA0", /*#__PURE__*/React.createElement("span", {
    style: {
      color: "#7a40a0"
    }
  }, "↓'"), " bend")), tabs.map((t, i) => /*#__PURE__*/React.createElement(TabBar, {
    key: i,
    tab: t
  })));
}
function HarmonicaMap() {
  const notes = [{
    t: 1,
    bl: "Do",
    dr: "Re",
    db: ["Do#"],
    bb: []
  }, {
    t: 2,
    bl: "Mi",
    dr: "Sol",
    db: ["Fa#", "Fa"],
    bb: []
  }, {
    t: 3,
    bl: "Sol",
    dr: "Si",
    db: ["Sib", "La", "Lab"],
    bb: []
  }, {
    t: 4,
    bl: "Do",
    dr: "Re",
    db: ["Do#"],
    bb: []
  }, {
    t: 5,
    bl: "Mi",
    dr: "Fa",
    db: ["Mi*"],
    bb: []
  }, {
    t: 6,
    bl: "Sol",
    dr: "La",
    db: ["Lab*"],
    bb: []
  }, {
    t: 7,
    bl: "Do",
    dr: "Si",
    db: [],
    bb: []
  }, {
    t: 8,
    bl: "Mi",
    dr: "Re",
    db: [],
    bb: ["Mib"]
  }, {
    t: 9,
    bl: "Sol",
    dr: "Fa",
    db: [],
    bb: ["Fa#"]
  }, {
    t: 10,
    bl: "Do",
    dr: "La",
    db: [],
    bb: ["Si", "Sib"]
  }];
  const W = 44,
    LW = 72;
  const cell = (bg, tc, bc) => ({
    width: W,
    padding: "5px 2px",
    textAlign: "center",
    background: bg,
    fontSize: 11,
    fontWeight: 700,
    color: tc,
    borderRight: "1px solid " + bc,
    lineHeight: 1.3,
    minHeight: 28,
    display: "flex",
    alignItems: "center",
    justifyContent: "center",
    flexDirection: "column"
  });
  const lbl = (bg, tc, bc) => ({
    width: LW,
    padding: "5px 4px",
    textAlign: "center",
    background: bg,
    fontSize: 9,
    fontFamily: "monospace",
    fontWeight: 700,
    color: tc,
    borderRight: "1px solid " + bc,
    display: "flex",
    alignItems: "center",
    justifyContent: "center",
    letterSpacing: "0.04em",
    lineHeight: 1.3
  });
  const bCol = {
    bg: "#f0eaf8",
    border: "#c0a0d8",
    text: "#7a40a0",
    empty: "#f8f6fc"
  };
  const blCol = {
    bg: "#e8f5ee",
    text: "#2a7a52",
    border: "#a0d0b0"
  };
  const drCol = {
    bg: "#fdf0e8",
    text: "#c85a20",
    border: "#e0c8a0"
  };
  return /*#__PURE__*/React.createElement("div", {
    style: {
      marginTop: 12
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      color: "#4a5fa0",
      marginBottom: 8
    }
  }, "Carte de l'harmonica en Do"), /*#__PURE__*/React.createElement("div", {
    style: {
      overflowX: "auto",
      paddingBottom: 4
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      display: "inline-flex",
      flexDirection: "column",
      border: "1px solid #d0c8b8",
      borderRadius: 8,
      overflow: "hidden",
      minWidth: "max-content"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: lbl(bCol.bg, bCol.text, bCol.border)
  }, "Bend souffle"), notes.map(n => /*#__PURE__*/React.createElement("div", {
    key: n.t,
    style: cell(n.bb.length ? bCol.bg : bCol.empty, n.bb.length ? bCol.text : "#c8c0b8", bCol.border)
  }, n.bb.length ? n.bb.map((b, i) => /*#__PURE__*/React.createElement("span", {
    key: i,
    style: {
      fontSize: 10
    }
  }, b, i < n.bb.length - 1 ? " >" : " ")) : /*#__PURE__*/React.createElement("span", {
    style: {
      opacity: 0.3
    }
  }, "-")))), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: lbl(blCol.bg, blCol.text, blCol.border)
  }, "Souffler"), notes.map(n => /*#__PURE__*/React.createElement("div", {
    key: n.t,
    style: cell(blCol.bg, blCol.text, blCol.border)
  }, n.bl))), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: lbl("#ede8e0", "#6a6050", "#d0c8b8")
  }, "Trou n"), notes.map(n => /*#__PURE__*/React.createElement("div", {
    key: n.t,
    style: {
      ...cell("#ede8e0", "#2a2520", "#d0c8b8"),
      fontSize: 13,
      fontFamily: "monospace",
      borderTop: "2px solid #b8b0a0",
      borderBottom: "2px solid #b8b0a0"
    }
  }, n.t))), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: lbl(drCol.bg, drCol.text, drCol.border)
  }, "Aspirer"), notes.map(n => /*#__PURE__*/React.createElement("div", {
    key: n.t,
    style: cell(drCol.bg, drCol.text, drCol.border)
  }, n.dr))), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: lbl(bCol.bg, bCol.text, bCol.border)
  }, "Bend aspire"), notes.map(n => /*#__PURE__*/React.createElement("div", {
    key: n.t,
    style: cell(n.db.length ? bCol.bg : bCol.empty, n.db.length ? bCol.text : "#c8c0b8", bCol.border)
  }, n.db.length ? n.db.map((b, i) => /*#__PURE__*/React.createElement("span", {
    key: i,
    style: {
      fontSize: b.endsWith("*") ? 9 : 10
    }
  }, b.replace("*", ""), b.endsWith("*") ? "*" : "", i < n.db.length - 1 ? " >" : " ")) : /*#__PURE__*/React.createElement("span", {
    style: {
      opacity: 0.3
    }
  }, "-")))))), /*#__PURE__*/React.createElement("div", {
    style: {
      marginTop: 7,
      padding: "7px 10px",
      background: "#f0eaf8",
      border: "1px solid #c0a0d8",
      borderRadius: 6,
      fontSize: 11,
      color: "#7a40a0",
      lineHeight: 1.6
    }
  }, "Trous 1-6 : bend en aspirant. Trous 8-10 : bend en soufflant. * = micro-bend (expression seulement)."));
}
function TwelveBarDiagram() {
  const bars = [{
    n: 1,
    r: "A",
    chord: "Sol",
    sub: "draw 1-4"
  }, {
    n: 2,
    r: "A",
    chord: "Sol",
    sub: "draw 1-4"
  }, {
    n: 3,
    r: "A",
    chord: "Sol",
    sub: "draw 1-4"
  }, {
    n: 4,
    r: "A",
    chord: "Sol",
    sub: "draw 1-4"
  }, {
    n: 5,
    r: "B",
    chord: "Do",
    sub: "blow 1-4"
  }, {
    n: 6,
    r: "B",
    chord: "Do",
    sub: "blow 1-4"
  }, {
    n: 7,
    r: "A",
    chord: "Sol",
    sub: "draw 1-4"
  }, {
    n: 8,
    r: "A",
    chord: "Sol",
    sub: "draw 1-4"
  }, {
    n: 9,
    r: "C",
    chord: "Re",
    sub: "draw 2-5"
  }, {
    n: 10,
    r: "C",
    chord: "Re",
    sub: "draw 2-5"
  }, {
    n: 11,
    r: "A",
    chord: "Sol",
    sub: "draw 1-4"
  }, {
    n: 12,
    r: "A",
    chord: "Sol",
    sub: "draw 1-4"
  }];
  const cols = {
    A: {
      bg: "#e8f5ee",
      border: "#80c8a0",
      text: "#2a7a52"
    },
    B: {
      bg: "#eeeef8",
      border: "#9090d0",
      text: "#4a5fa0"
    },
    C: {
      bg: "#fdf0e8",
      border: "#f0a070",
      text: "#c85a20"
    }
  };
  return /*#__PURE__*/React.createElement("div", {
    style: {
      marginTop: 12
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      color: "#8a7f70",
      marginBottom: 8
    }
  }, "Structure 12 mesures"), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "grid",
      gridTemplateColumns: "repeat(4,1fr)",
      gap: 5
    }
  }, bars.map(b => {
    const c = cols[b.r];
    return /*#__PURE__*/React.createElement("div", {
      key: b.n,
      style: {
        background: c.bg,
        border: "1.5px solid " + c.border,
        borderRadius: 6,
        padding: "6px 8px",
        textAlign: "center"
      }
    }, /*#__PURE__*/React.createElement("div", {
      style: {
        fontSize: 9,
        color: c.text,
        fontFamily: "monospace"
      }
    }, "Mesure ", b.n), /*#__PURE__*/React.createElement("div", {
      style: {
        fontSize: 16,
        fontWeight: 700,
        color: c.text
      }
    }, b.r), /*#__PURE__*/React.createElement("div", {
      style: {
        fontSize: 12,
        fontWeight: 700,
        color: "#2a2520"
      }
    }, b.chord), /*#__PURE__*/React.createElement("div", {
      style: {
        fontSize: 9,
        color: "#8a7f70"
      }
    }, b.sub));
  })));
}
function ThreeRhythmsSchema() {
  const drCol = {
    bg: "#fdf0e8",
    border: "#f0a070",
    text: "#c85a20"
  };
  const blCol = {
    bg: "#e8f5ee",
    border: "#80c8a0",
    text: "#2a7a52"
  };
  const rhythms = [{
    id: "A",
    label: "Rythme A - aspirer",
    col: drCol,
    holes: [1, 2, 3, 4],
    beats: ["d", "b", "d", "d"],
    note: "Commence et finit en aspirant = accord Sol"
  }, {
    id: "B",
    label: "Rythme B - souffler",
    col: blCol,
    holes: [1, 2, 3, 4],
    beats: ["b", "d", "b", "b"],
    note: "Commence et finit en soufflant = accord Do"
  }, {
    id: "C",
    label: "Rythme C - comme A decale",
    col: drCol,
    holes: [2, 3, 4, 5],
    beats: ["d", "b", "d", "d"],
    note: "Meme que A, glisse 1-2 trous vers la droite = accord Re"
  }];
  return /*#__PURE__*/React.createElement("div", {
    style: {
      marginTop: 12
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      color: "#8a7f70",
      marginBottom: 8
    }
  }, "Les 3 rythmes"), rhythms.map(r => /*#__PURE__*/React.createElement("div", {
    key: r.id,
    style: {
      background: r.col.bg,
      border: "1.5px solid " + r.col.border,
      borderRadius: 8,
      padding: "10px 12px",
      marginBottom: 8
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 12,
      fontWeight: 700,
      color: r.col.text,
      marginBottom: 6
    }
  }, r.label, " (trous ", r.holes[0], "-", r.holes[r.holes.length - 1], ")"), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 6,
      alignItems: "center",
      marginBottom: 6
    }
  }, r.beats.map((b, i) => /*#__PURE__*/React.createElement("div", {
    key: i,
    style: {
      display: "flex",
      flexDirection: "column",
      alignItems: "center",
      gap: 1,
      padding: "4px 8px",
      background: "#fff",
      border: "1px solid " + r.col.border,
      borderRadius: 5,
      minWidth: 34
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 16,
      color: r.col.text,
      fontWeight: 700
    }
  }, b === "b" ? "↑" : "↓"), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 11,
      fontFamily: "monospace",
      fontWeight: 700,
      color: r.col.text
    }
  }, r.holes[i]))), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 11,
      color: "#8a7f70",
      fontStyle: "italic",
      marginLeft: 4
    }
  }, "x2 mesures")), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 11,
      color: r.col.text
    }
  }, r.note))));
}
const SCHEMAS = {
  "harmonica-layout": HarmonicaMap,
  "twelve-bar": TwelveBarDiagram,
  "three-rhythms": ThreeRhythmsSchema
};

// ⚠️ NE JAMAIS CHANGER CETTE CLE
const STORAGE_KEY = "hm-damien-v1";
const allExoIds = PHASES.flatMap(p => p.exercises.map(e => e.id));
const totalExos = allExoIds.length;
function StatusBtn({
  status,
  onChange
}) {
  const s = STATUS[status];
  return /*#__PURE__*/React.createElement("button", {
    onClick: onChange,
    style: {
      display: "flex",
      flexDirection: "column",
      alignItems: "center",
      gap: 3,
      padding: "5px 10px",
      borderRadius: 10,
      border: "1.5px solid " + s.color,
      background: s.bg,
      color: s.color,
      cursor: "pointer",
      flexShrink: 0,
      minWidth: 68
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      alignItems: "center",
      gap: 4
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 14
    }
  }, s.emoji), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 10,
      fontWeight: 700,
      fontFamily: "monospace"
    }
  }, s.label)), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 3
    }
  }, STATUS.map((_, i) => /*#__PURE__*/React.createElement("div", {
    key: i,
    style: {
      width: 7,
      height: 7,
      borderRadius: "50%",
      background: i <= status ? s.color : "#d8d0c0",
      transition: "background 0.2s"
    }
  }))));
}
function MiniBar({
  value,
  total,
  color
}) {
  const pct = total === 0 ? 0 : Math.round(value / total * 100);
  return /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      alignItems: "center",
      gap: 8
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      flex: 1,
      height: 4,
      background: "#e0d8cc",
      borderRadius: 2,
      overflow: "hidden"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      width: pct + "%",
      height: "100%",
      background: color,
      borderRadius: 2,
      transition: "width 0.4s"
    }
  })), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 11,
      color: "#8a7f70",
      fontFamily: "monospace",
      minWidth: 32
    }
  }, value, "/", total));
}
function ExoCard({
  exo,
  progress,
  onStatusChange,
  onNoteChange
}) {
  const [open, setOpen] = useState(false);
  return /*#__PURE__*/React.createElement("div", {
    style: {
      border: "1px solid #d8d0c0",
      borderRadius: 8,
      overflow: "hidden",
      background: "#fff"
    }
  }, /*#__PURE__*/React.createElement("div", {
    onClick: () => setOpen(o => !o),
    style: {
      display: "flex",
      alignItems: "center",
      gap: 10,
      padding: "11px 14px",
      cursor: "pointer",
      background: open ? "#f8f3ec" : "#fff",
      borderBottom: open ? "1px solid #e8e0d0" : "none"
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 17,
      flexShrink: 0
    }
  }, exo.icon), /*#__PURE__*/React.createElement("div", {
    style: {
      flex: 1,
      minWidth: 0
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13.5,
      fontWeight: 600,
      color: "#2a2520"
    }
  }, exo.title), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      color: "#8a7f70",
      fontFamily: "monospace",
      marginTop: 1
    }
  }, exo.tag)), /*#__PURE__*/React.createElement(StatusBtn, {
    status: progress.status ?? 0,
    onChange: e => {
      e.stopPropagation();
      onStatusChange(((progress.status ?? 0) + 1) % STATUS.length);
    }
  }), /*#__PURE__*/React.createElement("span", {
    style: {
      color: "#b0a090",
      fontSize: 11,
      marginLeft: 2,
      flexShrink: 0
    }
  }, open ? "▲" : "▼")), open && /*#__PURE__*/React.createElement("div", {
    style: {
      padding: "13px 15px"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      background: "#fdf8f0",
      border: "1px solid #f0d8b0",
      borderRadius: 6,
      padding: "9px 12px",
      marginBottom: 12,
      fontSize: 13,
      color: "#6a4a20",
      lineHeight: 1.6
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontFamily: "monospace",
      fontSize: 10,
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      color: "#c87020",
      display: "block",
      marginBottom: 3
    }
  }, "Pourquoi ?"), exo.why), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 5,
      marginBottom: 12,
      flexWrap: "wrap"
    }
  }, STATUS.map((s, i) => /*#__PURE__*/React.createElement("div", {
    key: i,
    onClick: () => onStatusChange(i),
    style: {
      display: "flex",
      alignItems: "center",
      gap: 4,
      padding: "4px 9px",
      borderRadius: 20,
      border: "1.5px solid " + ((progress.status ?? 0) === i ? s.color : (progress.status ?? 0) > i ? "#a0c8a8" : "#d8d0c0"),
      background: (progress.status ?? 0) === i ? s.bg : (progress.status ?? 0) > i ? "#f0faf4" : "#f8f5f0",
      cursor: "pointer"
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 12,
      color: (progress.status ?? 0) >= i ? s.color : "#c0b8a8"
    }
  }, s.emoji), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      fontWeight: (progress.status ?? 0) === i ? 700 : 400,
      color: (progress.status ?? 0) === i ? s.color : (progress.status ?? 0) > i ? "#2a7a52" : "#9a9080"
    }
  }, s.label)))), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      color: "#8a7f70",
      marginBottom: 7
    }
  }, "Etapes"), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "grid",
      gap: 6,
      marginBottom: 12
    }
  }, exo.steps.map((step, i) => /*#__PURE__*/React.createElement("div", {
    key: i,
    style: {
      display: "flex",
      gap: 9,
      fontSize: 13,
      color: "#4a4038",
      lineHeight: 1.6
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      flexShrink: 0,
      width: 20,
      height: 20,
      borderRadius: "50%",
      background: "#f0ece4",
      display: "flex",
      alignItems: "center",
      justifyContent: "center",
      fontSize: 10,
      color: "#8a7f70",
      fontFamily: "monospace",
      marginTop: 2
    }
  }, i + 1), /*#__PURE__*/React.createElement("span", null, step)))), exo.tabs && /*#__PURE__*/React.createElement(TabDisplay, {
    tabs: exo.tabs
  }), exo.schema && (() => {
    const S = SCHEMAS[exo.schema];
    return S ? /*#__PURE__*/React.createElement(S, null) : null;
  })(), exo.extraSchema && (() => {
    const S = SCHEMAS[exo.extraSchema];
    return S ? /*#__PURE__*/React.createElement(S, null) : null;
  })(), /*#__PURE__*/React.createElement("div", {
    style: {
      borderTop: "1px solid #ede8e0",
      paddingTop: 10,
      marginTop: 12
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      color: "#8a7f70",
      letterSpacing: "0.1em",
      textTransform: "uppercase",
      marginBottom: 5
    }
  }, "Ma note"), /*#__PURE__*/React.createElement("textarea", {
    value: progress.note ?? "",
    onChange: e => onNoteChange(e.target.value),
    placeholder: "Ce qui marche, ce qui coince, la date...",
    rows: 2,
    style: {
      width: "100%",
      padding: "8px 11px",
      border: "1px solid #d8d0c0",
      borderRadius: 6,
      fontSize: 13,
      color: "#2a2520",
      background: "#f8f5f0",
      fontFamily: "inherit",
      lineHeight: 1.6,
      resize: "vertical",
      outline: "none"
    }
  }))));
}
function PhaseBlock({
  phase,
  progress,
  onStatusChange,
  onNoteChange
}) {
  const [open, setOpen] = useState(false);
  const wSum = phase.exercises.reduce((s, e) => s + (progress[e.id]?.status ?? 0), 0);
  const mastered = phase.exercises.filter(e => (progress[e.id]?.status ?? 0) === 4).length;
  const inProg = phase.exercises.filter(e => {
    const s = progress[e.id]?.status ?? 0;
    return s >= 1 && s <= 3;
  }).length;
  return /*#__PURE__*/React.createElement("div", {
    style: {
      border: "1px solid #d8d0c0",
      borderRadius: 12,
      overflow: "hidden",
      marginBottom: 14
    }
  }, /*#__PURE__*/React.createElement("div", {
    onClick: () => setOpen(o => !o),
    style: {
      display: "flex",
      alignItems: "center",
      gap: 14,
      padding: "18px 22px",
      cursor: "pointer",
      background: phase.bg,
      borderBottom: open ? "2px solid " + phase.color + "33" : "none"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontFamily: "Georgia,serif",
      fontSize: 34,
      fontWeight: 700,
      color: phase.color,
      lineHeight: 1,
      minWidth: 48
    }
  }, phase.num), /*#__PURE__*/React.createElement("div", {
    style: {
      flex: 1
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      alignItems: "center",
      gap: 8,
      marginBottom: 2
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      color: phase.color,
      letterSpacing: "0.12em",
      textTransform: "uppercase"
    }
  }, "Phase ", phase.num), phase.subtitle && /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      padding: "1px 8px",
      borderRadius: 20,
      background: phase.color + "20",
      color: phase.color,
      fontWeight: 700
    }
  }, phase.subtitle)), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 15,
      fontWeight: 700,
      color: "#2a2520",
      marginBottom: 5
    }
  }, phase.title), /*#__PURE__*/React.createElement(MiniBar, {
    value: wSum,
    total: phase.exercises.length * 4,
    color: phase.color
  })), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      flexDirection: "column",
      alignItems: "flex-end",
      gap: 3,
      flexShrink: 0
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      padding: "3px 9px",
      borderRadius: 20,
      background: phase.color + "20",
      color: phase.color
    }
  }, phase.badge), inProg > 0 && /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 10,
      color: "#c85a20",
      fontFamily: "monospace"
    }
  }, inProg, " en cours"), /*#__PURE__*/React.createElement("span", {
    style: {
      color: "#b0a090",
      fontSize: 12
    }
  }, open ? "▲" : "▼"))), open && /*#__PURE__*/React.createElement("div", {
    style: {
      padding: 14,
      background: "#fafaf7",
      display: "grid",
      gap: 9
    }
  }, phase.exercises.map(exo => /*#__PURE__*/React.createElement(ExoCard, {
    key: exo.id,
    exo: exo,
    progress: progress[exo.id] ?? {
      status: 0,
      note: ""
    },
    onStatusChange: lv => onStatusChange(exo.id, lv),
    onNoteChange: n => onNoteChange(exo.id, n)
  }))));
}
function LexiqueView() {
  const [search, setSearch] = useState("");
  const filt = LEXIQUE.map(cat => ({
    ...cat,
    terms: cat.terms.filter(t => t.word.toLowerCase().includes(search.toLowerCase()) || t.def.toLowerCase().includes(search.toLowerCase()))
  })).filter(cat => cat.terms.length > 0);
  return /*#__PURE__*/React.createElement("div", null, /*#__PURE__*/React.createElement("div", {
    style: {
      background: "#eeeef8",
      border: "1px solid #c8d0e8",
      borderRadius: 8,
      padding: "9px 14px",
      marginBottom: 14,
      display: "flex",
      gap: 10,
      alignItems: "center"
    }
  }, /*#__PURE__*/React.createElement("span", null, "🔍"), /*#__PURE__*/React.createElement("input", {
    type: "text",
    placeholder: "Chercher un terme...",
    value: search,
    onChange: e => setSearch(e.target.value),
    style: {
      flex: 1,
      border: "none",
      background: "transparent",
      fontSize: 13.5,
      color: "#2a2520",
      fontFamily: "inherit",
      outline: "none"
    }
  }), search && /*#__PURE__*/React.createElement("button", {
    onClick: () => setSearch(""),
    style: {
      border: "none",
      background: "none",
      cursor: "pointer",
      color: "#8a7f70",
      fontSize: 16
    }
  }, "x")), /*#__PURE__*/React.createElement(HarmonicaMap, null), /*#__PURE__*/React.createElement("div", {
    style: {
      height: 16
    }
  }), filt.map(cat => /*#__PURE__*/React.createElement("div", {
    key: cat.cat,
    style: {
      marginBottom: 20
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      letterSpacing: "0.14em",
      textTransform: "uppercase",
      color: cat.color,
      marginBottom: 8,
      paddingBottom: 5,
      borderBottom: "1.5px solid " + cat.color + "30"
    }
  }, cat.cat), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "grid",
      gap: 8
    }
  }, cat.terms.map(t => /*#__PURE__*/React.createElement("div", {
    key: t.word,
    style: {
      background: "#fff",
      border: "1px solid #d8d8ee",
      borderRadius: 8,
      padding: "11px 14px",
      borderLeft: "3px solid " + cat.color
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13.5,
      fontWeight: 700,
      color: "#2a2520",
      marginBottom: 4
    }
  }, t.word), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13,
      color: "#4a4858",
      lineHeight: 1.65
    }
  }, t.def)))))), filt.length === 0 && /*#__PURE__*/React.createElement("div", {
    style: {
      textAlign: "center",
      color: "#8a7f70",
      fontSize: 13,
      padding: "30px 0"
    }
  }, "Aucun terme pour \"", search, "\""));
}
function Metronome({
  defaultBpm = 80,
  bpmRange = [30, 240],
  timeSignature = 4
}) {
  const [bpm, setBpm] = useState(defaultBpm);
  const [isPlaying, setIsPlaying] = useState(false);
  const [activeBeat, setActiveBeat] = useState(-1);
  const ctxRef = useRef(null);
  const timerRef = useRef(null);
  const nextRef = useRef(0);
  const beatRef = useRef(0);
  const bpmRef = useRef(bpm);
  const playRef = useRef(false);
  useEffect(() => {
    bpmRef.current = bpm;
  }, [bpm]);
  useEffect(() => () => {
    clearInterval(timerRef.current);
  }, []);
  const click = useCallback((ctx, t, accent) => {
    const o = ctx.createOscillator(),
      g = ctx.createGain();
    o.connect(g);
    g.connect(ctx.destination);
    o.type = "sine";
    o.frequency.value = accent ? 1400 : 900;
    g.gain.setValueAtTime(0, t);
    g.gain.linearRampToValueAtTime(accent ? 0.8 : 0.45, t + 0.003);
    g.gain.exponentialRampToValueAtTime(0.001, t + 0.08);
    o.start(t);
    o.stop(t + 0.1);
  }, []);
  const sched = useCallback(() => {
    const ctx = ctxRef.current;
    if (!ctx || !playRef.current) return;
    while (nextRef.current < ctx.currentTime + 0.12) {
      const b = beatRef.current,
        t = nextRef.current;
      click(ctx, t, b === 0);
      const d = Math.max(0, (t - ctx.currentTime) * 1000);
      const cb = b;
      setTimeout(() => {
        if (playRef.current) setActiveBeat(cb);
      }, d);
      nextRef.current += 60 / bpmRef.current;
      beatRef.current = (beatRef.current + 1) % timeSignature;
    }
  }, [click, timeSignature]);
  const start = useCallback(() => {
    if (!ctxRef.current || ctxRef.current.state === "closed") ctxRef.current = new (window.AudioContext || window.webkitAudioContext)();
    if (ctxRef.current.state === "suspended") ctxRef.current.resume();
    nextRef.current = ctxRef.current.currentTime + 0.05;
    beatRef.current = 0;
    playRef.current = true;
    setIsPlaying(true);
    timerRef.current = setInterval(sched, 25);
  }, [sched]);
  const stop = useCallback(() => {
    clearInterval(timerRef.current);
    playRef.current = false;
    setIsPlaying(false);
    setActiveBeat(-1);
  }, []);
  const adj = d => setBpm(b => Math.max(bpmRange[0], Math.min(bpmRange[1], b + d)));
  return /*#__PURE__*/React.createElement("div", {
    style: {
      background: "#1a1816",
      borderRadius: 12,
      padding: "16px 18px",
      marginBottom: 14,
      border: "1px solid #3a3530"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      alignItems: "center",
      gap: 8,
      marginBottom: 12
    }
  }, /*#__PURE__*/React.createElement("span", null, "🥁"), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 11,
      fontFamily: "monospace",
      color: "#9a9080",
      textTransform: "uppercase",
      letterSpacing: "0.1em"
    }
  }, "Metronome")), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 8,
      justifyContent: "center",
      marginBottom: 14
    }
  }, Array.from({
    length: timeSignature
  }).map((_, i) => {
    const act = activeBeat === i,
      acc = i === 0;
    return /*#__PURE__*/React.createElement("div", {
      key: i,
      style: {
        width: acc ? 36 : 30,
        height: acc ? 36 : 30,
        borderRadius: "50%",
        background: act ? acc ? "#c85a20" : "#e8a060" : acc ? "#2a2218" : "#1e1c18",
        border: "2px solid " + (act ? acc ? "#c85a20" : "#c8906a" : acc ? "#4a3828" : "#2a2820"),
        transition: "background 0.05s",
        boxShadow: act ? "0 0 12px " + (acc ? "#c85a2080" : "#c8906a50") : "none",
        display: "flex",
        alignItems: "center",
        justifyContent: "center"
      }
    }, acc && /*#__PURE__*/React.createElement("div", {
      style: {
        width: 8,
        height: 8,
        borderRadius: "50%",
        background: act ? "#fff" : "#4a3828"
      }
    }));
  })), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      alignItems: "center",
      gap: 10,
      marginBottom: 10
    }
  }, /*#__PURE__*/React.createElement("button", {
    onClick: () => adj(-5),
    style: {
      width: 32,
      height: 32,
      borderRadius: "50%",
      background: "#2a2520",
      border: "1px solid #4a4038",
      color: "#c8b8a0",
      fontSize: 16,
      cursor: "pointer",
      display: "flex",
      alignItems: "center",
      justifyContent: "center",
      fontWeight: 700
    }
  }, "-"), /*#__PURE__*/React.createElement("button", {
    onClick: () => adj(-1),
    style: {
      width: 26,
      height: 26,
      borderRadius: "50%",
      background: "#221e1a",
      border: "1px solid #3a3028",
      color: "#8a7a68",
      fontSize: 13,
      cursor: "pointer",
      display: "flex",
      alignItems: "center",
      justifyContent: "center"
    }
  }, "-"), /*#__PURE__*/React.createElement("div", {
    style: {
      flex: 1,
      textAlign: "center"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 32,
      fontWeight: 700,
      fontFamily: "monospace",
      color: "#e8d8c0",
      lineHeight: 1
    }
  }, bpm), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      color: "#6a6258",
      fontFamily: "monospace"
    }
  }, "BPM")), /*#__PURE__*/React.createElement("button", {
    onClick: () => adj(1),
    style: {
      width: 26,
      height: 26,
      borderRadius: "50%",
      background: "#221e1a",
      border: "1px solid #3a3028",
      color: "#8a7a68",
      fontSize: 13,
      cursor: "pointer",
      display: "flex",
      alignItems: "center",
      justifyContent: "center"
    }
  }, "+"), /*#__PURE__*/React.createElement("button", {
    onClick: () => adj(5),
    style: {
      width: 32,
      height: 32,
      borderRadius: "50%",
      background: "#2a2520",
      border: "1px solid #4a4038",
      color: "#c8b8a0",
      fontSize: 16,
      cursor: "pointer",
      display: "flex",
      alignItems: "center",
      justifyContent: "center",
      fontWeight: 700
    }
  }, "+")), /*#__PURE__*/React.createElement("input", {
    type: "range",
    min: bpmRange[0],
    max: bpmRange[1],
    value: bpm,
    onChange: e => setBpm(Number(e.target.value)),
    style: {
      width: "100%",
      marginBottom: 12,
      accentColor: "#c85a20",
      cursor: "pointer"
    }
  }), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 6,
      marginBottom: 12,
      flexWrap: "wrap"
    }
  }, [[defaultBpm, "Debutant"], [Math.min(bpmRange[1], Math.round(defaultBpm * 1.5)), "x1.5"], [Math.min(bpmRange[1], Math.round(defaultBpm * 2)), "Cible"]].map(([val, label]) => /*#__PURE__*/React.createElement("button", {
    key: label,
    onClick: () => setBpm(val),
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      padding: "3px 9px",
      borderRadius: 20,
      border: "1px solid #3a3028",
      background: bpm === val ? "#3a2a18" : "#221e1a",
      color: bpm === val ? "#c8906a" : "#8a7a68",
      cursor: "pointer"
    }
  }, label, " (", val, ")"))), /*#__PURE__*/React.createElement("button", {
    onClick: isPlaying ? stop : start,
    style: {
      width: "100%",
      padding: "12px",
      borderRadius: 8,
      background: isPlaying ? "#3a1a10" : "#c85a20",
      border: "1px solid " + (isPlaying ? "#6a2a18" : "#c85a20"),
      color: isPlaying ? "#c86a50" : "#fff",
      fontSize: 14,
      fontWeight: 700,
      cursor: "pointer",
      display: "flex",
      alignItems: "center",
      justifyContent: "center",
      gap: 8
    }
  }, isPlaying ? "⏹ Stop" : "▶ Demarrer"));
}
function DiffBadge({
  label,
  color
}) {
  return /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      padding: "2px 8px",
      borderRadius: 20,
      background: color + "20",
      color,
      border: "1px solid " + color + "40"
    }
  }, label);
}
function SongCard({
  song,
  progress,
  onStatusChange,
  onNoteChange
}) {
  const [open, setOpen] = useState(false);
  return /*#__PURE__*/React.createElement("div", {
    style: {
      border: "1.5px solid " + song.color + "40",
      borderRadius: 12,
      overflow: "hidden",
      background: "#fff",
      marginBottom: 14
    }
  }, /*#__PURE__*/React.createElement("div", {
    onClick: () => setOpen(o => !o),
    style: {
      padding: "18px 20px",
      cursor: "pointer",
      background: song.bg,
      borderBottom: open ? "1px solid " + song.color + "30" : "none"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      alignItems: "flex-start",
      gap: 14
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 28,
      lineHeight: 1,
      flexShrink: 0
    }
  }, song.icon), /*#__PURE__*/React.createElement("div", {
    style: {
      flex: 1,
      minWidth: 0
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 16,
      fontWeight: 700,
      color: "#2a2520",
      marginBottom: 4
    }
  }, song.title), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 12,
      color: "#6a6060",
      marginBottom: 7
    }
  }, song.artist), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 6,
      flexWrap: "wrap"
    }
  }, /*#__PURE__*/React.createElement(DiffBadge, {
    label: song.style,
    color: song.color
  }), /*#__PURE__*/React.createElement(DiffBadge, {
    label: song.niveau,
    color: "#2a7a52"
  }), /*#__PURE__*/React.createElement(DiffBadge, {
    label: song.position + " position",
    color: "#4a5fa0"
  }), /*#__PURE__*/React.createElement(DiffBadge, {
    label: song.bends ? "Bends requis" : "Sans bends",
    color: song.bends ? "#c85a20" : "#2a7a52"
  }))), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      flexDirection: "column",
      alignItems: "flex-end",
      gap: 6,
      flexShrink: 0
    }
  }, /*#__PURE__*/React.createElement(StatusBtn, {
    status: progress.status ?? 0,
    onChange: e => {
      e.stopPropagation();
      onStatusChange(((progress.status ?? 0) + 1) % STATUS.length);
    }
  }), !open && /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 2
    }
  }, STATUS.map((_, i) => /*#__PURE__*/React.createElement("div", {
    key: i,
    style: {
      width: 6,
      height: 6,
      borderRadius: "50%",
      background: i <= (progress.status ?? 0) ? STATUS[progress.status ?? 0].color : "#d8d0c0"
    }
  }))), /*#__PURE__*/React.createElement("span", {
    style: {
      color: "#b0a090",
      fontSize: 11
    }
  }, open ? "▲" : "▼")))), open && /*#__PURE__*/React.createElement("div", {
    style: {
      padding: "16px 20px"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13.5,
      color: "#4a4038",
      lineHeight: 1.7,
      marginBottom: 12
    }
  }, song.desc), /*#__PURE__*/React.createElement("div", {
    style: {
      background: "#fdf8f0",
      border: "1px solid #f0d8b0",
      borderRadius: 6,
      padding: "9px 12px",
      marginBottom: 14,
      fontSize: 13,
      color: "#6a4a20",
      lineHeight: 1.6
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontFamily: "monospace",
      fontSize: 10,
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      color: "#c87020",
      display: "block",
      marginBottom: 3
    }
  }, "Conseil"), song.tips), song.masteryLevels && /*#__PURE__*/React.createElement("div", {
    style: {
      marginBottom: 14
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      color: "#8a7f70",
      marginBottom: 8
    }
  }, "Niveaux de maitrise"), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "grid",
      gap: 6
    }
  }, song.masteryLevels.map((crit, i) => {
    const s = STATUS[i],
      cur = progress.status ?? 0,
      reached = cur > i,
      active = cur === i;
    return /*#__PURE__*/React.createElement("div", {
      key: i,
      onClick: () => onStatusChange(i),
      style: {
        display: "flex",
        alignItems: "flex-start",
        gap: 10,
        padding: "9px 12px",
        borderRadius: 8,
        cursor: "pointer",
        border: "1.5px solid " + (reached ? "#a0c8a8" : active ? s.color : "#d8d0c0"),
        background: reached ? "#e8f5ee" : active ? s.bg : "#f8f5f0",
        transition: "all 0.2s"
      }
    }, /*#__PURE__*/React.createElement("div", {
      style: {
        flexShrink: 0,
        width: 24,
        height: 24,
        borderRadius: "50%",
        background: reached ? "#2a7a52" : active ? s.color : "#d8d0c0",
        display: "flex",
        alignItems: "center",
        justifyContent: "center",
        marginTop: 1
      }
    }, /*#__PURE__*/React.createElement("span", {
      style: {
        fontSize: 12,
        color: "#fff",
        fontWeight: 700
      }
    }, reached ? "✓" : active ? "→" : i + 1)), /*#__PURE__*/React.createElement("div", {
      style: {
        flex: 1
      }
    }, /*#__PURE__*/React.createElement("div", {
      style: {
        fontSize: 10,
        fontFamily: "monospace",
        color: reached ? "#2a7a52" : active ? s.color : "#9a9080",
        letterSpacing: "0.06em",
        marginBottom: 2
      }
    }, "NIVEAU ", i + 1, " - ", s.label.toUpperCase()), /*#__PURE__*/React.createElement("div", {
      style: {
        fontSize: 13,
        color: reached ? "#2a5a30" : active ? "#2a2520" : "#8a8078",
        fontWeight: active ? 600 : 400
      }
    }, crit)));
  }))), /*#__PURE__*/React.createElement(Metronome, {
    defaultBpm: song.suggestedBpm || 80,
    bpmRange: song.bpmRange || [30, 240],
    timeSignature: song.timeSignature || 4
  }), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 10,
      flexWrap: "wrap",
      alignItems: "center",
      marginBottom: 10,
      fontSize: 11,
      padding: "6px 10px",
      background: "#f0ece8",
      borderRadius: 6
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      color: "#8a7f70",
      fontFamily: "monospace",
      fontSize: 10
    }
  }, "LEGENDE :"), /*#__PURE__*/React.createElement("span", {
    style: {
      color: "#2a7a52",
      fontWeight: 700
    }
  }, "↑ souffler"), /*#__PURE__*/React.createElement("span", {
    style: {
      color: "#c85a20",
      fontWeight: 700
    }
  }, "↓ aspirer"), /*#__PURE__*/React.createElement("span", {
    style: {
      color: "#7a40a0",
      fontWeight: 700
    }
  }, "↓' bend"), /*#__PURE__*/React.createElement("span", {
    style: {
      color: "#6a6060"
    }
  }, "4 = trou 4 \xA0 1-3 = accord trous 1 a 3")), song.tabs.map((tab, i) => /*#__PURE__*/React.createElement(TabBar, {
    key: i,
    tab: tab,
    size: "lg"
  })), /*#__PURE__*/React.createElement("div", {
    style: {
      borderTop: "1px solid #ede8e0",
      paddingTop: 10,
      marginTop: 10
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      color: "#8a7f70",
      letterSpacing: "0.1em",
      textTransform: "uppercase",
      marginBottom: 5
    }
  }, "Ma note"), /*#__PURE__*/React.createElement("textarea", {
    value: progress.note ?? "",
    onChange: e => onNoteChange(e.target.value),
    placeholder: "Tempo atteint, difficultes, date...",
    rows: 2,
    style: {
      width: "100%",
      padding: "8px 11px",
      border: "1px solid #d8d0c0",
      borderRadius: 6,
      fontSize: 13,
      color: "#2a2520",
      background: "#f8f5f0",
      fontFamily: "inherit",
      lineHeight: 1.6,
      resize: "vertical",
      outline: "none"
    }
  }))));
}
function SongsView({
  progress,
  onStatusChange,
  onNoteChange
}) {
  const mc = SONGS.filter(s => (progress[s.id]?.status ?? 0) === 4).length;
  return /*#__PURE__*/React.createElement("div", null, /*#__PURE__*/React.createElement("div", {
    style: {
      background: "#fff",
      border: "1px solid #d8d0c0",
      borderRadius: 12,
      padding: "14px 18px",
      marginBottom: 16
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      color: "#c85a20",
      letterSpacing: "0.12em",
      textTransform: "uppercase",
      marginBottom: 6
    }
  }, "Lire la tablature"), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "grid",
      gridTemplateColumns: "1fr 1fr",
      gap: 7
    }
  }, [["↓  4", "Aspirer trou 4 seul"], ["↑  4", "Souffler trou 4 seul"], ["↓  1-3", "Aspirer trous 1, 2, 3 (accord)"], ["↑  4-6", "Souffler trous 4, 5, 6 (accord)"], ["↓' 3", "Aspirer trou 3 avec bend"], ["|", "Barre de mesure"]].map((r, i) => /*#__PURE__*/React.createElement("div", {
    key: i,
    style: {
      display: "flex",
      alignItems: "center",
      gap: 8,
      padding: "5px 8px",
      background: "#f8f5f0",
      borderRadius: 6
    }
  }, /*#__PURE__*/React.createElement("code", {
    style: {
      fontFamily: "monospace",
      fontSize: 12,
      fontWeight: 700,
      color: "#2a2520",
      minWidth: 44,
      background: "#ede8e0",
      padding: "2px 5px",
      borderRadius: 4
    }
  }, r[0]), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 11,
      color: "#6a6060"
    }
  }, r[1]))))), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      alignItems: "center",
      gap: 10,
      marginBottom: 16,
      padding: "10px 14px",
      background: "#fff",
      borderRadius: 8,
      border: "1px solid #d8d0c0"
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 12,
      color: "#8a7f70",
      fontFamily: "monospace"
    }
  }, "Morceaux maitrisés :"), /*#__PURE__*/React.createElement("div", {
    style: {
      flex: 1,
      height: 5,
      background: "#e0d8cc",
      borderRadius: 3,
      overflow: "hidden"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      width: Math.round(mc / SONGS.length * 100) + "%",
      height: "100%",
      background: "#2a7a52",
      borderRadius: 3,
      transition: "width 0.4s"
    }
  })), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 12,
      fontFamily: "monospace",
      color: "#2a7a52",
      fontWeight: 700
    }
  }, mc, "/", SONGS.length)), SONGS.map(song => /*#__PURE__*/React.createElement(SongCard, {
    key: song.id,
    song: song,
    progress: progress[song.id] ?? {
      status: 0,
      note: ""
    },
    onStatusChange: lv => onStatusChange(song.id, lv),
    onNoteChange: n => onNoteChange(song.id, n)
  })));
}
function SaveRestore({
  progress,
  onRestore
}) {
  const [mode, setMode] = useState(null);
  const [importText, setImportText] = useState("");
  const [msg, setMsg] = useState("");
  const doExport = () => {
    const d = JSON.stringify(progress);
    setMode("export");
    setMsg("");
    try {
      navigator.clipboard.writeText(d).then(() => setMsg("Copie dans le presse-papier !"));
    } catch (_) {}
    return d;
  };
  const doImport = () => {
    try {
      const parsed = JSON.parse(importText.trim());
      onRestore(parsed);
      setMode(null);
      setImportText("");
      setMsg("");
    } catch (e) {
      setMsg("JSON invalide - as-tu tout copie ?");
    }
  };
  const json = mode === "export" ? JSON.stringify(progress) : "";
  return /*#__PURE__*/React.createElement("div", {
    style: {
      marginTop: 12,
      borderTop: "1px solid #e8e0d0",
      paddingTop: 12
    }
  }, mode === null && /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 8,
      flexWrap: "wrap"
    }
  }, /*#__PURE__*/React.createElement("button", {
    onClick: doExport,
    style: {
      fontSize: 11,
      fontFamily: "monospace",
      padding: "5px 12px",
      borderRadius: 20,
      border: "1px solid #d8d0c0",
      background: "#f8f5f0",
      color: "#6a6060",
      cursor: "pointer"
    }
  }, "💾 Sauvegarder ma progression"), /*#__PURE__*/React.createElement("button", {
    onClick: () => setMode("import"),
    style: {
      fontSize: 11,
      fontFamily: "monospace",
      padding: "5px 12px",
      borderRadius: 20,
      border: "1px solid #d8d0c0",
      background: "#f8f5f0",
      color: "#6a6060",
      cursor: "pointer"
    }
  }, "📥 Restaurer une sauvegarde")), mode === "export" && /*#__PURE__*/React.createElement("div", null, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 11,
      color: "#6a6060",
      marginBottom: 6
    }
  }, "Copie ce texte et garde-le en lieu sur.", msg && /*#__PURE__*/React.createElement("strong", {
    style: {
      color: "#2a7a52",
      marginLeft: 8
    }
  }, msg)), /*#__PURE__*/React.createElement("textarea", {
    readOnly: true,
    value: json,
    rows: 3,
    onClick: e => e.target.select(),
    style: {
      width: "100%",
      padding: "8px",
      border: "1px solid #c8c0b8",
      borderRadius: 6,
      fontSize: 11,
      fontFamily: "monospace",
      background: "#f0ece4",
      color: "#2a2520",
      resize: "vertical",
      outline: "none"
    }
  }), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 8,
      marginTop: 8
    }
  }, /*#__PURE__*/React.createElement("button", {
    onClick: () => {
      const el = document.createElement("textarea");
      el.value = json;
      document.body.appendChild(el);
      el.select();
      document.execCommand("copy");
      document.body.removeChild(el);
      setMsg("Copie !");
    },
    style: {
      fontSize: 11,
      padding: "5px 12px",
      borderRadius: 20,
      border: "1px solid #2a7a52",
      background: "#e8f5ee",
      color: "#2a7a52",
      cursor: "pointer",
      fontFamily: "monospace"
    }
  }, "Copier"), /*#__PURE__*/React.createElement("button", {
    onClick: () => setMode(null),
    style: {
      fontSize: 11,
      padding: "5px 12px",
      borderRadius: 20,
      border: "1px solid #d8d0c0",
      background: "#f8f5f0",
      color: "#8a7f70",
      cursor: "pointer",
      fontFamily: "monospace"
    }
  }, "Fermer"))), mode === "import" && /*#__PURE__*/React.createElement("div", null, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 11,
      color: "#6a6060",
      marginBottom: 6
    }
  }, "Colle ici le texte de ta sauvegarde :", msg && /*#__PURE__*/React.createElement("span", {
    style: {
      color: "#c85a20",
      marginLeft: 8
    }
  }, msg)), /*#__PURE__*/React.createElement("textarea", {
    value: importText,
    onChange: e => setImportText(e.target.value),
    placeholder: "{\"s1\":{\"status\":2},...}",
    rows: 3,
    style: {
      width: "100%",
      padding: "8px",
      border: "1px solid #c8c0b8",
      borderRadius: 6,
      fontSize: 11,
      fontFamily: "monospace",
      background: "#fff",
      color: "#2a2520",
      resize: "vertical",
      outline: "none"
    }
  }), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 8,
      marginTop: 8
    }
  }, /*#__PURE__*/React.createElement("button", {
    onClick: doImport,
    disabled: !importText.trim(),
    style: {
      fontSize: 11,
      padding: "5px 12px",
      borderRadius: 20,
      border: "1px solid #2a7a52",
      background: "#e8f5ee",
      color: "#2a7a52",
      cursor: "pointer",
      fontFamily: "monospace",
      opacity: importText.trim() ? 1 : 0.5
    }
  }, "Restaurer"), /*#__PURE__*/React.createElement("button", {
    onClick: () => {
      setMode(null);
      setImportText("");
      setMsg("");
    },
    style: {
      fontSize: 11,
      padding: "5px 12px",
      borderRadius: 20,
      border: "1px solid #d8d0c0",
      background: "#f8f5f0",
      color: "#8a7f70",
      cursor: "pointer",
      fontFamily: "monospace"
    }
  }, "Annuler"))));
}

// ─── ONGLET BLUES ─────────────────────────────────────────────────────────────
function BluesView() {
  const [openSection, setOpenSection] = useState(null);
  const toggle = id => setOpenSection(s => s === id ? null : id);
  const Section = ({
    id,
    icon,
    title,
    color,
    children
  }) => /*#__PURE__*/React.createElement("div", {
    style: {
      border: "1.5px solid " + color + "40",
      borderRadius: 12,
      overflow: "hidden",
      marginBottom: 14
    }
  }, /*#__PURE__*/React.createElement("div", {
    onClick: () => toggle(id),
    style: {
      display: "flex",
      alignItems: "center",
      gap: 12,
      padding: "16px 18px",
      cursor: "pointer",
      background: color + "10",
      borderBottom: openSection === id ? "1px solid " + color + "30" : "none"
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 22
    }
  }, icon), /*#__PURE__*/React.createElement("div", {
    style: {
      flex: 1,
      fontSize: 15,
      fontWeight: 700,
      color: "#2a2520"
    }
  }, title), /*#__PURE__*/React.createElement("span", {
    style: {
      color: color,
      fontSize: 12,
      fontWeight: 700
    }
  }, openSection === id ? "▲" : "▼")), openSection === id && /*#__PURE__*/React.createElement("div", {
    style: {
      padding: "18px 20px",
      background: "#fff"
    }
  }, children));
  const ChordBox = ({
    label,
    holes,
    dir,
    note,
    role,
    color
  }) => /*#__PURE__*/React.createElement("div", {
    style: {
      background: color + "10",
      border: "1.5px solid " + color + "40",
      borderRadius: 10,
      padding: "14px 16px",
      marginBottom: 10
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      alignItems: "center",
      gap: 10,
      marginBottom: 10
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 22,
      fontWeight: 700,
      color: color,
      fontFamily: "Georgia,serif",
      minWidth: 32
    }
  }, label), /*#__PURE__*/React.createElement("div", null, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13,
      fontWeight: 700,
      color: "#2a2520"
    }
  }, role), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 11,
      color: "#8a7f70"
    }
  }, "Note de base : ", note))), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 5,
      flexWrap: "wrap",
      marginBottom: 8
    }
  }, holes.map((h, i) => /*#__PURE__*/React.createElement("div", {
    key: i,
    style: {
      display: "flex",
      flexDirection: "column",
      alignItems: "center",
      gap: 2,
      padding: "6px 10px",
      background: dir === "d" ? "#fdf0e8" : "#e8f5ee",
      border: "1.5px solid " + (dir === "d" ? "#f0a070" : "#80c8a0"),
      borderRadius: 6,
      minWidth: 36
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 16,
      fontWeight: 700,
      color: dir === "d" ? "#c85a20" : "#2a7a52"
    }
  }, dir === "d" ? "↓" : "↑"), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 12,
      fontFamily: "monospace",
      fontWeight: 700,
      color: dir === "d" ? "#c85a20" : "#2a7a52"
    }
  }, h))), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      alignItems: "center",
      padding: "6px 12px",
      background: "#f8f5f0",
      border: "1px solid #e0d8cc",
      borderRadius: 6,
      fontSize: 11,
      color: "#8a7f70"
    }
  }, dir === "d" ? "aspirer" : "souffler", " trous ", holes[0], "-", holes[holes.length - 1])));
  const Tip = ({
    emoji,
    title,
    text,
    color = "#c85a20"
  }) => /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 12,
      padding: "12px 14px",
      background: color + "08",
      border: "1px solid " + color + "30",
      borderRadius: 8,
      marginBottom: 10
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 20,
      flexShrink: 0
    }
  }, emoji), /*#__PURE__*/React.createElement("div", null, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13,
      fontWeight: 700,
      color: "#2a2520",
      marginBottom: 3
    }
  }, title), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13,
      color: "#4a4038",
      lineHeight: 1.65
    }
  }, text)));
  return /*#__PURE__*/React.createElement("div", null, /*#__PURE__*/React.createElement("div", {
    style: {
      background: "#fff",
      border: "1px solid #d8d0c0",
      borderRadius: 12,
      padding: "14px 18px",
      marginBottom: 18
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      color: "#c85a20",
      letterSpacing: "0.12em",
      textTransform: "uppercase",
      marginBottom: 6
    }
  }, "Tout ce qu il faut savoir"), /*#__PURE__*/React.createElement("div", {
    style: {
      fontFamily: "Georgia,serif",
      fontSize: 18,
      fontWeight: 700,
      color: "#2a2520",
      marginBottom: 6
    }
  }, "Theorie blues appliquee a l harmonica"), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13,
      color: "#6a6060",
      lineHeight: 1.6
    }
  }, "Les 3 accords, les notes importantes, les positions, et comment improviser. Tout est donne en termes de trous et de souffle — pas de solfege.")), /*#__PURE__*/React.createElement(Section, {
    id: "chords",
    icon: "🎸",
    title: "Les 3 accords du blues",
    color: "#c85a20"
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13,
      color: "#4a4038",
      lineHeight: 1.7,
      marginBottom: 16
    }
  }, "Toute la musique blues (et la majorite du rock) repose sur 3 accords. Sur ton harmonica en Do joue en 2eme position, tu les as naturellement — sans apprendre de doigts, juste en soufflant ou aspirant."), /*#__PURE__*/React.createElement(ChordBox, {
    label: "I",
    holes: [1, 2, 3],
    dir: "d",
    note: "Sol",
    color: "#2a7a52",
    role: "Accord maison — chez toi, stable, resolu"
  }), /*#__PURE__*/React.createElement(ChordBox, {
    label: "IV",
    holes: [1, 2, 3, 4],
    dir: "b",
    note: "Do",
    color: "#4a5fa0",
    role: "Accord du milieu — on s eloigne doucement"
  }), /*#__PURE__*/React.createElement(ChordBox, {
    label: "V",
    holes: [4, 5, 6],
    dir: "d",
    note: "Re",
    color: "#c85a20",
    role: "Accord de tension — envie forte de rentrer"
  }), /*#__PURE__*/React.createElement("div", {
    style: {
      background: "#f8f5f0",
      borderRadius: 8,
      padding: "14px 16px",
      marginTop: 6
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 11,
      fontFamily: "monospace",
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      color: "#8a7f70",
      marginBottom: 10
    }
  }, "Comment les reconnaitre a l oreille"), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "grid",
      gap: 8
    }
  }, [{
    chord: "I",
    emoji: "🏠",
    desc: "Sonne comme arriver a la maison. Stable, pose, resolu. Ton draw chord trous 1-2-3."
  }, {
    chord: "IV",
    emoji: "🚶",
    desc: "Sonne comme s eloigner doucement. Moins stable mais pas tendu. Blow chord — souffler."
  }, {
    chord: "V",
    emoji: "↩️",
    desc: "Sonne comme une forte envie de revenir. Tendu, suspendu. Dans les trous 4-5-6 aspires."
  }].map(r => /*#__PURE__*/React.createElement("div", {
    key: r.chord,
    style: {
      display: "flex",
      gap: 10,
      padding: "10px 12px",
      background: "#fff",
      border: "1px solid #e0d8cc",
      borderRadius: 7
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 20
    }
  }, r.emoji), /*#__PURE__*/React.createElement("div", null, /*#__PURE__*/React.createElement("span", {
    style: {
      fontFamily: "monospace",
      fontWeight: 700,
      color: "#c85a20"
    }
  }, "Accord ", r.chord, " — "), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 13,
      color: "#4a4038"
    }
  }, r.desc)))))), /*#__PURE__*/React.createElement("div", {
    style: {
      marginTop: 14,
      padding: "12px 16px",
      background: "#fdf8f0",
      border: "1px solid #f0d8b0",
      borderRadius: 8,
      fontSize: 13,
      color: "#6a4a20",
      lineHeight: 1.7
    }
  }, /*#__PURE__*/React.createElement("strong", null, "Regle d or :"), " dans un blues 12 mesures, tu entends toujours I (4 fois), IV (2 fois), I (2 fois), V (1 fois), IV (1 fois), I (2 fois). Meme structure depuis 100 ans, dans tous les styles.")), /*#__PURE__*/React.createElement(Section, {
    id: "notes",
    icon: "🎵",
    title: "Les notes importantes",
    color: "#2a7a52"
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13,
      color: "#4a4038",
      lineHeight: 1.7,
      marginBottom: 16
    }
  }, "Tu n as pas besoin de jouer toutes les notes. En blues, 5 notes suffisent — c est la gamme pentatonique. Les grands harmonicistes font des solos entiers avec 2 ou 3 notes bien choisies."), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 11,
      fontFamily: "monospace",
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      color: "#8a7f70",
      marginBottom: 10
    }
  }, "Les 5 notes cles (2eme position, trous 1-4)"), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "grid",
      gap: 8,
      marginBottom: 16
    }
  }, [{
    trou: 2,
    dir: "d",
    note: "Sol",
    role: "Note maison ★★★",
    desc: "La plus importante. Toutes les phrases reviennent ici.",
    color: "#2a7a52"
  }, {
    trou: 3,
    dir: "d",
    note: "Si",
    role: "Note expressive ★★★",
    desc: "3 bends possibles. Le son qui pleure du blues.",
    color: "#7a40a0"
  }, {
    trou: 1,
    dir: "d",
    note: "Re",
    role: "Note grave ★★",
    desc: "Puissante, profonde. Ancre les phrases dans le grave.",
    color: "#c85a20"
  }, {
    trou: 4,
    dir: "d",
    note: "Re",
    role: "Note de passerelle ★★",
    desc: "Meme note que trou 1 mais plus haute. Pont entre registres.",
    color: "#c85a20"
  }, {
    trou: 3,
    dir: "b",
    note: "Sol",
    role: "Note soufflee ★",
    desc: "Meme note que Draw 2. Cree la tension (blue note naturelle).",
    color: "#4a5fa0"
  }].map(n => /*#__PURE__*/React.createElement("div", {
    key: n.trou + n.dir,
    style: {
      display: "flex",
      alignItems: "center",
      gap: 12,
      padding: "10px 14px",
      background: n.color + "08",
      border: "1px solid " + n.color + "30",
      borderRadius: 8
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      flexDirection: "column",
      alignItems: "center",
      padding: "6px 10px",
      background: n.dir === "d" ? "#fdf0e8" : "#e8f5ee",
      border: "1.5px solid " + (n.dir === "d" ? "#f0a070" : "#80c8a0"),
      borderRadius: 6,
      minWidth: 40
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 16,
      fontWeight: 700,
      color: n.dir === "d" ? "#c85a20" : "#2a7a52"
    }
  }, n.dir === "d" ? "↓" : "↑"), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 12,
      fontFamily: "monospace",
      fontWeight: 700,
      color: n.dir === "d" ? "#c85a20" : "#2a7a52"
    }
  }, n.trou)), /*#__PURE__*/React.createElement("div", {
    style: {
      flex: 1
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 12,
      fontWeight: 700,
      color: n.color
    }
  }, n.note, " — ", n.role), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 12,
      color: "#6a6060"
    }
  }, n.desc))))), /*#__PURE__*/React.createElement("div", {
    style: {
      background: "#f0eaf8",
      border: "1px solid #c0a0d8",
      borderRadius: 8,
      padding: "14px 16px",
      fontSize: 13,
      color: "#5a3070",
      lineHeight: 1.7
    }
  }, /*#__PURE__*/React.createElement("strong", null, "Les blue notes :"), " ce sont les notes bendees — surtout Draw 3 (Si abaisse vers Sib, La, Lab). Elles n existent pas dans la gamme normale. Elles sonnent \"fausses et parfaites\" a la fois. C est le son caracteristique du blues.")), /*#__PURE__*/React.createElement(Section, {
    id: "positions",
    icon: "🔄",
    title: "Les positions — reconnaitre et choisir",
    color: "#4a5fa0"
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13,
      color: "#4a4038",
      lineHeight: 1.7,
      marginBottom: 16
    }
  }, "Une position c est juste choisir quelle note est \"chez toi\". Meme harmonica, meme trous — mais un point d atterrissage different."), [{
    num: "1re",
    name: "Straight harp",
    color: "#2a7a52",
    harp: "Do",
    joue: "Do",
    home: "Trou 4 souffler",
    homeNote: "Do",
    accord: "Souffler trous 1-4",
    son: "Melodieux, lumineux, folk",
    genres: "Folk, country, chansons populaires, hymnes",
    reconnaitre: "Les phrases finissent sur trou 4 souffle. Sonne joyeux et equilibre.",
    exemples: "Frere Jacques, Ode a la joie, Oh Susanna, When the Saints",
    astuce: "Tu joues dans la tonalite de l harmonica. Pas de decalage."
  }, {
    num: "2e",
    name: "Cross harp",
    color: "#c85a20",
    harp: "Do",
    joue: "Sol",
    home: "Trou 2 aspirer",
    homeNote: "Sol",
    accord: "Aspirer trous 1-2-3",
    son: "Blues, tension naturelle, expressif",
    genres: "Blues, rock, R&B, country blues",
    reconnaitre: "Les phrases finissent sur les trous aspires 1-2-3. Sonne blues naturellement.",
    exemples: "Mannish Boy, Kansas City, ton riff 5 variations, Riff blues de base",
    astuce: "Le Do souffle cree une tension contre le Sol aspire. Cette friction EST le blues."
  }, {
    num: "3e",
    name: "(pas de surnom)",
    color: "#8a4a98",
    harp: "Do",
    joue: "Re mineur",
    home: "Trou 4 aspirer",
    homeNote: "Re",
    accord: "Aspirer trous 4-5-6",
    son: "Mineur, melancolique, sombre",
    genres: "Blues mineur, soul, gospel mineur",
    reconnaitre: "Sonne mineur et triste. Phrases finissent sur Draw 4.",
    exemples: "Morceaux en mode mineur, certains gospels",
    astuce: "Utilise si le morceau sonne triste ou mineur."
  }].map(pos => /*#__PURE__*/React.createElement("div", {
    key: pos.num,
    style: {
      background: pos.color + "08",
      border: "1.5px solid " + pos.color + "30",
      borderRadius: 10,
      padding: "14px 16px",
      marginBottom: 12
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      alignItems: "center",
      gap: 10,
      marginBottom: 12
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 28,
      fontWeight: 700,
      fontFamily: "Georgia,serif",
      color: pos.color
    }
  }, pos.num), /*#__PURE__*/React.createElement("div", null, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 14,
      fontWeight: 700,
      color: "#2a2520"
    }
  }, pos.name), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 11,
      color: pos.color,
      fontFamily: "monospace"
    }
  }, "Harmonica en ", pos.harp, " → joue en ", pos.joue))), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "grid",
      gridTemplateColumns: "1fr 1fr",
      gap: 8,
      marginBottom: 10
    }
  }, [{
    k: "Note maison",
    v: pos.home + " (" + pos.homeNote + ")"
  }, {
    k: "Accord maison",
    v: pos.accord
  }, {
    k: "Son",
    v: pos.son
  }, {
    k: "Genres",
    v: pos.genres
  }].map(r => /*#__PURE__*/React.createElement("div", {
    key: r.k,
    style: {
      padding: "8px 10px",
      background: "#fff",
      border: "1px solid #e0d8cc",
      borderRadius: 6
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      color: "#8a7f70",
      textTransform: "uppercase",
      letterSpacing: "0.08em",
      marginBottom: 2
    }
  }, r.k), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 12,
      color: "#2a2520",
      fontWeight: 600
    }
  }, r.v)))), /*#__PURE__*/React.createElement("div", {
    style: {
      padding: "10px 12px",
      background: pos.color + "10",
      borderRadius: 7,
      marginBottom: 8
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      color: pos.color,
      textTransform: "uppercase",
      letterSpacing: "0.08em",
      marginBottom: 4
    }
  }, "Comment la reconnaitre"), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13,
      color: "#4a4038"
    }
  }, pos.reconnaitre)), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 12,
      color: "#6a6060",
      fontStyle: "italic"
    }
  }, "Exemples : ", pos.exemples)))), /*#__PURE__*/React.createElement(Section, {
    id: "impro",
    icon: "🎲",
    title: "Cles pour improviser",
    color: "#c8960a"
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13,
      color: "#4a4038",
      lineHeight: 1.7,
      marginBottom: 16
    }
  }, "L improvisation ca parait mysterieux mais c est juste connaitre quelques regles simples et les appliquer en ecoutant ce qui se passe. Voici les outils concrets."), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 11,
      fontFamily: "monospace",
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      color: "#8a7f70",
      marginBottom: 10
    }
  }, "Regle 1 — Suivre les accords"), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "grid",
      gap: 8,
      marginBottom: 16
    }
  }, [{
    chord: "Accord I (draw 1-3)",
    action: "Joue principalement en aspirant. Draw 1, 2, 3, 4. Tu es chez toi.",
    color: "#2a7a52"
  }, {
    chord: "Accord IV (blow 1-4)",
    action: "Glisse vers les notes soufflees. Blow 1, 2, 3, 4. Le Do devient ta nouvelle maison temporaire.",
    color: "#4a5fa0"
  }, {
    chord: "Accord V (draw 4-6)",
    action: "Monte vers les trous 4-5-6 aspires. Cree la tension. Prepare le retour.",
    color: "#c85a20"
  }].map(r => /*#__PURE__*/React.createElement("div", {
    key: r.chord,
    style: {
      padding: "10px 14px",
      background: r.color + "08",
      border: "1px solid " + r.color + "30",
      borderRadius: 8
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 12,
      fontWeight: 700,
      color: r.color,
      marginBottom: 3
    }
  }, r.chord), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13,
      color: "#4a4038"
    }
  }, r.action)))), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 11,
      fontFamily: "monospace",
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      color: "#8a7f70",
      marginBottom: 10
    }
  }, "Regle 2 — La note Draw 2 resout tout"), /*#__PURE__*/React.createElement("div", {
    style: {
      padding: "12px 14px",
      background: "#e8f5ee",
      border: "1px solid #80c8a0",
      borderRadius: 8,
      fontSize: 13,
      color: "#2a5a30",
      lineHeight: 1.7,
      marginBottom: 16
    }
  }, "Peu importe ou tu te perds dans une improvisation — reviens sur Draw 2. Cette note sonne juste sur l accord I, acceptable sur le IV, et cree une belle tension sur le V. C est ton filet de securite."), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 11,
      fontFamily: "monospace",
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      color: "#8a7f70",
      marginBottom: 10
    }
  }, "Regle 3 — Structure tes phrases"), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "grid",
      gap: 8,
      marginBottom: 16
    }
  }, [{
    num: "1",
    title: "Courte et repetee",
    desc: "Joue un lick de 2-3 notes. Repete-le. Varie-le legèrement. Le blues fonctionne par repetition."
  }, {
    num: "2",
    title: "Tension et resolution",
    desc: "Monte vers les aigus (tension), redescends vers Draw 2 (resolution). Ce mouvement EST le blues."
  }, {
    num: "3",
    title: "Le silence compte",
    desc: "Ne pas jouer est aussi musical que jouer. Un silence bien place dit plus qu une cascade de notes."
  }, {
    num: "4",
    title: "Ecoute avant de jouer",
    desc: "Entends mentalement la note avant de la jouer. Ca evite de tâtonner et de sonner perdu."
  }].map(r => /*#__PURE__*/React.createElement("div", {
    key: r.num,
    style: {
      display: "flex",
      gap: 10,
      padding: "10px 14px",
      background: "#fff",
      border: "1px solid #e0d8cc",
      borderRadius: 8
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      width: 24,
      height: 24,
      borderRadius: "50%",
      background: "#fdf8e8",
      border: "1.5px solid #c8960a",
      color: "#c8960a",
      fontFamily: "monospace",
      fontWeight: 700,
      fontSize: 12,
      display: "flex",
      alignItems: "center",
      justifyContent: "center",
      flexShrink: 0,
      marginTop: 1
    }
  }, r.num), /*#__PURE__*/React.createElement("div", null, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13,
      fontWeight: 700,
      color: "#2a2520",
      marginBottom: 2
    }
  }, r.title), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13,
      color: "#4a4038",
      lineHeight: 1.6
    }
  }, r.desc))))), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 11,
      fontFamily: "monospace",
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      color: "#8a7f70",
      marginBottom: 10
    }
  }, "Regle 4 — Licks de depart pour improviser"), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13,
      color: "#4a4038",
      lineHeight: 1.7,
      marginBottom: 10
    }
  }, "Ces 3 mouvements fonctionnent a tout moment dans un blues 12 mesures :"), [{
    label: "Retour maison",
    notes: [{
      h: 4,
      d: "d"
    }, {
      h: 3,
      d: "d"
    }, {
      h: 2,
      d: "d"
    }],
    hint: "Descendre vers Draw 2. Sonne comme une conclusion."
  }, {
    label: "Question blues",
    notes: [{
      h: 2,
      d: "d"
    }, {
      h: 3,
      d: "d"
    }, {
      h: 4,
      d: "d"
    }, {
      h: 3,
      d: "b"
    }],
    hint: "Monter et finir sur Blow 3. Sonne comme une question."
  }, {
    label: "Tension V-I",
    notes: [{
      h: 4,
      d: "d"
    }, {
      h: 3,
      d: "b"
    }, {
      h: 2,
      d: "d"
    }],
    hint: "Draw 4, Blow 3, Draw 2. Tension puis resolution. Classique."
  }].map((t, i) => /*#__PURE__*/React.createElement("div", {
    key: i,
    style: {
      marginBottom: 10
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 11,
      color: "#8a7f70",
      fontFamily: "monospace",
      textTransform: "uppercase",
      letterSpacing: "0.08em",
      marginBottom: 5
    }
  }, t.label), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 4,
      flexWrap: "wrap",
      alignItems: "center",
      padding: "10px 12px",
      background: "#f8f5f0",
      borderRadius: 8,
      border: "1px solid #e0d8cc"
    }
  }, t.notes.map((n, j) => /*#__PURE__*/React.createElement("div", {
    key: j,
    style: {
      display: "flex",
      flexDirection: "column",
      alignItems: "center",
      gap: 2,
      padding: "5px 8px",
      background: n.d === "d" ? "#fdf0e8" : "#e8f5ee",
      border: "1.5px solid " + (n.d === "d" ? "#f0a070" : "#80c8a0"),
      borderRadius: 6,
      minWidth: 30
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 15,
      fontWeight: 700,
      color: n.d === "d" ? "#c85a20" : "#2a7a52"
    }
  }, n.d === "d" ? "↓" : "↑"), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 11,
      fontFamily: "monospace",
      fontWeight: 700,
      color: n.d === "d" ? "#c85a20" : "#2a7a52"
    }
  }, n.h)))), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 11,
      color: "#8a7f70",
      fontStyle: "italic",
      marginTop: 4,
      paddingLeft: 2
    }
  }, t.hint))), /*#__PURE__*/React.createElement("div", {
    style: {
      marginTop: 6,
      padding: "14px 16px",
      background: "#1a1816",
      borderRadius: 10,
      fontSize: 13,
      color: "#e8d8c0",
      lineHeight: 1.75
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 11,
      fontFamily: "monospace",
      color: "#9a9080",
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      marginBottom: 8
    }
  }, "Le secret de l improvisation blues"), "Tu n inventes pas des notes. Tu reponds a ce que tu viens de jouer. Joue un lick → ecoute ce que ca dit → reponds-y. C est une conversation avec toi-meme. Le blues c est ca.")));
}

// ===== ANALYSEUR DE BEND + TECHNIQUES =====
function BendTrainer() {
  const [tab, setTab] = useState("technique");
  return /*#__PURE__*/React.createElement("div", null, /*#__PURE__*/React.createElement("div", {
    style: {
      background: "#fff",
      border: "1px solid #d8d0c0",
      borderRadius: 12,
      padding: "14px 18px",
      marginBottom: 16
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      color: "#7a40a0",
      letterSpacing: "0.12em",
      textTransform: "uppercase",
      marginBottom: 6
    }
  }, "Le bend - la technique cle du blues"), /*#__PURE__*/React.createElement("div", {
    style: {
      fontFamily: "Georgia,serif",
      fontSize: 18,
      fontWeight: 700,
      color: "#2a2520",
      marginBottom: 6
    }
  }, "Apprendre a bender"), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13,
      color: "#6a6060",
      lineHeight: 1.6
    }
  }, "Le bend fait descendre la hauteur d une note. C est ce qui donne le son qui \"pleure\" du blues. Comprends d abord la technique, puis entraine-toi avec le micro.")), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 8,
      marginBottom: 16
    }
  }, [["technique", "📖 La technique"], ["micro", "🎤 Entrainement micro"]].map(([k, l]) => /*#__PURE__*/React.createElement("button", {
    key: k,
    onClick: () => setTab(k),
    style: {
      padding: "8px 16px",
      borderRadius: 20,
      border: "1.5px solid",
      borderColor: tab === k ? "#7a40a0" : "#d8d0c0",
      background: tab === k ? "#f0eaf8" : "#fff",
      color: tab === k ? "#7a40a0" : "#8a7f70",
      cursor: "pointer",
      fontSize: 13,
      fontWeight: tab === k ? 700 : 400
    }
  }, l))), tab === "technique" ? /*#__PURE__*/React.createElement(BendTechnique, null) : /*#__PURE__*/React.createElement(BendMic, null));
}
function BendTechnique() {
  const Block = ({
    icon,
    title,
    color,
    children
  }) => /*#__PURE__*/React.createElement("div", {
    style: {
      border: "1.5px solid " + color + "40",
      borderRadius: 12,
      overflow: "hidden",
      marginBottom: 14
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      alignItems: "center",
      gap: 10,
      padding: "14px 16px",
      background: color + "10"
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 20
    }
  }, icon), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 14,
      fontWeight: 700,
      color: "#2a2520"
    }
  }, title)), /*#__PURE__*/React.createElement("div", {
    style: {
      padding: "16px 18px",
      background: "#fff"
    }
  }, children));
  const Step = ({
    n,
    children
  }) => /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 10,
      fontSize: 13.5,
      color: "#4a4038",
      lineHeight: 1.65,
      marginBottom: 10
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      flexShrink: 0,
      width: 22,
      height: 22,
      borderRadius: "50%",
      background: "#f0eaf8",
      display: "flex",
      alignItems: "center",
      justifyContent: "center",
      fontSize: 11,
      color: "#7a40a0",
      fontFamily: "monospace",
      fontWeight: 700,
      marginTop: 1
    }
  }, n), /*#__PURE__*/React.createElement("span", null, children));
  return /*#__PURE__*/React.createElement("div", null, /*#__PURE__*/React.createElement(Block, {
    icon: "💡",
    title: "Le principe - ce qui se passe vraiment",
    color: "#7a40a0"
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13.5,
      color: "#4a4038",
      lineHeight: 1.7
    }
  }, "Bender n est PAS souffler plus fort. C est changer la forme de l interieur de ta bouche pour \"reaccorder\" l air sur une note plus basse. La languette de l harmonica suit cette nouvelle forme et descend en hauteur. Tout se passe avec la ", /*#__PURE__*/React.createElement("strong", null, "langue"), ", pas avec le souffle.")), /*#__PURE__*/React.createElement(Block, {
    icon: "👄",
    title: "Le K-spot - le declencheur",
    color: "#c85a20"
  }, /*#__PURE__*/React.createElement(Step, {
    n: "1"
  }, "Dis \"kuh-kuh-kuh\" doucement. Sens l endroit ou le milieu de ta langue touche le palais : c est le K-spot."), /*#__PURE__*/React.createElement(Step, {
    n: "2"
  }, "Maintenant chuchote \"eee\" puis \"ooh\" en gardant les levres rondes. Sens ta langue reculer vers l arriere."), /*#__PURE__*/React.createElement(Step, {
    n: "3"
  }, "Ce recul de la langue, c est exactement le geste du bend. \"eee\" = note normale, \"ooh\" = note bendee."), /*#__PURE__*/React.createElement("div", {
    style: {
      marginTop: 10,
      padding: "10px 12px",
      background: "#fdf0e8",
      border: "1px solid #f0c898",
      borderRadius: 8,
      fontSize: 12.5,
      color: "#7a3a10",
      lineHeight: 1.6
    }
  }, "Astuce : plus la cavite de ta bouche est grande (langue reculee), plus la note descend bas.")), /*#__PURE__*/React.createElement(Block, {
    icon: "🎯",
    title: "Par ou commencer",
    color: "#2a7a52"
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 13.5,
      color: "#4a4038",
      lineHeight: 1.7,
      marginBottom: 12
    }
  }, "Commence par le ", /*#__PURE__*/React.createElement("strong", null, "Draw 4"), " (aspirer trou 4). Son bend est le plus petit (1 demi-ton), donc le plus facile a controler. Une fois acquis, passe aux trous 2 et 3."), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "grid",
      gap: 8
    }
  }, [{
    trou: "Draw 4",
    diff: "Facile",
    amp: "1 demi-ton",
    col: "#2a7a52"
  }, {
    trou: "Draw 1",
    diff: "Moyen",
    amp: "1 demi-ton",
    col: "#c8960a"
  }, {
    trou: "Draw 2",
    diff: "Moyen",
    amp: "2 demi-tons",
    col: "#c8960a"
  }, {
    trou: "Draw 3",
    diff: "Difficile",
    amp: "3 demi-tons",
    col: "#c84a6f"
  }].map(r => /*#__PURE__*/React.createElement("div", {
    key: r.trou,
    style: {
      display: "flex",
      alignItems: "center",
      gap: 12,
      padding: "9px 12px",
      background: r.col + "08",
      border: "1px solid " + r.col + "30",
      borderRadius: 8
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontFamily: "monospace",
      fontWeight: 700,
      color: r.col,
      minWidth: 60
    }
  }, r.trou), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 12,
      color: "#6a6060",
      flex: 1
    }
  }, r.diff), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 11,
      fontFamily: "monospace",
      color: "#8a7f70"
    }
  }, r.amp))))), /*#__PURE__*/React.createElement(Block, {
    icon: "📋",
    title: "Les 4 etapes de controle",
    color: "#4a5fa0"
  }, /*#__PURE__*/React.createElement(Step, {
    n: "1"
  }, /*#__PURE__*/React.createElement("strong", null, "Bend et release :"), " note normale → bender → revenir a la normale. Penser \"Eee-Ooh-Eee\"."), /*#__PURE__*/React.createElement(Step, {
    n: "2"
  }, /*#__PURE__*/React.createElement("strong", null, "Bend et stop :"), " bender et maintenir la note baissee sans la relacher."), /*#__PURE__*/React.createElement(Step, {
    n: "3"
  }, /*#__PURE__*/React.createElement("strong", null, "Bend, stop, restart :"), " reprendre le souffle depuis la position baissee, sans bouger la langue."), /*#__PURE__*/React.createElement(Step, {
    n: "4"
  }, /*#__PURE__*/React.createElement("strong", null, "Bend et transition :"), " enchainer le bend vers une autre note. C est le niveau musical.")), /*#__PURE__*/React.createElement(Block, {
    icon: "⚠️",
    title: "Les erreurs a eviter",
    color: "#c84a6f"
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      display: "grid",
      gap: 8
    }
  }, ["Souffler/aspirer plus fort : ca n aide pas et ca abime l harmonica. C est la langue qui travaille.", "Forcer quand ca ne vient pas : si le bend ne sort pas, la langue n est pas au bon endroit. Repositionne, ne force pas.", "Vouloir aller trop vite : le bend prend des jours voire des semaines. C est normal. Patience.", "Negliger le Draw 4 : tout le monde veut le Draw 3, mais le 4 est l ecole. Maitrise-le d abord."].map((t, i) => /*#__PURE__*/React.createElement("div", {
    key: i,
    style: {
      display: "flex",
      gap: 8,
      fontSize: 13,
      color: "#4a4038",
      lineHeight: 1.6
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      color: "#c84a6f",
      flexShrink: 0
    }
  }, "✗"), /*#__PURE__*/React.createElement("span", null, t))))));
}
function BendMic() {
  const [active, setActive] = useState(false);
  const [pitch, setPitch] = useState(null);
  const [note, setNote] = useState(null);
  const [error, setError] = useState("");
  const [target, setTarget] = useState("draw4");
  const ctxRef = useRef(null);
  const analyserRef = useRef(null);
  const rafRef = useRef(null);
  const streamRef = useRef(null);
  const NOTE_FREQS = {
    "C#4": 277.2,
    "D4": 293.7,
    "F4": 349.2,
    "G4": 392.0,
    "G#4": 415.3,
    "B4": 493.9,
    "C#5": 554.4,
    "D5": 587.3
  };
  const TARGETS = {
    draw4: {
      label: "Draw 4 (facile - commence ici)",
      base: "D5",
      bent: "C#5",
      baseN: "Re",
      bentN: "Do#"
    },
    draw2: {
      label: "Draw 2 (LE blues)",
      base: "G4",
      bent: "F4",
      baseN: "Sol",
      bentN: "Fa"
    },
    draw3: {
      label: "Draw 3 (profond)",
      base: "B4",
      bent: "G#4",
      baseN: "Si",
      bentN: "Lab"
    },
    draw1: {
      label: "Draw 1 (grave)",
      base: "D4",
      bent: "C#4",
      baseN: "Re",
      bentN: "Do#"
    }
  };
  const freqToNote = freq => {
    const A4 = 440,
      st = 12 * Math.log2(freq / A4),
      r = Math.round(st);
    const names = ["A", "A#", "B", "C", "C#", "D", "D#", "E", "F", "F#", "G", "G#"];
    const idx = (r % 12 + 12) % 12,
      oct = 4 + Math.floor((r + 9) / 12);
    return names[idx] + oct;
  };
  const detectPitch = (buf, sr) => {
    const N = buf.length;
    let rms = 0;
    for (let i = 0; i < N; i++) rms += buf[i] * buf[i];
    rms = Math.sqrt(rms / N);
    if (rms < 0.01) return -1;
    let r1 = 0,
      r2 = N - 1,
      th = 0.2;
    for (let i = 0; i < N / 2; i++) {
      if (Math.abs(buf[i]) < th) {
        r1 = i;
        break;
      }
    }
    for (let i = 1; i < N / 2; i++) {
      if (Math.abs(buf[N - i]) < th) {
        r2 = N - i;
        break;
      }
    }
    const b = buf.slice(r1, r2),
      n = b.length,
      c = new Array(n).fill(0);
    for (let i = 0; i < n; i++) for (let j = 0; j < n - i; j++) c[i] += b[j] * b[j + i];
    let d = 0;
    while (c[d] > c[d + 1]) d++;
    let mv = -1,
      mp = -1;
    for (let i = d; i < n; i++) {
      if (c[i] > mv) {
        mv = c[i];
        mp = i;
      }
    }
    let T = mp;
    if (T <= 0) return -1;
    const x1 = c[T - 1],
      x2 = c[T],
      x3 = c[T + 1],
      a = (x1 + x3 - 2 * x2) / 2,
      bb = (x3 - x1) / 2;
    if (a) T = T - bb / (2 * a);
    return sr / T;
  };
  const update = () => {
    const an = analyserRef.current;
    if (!an) return;
    const buf = new Float32Array(an.fftSize);
    an.getFloatTimeDomainData(buf);
    const f = detectPitch(buf, ctxRef.current.sampleRate);
    if (f > 60 && f < 2000) {
      setPitch(Math.round(f));
      setNote(freqToNote(f));
    } else {
      setPitch(null);
      setNote(null);
    }
    rafRef.current = requestAnimationFrame(update);
  };
  const start = async () => {
    setError("");
    if (!navigator.mediaDevices || !navigator.mediaDevices.getUserMedia) {
      setError("Ce navigateur ne donne pas acces au micro. Sur un fichier ouvert localement (file://), le micro est bloque par securite. Il faut ouvrir l app via un lien https.");
      return;
    }
    try {
      const stream = await navigator.mediaDevices.getUserMedia({
        audio: {
          echoCancellation: false,
          noiseSuppression: false,
          autoGainControl: false
        }
      });
      streamRef.current = stream;
      const ctx = new (window.AudioContext || window.webkitAudioContext)();
      ctxRef.current = ctx;
      const src = ctx.createMediaStreamSource(stream);
      const an = ctx.createAnalyser();
      an.fftSize = 2048;
      src.connect(an);
      analyserRef.current = an;
      setActive(true);
      update();
    } catch (e) {
      if (e.name === "NotAllowedError") setError("Acces au micro refuse. Autorise le micro dans les reglages du navigateur, puis reessaie.");else if (e.name === "NotFoundError") setError("Aucun micro detecte sur cet appareil.");else setError("Micro bloque. Cause probable : l app est ouverte en fichier local (file://). Le micro n est autorise que sur https. Heberge le fichier sur un lien https (ex: Netlify Drop) pour activer cette fonction.");
    }
  };
  const stop = () => {
    cancelAnimationFrame(rafRef.current);
    if (streamRef.current) streamRef.current.getTracks().forEach(t => t.stop());
    if (ctxRef.current) ctxRef.current.close();
    setActive(false);
    setPitch(null);
    setNote(null);
  };
  useEffect(() => () => stop(), []);
  const tg = TARGETS[target];
  const bf = NOTE_FREQS[tg.base],
    xf = NOTE_FREQS[tg.bent];
  let cursorPct = null;
  if (pitch && bf && xf) {
    cursorPct = Math.max(0, Math.min(100, (bf - pitch) / (bf - xf) * 100));
  }
  let status = "—",
    sc = "#8a7f70";
  if (pitch) {
    const tb = Math.abs(1200 * Math.log2(pitch / bf)),
      tx = Math.abs(1200 * Math.log2(pitch / xf));
    if (tb < 25) {
      status = "Note normale ✓";
      sc = "#2a7a52";
    } else if (tx < 25) {
      status = "BEND ATTEINT ! ✓";
      sc = "#c85a20";
    } else if (pitch < bf && pitch > xf) {
      status = "En train de bender...";
      sc = "#c8960a";
    } else if (pitch < xf) {
      status = "Trop bas";
      sc = "#c84a6f";
    } else {
      status = "Trop haut";
      sc = "#4a5fa0";
    }
  }
  return /*#__PURE__*/React.createElement("div", null, /*#__PURE__*/React.createElement("div", {
    style: {
      padding: "12px 14px",
      background: "#fdf8e8",
      border: "1px solid #f0d8a0",
      borderRadius: 8,
      fontSize: 12,
      color: "#8a6a20",
      lineHeight: 1.6,
      marginBottom: 14
    }
  }, "⚠️ Le micro ne marche que si l app est ouverte via un lien ", /*#__PURE__*/React.createElement("strong", null, "https"), " (pas par double-clic local). Si tu as ouvert le fichier directement, cette fonction sera bloquee par le navigateur."), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "grid",
      gridTemplateColumns: "1fr 1fr",
      gap: 8,
      marginBottom: 16
    }
  }, Object.entries(TARGETS).map(([k, t]) => /*#__PURE__*/React.createElement("button", {
    key: k,
    onClick: () => setTarget(k),
    style: {
      padding: "10px 12px",
      borderRadius: 8,
      cursor: "pointer",
      textAlign: "left",
      border: "1.5px solid " + (target === k ? "#7a40a0" : "#d8d0c0"),
      background: target === k ? "#f0eaf8" : "#fff"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 12,
      fontWeight: 700,
      color: target === k ? "#7a40a0" : "#2a2520"
    }
  }, t.label), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      color: "#8a7f70",
      fontFamily: "monospace"
    }
  }, t.baseN, " → ", t.bentN)))), /*#__PURE__*/React.createElement("div", {
    style: {
      background: "#1a1816",
      borderRadius: 14,
      padding: "20px",
      marginBottom: 16
    }
  }, !active ? /*#__PURE__*/React.createElement("div", {
    style: {
      textAlign: "center"
    }
  }, /*#__PURE__*/React.createElement("button", {
    onClick: start,
    style: {
      padding: "14px 28px",
      borderRadius: 30,
      border: "none",
      background: "#7a40a0",
      color: "#fff",
      fontSize: 15,
      fontWeight: 700,
      cursor: "pointer"
    }
  }, "🎤 Activer le micro"), error && /*#__PURE__*/React.createElement("div", {
    style: {
      color: "#e8a0a0",
      fontSize: 12,
      marginTop: 14,
      lineHeight: 1.6,
      maxWidth: 380,
      marginLeft: "auto",
      marginRight: "auto"
    }
  }, error)) : /*#__PURE__*/React.createElement("div", null, /*#__PURE__*/React.createElement("div", {
    style: {
      textAlign: "center",
      marginBottom: 16
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 42,
      fontWeight: 700,
      fontFamily: "monospace",
      color: "#e8d8c0",
      lineHeight: 1
    }
  }, note || "—"), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 12,
      color: "#8a7a90",
      fontFamily: "monospace",
      marginTop: 4
    }
  }, pitch ? pitch + " Hz" : "joue une note...")), /*#__PURE__*/React.createElement("div", {
    style: {
      position: "relative",
      height: 50,
      background: "#2a2520",
      borderRadius: 8,
      marginBottom: 12,
      overflow: "hidden"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      position: "absolute",
      left: 0,
      top: 0,
      bottom: 0,
      width: "15%",
      background: "#1e3a2a",
      borderRight: "2px solid #2a7a52"
    }
  }), /*#__PURE__*/React.createElement("div", {
    style: {
      position: "absolute",
      right: 0,
      top: 0,
      bottom: 0,
      width: "15%",
      background: "#3a2418",
      borderLeft: "2px solid #c85a20"
    }
  }), /*#__PURE__*/React.createElement("div", {
    style: {
      position: "absolute",
      left: 8,
      top: "50%",
      transform: "translateY(-50%)",
      fontSize: 10,
      color: "#2a7a52",
      fontFamily: "monospace",
      fontWeight: 700
    }
  }, tg.baseN), /*#__PURE__*/React.createElement("div", {
    style: {
      position: "absolute",
      right: 8,
      top: "50%",
      transform: "translateY(-50%)",
      fontSize: 10,
      color: "#c85a20",
      fontFamily: "monospace",
      fontWeight: 700
    }
  }, tg.bentN), cursorPct !== null && /*#__PURE__*/React.createElement("div", {
    style: {
      position: "absolute",
      top: 0,
      bottom: 0,
      left: cursorPct + "%",
      width: 3,
      background: "#fff",
      boxShadow: "0 0 8px #fff",
      transition: "left 0.08s"
    }
  })), /*#__PURE__*/React.createElement("div", {
    style: {
      textAlign: "center",
      padding: "10px",
      borderRadius: 8,
      background: sc + "22",
      border: "1px solid " + sc,
      fontSize: 14,
      fontWeight: 700,
      color: sc,
      marginBottom: 12
    }
  }, status), /*#__PURE__*/React.createElement("button", {
    onClick: stop,
    style: {
      width: "100%",
      padding: "10px",
      borderRadius: 8,
      border: "1px solid #6a2a18",
      background: "#3a1a10",
      color: "#c86a50",
      fontSize: 13,
      fontWeight: 700,
      cursor: "pointer"
    }
  }, "⏹ Arreter"))), /*#__PURE__*/React.createElement("div", {
    style: {
      background: "#f0eaf8",
      border: "1px solid #c0a0d8",
      borderRadius: 10,
      padding: "14px 16px"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 11,
      fontFamily: "monospace",
      textTransform: "uppercase",
      letterSpacing: "0.1em",
      color: "#7a40a0",
      marginBottom: 8
    }
  }, "Comment s en servir"), ["Choisis un trou (commence par Draw 4).", "Active le micro, joue la note NORMALE - curseur a gauche (vert).", "Bende doucement avec le K-spot - le curseur glisse vers la droite.", "Objectif : amener le curseur dans la zone orange (bend atteint)."].map((s, i) => /*#__PURE__*/React.createElement("div", {
    key: i,
    style: {
      display: "flex",
      gap: 9,
      fontSize: 13,
      color: "#4a4038",
      lineHeight: 1.6,
      marginBottom: 6
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      flexShrink: 0,
      width: 20,
      height: 20,
      borderRadius: "50%",
      background: "#e0d0ec",
      display: "flex",
      alignItems: "center",
      justifyContent: "center",
      fontSize: 10,
      color: "#7a40a0",
      fontFamily: "monospace",
      fontWeight: 700,
      marginTop: 1
    }
  }, i + 1), /*#__PURE__*/React.createElement("span", null, s)))));
}

function FileSync(props) {
  const supportsFS = props.supportsFS, fileLinked = props.fileLinked, progress = props.progress, onRestore = props.onRestore;
  const inputRef = useRef(null);
  const downloadFile = () => {
    const blob = new Blob([JSON.stringify(progress)], {type:"application/json"});
    const url = URL.createObjectURL(blob);
    const a = document.createElement("a");
    a.href = url; a.download = "harmonica-progression.json";
    document.body.appendChild(a); a.click(); document.body.removeChild(a);
    URL.revokeObjectURL(url);
  };
  const uploadFile = (e) => {
    const file = e.target.files[0]; if(!file) return;
    const reader = new FileReader();
    reader.onload = (ev) => { try { onRestore(JSON.parse(ev.target.result)); } catch(err){ alert("Fichier invalide : "+err.message); } };
    reader.readAsText(file); e.target.value = "";
  };
  if(!supportsFS) return React.createElement("div", {style:{marginTop:10,padding:"12px 14px",background:"#eeeef8",border:"1px solid #c8d0e8",borderRadius:8}},
    React.createElement("div", {style:{fontSize:11,color:"#4a5fa0",marginBottom:8,lineHeight:1.5}}, "Sauvegarde fichier (Firefox) - telecharge vers ton dossier sync, recharge au retour :"),
    React.createElement("div", {style:{display:"flex",gap:8,flexWrap:"wrap"}},
      React.createElement("button", {onClick:downloadFile, style:{fontSize:11,fontFamily:"monospace",padding:"5px 12px",borderRadius:20,border:"1px solid #2a7a52",background:"#e8f5ee",color:"#2a7a52",cursor:"pointer"}}, "\u2b07\ufe0f Telecharger"),
      React.createElement("button", {onClick:()=>inputRef.current.click(), style:{fontSize:11,fontFamily:"monospace",padding:"5px 12px",borderRadius:20,border:"1px solid #4a5fa0",background:"#eeeef8",color:"#4a5fa0",cursor:"pointer"}}, "\u2b06\ufe0f Charger"),
      React.createElement("input", {ref:inputRef, type:"file", accept:".json,application/json", onChange:uploadFile, style:{display:"none"}})
    ),
    React.createElement("div", {style:{fontSize:10,color:"#8a7f70",marginTop:8,fontStyle:"italic",lineHeight:1.5}}, "Garde le meme nom de fichier dans ton dossier sync.")
  );
  return React.createElement("div", {style:{marginTop:10,padding:"10px 12px",background:fileLinked?"#e8f5ee":"#eeeef8",border:"1px solid "+(fileLinked?"#80c8a0":"#c8d0e8"),borderRadius:8}},
    fileLinked
      ? React.createElement("div", {style:{fontSize:11,color:"#2a7a52",fontFamily:"monospace",display:"flex",alignItems:"center",gap:6}}, React.createElement("span",null,"\ud83d\udd17 Fichier lie - sauvegarde auto"))
      : React.createElement("div", null,
          React.createElement("div", {style:{fontSize:11,color:"#4a5fa0",marginBottom:8,lineHeight:1.5}}, "Lier un fichier de sauvegarde (dossier sync), sauvegarde auto ensuite :"),
          React.createElement("div", {style:{display:"flex",gap:8,flexWrap:"wrap"}},
            React.createElement("button", {onClick:props.onLink, style:{fontSize:11,fontFamily:"monospace",padding:"5px 12px",borderRadius:20,border:"1px solid #4a5fa0",background:"#eeeef8",color:"#4a5fa0",cursor:"pointer"}}, "\ud83d\udcc2 Ouvrir un fichier"),
            React.createElement("button", {onClick:props.onCreate, style:{fontSize:11,fontFamily:"monospace",padding:"5px 12px",borderRadius:20,border:"1px solid #2a7a52",background:"#e8f5ee",color:"#2a7a52",cursor:"pointer"}}, "\u2795 Creer un fichier")
          )
        )
  );
}

function App() {
  const [progress, setProgress] = useState({});
  const [loaded, setLoaded] = useState(false);
  const [saving, setSaving] = useState(false);
  const [tab, setTab] = useState("exercices");
  const [fileLinked, setFileLinked] = useState(false);
  const fileHandleRef = useRef(null);
  const supportsFS = typeof window !== "undefined" && "showOpenFilePicker" in window;
  useEffect(() => {
    (async () => {
      try {
        const raw = localStorage.getItem(STORAGE_KEY); const r = raw ? {value:raw} : null;
        if (r?.value) setProgress(JSON.parse(r.value));
      } catch (_) {}
      setLoaded(true);
    })();
  }, []);
  const save = useCallback(async next => {
    setSaving(true);
    try {
      localStorage.setItem(STORAGE_KEY, JSON.stringify(next)); if(fileHandleRef.current){ try{ const w=await fileHandleRef.current.createWritable(); await w.write(JSON.stringify(next)); await w.close(); }catch(_){} }
    } catch (_) {}
    setTimeout(() => setSaving(false), 600);
  }, []);
  const handleStatus = useCallback((id, lv) => {
    setProgress(prev => {
      const cur = prev[id]?.status ?? 0;
      const next = {
        ...prev,
        [id]: {
          ...(prev[id] ?? {}),
          status: lv !== undefined ? lv : (cur + 1) % STATUS.length
        }
      };
      save(next);
      return next;
    });
  }, [save]);
  const handleNote = useCallback((id, note) => {
    setProgress(prev => {
      const next = {
        ...prev,
        [id]: {
          ...(prev[id] ?? {}),
          note
        }
      };
      save(next);
      return next;
    });
  }, [save]);
  const handleRestore = useCallback(data => {
    setProgress(data);
    save(data);
  }, [save]);
  const linkExistingFile = useCallback(async () => {
    try {
      const [h] = await window.showOpenFilePicker({types:[{description:"Sauvegarde",accept:{"application/json":[".json"]}}]});
      const file = await h.getFile(); const text = await file.text();
      if(text.trim()){ const data = JSON.parse(text); setProgress(data); localStorage.setItem(STORAGE_KEY, JSON.stringify(data)); }
      fileHandleRef.current = h; setFileLinked(true);
    } catch(e){ if(e.name!=="AbortError") alert("Erreur : "+e.message); }
  }, []);
  const createNewFile = useCallback(async () => {
    try {
      const h = await window.showSaveFilePicker({suggestedName:"harmonica-progression.json",types:[{description:"Sauvegarde",accept:{"application/json":[".json"]}}]});
      const w = await h.createWritable(); await w.write(JSON.stringify(progress)); await w.close();
      fileHandleRef.current = h; setFileLinked(true);
    } catch(e){ if(e.name!=="AbortError") alert("Erreur : "+e.message); }
  }, [progress]);
  const wSum = allExoIds.reduce((s, id) => s + (progress[id]?.status ?? 0), 0);
  const mastered = allExoIds.filter(id => (progress[id]?.status ?? 0) === 4).length;
  const inProg = allExoIds.filter(id => {
    const s = progress[id]?.status ?? 0;
    return s >= 1 && s <= 3;
  }).length;
  const pct = Math.round(wSum / (totalExos * 4) * 100);
  if (!loaded) return /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      alignItems: "center",
      justifyContent: "center",
      height: "100vh",
      background: "#f5f0e8",
      color: "#8a7f70",
      fontFamily: "monospace"
    }
  }, "Chargement...");
  return /*#__PURE__*/React.createElement("div", {
    style: {
      background: "#f5f0e8",
      minHeight: "100vh",
      fontFamily: "system-ui,sans-serif"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      background: "#fff",
      borderBottom: "2px solid #d8d0c0",
      padding: "22px 22px 16px",
      maxWidth: 720,
      margin: "0 auto"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      letterSpacing: "0.15em",
      color: "#c85a20",
      textTransform: "uppercase",
      marginBottom: 7
    }
  }, "Harmonica - Suivi de progression"), /*#__PURE__*/React.createElement("div", {
    style: {
      fontFamily: "Georgia,serif",
      fontSize: 24,
      fontWeight: 700,
      color: "#2a2520",
      marginBottom: 12
    }
  }, "Mon carnet d'exercices"), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "grid",
      gridTemplateColumns: "1fr 1fr 1fr",
      gap: 8,
      marginBottom: 12
    }
  }, [{
    label: "Maitrisés",
    value: mastered,
    color: "#2a7a52",
    bg: "#e8f5ee"
  }, {
    label: "En cours",
    value: inProg,
    color: "#c85a20",
    bg: "#fdf0e8"
  }, {
    label: "Total",
    value: totalExos,
    color: "#4a5fa0",
    bg: "#eeeef8"
  }].map(s => /*#__PURE__*/React.createElement("div", {
    key: s.label,
    style: {
      background: s.bg,
      borderRadius: 8,
      padding: "9px 10px",
      textAlign: "center"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 20,
      fontWeight: 700,
      color: s.color,
      fontFamily: "Georgia,serif"
    }
  }, s.value), /*#__PURE__*/React.createElement("div", {
    style: {
      fontSize: 10,
      color: s.color,
      fontFamily: "monospace"
    }
  }, s.label)))), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      alignItems: "center",
      gap: 10,
      marginBottom: 14
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      flex: 1,
      height: 6,
      background: "#e0d8cc",
      borderRadius: 3,
      overflow: "hidden"
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      width: pct + "%",
      height: "100%",
      background: "#2a7a52",
      borderRadius: 3,
      transition: "width 0.5s"
    }
  })), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 12,
      fontFamily: "monospace",
      color: "#2a7a52",
      fontWeight: 700,
      minWidth: 36
    }
  }, pct, "%"), saving && /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 10,
      color: "#8a7f70",
      fontFamily: "monospace"
    }
  }, "💾")), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 6,
      flexWrap: "wrap"
    }
  }, [["exercices", "🎵 Exercices"], ["morceaux", "🎸 Morceaux"], ["blues", "🎶 Blues"], ["bend", "🎯 Bends"], ["lexique", "📖 Lexique"]].map(([k, l]) => /*#__PURE__*/React.createElement("button", {
    key: k,
    onClick: () => setTab(k),
    style: {
      padding: "7px 14px",
      borderRadius: 20,
      border: "1.5px solid",
      borderColor: tab === k ? "#c85a20" : "#d8d0c0",
      background: tab === k ? "#fdf0e8" : "#fff",
      color: tab === k ? "#c85a20" : "#8a7f70",
      cursor: "pointer",
      fontSize: 12,
      fontWeight: tab === k ? 700 : 400
    }
  }, l))), /*#__PURE__*/React.createElement(SaveRestore, {
    progress: progress,
    onRestore: handleRestore
  }), /*#__PURE__*/React.createElement(FileSync, {
    supportsFS: supportsFS,
    fileLinked: fileLinked,
    onLink: linkExistingFile,
    onCreate: createNewFile,
    progress: progress,
    onRestore: handleRestore
  })), /*#__PURE__*/React.createElement("div", {
    style: {
      maxWidth: 720,
      margin: "0 auto",
      padding: "18px 22px 60px"
    }
  }, tab === "lexique" ? /*#__PURE__*/React.createElement(LexiqueView, null) : tab === "bend" ? /*#__PURE__*/React.createElement(BendTrainer, null) : tab === "blues" ? /*#__PURE__*/React.createElement(BluesView, null) : tab === "morceaux" ? /*#__PURE__*/React.createElement(SongsView, {
    progress: progress,
    onStatusChange: handleStatus,
    onNoteChange: handleNote
  }) : /*#__PURE__*/React.createElement(React.Fragment, null, /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 8,
      flexWrap: "wrap",
      marginBottom: 16,
      padding: "12px 14px",
      background: "#fff",
      borderRadius: 10,
      border: "1px solid #d8d0c0"
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 10,
      fontFamily: "monospace",
      color: "#8a7f70",
      alignSelf: "center",
      marginRight: 4
    }
  }, "PHASES :"), [{
    color: "#2a7a52",
    label: "Fondations"
  }, {
    color: "#c85a20",
    label: "Expression et Bends"
  }, {
    color: "#4a5fa0",
    label: "Tongue Block"
  }, {
    color: "#8a4a98",
    label: "Positions"
  }, {
    color: "#c8960a",
    label: "Technique avancee"
  }].map(g => /*#__PURE__*/React.createElement("div", {
    key: g.label,
    style: {
      display: "flex",
      alignItems: "center",
      gap: 5,
      fontSize: 11
    }
  }, /*#__PURE__*/React.createElement("div", {
    style: {
      width: 10,
      height: 10,
      borderRadius: "50%",
      background: g.color,
      flexShrink: 0
    }
  }), /*#__PURE__*/React.createElement("span", {
    style: {
      color: g.color,
      fontWeight: 600
    }
  }, g.label)))), PHASES.map(phase => /*#__PURE__*/React.createElement(PhaseBlock, {
    key: phase.id,
    phase: phase,
    progress: progress,
    onStatusChange: handleStatus,
    onNoteChange: handleNote
  })), /*#__PURE__*/React.createElement("div", {
    style: {
      display: "flex",
      gap: 12,
      justifyContent: "center",
      flexWrap: "wrap",
      padding: "14px",
      background: "#fff",
      borderRadius: 12,
      border: "1px solid #d8d0c0"
    }
  }, STATUS.map(s => /*#__PURE__*/React.createElement("div", {
    key: s.label,
    style: {
      display: "flex",
      alignItems: "center",
      gap: 5,
      fontSize: 12,
      color: s.color
    }
  }, /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 14
    }
  }, s.emoji), s.label)), /*#__PURE__*/React.createElement("span", {
    style: {
      fontSize: 10,
      color: "#b0a090",
      fontFamily: "monospace"
    }
  }, "cliquer pour changer")))));
}
    var root = ReactDOM.createRoot(document.getElementById("root"));
    root.render(React.createElement(App, null));
  } catch(e) {
    document.getElementById("root").innerHTML =
      '<div class="loading"><div>Erreur au demarrage</div><div class="err">' + e.message + '</div></div>';
    console.error(e);
  }
}
function boot(tries){
  if(typeof React !== "undefined" && typeof ReactDOM !== "undefined"){ startApp(); }
  else if(tries > 0){ setTimeout(function(){ boot(tries-1); }, 100); }
  else { loadFallback(startApp); }
}
boot(30);
</script>
</body>
</html>
