---
layout: default
title: Inicio
---

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Riesgos Laborales en el Trabajo Informático</title>

    <style>
        :root {
            --color-fondo: #0f172a;
            --color-principal: #1e293b;
            --color-secundario: #38bdf8;
            --color-texto: #e2e8f0;
            --color-acento: #22c55e;
        }

        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, sans-serif;
            background-color: var(--color-fondo);
            color: var(--color-texto);
            line-height: 1.6;
        }

        header {
            background: var(--color-principal);
            padding: 20px;
            text-align: center;
            border-bottom: 3px solid var(--color-secundario);
        }

        header h1 {
            margin: 0;
            color: var(--color-secundario);
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            background: #020617;
            padding: 10px;
        }

        nav a {
            color: var(--color-texto);
            text-decoration: none;
            transition: 0.3s;
        }

        nav a:hover {
            color: var(--color-secundario);
        }

        main {
            max-width: 1000px;
            margin: auto;
            padding: 20px;
        }

        section {
            margin-bottom: 40px;
        }

        h2 {
            color: var(--color-acento);
            border-left: 5px solid var(--color-acento);
            padding-left: 10px;
        }

        .imagen {
            width: 100%;
            border-radius: 10px;
            margin-top: 15px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
        }

        th, td {
            padding: 12px;
            text-align: left;
        }

        th {
            background-color: var(--color-principal);
        }

        tr:nth-child(even) {
            background-color: #1e293b;
        }

        tr:nth-child(odd) {
            background-color: #0f172a;
        }

        footer {
            text-align: center;
            padding: 15px;
            background: var(--color-principal);
            border-top: 2px solid var(--color-secundario);
            margin-top: 40px;
        }

        .referencias {
            font-size: 0.9em;
        }

        .referencias li {
            margin-bottom: 8px;
        }
    </style>
</head>
<body>

<header>
    <h1>🛡️ Riesgos Laborales en el Trabajo Informático</h1>
    <p>Análisis técnico de los principales factores de riesgo en entornos digitales</p>
</header>

<nav>
    <a href="index.html">Inicio</a>
    <a href="riesgos.html">Riesgos</a>
    <a href="prevencion.html">Prevención</a>
</nav>

<main>

<section>
    <h2>📌 Introducción</h2>
    <p>
        El trabajo en el ámbito informático presenta riesgos derivados del uso intensivo de equipos,
        la exposición prolongada a pantallas y la carga mental. Identificarlos es clave para mejorar la seguridad laboral.
    </p>
    <img class="imagen" src="https://images.unsplash.com/photo-1581092334651-ddf26d9a09d0" alt="Trabajo informático">
</section>

<section>
    <h2>⚠️ Tipos de Riesgos</h2>

    <table>
        <tr>
            <th>Tipo de Riesgo</th>
            <th>Descripción</th>
            <th>Consecuencias</th>
        </tr>

        <tr>
            <td>Ergonómico</td>
            <td>Posturas incorrectas</td>
            <td>Dolores musculares</td>
        </tr>

        <tr>
            <td>Visual</td>
            <td>Uso prolongado de pantallas</td>
            <td>Fatiga ocular</td>
        </tr>

        <tr>
            <td>Psicosocial</td>
            <td>Estrés laboral</td>
            <td>Ansiedad</td>
        </tr>

        <tr>
            <td>Tecnoestrés</td>
            <td>Exceso de tecnología</td>
            <td>Fatiga mental</td>
        </tr>
    </table>
</section>

<section>
    <h2>💻 Riesgos Ergonómicos</h2>
    <p>
        Las malas posturas pueden provocar lesiones musculoesqueléticas. Es fundamental adaptar el puesto de trabajo.
    </p>
    <img class="imagen" src="https://images.unsplash.com/photo-1593642532400-2682810df593" alt="Ergonomía oficina">
</section>

<section>
    <h2>👁️ Riesgos Visuales</h2>
    <p>
        La exposición a pantallas provoca fatiga visual. Se recomienda aplicar la regla 20-20-20.
    </p>
    <img class="imagen" src="https://images.unsplash.com/photo-1517336714731-489689fd1ca8" alt="Pantalla ordenador">
</section>

<section>
    <h2>🧠 Riesgos Psicosociales</h2>
    <p>
        El estrés y la sobrecarga laboral afectan al bienestar mental. Es importante gestionar tiempos y descansos.
    </p>
    <img class="imagen" src="https://images.unsplash.com/photo-1551836022-d5d88e9218df" alt="Estrés laboral">
</section>

<section>
    <h2>📊 Evaluación de Riesgos</h2>
    <p>
        La evaluación continua permite detectar problemas y aplicar mejoras basadas en normativas oficiales.
    </p>
</section>

<section>
    <h2>📚 Referencias</h2>
    <ul class="referencias">
        <li>Instituto Nacional de Seguridad y Salud en el Trabajo (INSST).</li>
        <li>ISO 9241: Ergonomía de la interacción persona-sistema.</li>
        <li>Guía Técnica para la Evaluación de Riesgos en Pantallas de Visualización de Datos (PVD).</li>
        <li>Organización Mundial de la Salud (OMS) - Salud laboral.</li>
    </ul>
</section>

</main>

<footer>
    <p>Proyecto de Seguridad en el Trabajo Informático | 2026</p>
</footer>

</body>
</html>
