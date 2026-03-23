
## Objectif du projet tp1(35%)
Bonjour, aujourd'hui je vais vous d'ecrire mon expérience durant le projet 1 du cours de web 2.Pour commencer, le projet avait pour but de reproduire une maquette fillaire recu depuis figma
et reproduire la même chose sur vscode toute en changant certaines choses comme les designs tokens,couleurs. J'ai commencé le 5 mars 2026.


## Sources
MDN
W3schools
Google
Nekocalc
Chatgpt


### Nomenclature
j'ai choisis de pendre le systeme de méthode BEM (Block, Element et Modifier) parce-qu'elle était obligatoire, mais sinon elle facilite l'organisation du code. Je vais vous donner un exemple pour que vous compreniez.

Dans mon projet, il y avait dans le header le nav:

Navbar
navbar__brand
navbar__links
navbar__cta
btn btn--primary


Le navbar représente le composant principale. Sans lui, le reste n'existent pas.
navbar__brand,navbar__links et navbar__cta sont des elements comme le __ l'indique. Elle montre qu'ils sont enfants de celui-ci.Puis, nous avons le Modifier  btn btn--primary qui est une variante . Elle permet de changer le style du bouton.

### Design tokens
Pour commencer, mes variables sont les suivants:


 Les couleurs:
--color-primary: #2f5d3a;
  --color-secondary: #8bc34a;
  --color-background: #F5F5DC;
  --color-text: #333;
  --color-white: #ffffff;

Les palettes me servent à ne pas mettre d'autres couleurs inutiles.Puisque, le site est en partie dans le monochrome vert, elle me facilite a juste recopier plus simplement.


  /* l'espacement */
  --space-xs: 0.25rem;
  --space-sm: 0.5rem;
  --space-md: 1rem;
  --space-md-lg: 1.5rem;
  --space-lg: 2rem;
  --space-xl: 4rem;

 Utilisées pour remplacer tout ce qui est padding,gap,etc


  /* typo */
  --font-size-sm: 0.8rem;
  --font-size-base: 1rem;
  --font-size-lg: 1.5rem;
  --font-size-xl: 2rem;
  --font-size-xxl: 3rem;

Permet de changer la typo pour rester visuellement cohérent.



## composants réutilisables CSS 
Dans mon projet, les composants réutilisables que j'ai utilisé se résume à
-btn  
-btn--primary

 Utilisé dans navbar,contact et footer. Ce sont les seuls boutons utilisés dans le projet.

services__card
testimonials__card
about__block
activities__card

Elles sont été utilisés pour faire les cartes. Cela ma simplifier la tache, car dans le code elle se repettent plus de 3 fois.

 
.contact__group
.contact__name
.contact__box

Dans la section contact, Elle se repette 3 fois pour permettre a l'utilisateur de rentrer ce qu'il veut dedans.
                                                            
 

 ## Flexbox 
 J'ai utilisé flexbox  pour permettre de bien organiser et de rendre tout vraiment simple. Pour illustrer un exemple, dans le navbar, jai utilisé flexbox pour permettre d'avoir tous les éléments (liens,logo,titre,bouton) sur une ligne. Dans hero,elle est utilisé pour mettre les titres à gauche et mettre l'image à droite. Pour testimonials et services, flexbox me sert à alligner  les cartes et gap me sert a mettre de l'espace entre eux. Pour finir, activities jai mis flex-direction: column pour permettre de voir la liste à droite et en dessous de chacun.

 ## Focntuoc CSS fluides (clmap/calc)
 Pour commencer, Jai utilisé clamp pour tout ce qui est titre, car le titre est le plus important. Cette fonction sert à mettre une valeur définit. Elle possède une valeur minimale, valeur ideal et une valeur maximale. En gros, il s'adapte à l'écran. je n'ai pas utilisé calc, car je l'avais oublié.


 ## Définie rencontrés

 Alors pour commencer, j'ai pris beaucoup plus de temps à le faire. J'avais bloqué à l'html parce que j'avais completement oublié comment fonctionne le bem. Ensuite, je suis passer à le Css et c'est la que tous les problèmes du monde sont arrivés. Pour commencer, j'avais rater les cours de clamps et flexbox, donc jai du regarder des videos et utiliser pleins de site comme mdn,w3schools,etc. Ensuite, j'avais ensuite des problemes de code html, car je n'avais pas bien fermer les divs ainsi que les positions des classes. Par exemple: j'avais mis une image en fin de section, mais l'image était le background, donc il fallait le mettre au début. Même chose pour les titres comme dans témoignages et à propos. Je n'ai pas réussis à trouver toutes les solutions, mais pour la plupart que j'ai faite son réusis. Le titre planeteb je n'avais aucune idée de le faire. Bref, si j'avais commencé et pris mon temps pour le faire, j'aurais eu un meilleur résultat. Je suis un peu déçu. 

 ### Utilisation de l’IA

Outil utilisé : ChatGPT
Version : GPT-5.3
Date d'utilisation  Mars 2026



J'ai utilisé de l'ai pour m'aider à comprendre quelques concept que j'avais oublié comme le bem,clamp,flexbox etc. Elle ma aussi aidé corriger quelques fautes et comprendre ce que je devais écrire dans la documentation. La plupart du temps l'AI ne m'aidait pas tant que cela et je n'ai pas utilisé l'AI de vscode. J'ai plus demandé de l'aide à l'exterieur et au note de cours. J'ai aussi mentionné de ne pas me dire les réponses et de me laisser réflechir.

-   Est-ce que je respect la nomclature du bem?
-   Comment je peux ameliorer mon code(html)
-   Est-ce que j'ai le droit d'écrire en francais dans la nomenclature bem?
-   Mon image ne veut pas etre dans le background
-   Explique moi en quelques phrases le flexbox
-   Regarde si j'ai fais des fautes d'orthographe important



