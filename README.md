<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Animada para Damián</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea, #764ba2);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }

        .container {
            background-color: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            text-align: center;
            animation: fadeIn 1s ease-out;
            margin: 20px;
            width: 90%;
            max-width: 600px;
        }

        h1 {
            font-size: 2.5rem;
            color: #333;
            margin: 0 0 10px;
            animation: slideIn 0.8s ease-out;
        }

        p {
            font-size: 1.2rem;
            color: #555;
            margin: 0 0 20px;
        }

        .button {
            background-color: #764ba2;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: transform 0.3s ease;
        }

        .button:hover {
            transform: scale(1.05);
            background-color: #667eea;
        }

        img {
            width: 100%;
            height: auto;
            border-radius: 15px;
            margin-top: 15px;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideIn {
            from { transform: translateY(-20px); }
            to { transform: translateY(0); }
        }
    </style>
</head>
<body>
    <audio autoplay loop>
        <source src="ninos_maravilla.mp3" type="audio/mpeg">
    </audio>    
    <div class="container">
        <h1>¡Hola, Damián!</h1>
        <p>Damián Rodríguez (mi pené), mi hermano de otra sangre, desde pequeños nadie nos separaba y no parábamos de experimentar cosas nuevas y de reírnos de cosas absurdas como la mua o el colacao, solo con hacer el gesto nos leemos la mente, y otra cosa nos gusta estudiar lo mismo pero yo he tenido el error de meterme en esta mierda, pero tranquilo que ya llegaré yo para hacerlo todo broza, no hay nada más que decir que disfrutes de tus 17 con los que quieres. Un abrazo hermano. ❤❤</p>
        <button class="button">¡Eres el mejor!</button>
        <img src="IMG.png" alt="Foto con amigos">
