Ти можеш скористатися блоком `з'єднати`{:class="block3operators"}, який знаходиться на вкладці Коду `Оператори`{:class="block3operators"}, щоб з'єднати текст та змінні для створення довших рядків.

Перетягни блок `з'єднати`{:class="block3operators"} в блок, де ти хочеш його використати:

```blocks3
say (join [apple ] [banana]) for [2] seconds
```

Зміни текст на потрібний тобі текст, або перетягни змінну:

```blocks3
set [name v] to [Scratch]
say (join [Hi, I'm ] (name)) for [2] seconds
```

**Порада:** Блок `з'єднати`{:class="block3operators"} не додає пробілів, тому їх потрібно вводити вручну.

Ти можеш перетягнути блок `з'єднати`{:class="block3operators"} всередину іншого блоку `з'єднати`{:class="block3operators"}, щоб створювати довші рядки тексту:

```blocks3
say (join [Hi, I'm ] (join (name) [ the cat])) for [2] seconds
```

Зверни увагу на 'пробіл' в кінці `Привіт, я` та на початку `кіт`.



