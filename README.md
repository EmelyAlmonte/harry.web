<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Harry Potter - Mundo Mágico</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Bienvenidos al Mundo Mágico de Harry Potter</h1>
        <nav>
            <ul>
                <li><a href="#harry">Harry Potter</a></li>
                <li><a href="#hermione">Hermione Granger</a></li>
                <li><a href="#ron">Ron Weasley</a></li>
                <li><a href="#dumbledore">Albus Dumbledore</a></li>
                <li><a href="#snape">Severus Snape</a></li>
                <li><a href="#casas">Casas de Hogwarts</a></li>
                <li><a href="#hogwarts">Hogwarts</a></li>
                <li><a href="#carrusel">Galería</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="harry">
            <h2>Harry Potter</h2>
            <p>Harry Potter es un joven mago famoso por sobrevivir a un ataque del malvado Lord Voldemort siendo solo un bebé. Junto a sus amigos Hermione Granger y Ron Weasley, Harry vive emocionantes aventuras en Hogwarts.</p>
            <img src="./Imagenes/Harry potter.jpg" alt="Harry">
        </section>

        <section id="hermione">
            <h2>Hermione Granger</h2>
            <p>Hermione Granger es la bruja más brillante de su generación. Hija de muggles, destaca por su inteligencia, valentía y lealtad. Es una pieza clave en la lucha contra Voldemort.</p>
            <img src="./Imagenes/hermione.webp" alt="Hermione">
        </section>

        <section id="ron">
            <h2>Ron Weasley</h2>
            <p>Ron Weasley es el mejor amigo de Harry Potter y miembro de la familia Weasley, una familia de magos de sangre pura. Conocido por su gran sentido del humor y lealtad, Ron es un valiente aliado en la lucha contra las fuerzas oscuras.</p>
            <img src="./Imagenes/ron.jpeg" alt="ron">
        </section>

        <section id="dumbledore">
            <h2>Albus Dumbledore</h2>
            <p>Albus Dumbledore es el director de Hogwarts y uno de los magos más poderosos y sabios de la historia. Mentor de Harry Potter, Dumbledore es una figura fundamental en la lucha contra Voldemort y sus seguidores.</p>
            <img src="./Imagenes/albus.jpg" alt="albus">
        </section>

        <section id="snape">
            <h2>Severus Snape</h2>
            <p>Severus Snape es el enigmático profesor de Pociones de Hogwarts, conocido por su comportamiento severo y misterioso. A lo largo de la serie, Snape demuestra ser un personaje complejo con un papel crucial en la historia de Harry.</p>
            <img src="./Imagenes/severus.jpg" alt="severus">
        </section>
        
        <section id="casas">
            <h2>Casas de Hogwarts</h2>
            <img src="./Imagenes/casas.jpg" alt="casas">
            <div class="casa">
                <h3>Gryffindor</h3>
                <p>Valentía, audacia y coraje son las cualidades que definen a esta casa. Fundada por Godric Gryffindor, es conocida por tener algunos de los magos más valientes.</p>
            </div>
            <div class="casa">
                <h3>Slytherin</h3>
                <p>Ambición, astucia y determinación son características de los estudiantes de Slytherin. Esta casa fue fundada por Salazar Slytherin y es conocida por su astucia y liderazgo.</p>
            </div>
            <div class="casa">
                <h3>Ravenclaw</h3>
                <p>Inteligencia, creatividad y sabiduría son los valores de la casa Ravenclaw. Fundada por Rowena Ravenclaw, es el hogar de los estudiantes más intelectuales y curiosos.</p>
            </div>
            <div class="casa">
                <h3>Hufflepuff</h3>
                <p>Lealtad, paciencia y trabajo duro son las señas de identidad de esta casa. Fundada por Helga Hufflepuff, es conocida por su inclusión y valores de justicia.</p>
            </div>
        </section>
       
        <section id="hogwarts">
            <h2>Colegio Hogwarts de Magia y Hechicería</h2>
            <p>Hogwarts es la escuela de magia más prestigiosa del mundo. Aquí, los jóvenes magos y brujas aprenden todo sobre hechizos, pociones y criaturas mágicas.</p>
            <img src="./Imagenes/hogwarts.webp" alt="escuela">
        </section>

        <section id="carrusel">
            <h2>Galería de Imágenes</h2>
            <div class="carousel-container">
                <button id="prev" class="carousel-button">‹</button>
                <div class="carousel">
                    <div class="carousel-inner">
                <img src="./Imagenes/Harry potter.jpg" alt="Harry Potter">
                <img src="./Imagenes/hermione.webp" alt="Hermione Granger">
                <img src="./Imagenes/ron.jpeg" alt="Ron Weasley">
                <img src="./Imagenes/albus.jpg" alt="Albus Dumbledore">
                <img src="./Imagenes/severus.jpg" alt="Severus Snape">
                <img src="./Imagenes/los tres.jpg" alt="tres">
                <img src="./Imagenes/fundadores.jpg" alt="">
            </div>
        </div>
        <button id="next" class="carousel-button">›</button>
    </div>
</section>


    <footer>
        <p>&copy; 2024 Mundo Mágico de Harry Potter. Todos los derechos reservados.</p>
    </footer>

    <script src="main.js"></script>
</body>
</html>
