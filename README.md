# eurostar
eurostar

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="css/styles.css">
    <title>Eurostar</title>
</head>

<body>
    <header>

        <!--  Navigatie balk----------------------->
        <nav>
            <ul>
                <li><img src="images/eurostar.png" alt="eurostar logo"></li>
            </ul>
        </nav>

        <article>
            <h1> Anders dan normaal?</h1>
            <input type="submit" name="Ontdek">
            <img src="images/headerfoto.jpeg" alt="achtergrondfoto">
        </article>
    </header>

        <!--  FILTER EN SORTEREN-------------->

    <section>
        <h2>Filteren en sorteren</h2>

        <form action="Emotie">
           <p>Genre</p>
            <select name="Genre" id="Genre">
  <option value="Spannend">Spannend</option>
  <option value="Humor">Humor</option>
  <option value="Roman">Fantasie</option>
  <option value="Roman">Wantrouwens</option>
  <option value="Roman">Thriller</option>
      </select>
        </form>

        <form action="Emotie">
            <p>Emotie</p>
            <select name="Emotie" id="Emotie">
  <option value="Blij">Blij</option>
  <option value="Boos">Boos</option>
  <option value="Verdrietig">Verdrietig</option>
  <option value="Verliefd">Verliefd</option>
  <option value="Bang">Bang</option>
      </select>
        </form>

        <p>Taalgebruik</p>
        <form action="Taalgebruik">
            <input type="radio" name="Agressief taalgebruik" value="agressief taalgebruik"> Agressief taalgebruik<br>
            <input type="radio" name="Normaal taalgebruik" value="Normaal taalgebruik"> Normaal taalgebruik<br>
        </form>

        <p>Sorteren</p>
        <form action="Sorteren">
            <input type="radio" name="A-Z" value="A-Z"> A-Z<br>
            <input type="radio" name="Oud-Nieuw" value="Oud-Nieuw"> Oud-Nieuw<br>
            <input type="radio" name="Best beoordeeld" value="Best beoordeeld"> Best beoordeeld<br>
        </form>

   <input type="submit" value="Zoeken">
    </section>


    <!--  --------------------------->

    <main>
        <h2>Resultaten</h2>

        <section>
            <h3>Gefrustreerd</h3>
            <p>Ik stap uit die godverdomme stinkbus. De mensen krioelen als mieren over het stationsplein. Ik wil ze vertrappen..</p>
        </section>

        <section>
            <h3>Gefrustreerd</h3>
            <p>Ik stap uit die godverdomme stinkbus. De mensen krioelen als mieren over het stationsplein. Ik wil ze vertrappen..</p>
        </section>

        <section>
            <h3>Gefrustreerd</h3>
            <p>Ik stap uit die godverdomme stinkbus. De mensen krioelen als mieren over het stationsplein. Ik wil ze vertrappen..</p>
        </section>


    </main>



</body>
</html>

