Je kunt het `voeg ... en ... samen`{:class="block3operators"} blok uit `Functies`{:class="block3operators"} gebruiken om tekst en variabelen samen te voegen om langere strings te maken.

Sleep een `voeg ... en ... samen`{:class="block3operators"} blok in het blok waar je het wilt gebruiken:

```blocks3
say (join [apple ] [banana]) for [2] seconds
```

Vervang de tekst door de tekst die je wilt gebruiken, of sleep er een variabele in:

```blocks3
set [naam v] to [Scratch]
say (join [Hoi, ik ben ] (naam)) for [2] seconds
```

**Tip:** Het `voeg ... en ... samen`{:class="block3operators"} blok voegt geen spaties toe, dus je moet ze zelf typen.

Je kunt een `voeg ... en ... samen`{:class="block3operators"} blok in een ander `voeg ... en ... samen`{:class="block3operators"} blok slepen om nog langere strings te maken:

```blocks3
say (join [Hoi, ik ben ] (join (naam) [ de kat])) for [2] seconds
```

Let op de 'spatie' aan het einde van `Hallo, ik ben` en voor het begin van `de kat`.



