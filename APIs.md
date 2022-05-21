# Buienradar App

We gaan nu iets dieper de stof in duiken. We gaan in de volgende opdrachten gebruik maken van een API van buienradar om onze eigen weer applicatie te schrijven. Een API is een Application Programming Interface, daarmee kan buienradar ons informatie verstrekken in een bepaald formaat die wij bij hun kunnen ophalen.

## Les 1: Gebruik maken van een API.

Om informatie op te halen van een API kunnen we gebruik maken van `fetch('URL')`. Hieronder volgt een voorbeeld met een dummy api.

```javascript
fetch('https://dummyjson.com/products').then(res => res.json()).then(function(res) {
    console.log(res);
});
```

Bouw met het bovenstaande voorbeeld een simpele webpagina en kijk wat je krijgt te zien in de console van je browser. Wat je in de console ziet staan staat opgeslagen in `res`.

## Opdracht 1

- [] Dump de lijst van producten in je console.

## Les 2: Loopen door een array.

De lijst van producten wordt ook wel een array genoemd. Om door een array heen te loopen kan je een `for` loop gebruiken, dit doe je door gebruik te maken van de `.length` waarde. Hier volgt een voorbeeld:

```javascript
let products = [
    {name: 'appel', price: 3},
    {name: 'banaan', price: 2.5},
    {name: 'mango', price: 5}
];

for(var i = 0; i < products.length; i++) {
    let currentProduct = products[i];
    console.log(currentProduct.name);
}
```

## Opdracht 2

- [] Pas het bovenstaande voorbeeld dusdanig aan zodat de naam en de prijs los van elkaar in de console komen te staan.

- [] Haal de lijst van producten uit de dummy API op en loop erdoorheen. In de loop moet je nogmaals de naam en prijs van de producten los van elkaar in de console zetten, maar je moet ervoor zorgen dat de prijs van het product minimaal 100 euro is.