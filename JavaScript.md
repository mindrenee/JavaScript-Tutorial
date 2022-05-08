# JavaScript

Met JavaScript kun je webpagina's dynamisch maken. Je kunt vanaf je webpagina de gebruiker om input vragen en dit verwerken. Je gaat in de volgende opdrachten kennis maken hoe JavaScript gebruikt kan worden in jouw website.

## Les 1: Basis

JavaScript schrijf je tussen de head-tags van je webpagina. Je kunt hier direct JavaScript code in schrijven. Dit script wordt uitgevoerd als de webpagina geladen wordt. Met het commando document.write() schrijf je direct op de blanco webpagina.

```
<head>
  <title>JavaScript Les 1</title>
  <script>
    document.write(5 + 6);
  </script>
</head>
<body>
  
</body>
```

Je kunt ook uitvoer op de pagina tonen op andere manieren. Het is ook mogelijk om een pop-up te tonen. Pop-ups moeten dan wel worden toegestaan in de browser.

```
<head>
  <title>JavaScript Les 1</title>
  <script>
    window.alert(5 + 6);
  </script>
</head>
<body>
  
</body>
```

Je ziet al verschil tussen de 2 commando's. In de eerste staat document, en in de tweede windows. Het document is dus de webpagina en window is het browser window waar de output (uitvoer) op verschijnt. 

Er is nog een derde manier om uitvoer te krijgen van JavaScript. Via de web-console.

## Les 2: Loops

Statement 1 is executed (one time) before the execution of the code block.

Statement 2 defines the condition for executing the code block.

Statement 3 is executed (every time) after the code block has been executed.


