Możesz użyć bloku `połącz`{:class="block3operators"} z bloku `Wyrażenia`{:class="block3operators"}, aby połączyć tekst i zmienne w celu utworzenia dłuższych wyrażeń.

Przeciągnij blok `Połącz`{:class="block3operators"} do innego bloku, w którym chcesz go użyć:

```blocks3
say (join [apple ] [banana]) for [2] seconds
```

Zastąp przykładowy tekst wyrażeniem, którego chcesz użyć, lub przeciągnij i dodaj zmienną:

```blocks3
set [imię v] to [Scratch]
say (join [Cześć, jestem ] (imię)) for [2] seconds
```

**Wskazówka:** Blok `połącz`{:class="block3operators"} nie dodaje spacji, więc będziesz musiał je wpisać.

Możesz przeciągnąć blok `połącz`{:class="block3operators"} do innego bloku `połącz`{:class="block3operators"}, aby tworzyć dłuższe ciągi tekstowe:

```blocks3
say (join [Cześć, jestem ] (join [kot ] (imię))) for [2] seconds
```

Zwróć uwagę na „spację” na końcu `Cześć, jestem` i `kot`.



