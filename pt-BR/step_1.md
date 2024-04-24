Você pode usar o bloco `join`{:class="block3operators"} do bloco `Operadores`{:class="block3operators"} para juntar texto e variáveis para criar strings mais longas.

Arraste um bloco `join`{:class="block3operators"} para o bloco onde você deseja usá-lo:

```blocks3
say (join [apple ] [banana]) for [2] seconds
```

Substitua o texto pelo texto que deseja usar ou arraste uma variável:

```blocks3
set [name v] to [Scratch]
say (join [Hi, I'm ] (name)) for [2] seconds
```

**Dica:** O bloco `join`{:class="block3operators"} não adiciona espaços, então você precisará digitá-los.

Você pode arrastar um bloco `join`{:class="block3operators"} dentro de outro `join`{:class="block3operators"} para criar strings de texto mais longas:

```blocks3
say (join [Hi, I'm ] (join (name) [ the cat])) for [2] seconds
```

Observe o 'espaço' no final de `Olá, sou` e no início de `o gato`.



