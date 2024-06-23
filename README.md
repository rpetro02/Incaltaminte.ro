# Andreeascooking( index.html )

Am ales sa explic codul sursa al site-ului adica index.html pentru ca mi se pare cel mai important, de la el plecand tot.

Structura generala

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Andrea's Cooking</title>
    <link rel="stylesheet" href="still.css">
</head>
<body>

<!DOCTYPE html>: Declară că documentul este un document HTML5.
<html lang="en">: Specifică limba principală a documentului ca fiind engleză.
<head>: Conține metadatele documentului.
<meta charset="UTF-8">: Specifică setul de caractere ca fiind UTF-8.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Asigură că pagina este redimensionată corect pe diferite dispozitive.
<title>Andrea's Cooking</title>: Titlul paginii afișat în fila browserului.
<link rel="stylesheet" href="still.css">: Include o foaie de stil CSS externă pentru a stiliza pagina.

Corpul Paginii

<body>
    <header>
        <div class="logo">
            <img src="b.jpg" alt="Retelele Casei Logo" class="logo">
        </div>
        <h1>Andrea's Cooking</h1>
    </header>

    <body>: Conține conținutul vizibil al paginii web.
<header>: Definiți antetul paginii, care include:
O diviziune pentru logo (<div class="logo">) care conține o imagine (<img src="b.jpg" alt="Retelele Casei Logo" class="logo">).
Titlul principal al paginii (<h1>Andrea's Cooking</h1>).

Navigare
<nav>
        <a href="index.html">Acasa</a>
        <a href="despre.html">Despre</a>
        <a href="aperitive.html">Aperitive</a>
        <a href="deserturi.html">Deserturi</a>
        <a href="salate.html">Salate</a>
        <a href="login.html" style="float: right;">Log In</a>
    </nav>

<nav>: Conține elementele de navigare ale paginii:
Linkuri (<a href="...">) către diferite secțiuni ale site-ului (Acasa, Despre, Aperitive, Deserturi, Salate).
Un link pentru autentificare (<a href="login.html" style="float: right;">Log In</a>) poziționat la dreapta.

Secțiunea Principală

<section>
        <h2>Bine ați venit la Retelele Casei!</h2>
        <p>Explorează lumea gusturilor delicioase și descoperă rețete noi și inovatoare. La Retelele Casei, îmbinăm pasiunea pentru gătit cu tehnologia pentru a vă oferi cele mai bune experiențe culinare.</p>
        <p>Începe călătoria ta culinară astăzi și descoperă bucuria gătitului!</p>
    </section>

    <section>: Conține conținutul principal al paginii:
Un titlu secundar (<h2>Bine ați venit la Retelele Casei!</h2>).
Două paragrafe descriptive (<p>), care oferă informații despre site și invită utilizatorii să exploreze rețetele.

Subsolul

 <footer>
        <p>&copy; 2024 Andrea's Cooking. All rights reserved.</p>
    </footer>
</body>
</html>

<footer>: Conține informațiile din subsolul paginii:
Un paragraf (<p>) care conține drepturile de autor și anul.


