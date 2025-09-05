
<html lang="fr">

<head>

<meta charset="UTF-8">

<title>Indice Secret – Bunker</title>

<style>

body {

    font-family: 'Georgia', serif; /* Police type “lettre” */

    background-color: #f3e4d0; /* Fond beige clair / marron clair */

    color: #3e2f1c; /* Couleur texte foncée */

    padding: 40px;

}

#secret {

    display: none;

    font-style: italic; /* Texte en italique pour effet lettre */

    line-height: 1.8;

    max-width: 600px;

    margin: auto;

    border: 1px solid #cbb79b;

    padding: 20px;

    background-color: #fff3e0; /* Fond légèrement plus clair pour la lettre */

}

#login {

    text-align: center;

    max-width: 400px;

    margin: auto;

}

input {

    padding: 10px;

    font-size: 16px;

    margin-top: 10px;

}

button {

    padding: 10px 15px;

    font-size: 16px;

    margin-top: 10px;

    cursor: pointer;

}

</style>

<script>

function checkPassword() {

    var pass = document.getElementById("password").value;

    if(pass === "LAPERLENOIRE") { // Remplace MONCODE par ton mot de passe

        document.getElementById("secret").style.display = "block";

        document.getElementById("login").style.display = "none";

    } else {

        alert("Mot de passe incorrect !");

    }

}

</script>

</head>

<body>



<div id="login">

<h2>Entrez le code pour accéder à l'indice</h2>

<input type="password" id="password" placeholder="Votre code">

<br>

<button onclick="checkPassword()">Valider</button>

</div>



<div id="secret">

<h2>La pointe</h2>

<p>Là où le Bassin s’ouvre sur l’océan, là où les vents racontent des histoires sur la folie des Hommes… Cherche l’ombre du passé, là où la terre a été fortifiée. Entre les dunes et l'océan par All. des Souchets, un refuge oublié t’attend…
</p>
