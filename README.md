# Skill-and-You-se-perfectionner-en-HTML-CSS-2

Atelier : mettre en forme une page avec les conteneurs de texte

Ce projet est un exercice pratique de mise en forme web axé sur la structuration du texte et l'utilisation avancée des conteneurs HTML et des propriétés CSS modernes (notamment le système de colonnes). La page rend hommage à Léonard de Vinci, présent dans une mise en page sous forme d'article dynamique.

🔍 Aperçu du projet :
La page présente :
Une Introduction définissant le polymathe italien.
Une section Biographie organisée en 3 colonnes.
Une section Œuvres présentant ses pièces majeures (La Cène, La Joconde, La Vierge aux rochers, L'Homme de Vitruve) sur 4 colonnes.

🏷️ Notions et balises HTML abordées :
Cet atelier met en avant l'usage de balises sémantiques précises :
<time datetime="..."> : pour structurer les dates d'événements historiques.
<dfn> : pour marquer la définition d'un terme principal.
<address> : pour indiquer les lieux et institutions (ex: Musée du Louvre, Santa Maria delle Grazie).
<cite> : pour titrer les œuvres d'art présentées.

🎨 Techniques CSS utilisées :
Multi-columns CSS :
column-count : divise le texte en plusieurs colonnes fluides (3 pour la biographie, 4 pour les œuvres).
column-gap et column-rule : gèrent l'espacement et les séparateurs verticaux entre colonnes.
column-span: all : permet aux titres <h2> de s'étendre sur la largeur totale du bloc sans être coupés par les colonnes.
Typographie et styles : ombrages de texte (text-shadow), espacement des lettres (letter-spacing) et bordures composées (border: double).

📁 Structure des fichiers :
.
├── index_2.html     # Document principal contenant la structure HTML et les styles de l'atelier
└── style.css        # Feuille de style externe (optionnelle)
