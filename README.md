Redécouvrir JavaScript avec Node.js
===================================

Sur ce repository vous trouverez les sources de la dernière version de mon livre _Redécouvrir JavaScript avec Node.js_.

## Licence

Le livre est diffusé sous licence **Creative Commons**, ce qui signifie que vous êtes libre de le partager et de l'adapter, sous certains conditions dont les détails sont visibles ici : http://creativecommons.org/licenses/by-nc-sa/4.0/deed.fr

## Téléchargement

Le livre est lisible en ligne aux formats [HTML](http://scastiel.github.io/decouvrir-nodejs/redecouvrir-javascript-avec-nodejs.html) et [PDF](http://scastiel.github.io/decouvrir-nodejs/redecouvrir-javascript-avec-nodejs.pdf). Vous pouvez également télécharger le fichier [ePub](http://scastiel.github.io/decouvrir-nodejs/redecouvrir-javascript-avec-nodejs.epub), qui pourra être importé sur la plupart des liseuses ou converti si nécessaire via l'utilitaire [Calibre](http://calibre-ebook.com/) par exemple.

## Exemples

J'ai commencé à fournir sur ce dépôt les codes sources des exemples du livre. Pour les exécuter, la procédure est normalement toujours la même ; il suffit d'installer les dépendances de manière classique grace à `npm install`, par exemple :

```sh
$ cd exemples/03-express/32-application-basique
$ npm install
$ node index.js
```

## Construction du livre en HTML, ePub et PDF

Les sources du livre sont au format Markdown ; le livre peut être généré aux formats HTML (page web) et ePub (livre électronique). Pour cela vous aurez besoin du programme [Pandoc](http://johnmacfarlane.net/pandoc/) et de l'utilitaire *make*. Afin de générer le PDF, il vous faudra également disposer du programme _pdflatex_, disponible dans les distributions [LaTeX](http://latex-project.org/ftp.html).

 * Pour générer le HTML : `make html`
 * Pour générer le ePub : `make epub`
 * Pour générer le PDF : `make pdf`

Les fichiers sont générés dans le répertoire _dist_.
