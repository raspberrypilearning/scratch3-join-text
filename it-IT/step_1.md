Puoi utilizzare il blocco `unisci`{:class="block3operators"} dal blocco `Operatori`{:class="block3operators"} per combinare testo e variabili, creando stringhe più lunghe.

Trascina un blocco `unisci`{:class="block3operators"} nel blocco in cui desideri utilizzarlo:

```blocks3
say (join [apple ] [banana]) for [2] seconds
```

Sostituisci il testo con quello che desideri utilizzare oppure trascina una variabile:

```blocks3
set [name v] to [Scratch]
say (join [Hi, I'm ] (name)) for [2] seconds
```

**Suggerimento:** il blocco `unisci`{:class="block3operators"} non aggiunge spazi automaticamente, quindi dovrai inserirli manualmente.

Puoi trascinare un blocco `unisci`{:class="block3operators"} dentro un altro blocco `unisci`{:class="block3operators"} per creare stringhe di testo più lunghe:

```blocks3
say (join [Hi, I'm ] (join (name) [ the cat])) for [2] seconds
```

Nota lo "spazio" alla fine di `Ciao, sono` e all'inizio di `il gatto`.



