Η απάντηση είναι: `1`, και μετά `undefined`.

```js run
alert( alert(1) && alert(2) );
```

Η κλήση για `alert` επιστρέφει `undefined` (δείχνει μόνο ένα μήνυμα, οπότε δεν υπάρχει ουσιαστική επιστροφή).

Εξαιτίας αυτού, το `&&` αξιολογεί τον αριστερό τελεστή (εξόδους `1`) και σταματά αμέσως, επειδή το `undefined` είναι falsy τιμή. Και το `&&` αναζητά μια ψεύτικη τιμή και την επιστρέφει, οπότε τελείωσε.

