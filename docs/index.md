<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Horario 3D Interactivo</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;700&display=swap');

        .centered-table {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100%;
            width: 100%;
            perspective: 1500px;
        }

        table {
            border-collapse: separate;
            border-spacing: 5px;
            background: linear-gradient(145deg, #ffffff, #f0f8ff);
            border-radius: 15px;
            overflow: hidden;
            transform-style: preserve-3d;
            transition: transform 0.1s ease;
            width: 90%;
            max-width: 1200px;
            font-size: 1.2em;
        }

        th, td {
            border: none;
            padding: 25px;
            text-align: center;
            vertical-align: middle;
            font-family: 'Poppins', sans-serif;
            color: #34495e;
            transition: all 0.3s ease;
        }

        th {
            background-color: #2980b9;
            font-weight: 700;
            color: #FFF;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            font-size: 1.4em;
            text-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
            box-shadow: 0 0 15px rgba(41, 128, 185, 0.9), 0 0 30px rgba(41, 128, 185, 0.6);
            transition: 0.3s;
        }

        th:hover {
            box-shadow: 0 0 20px rgba(41, 128, 185, 1), 0 0 40px rgba(41, 128, 185, 0.8);
        }

        td {
            background-color: rgba(255, 255, 255, 0.6);
            font-weight: 300;
            box-shadow: inset 0 0 10px rgba(0, 0, 0, 0.1);
        }

        tr:nth-child(even) td {
            background-color: rgba(230, 230, 250, 0.5);
        }

        tr:nth-child(4) td {
            border-radius: 10px;
            background: linear-gradient(45deg, #ff6b6b, #ff4b4b);
            color: white;
            font-size: 1.4em;
            text-transform: uppercase;
            box-shadow: 0 0 15px rgba(231, 76, 60, 0.9);
            text-shadow: 0 2px 5px rgba(0, 0, 0, 0.5);
            transition: 0.3s;
        }

        tr:nth-child(4) td:hover {
            box-shadow: 0 0 20px rgba(231, 76, 60, 1);
            
        }

        td:hover {
            transform: translateZ(20px);
            background-color: rgba(41, 128, 185, 0.3);
            font-weight: 400;
            
        }

        .cell-content {
            transition: transform 0.3s ease;
        }

        tr:nth-child(4) td {
            font-weight: bold;
            text-align: center; /* Alinea horizontalmente */
            vertical-align: middle; /* Alinea verticalmente */
        }

        /* Forzar centrado para celdas con colspan */
        td[colspan] {
            text-align: center !important; /* Forzar centrado horizontal */
            vertical-align: middle !important; /* Forzar centrado vertical */
        }

        
    </style>
</head>
<body>
    <div class="centered-table">
        <table id="horario">
            <thead>
                <tr>
                    <th style="text-align: center;">LUNES</th>
                    <th style="text-align: center;">MARTES</th>
                    <th style="text-align: center;">MIÉRCOLES</th>
                    <th style="text-align: center;">JUEVES</th>
                    <th style="text-align: center;">VIERNES</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td style="text-align: center;">Mates</td>
                    <td style="text-align: center;">Mates</td>
                    <td style="text-align: center;">Historia</td>
                    <td style="text-align: center;">Tecnología</td>
                    <td style="text-align: center;">Tecnología</td>
                </tr>
                <tr>
                    <td style="text-align: center;">Historia</td>
                    <td style="text-align: center;">Tecnología</td>
                    <td style="text-align: center;">Mates</td>
                    <td style="text-align: center;">Mates</td>
                    <td style="text-align: center;">Física</td>
                </tr>
                <tr>
                    <td style="text-align: center;">TEC</td>
                    <td style="text-align: center;">Religión</td>
                    <td style="text-align: center;">Programación</td>
                    <td style="text-align: center;">Francés</td>
                    <td style="text-align: center;">Francés</td>
                </tr>
                <tr>
                    <td colspan="5">RECREO</td>
                </tr>
                <tr>
                    <td style="text-align: center;">Física</td>
                    <td style="text-align: center;">Filosofía</td>
                    <td style="text-align: center;">Física</td>
                    <td style="text-align: center;">TIC</td>
                    <td style="text-align: center;">Lengua</td>
                </tr>
                <tr>
                    <td style="text-align: center;">Programación</td>
                    <td style="text-align: center;">TIC</td>
                    <td style="text-align: center;">Lengua</td>
                    <td style="text-align: center;">Física</td>
                    <td style="text-align: center;">Filosofía</td>
                </tr>
                <tr>
                    <td style="text-align: center;">Francés</td>
                    <td style="text-align: center;">Lengua</td>
                    <td style="text-align: center;">Filosofía</td>
                    <td style="text-align: center;">Historia</td>
                    <td style="text-align: center;">Historia</td>
                </tr>
            </tbody>
        </table>
    </div>

</body>
</html>