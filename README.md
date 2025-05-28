<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yadhira Yurikho Coyuri Tirado</title>
    <style>
        /* General */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #f0f4f8, #d9e8ff); /* Fondo con degradado suave */
            color: #333; /* Texto general */
            line-height: 1.6;
            overflow-x: hidden;
        }

        /* Header */
        header {
            background: linear-gradient(90deg, #00695c, #004d40); /* Degradado moderno */
            color: white;
            text-align: center;
            padding: 20px 0;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 2.5rem;
            font-weight: bold;
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            color: #a5d6a7; /* Verde pastel */
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.1rem;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #ffffff; /* Blanco al pasar el mouse */
        }

        /* Main Section */
        main {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }

        section {
            background-color: #ffffff;
            width: 90%;
            max-width: 800px;
            margin: 20px 0;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.15);
            animation: fadeIn 0.5s ease;
        }

        section h2 {
            color: #00695c; /* Verde pastel */
            border-bottom: 3px solid #80cbc4; /* Detalle de línea */
            padding-bottom: 10px;
            margin-bottom: 20px;
            font-size: 1.8rem;
        }

        section p, section ul {
            font-size: 1rem;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            margin: 10px 0;
        }

        ul li strong {
            color: #004d40;
        }

        ul li a {
            color: #00796b;
            text-decoration: none;
            font-weight: bold;
        }

        ul li a:hover {
            text-decoration: underline;
            color: #004d40;
        }

        /* Footer */
        footer {
            background: linear-gradient(90deg, #004d40, #00695c);
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 30px;
            font-size: 0.9rem;
        }

        footer a {
            color: #a5d6a7;
            text-decoration: none;
        }

        footer a:hover {
            color: #ffffff;
        }

        /* Keyframes for animations */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(10px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Responsive */
        @media (min-width: 768px) {
            nav a {
                font-size: 1.2rem;
            }

            section {
                margin: 30px 0;
                padding: 30px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Yadhira Yurikho Coyuri Tirado</h1>
        <nav>
            <a href="#biografia">Biografía</a>
            <a href="#estudios">Estudios y Cursos</a>
            <a href="#contacto">Contacto</a>
        </nav>
    </header>

    <main>
        <section id="biografia">
            <h2>Biografía</h2>
            <p>Soy Yadhira Yurikho Coyuri Tirado, estudiante de Ingeniería Industrial en la <strong>Universidad Católica San Pablo</strong> (UCSP) de Arequipa, Perú.</p>
            <p>Me acompañan en este camino mis amigos <strong>Gabriel Mauricio Rodriguez Peña</strong>, <strong>Dayalma Yasbel Yanque Clemente</strong> y <strong>Karlayne chuctaya Castro</strong>.</p>
            <p>Me gusta tocar el violin y me gusta ir al gym.</p>
        </section>

        <section id="estudios">
            <h2>Estudios y Cursos</h2>
            <p>Ya hice estos cursos de aqui::</p>
            <ul>
                <li><strong>Matemática 1:</strong> Fundamentos matemáticos necesarios para el análisis en ingeniería.</li>
                <li><strong>Química 1:</strong> Introducción a los principios químicos aplicados a la ingeniería.</li>
                <li><strong>Metodología de la Investigación Científica:</strong> Métodos y técnicas de investigación en ingeniería.</li>
                <li><strong>Economía General:</strong> Principios económicos y su aplicación en la industria.</li>
                <li><strong>Introducción a la Filosofía:</strong> Reflexión crítica sobre conceptos fundamentales de la filosofía.</li>
            </ul>
            <p>También colaboro y comparto experiencias con mis compañeros:</p>
            <ul>
                <li><a href="https://fabriciobernardovillanueva.github.io/githubpagetest/" target="_blank">Fabricio Bernardo Villanueva Valdivia</a></li>
                <li><a href="https://luisstefanopachecovaldivia.github.io/LuisStefanoPachecoValdivia/" target="_blank">Luis Stefano Pacheco Valdivia</a></li>
            </ul>
        </section>

        <section id="contacto">
            <h2>Contacto</h2>
            <p>Si deseas ponerte en contacto conmigo, no dudes en escribirme:</p>
            <p>Email: <a href="mailto:gabriel.rodriguez.pena@ucsp.edu.pe">gabriel.rodriguez.pena@ucsp.edu.pe</a></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Yadhira Yurikho Coyuri Tirado</p>
    </footer>
</body>
</html>

