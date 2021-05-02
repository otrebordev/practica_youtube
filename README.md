# practica_youtube
Espero que les guste

# Captures
![image](https://user-images.githubusercontent.com/83046233/116802251-6f7faf80-aadf-11eb-981b-b4d99a0cd7d4.png)
![image](https://user-images.githubusercontent.com/83046233/116802280-8de5ab00-aadf-11eb-9261-fc4f4b62b7c9.png)
![image](https://user-images.githubusercontent.com/83046233/116802288-a655c580-aadf-11eb-8f3a-cc2252da0959.png)


# Código 
HTML
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Practica | @otrebor.dev</title>
    <link rel="stylesheet" href="css/styles.css">
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css"
        integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous" />
</head>

<body>
    <div class="header">
        <div class="logo">
            <p>Oves</p>
        </div>

        <div class="menu">
            <i class="fas fa-bars"></i>
        </div>
    </div>

    <div class="main">
        <div class="grup-text">
            <h1>Amamos a las aves</h1>
            <h2>Cuidemolas y amamolas</h2>
        </div>

        <div class="redes">
            <i class="fab fa-instagram"></i>
            <i class="fab fa-facebook"></i>
        </div>
    </div>

    <div class="footer">
        <p>Page by @otrebor.dev</p>
        <p>Sigueme para más | @otrebor.dev</p>
    </div>

    <!-- Page by @otrebor.dev -->
</body>

</html>

CSS

/* ==================
    * IMPORTS *
===================== */
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600;700&display=swap');

/* ==================
    * VARIABLES *
===================== */
:root {

    /* ? Paleta de colores */
    --color-primario: #fdfdfd;

    /* ? Tipo de fuente */
    --fuente: 'Montserrat', sans-serif;
}

/* ==================
    * GENERAL *
===================== */    
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    height: 100vh;
    background-image: url('/images/fondo-2.svg');
    background-size: cover;
    font-family: var(--fuente);
}

/* ==================
    * HEADER *
===================== */
.header {
    width: 100%;
    height: 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
    color: var(--color-primario);
}

/* ? Logo */
.logo {
    font-size: 25px;
    font-weight: bold;
}

/* ? Menu */
.menu > i {
    font-size: 25px;
}

/* ==================
    * MAIN *
===================== */
.main {
    width: 100%;
    height: 80vh;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}

/* ? Estilos a los textos */
.grup-text {
    line-height: 55px;   
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: var(--color-primario);
}

.grup-text > h1 {
    font-size: 50px;
    font-weight: bold;
}

.grup-text > h2 {
    font-size: 30px;
    font-weight: bold;
}

/* ? Redes */
.redes {
    height: 100px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
}

.redes > i {
    color: var(--color-primario);
    font-size: 30px;
    cursor: pointer;
}


/* ==================
    * FOOTER *
===================== */
.footer {
    width: 100%;
    height: 50px;
    position: absolute;
    bottom: 0;
    color: var(--color-primario);
    display: flex;
    align-items: center;
    justify-content: space-around;
}

.footer > p {
    font-size: 10px;
    font-weight: bold;
}
