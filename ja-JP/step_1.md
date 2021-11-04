You can use the `join`{:class="block3operators"} block from the `Operators`{:class="block3operators"} block to join text and variables to make longer strings.

Drag a `join`{:class="block3operators"} block into the block where you want to use it:

```blocks3
say (join [apple ] [banana]) for [2] seconds
```

Replace the text with the text you want to use, or drag in a variable:

```blocks3
set [name v] to [Scratch]
say (join [Hi, I'm ] (name)) for [2] seconds
```

**Tip:** The `join`{:class="block3operators"} block doesn't add spaces so you will need to type them.

You can drag a `join`{:class="block3operators"} block inside another `join`{:class="block3operators"} to create longer text strings:

```blocks3
say (join [Hi, I'm ] (join (name) [ the cat])) for [2] seconds
```

Notice the 'space' at the end of `Hi, I'm` and the beginning of `the cat`.



