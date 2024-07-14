# JavaScript
 
Ecco la versione riscritta del codice per un file `.md` con titoli, sottotitoli e suddivisioni in diverse parti:

```markdown
# Introduzione a JavaScript

In questo documento, esploreremo i concetti fondamentali di JavaScript, tra cui variabili, tipi di dati, strutture di controllo, array, funzioni e manipolazione del DOM.

## 1. Console.log

Il comando `console.log` è utilizzato per stampare o mostrare qualcosa nella console del browser.

```javascript
console.log("Hello World");
```

## 2. Variabili e Tipi

### Dichiarazione delle Variabili

- **`var`**: Dichiarazione di variabili globali, che possono essere modificate ovunque nel codice.
- **`let`**: Dichiarazione di variabili con ambito di blocco, che possono essere modificate solo all'interno del blocco in cui sono dichiarate.
- **`const`**: Dichiarazione di costanti, che non possono essere modificate dopo la loro inizializzazione.

### Esempi

```javascript
// Dichiarazione e utilizzo di variabili
var x = 5;   // Inizializzazione di x con il valore 5
x = x * 2;   // Aggiornamento di x: x = 10
console.log(x); // Stampa il valore di x
```

## 3. Controlli di Condizione

### If, Else, e Else If

```javascript
if (x == 2 && y == 4) {
    console.log("primo blocco");
} else if (y > 10) {
    console.log("x non è uguale a 2");
} else {
    console.log("x non è uguale a 2");
}
```

### Operatori di Comparazione

- `==`  : Uguale a
- `!=`  : Diverso da
- `>`   : Maggiore di
- `<`   : Minore di
- `>=`  : Maggiore o uguale a
- `<=`  : Minore o uguale a
- `&&`  : E logico
- `||`  : O logico
- `!`   : Non logico

## 4. Vettori e Matrici

### Vettori (Array)

```javascript
var vettor = [1, 2, 3, 4, 5];
console.log(vettor);      // Stampa l'intero array
console.log(vettor[2]);   // Stampa il valore all'indice 2 (3)
```

### Matrici (Array di Array)

```javascript
var matrice = [[1, 2, 3], [4, 5, 6], [7, 8, 9]];
console.log(matrice);       // Stampa l'intera matrice
console.log(matrice[1][2]); // Stampa il valore alla posizione [1][2] (6)
```

## 5. Cicli

### For

```javascript
for (var i = 0; i < 10; i++) {
    console.log(i); // Stampa i numeri da 0 a 9
}
```

### While

```javascript
var j = 0;
while (j < 10) {
    console.log(j);
    j++;
}
```

### Do While

```javascript
var k = 0;
do {
    console.log(k);
    k++;
} while (k < 10);
```

## 6. Funzioni e Procedure

### Procedure

```javascript
function procedura(nome) {
    console.log("Questa è una procedura ed il tuo nome è: " + nome);
}

procedura("Mario");
```

### Funzioni

```javascript
function funzione(numero) {
    var doppio = numero * 2;
    return doppio;
}

console.log(funzione(2)); // Stampa 4
```

## 7. Strutture Dati

### Oggetti

```javascript
var vicinoDiCasa = {
    nome: "Mario",
    cognome: "Rossi",
    età: 20,
    sesso: "Maschio",
    numeroDiTelefono: "3333333333",
};

console.log(vicinoDiCasa);         // Stampa tutti i valori dell'oggetto
console.log(vicinoDiCasa.nome);    // Stampa solo il valore della proprietà 'nome'
```

## 8. Manipolazione DOM

### Selezionare e Modificare Elementi

```javascript
document.getElementsByTagName("button")[0].onclick = function() {
    document.getElementsByTagName("button")[0].style.backgroundColor = "red";
}
```

## 9. Numeri e Operatori Matematici

### Tipi di Numeri

```javascript
let intero = 20;      // Numero intero
let float = 20.5;    // Numero con decimali
let double = 20e3;   // Numero con notazione esponenziale
```

### Metodi dei Numeri

```javascript
const numero = 50.823748932;
console.log(numero.toFixed(2)); // Stampa 50.82

const numeroStringa = "20";
console.log(Number(numeroStringa) + 10); // Stampa 30
```

### Operatori Matematici

- `+` : Addizione
- `-` : Sottrazione
- `*` : Moltiplicazione
- `/` : Divisione
- `%` : Modulo (resto della divisione)
- `**` : Potenza

### Operatori di Assegnazione

```javascript
let numero = 10;
numero += 10; // Aggiunge 10 a numero
console.log(numero); // Stampa 20
```

## 10. Stringhe di Testo

### Creare e Manipolare Stringhe

```javascript
let testo = 'ciao sono una stringa';
console.log(testo.length); // Stampa la lunghezza della stringa
console.log(testo.toUpperCase()); // Stampa 'CIAO SONO UNA STRINGA'
console.log(testo.replace('ciao', 'hello')); // Stampa 'hello sono una stringa'
```

### Template Literals

```javascript
let variabile = 'ciao sono una variabile';
let elemento = `<h1>${variabile} bellissima</h1>`;
document.body.innerHTML = elemento; // Modifica il contenuto del body con l'HTML
```

## 11. Array

### Creare e Manipolare Array

```javascript
let citta = ['Roma', 'Milano', 'Napoli'];
console.log(citta[1]); // Stampa 'Milano'
citta.push('Firenze'); // Aggiunge 'Firenze' alla fine dell'array
console.log(citta.join(', ')); // Stampa 'Roma, Milano, Napoli, Firenze'
```

## 12. Condizioni con IF ELSE e SWITCH

### Utilizzare Condizioni

```javascript
let numero = 15;
if (numero < 20) {
    console.log('Il numero è minore di 20');
} else {
    console.log('Il numero non è minore di 20');
}
```

### Switch Statement

```javascript
let nome = 'Luca';
switch (nome) {
    case 'Luca':
        console.log('Benvenuto Luca');
        break;
    case 'Marco':
        console.log('Benvenuto Marco');
        break;
    default:
        console.log('Nome non riconosciuto');
        break;
}
```

### Operatore Ternario

```javascript
let risultato = (numero < 20) ? "Minore di 20" : "Non minore di 20";
console.log(risultato);
```

## 13. Loop e Cicli

### For Loop

```javascript
let array = [29, 45, 48];
for (let i = 0; i < array.length; i++) {
    console.log(array[i]);
}
```

### While e Do While

```javascript
let j = 0;
while (j < 10) {
    console.log(j);
    j++;
}

let k = 0;
do {
    console.log(k);
    k++;
} while (k < 10);
```

### Break e Continue

```javascript
let array = [29, 45, 48];
for (let i = 0; i < array.length; i++) {
    if (array[i] == 45) {
        break; // Interrompe il ciclo
    }
    console.log(array[i]);
}
```

```javascript
let array = [29, 45, 48];
for (let i = 0; i < array.length; i++) {
    if (array[i] == 45) {
        continue; // Salta l'iterazione corrente
    }
    console.log(array[i]);
}
```

---

**Nota:** Questo documento offre una panoramica dei principali concetti e funzionalità di JavaScript. Per approfondire ulteriormente, consulta la documentazione ufficiale e le risorse aggiuntive.

```

Questo documento markdown fornisce una guida ben strutturata sui concetti fondamentali di JavaScript con esempi di codice e spiegazioni. Puoi modificarlo ulteriormente per adattarlo alle tue esigenze specifiche.