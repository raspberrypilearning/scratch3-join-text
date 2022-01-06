Tu peux utiliser le bloc `regrouper`{:class="block3operators"} du bloc `Operateurs`{:class="block3operators"} pour regrouper du texte et des variables afin de créer des chaînes plus longues.

Fais glisser un bloc `regrouper`{:class="block3operators"} dans le bloc où tu souhaites l'utiliser :

```blocks3
say (join [apple ] [banana]) for [2] seconds
```

Remplace le texte par le texte que tu souhaites utiliser ou fais glisser une variable :

```blocks3
set [name v] to [Scratch]
say (join [Hi, I'm ] (name)) for [2] seconds
```

**Astuce :** Le bloc `regrouper`{:class="block3operators"} n'ajoute pas d'espaces, tu devras donc les saisir.

Tu peux faire glisser un bloc `regrouper`{:class="block3operators"} dans un autre `regrouper`{:class="block3operators"} pour créer des chaînes de texte plus longues :

```blocks3
say (join [Hi, I'm ] (join (name) [ the cat])) for [2] seconds
```

Remarque l'espace à la fin de `Salut, je suis` et au début `du chat`.



