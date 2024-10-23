# -alura-flix-https://www.figma.com/board/fLyXRRavW8s0aWqughpd0D/Fluxograma%3A-crie-uma-aventura-com-HTML%2C-CSS-e-JavaScript-(Community)?node-id=0-1&t=Z1g3CxnmgZOF7dc3-1
html lang="pt-BR">
<head>
    <link rel="stylesheet" href="styles.css">
    <title>Aluraflix</title>
</head>
<body>
    <header>ALURAFLIX</header>
    <section>
        <div>
            <h1>ATRAVÉS DO ARANHAVERSO SUPERA O PRIMEIRO FILME?</h1>
            <p>#homem-aranha</p>
        </div>
        <div>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/gt_fAE1Eg2Q?si=EEv-tsY_b1B2OwKE"
                title="YouTube video player" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
    </section>
</body>
</html>
‎styles.css
+ 4
Número da linha do arquivo original	Número da linha de diferença	Mudança de linha diferencial
@@ -0,0 +1,4 @@
body {
    color: white;
    background: black;
} margin: 0px;
    font-family: "Chakra Petch", sans-serif;
}

header {
@@ -12,13 +13,21 @@ header {
}

section {
	background: rgb(184,156,213);
	padding-bottom: 80px;
	padding-top: 80px;
	display: flex;
	justify-content: center;
    background: rgb(184, 156, 213);
    padding-bottom: 80px;
    padding-top: 80px;
    display: flex;
    justify-content: center;
}

.chamada-texto {
    margin-right: 5%;
}
h1 {
    font-size: 40px;
}
p {
    font-size: 20px;
} margin: 0px;
    font-family: "Chakra Petch", sans-serif;
}

header {
@@ -12,13 +13,21 @@ header {
}

section {
	background: rgb(184,156,213);
	padding-bottom: 80px;
	padding-top: 80px;
	display: flex;
	justify-content: center;
    background: rgb(184, 156, 213);
    padding-bottom: 80px;
    padding-top: 80px;
    display: flex;
    justify-content: center;
}

.chamada-texto {
    margin-right: 5%;
}
h1 {
<link
        href="https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap"
        rel="stylesheet">
    <title>Aluraflix</title>
    <title>Guiminamflix</title>
</head>

<body>
    <header>ALURAFLIX</header>
    <header>GUIMINAMFLIX</header>

    <section class="chamada">
        <div class="chamada-texto">
    font-size: 40px;
}
p {
    font-size: 20px;
}
