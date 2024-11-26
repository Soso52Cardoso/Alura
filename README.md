@@ -3,6 +3,7 @@ body {
    background: black;
    margin: 0px;
    font-family: "Chakra Petch", sans-serif;
    margin-bottom: 100px;
}

header {
@@ -32,10 +33,6 @@ p {
    font-size: 20px;
}

img {
    height: 200px;
}
.categoria-videos {
    display: flex;
    overflow-x: auto;
@@ -45,4 +42,19 @@ img {
.categoria {
    padding-left: 20px;
    padding-right: 20px;
    margin-top: 50px;
}
.categoria-videos img {
    opacity: 0.5;
    height: 200px;
}
.categoria-videos img:hover {
    opacity: 1.0;
    border: 3px solid green;
}
.categoria h2 {
    color: rgb(42, 122, 228);
}
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
