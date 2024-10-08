<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Receptek</title>
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <header>
        <h1>Magyar Receptek</h1>
    </header>

    <main>
        <section class="recipe">
            <h2>Gulyásleves</h2>
            <h3>Hozzávalók:</h3>
            <ul>
                <li>500 g marhahús (lábszár vagy lapocka)</li>
                <li>2 db közepes hagyma</li>
                <li>3 gerezd fokhagyma</li>
                <li>2 db sárgarépa</li>
                <li>2 db fehérrépa</li>
                <li>4-5 közepes krumpli</li>
                <li>1 db paradicsom</li>
                <li>1 db zöldpaprika</li>
                <li>1 evőkanál pirospaprika</li>
                <li>1 teáskanál kömény</li>
                <li>Só, bors ízlés szerint</li>
                <li>Víz</li>
                <li>1 evőkanál zsír vagy olaj</li>
            </ul>
            <h3>Elkészítés:</h3>
            <ol>
                <li>A hagymát apróra vágjuk, és zsíron megdinszteljük.</li>
                <li>Hozzáadjuk a felkockázott marhahúst, és fehéredésig pirítjuk.</li>
                <li>Levesszük a tűzről, megszórjuk pirospaprikával, majd visszatesszük és alaposan összekeverjük.</li>
                <li>Felöntjük vízzel, majd hozzáadjuk a köményt, a fokhagymát, a paradicsomot és a paprikát.</li>
                <li>Lefedve, lassú tűzön főzzük, amíg a hús félig megpuhul.</li>
                <li>Ezután hozzáadjuk a felkarikázott sárgarépát, fehérrépát és krumplit, majd további vízzel pótoljuk, ha szükséges.</li>
                <li>Fűszerezzük sóval, borssal, és lassú tűzön addig főzzük, amíg minden zöldség és a hús teljesen megpuhul.</li>
                <li>Forrón tálaljuk, friss kenyérrel.</li>
            </ol>
        </section>

        <section class="recipe">
            <h2>Paprikás Csirke</h2>
            <h3>Hozzávalók:</h3>
            <ul>
                <li>4 db csirkecomb (felső és alsó)</li>
                <li>2 db közepes hagyma</li>
                <li>2 gerezd fokhagyma</li>
                <li>1 db zöldpaprika</li>
                <li>1 db paradicsom</li>
                <li>1 evőkanál pirospaprika</li>
                <li>2 dl tejföl</li>
                <li>1 evőkanál liszt</li>
                <li>Só, bors ízlés szerint</li>
                <li>1 evőkanál zsír vagy olaj</li>
            </ul>
            <h3>Elkészítés:</h3>
            <ol>
                <li>A hagymát apróra vágjuk, és zsíron vagy olajon megdinszteljük.</li>
                <li>A csirkecombokat hozzáadjuk, és mindkét oldalukat megpirítjuk.</li>
                <li>Levesszük a tűzről, megszórjuk pirospaprikával, összekeverjük, majd visszatesszük a tűzre.</li>
                <li>Hozzáadjuk a felaprított zöldpaprikát, paradicsomot és a fokhagymát, majd felöntjük kevés vízzel.</li>
                <li>Lefedve, lassú tűzön pároljuk, amíg a csirkecombok teljesen megpuhulnak.</li>
                <li>A tejfölt a liszttel kikeverjük, és a csirke levéhez adjuk, majd még néhány percig forraljuk.</li>
                <li>Sóval, borssal ízesítjük, és főtt tésztával vagy galuskával tálaljuk.</li>
            </ol>
        </section>
    </main>
</body>
</html>


/* Alapvető stílusok */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f8f9fa;
    color: #333;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

header {
    background-color: #ff5733;
    color: white;
    padding: 20px;
    text-align: center;
}

h1 {
    margin: 0;
}

main {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

.recipe {
    margin-bottom: 40px;
}

h2 {
    color: #ff5733;
    border-bottom: 2px solid #ff5733;
    padding-bottom: 10px;
}

h3 {
    color: #333;
    margin-bottom: 10px;
}

ul, ol {
    margin-left: 20px;
    margin-bottom: 20px;
}

ul li, ol li {
    margin-bottom: 8px;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: white;
    position: relative;
    bottom: 0;
    width: 100%;
}

