# Réponses aux questions posées le 2019-10-09, le 2020-02-07

## Comparatif Mendeley/Zotero

Un tableau comparatif synthétique a été établi par les bibliothécaires de l'EPFL, il est disponible à l'adresse suivante : https://fbib.gitbooks.io/up-to-speed-with-zotero/content/02-comparing-refman/

Le billet [Pourquoi Zotero?](https://zotero.hypotheses.org/1998) sur le blog Zotero francophone donne quelques exemples des limitations de Mendeley.

## Rechercher dans sa bibliothèque Zotero : rechercher un champ vide

La syntaxe correcte pour créer une recherche affichant tous les documents pour lesquels le champ résumé est vide est la suivante :

```
Rechercher > Résumé > ne contient pas > %

```

Une copie d'écran est fournie dans le billet [Un été avec Zotero](https://zotero.hypotheses.org/1840) sur le blog Zotero francophone.

## Quel est le meilleur choix de navigateur?

La discussion [Zotero connectors differences?](https://forums.zotero.org/discussion/comment/289139) sur le forum Zotero ne donne pas un avantage à Chrome ni à Firefox, les fonctionnalités sont équivalentes.

**_Mise à jour 2020-02_**

Si un nouveau connecteur Zotero a été développé pour Safari 13, les limitations existantes persistent, à savoir l’**absence de détection automatique des proxies** et l’**absence d’import automatique RIS/BibTeX/CSL**. La configuration manuelle des proxies n’est pour l’instant pas disponible, mais devrait l’être à nouveau prochainement.
La page de la documentation Zotero [Connecteur Zotero et Safari 13](https://www.zotero.org/support/kb/safari_compatibility) fournit tous les détails nécessaires pour les utilisateurs de Safari.

## Visualiser dans sa bibliothèque Zotero les documents cités dans un fichier Word

Le module complémentaire [Reference extractor](http://rintze.zelle.me/ref-extractor/) devrait permettre de faire cela. Je ne l'ai pas testé.

## Dans Word, pourquoi certains caractères sont-ils remplacés par des carrés?

Cette anomalie a fait l'objet d'une discussion sur le forum Zotero : [Tirets remplacés par des carrés dans la bibliographie](https://forums.zotero.org/discussion/comment/161506/).

Créer une bibliographie en html permet de s'assurer que l'anomalie ne vient pas de Zotero mais de Word, plus précisément de l'encodage des caractères, parfois lié à l'usage de certaines polices de caractères, ainsi que le rapporte l'un des contributeurs à la discussion.

> Des carrés sont restés au lieu des espaces dans un document (en Arial), tandis que les carrés sont restés au lieu des traits d'union dans l'autre (en Verdana). Dans le document où les traits d'union sont tous réapparus, certains étaient dans la même police que le reste du texte (Arial), certains étaient dans une autre police (MS Gothic).

La discussion fournit entre autres recommandations des liens vers 2 listes utiles si l'anomalie provient de la police de caractères.
* [Liste de certaines polices compatibles avec le trait d'union insécable](http://www.fileformat.info/info/unicode/char/2011/fontsupport.htm)
* [Liste de certaines polices compatibles avec l'espace fine insécable](http://www.fileformat.info/info/unicode/char/202f/fontsupport.htm) 
