﻿
\### Indice 10 : recherche ###

\#### `grep` ####

Chercher à l'intérieur de fichiers est aussi utile. Essayer

grep secret README.md

Cela affichera toutes les lignes qui contiennent le mot "secret". `grep` est

l'acronyme de "GNU Regular Expression Parsing". GNU est une communauté qui

publie des logiciels libres (dont la source est publique) et gratuits. Une

expression régulière est un motif de texte. Dans ce cas, notre expression

régulière est uniquement "secret", et `grep` trouvera uniquement les

correspondances exactes. Les expressions régulières peuvent être plus

compliquées. Par exemple,

grep m.n README.md

trouvera toutes les lignes qui contiennent les lettres m et n séparées

uniquement d'un seul caractère. Consultez la page de manuel pour découvrir de

nombreuses fonctionnalités intéressantes de `grep`.

\#### Trouver l'indice 11 ####

L'indication suivante est le mot qui apparaît avant "baobab" dans

`/usr/share/dict/words`. Il existe une option spécifique de `grep` qui rend

cette recherche facile.
