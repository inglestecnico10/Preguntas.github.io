<html>

<head>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        h1 {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            margin: 0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }

        .question {
            margin-bottom: 20px;
            text-align: left;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            background-color: #f9f9f9;
        }

        .options {
            margin-top: 10px;
        }

        label {
            display: block;
            margin-bottom: 10px;
        }

        input[type="radio"] {
            margin-right: 5px;
        }

        .button-container {
            text-align: center;
            margin-top: 20px;
        }

        button {
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .result-container {
            margin-top: 20px;
        }

        .incorrect {
            color: red;
        }
    </style>
</head>

<body>
    <h1>Componentes de PC</h1>

    <div class="container">
        <div class="question">
            <p>Pregunta 1: ¿Qué componente es responsable del almacenamiento de datos a largo plazo en una computadora?</p>
            <div class="options">
                <label><input type="radio" name="q1" value="a"> a. CPU</label>
                <label><input type="radio" name="q1" value="b"> b. RAM</label>
                <label><input type="radio" name="q1" value="c"> c. Disco duro</label>
            </div>
        </div>

        <div class="question">
            <p>Pregunta 2: ¿Cuál de las siguientes opciones describe mejor la función de una placa base?</p>
            <div class="options">
                <label><input type="radio" name="q2" value="a"> a. Procesa datos y ejecuta programas.</label>
                <label><input type="radio" name="q2" value="b"> b. Conecta todos los componentes de la computadora y facilita la comunicación entre ellos.</label>
                <label><input type="radio" name="q2" value="c"> c. Almacena archivos y aplicaciones.</label>
            </div>
        </div>

        <div class="question">
            <p>Pregunta 3: ¿Qué dispositivo es esencial para la salida de audio en una computadora?</p>
            <div class="options">
                <label><input type="radio" name="q3" value="a"> a. Monitor</label>
                <label><input type="radio" name="q3" value="b"> b. Altavoces</label>
                <label><input type="radio" name="q3" value="c"> c. Teclado</label>
            </div>
        </div>

        <div class "question">
        <p>Pregunta 4: ¿Qué tipo de memoria se utiliza para almacenar datos y programas temporalmente mientras la computadora está encendida?</p>
        <div class="options">
            <label><input type="radio" name="q4" value="a"> a. Disco duro</label>
            <label><input type="radio" name="q4" value="b"> b. RAM</label>
            <label><input type="radio" name="q4" value="c"> c. CPU</label>
        </div>
    </div>

    <div class="question">
        <p>Pregunta 5: ¿Qué componente es responsable de enfriar la CPU en una computadora?</p>
        <div class="options">
            <label><input type="radio" name="q5" value="a"> a. Fuente de alimentación</label>
            <label><input type="radio" name="q5" value="b"> b. Ventilador de la CPU</label>
            <label><input type="radio" name="q5" value="c"> c. Disco duro</label>
        </div>
    </div>

    <div class="question">
        <p>Pregunta 6: ¿Qué parte de la computadora suministra energía eléctrica a todos los componentes?</p>
        <div class="options">
            <label><input type="radio" name="q6" value="a"> a. Placa base</label>
            <label><input type="radio" name="q6" value="b"> b. Unidad de fuente de alimentación</label>
            <label><input type="radio" name="q6" value="c"> c. CPU</label>
        </div>
    </div>

    <div class="question">
        <p>Pregunta 7: ¿Cuál de las siguientes opciones describe mejor la función de una tarjeta gráfica?</p>
        <div class="options">
            <label><input type="radio" name="q7" value="a"> a. Almacena archivos gráficos.</label>
            <label><input type="radio" name="q7" value="b"> b. Procesa cálculos matemáticos complejos.</label>
            <label><input type="radio" name="q7" value="c"> c. Genera imágenes en la pantalla y acelera los gráficos en juegos y aplicaciones.</label>
        </div>
    </div>

    <div class="question">
        <p>Pregunta 8: ¿Qué dispositivo se utiliza para introducir datos en una computadora moviéndolo sobre una superficie plana?</p>
        <div class="options">
            <label><input type="radio" name="q8" value="a"> a. Monitor</label>
            <label><input type="radio" name="q8" value="b"> b. Ratón</label>
            <label><input type="radio" name="q8" value="c"> c. Teclado</label>
        </div>
    </div>

    <div class="question">
        <p>Pregunta 9: ¿Cuál de los siguientes componentes suele ser una unidad de estado sólido (SSD) o un disco duro (HDD)?</p>
        <div class="options">
            <label><input type="radio" name="q9" value="a"> a. CPU</label>
            <label><input type="radio" name="q9" value="b"> b. RAM</label>
            <label><input type="radio" name="q9" value="c"> c. Almacenamiento de datos</label>
        </div>
    </div>

    <div class="question">
        <p>Pregunta 10: ¿Qué tipo de memoria es volátil y se borra cuando se apaga la computadora?</p>
        <div class="options">
            <label><input type="radio" name="q10" value="a"> a. Disco duro</label>
            <label><input type="radio" name="q10" value="b"> b. RAM</label>
            <label><input type="radio" name="q10" value="c"> c. CPU</label>
        </div>
    </div>

    <div class="question">
        <p>Pregunta 11: ¿Qué tipo de conector se utiliza para conectar periféricos como impresoras y cámaras a una computadora?</p>
        <div class="options">
            <label><input type="radio" name="q11" value="a"> a. USB</label>
            <label><input type="radio" name="q11" value="b"> b. HDMI</label>
            <label><input type="radio" name="q11" value="c"> c. VGA</label>
        </div>
    </div>

    <div class="question">
        <p>Pregunta 12: ¿Qué componente es esencial para mostrar información en una computadora?</p>
        <div class="options">
            <label><input type="radio" name="q12" value="a"> a. Tarjeta de sonido</label>
            <label><input type="radio" name="q12" value="b"> b. Placa base</label>
            <label><input type="radio" name="q12" value="c"> c. Tarjeta gráfica</label>
        </div>
    </div>

    <div class="button-container">
        <button onclick="calcularPuntaje()">Calcular Puntaje</button>
    </div>

    <div class="result-container">
        <p id="puntaje"></p>
        <p id="respuestasIncorrectas" class="incorrect"></p>
    </div>
</div>

<script>
    function calcularPuntaje() {
        var puntaje = 0;
        var respuestas = ["b", "b", "c", "b", "b", "c", "b", "c", "b", "b", "a", "c"];
        var respuestasUsuario = [];

        for (var i = 1; i <= 12; i++) {
            var seleccion = document.querySelector('input[name="q' + i + '"]:checked');
            if (seleccion) {
                respuestasUsuario.push(seleccion.value);
                if (seleccion.value === respuestas[i - 1]) {
                    puntaje++;
                }
            } else {
                respuestasUsuario.push("");
            }
        }

        var resultado = "Puntaje: " + puntaje + " respuestas correctas de 12";
        document.getElementById("puntaje").innerHTML = resultado;

        // Mostrar respuestas incorrectas
        var respuestasIncorrectas = [];
        for (var i = 0; i < respuestas.length; i++) {
            if (respuestasUsuario[i] !== respuestas[i]) {
                respuestasIncorrectas.push("Pregunta " + (i + 1) + ": Tu respuesta - " + respuestasUsuario[i] + ", Respuesta correcta - " + respuestas[i]);
            }
        }

        var textoRespuestasIncorrectas = respuestasIncorrectas.length > 0 ? "Respuestas incorrectas: " + respuestasIncorrectas.join(", ") : "Todas las respuestas son correctas";
        document.getElementById("respuestasIncorrectas").innerHTML = textoRespuestasIncorrectas;
    }
</script>

</body>

</html>
