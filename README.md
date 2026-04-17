<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Actividad HTML5 - Unidad 2</title>
</head>
<body>

    <header>
        <h1>Actividad HTML5 - Unidad 2</h1>
        <h2>Etiquetas de sección, tablas y multimedia</h2>
    </header>

    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#info">Información Personal</a>
        <a href="#tabla">Tabla</a>
        <a href="#imagen">Imagen</a>
    </nav>

    <hr>

    <section id="inicio">
        <h3>Bienvenido a mi Página Web</h3>
        <p>
            Esta es una página creada con HTML5 utilizando etiquetas semánticas como
            header, nav, section y footer.
        </p>
    </section>

    <hr>

    <section id="info">
        <h3>Información Personal</h3>
        <p><b>Nombre:</b> Juan Miguel Pino Flórez</p>
        <p><b>Código:</b> 192778</p>
        <p><b>Programa:</b> Ingeniería de Sistemas</p>
        <p><b>Universidad:</b> Universidad Francisco de Paula Santander</p>
    </section>

    <hr>

    <section id="tabla">
        <h3>Tabla de Ejemplo</h3>

        <table border="1">
            <tr>
                <th>Nombre</th>
                <th>Edad</th>
            </tr>

            <tr>
                <td>Juan</td>
                <td>20</td>
            </tr>

            <tr>
                <td>Ana</td>
                <td>19</td>
            </tr>

            <tr>
                <td>Carlos</td>
                <td>22</td>
            </tr>
        </table>
    </section>

    <hr>

    <section id="imagen">
        <h3>Imagen</h3>
        <img src="imagen.jpg" alt="Imagen representativa de HTML5" width="300">
    </section>

    <hr>

    <footer>
        <p><b>Docente:</b> Ángela María Guerrero Bayona</p>
        <p><b>Estudiante:</b> Juan Miguel Pino Flórez</p>
        <p><b>Año:</b> 2026</p>
    </footer>
</body>
</html>
