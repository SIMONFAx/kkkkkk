<!DOCTYPE html> <html lang="es"> <head> <meta charset="UTF-8"> <meta name="viewport"
                                                                 content="width=device-width, initial-scale=1.0"> 
  <title>Página Interactiva</title> <style> body { font-famil
    y: Arial, sans-serif; background-color: #000; color: #fff; margin: 0; pad
    ding: 0; display: flex; flex-direction: co
    lumn; align-items: cen
    ter; } header { width: 100%; background-color: #333; padding: 10px 
    0; text-align: center; } header nav a {
    color: #fff; text-decoration: none; margin: 0 15px; } .content { padding: 20px; max-width: 800px; text-align: ce{nter; } .brillo { font-size: 2em; color: #00e6e6; text-shadow: 0 0 5px #00e6e6, 0 0 10px
    #00e6e6, 0 0 20px #00e6e6, 0 0 40px #00e6e6, 0 0 80px #00e6e6; animation: brillo-efecto 2s infinite alternate; } @keyframes 
    brillo-efecto { from { opacity: 1; } to { opacity: 0.6; } } .animation-box { width: 100px; height: 100px; background-color: #00e6e6; 
                                                                                                                                                                                               margin: 20px auto; animation: mover 5s infinite; } @keyframe
    s mover { 0% { transform: translateX(0); } 50% { transform: translateX(200px); } 100%
    { transform: translateX(0); } } footer { width: 100%; background-color: #333; padding: 10px 0; text-align: center; position: 
    absolute; bottom: 0; } </style> </head> <body> <header> <n
                                                                                                                                                                                     av> <a href="#inicio">Inicio</a> <a href="#contenido">Contenido</a> <a href="#contacto">Contacto</a> </nav>
    </header> <div class="content"> <h1 class="brillo">¡Bienvenido 
                                                                                                                                                                                                                             
  r.</p> <div class="animation-box"></div> </div> <footer> 
  <p>&copy; 2024 Página Interactiva</p> </footer> <script> // Puedes añadir funcionalidades adicionales con JavaScript aquí document.addEventListener('DOMConten

<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saludo y Adjuntar Imágenes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            text-align: center;
            width: 100%;
        }
        main {
            margin: 20px;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0,
  <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario con Todo Tipo de Entradas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        main {
            margin: 20px;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
            width: 100%;
            max-width: 600px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
        input, select, textarea, button {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 1em;
        }
        button {
            background-color: #4CAF50;
            color: white;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <main>
        <h1>Formulario con Todo Tipo de Entradas</h1>
        <form id="full-inputs-form">
            <div class="form-group">
                <label for="text-input">Texto:</label>
                <input type="text" id="text-input" name="text-input" required>
            </div>
            <div class="form-group">
                <label for="email-input">Email:</label>
                <input type="email" id="email-input" name="email-input" required>
            </div>
            <div class="form-group">
                <label for="password-input">Contraseña:</label>
                <input type="password" id="password-input" name="password-input" required>
            </div>
            <div class="form-group">
                <label for="number-input">Número:</label>
                <input type="number" id="number-input" name="number-input" required>
            </div>
            <div class="form-group">
                <label for="date-input">Fecha:</label>
                <input type="date" id="date-input" name="date-input" required>
            </div>
            <div class="form-group">
                <label for="time-input">Hora:</label>
                <input type="time" id="time-input" name="time-input" required>
            </div>
            <div class="form-group">
                <label for="color-input">Color:</label>
                <input type="color" id="color-input" name="color-input" required>
            </div>
            <div class="form-group">
                <label for="range-input">Rango:</label>
                <input type="range" id="range-input" name="range-input" min="0" max="100" required>
            </div>
            <div class="form-group">
                <label for="checkbox-input">Checkbox:</label>
                <input type="checkbox" id="checkbox-input" name="checkbox-input">
            </div>
            <div class="form-group">
                <label for="radio-input">Radio:</label>
                <input type="radio" id="radio-input" name="radio-group" value="opcion1"> Opción 1
                <input type="radio" id="radio-input" name="radio-group" value="opcion2"> Opción 2
            </div>
            <div class="form-group">
                <label for="file-input">Archivo:</label>
                <input type="file" id="file-input" name="file-input" multiple>
            </div>
            <div class="form-group">
                <label for="select-input">Seleccionar:</label>
                <select id="select-input" name="select-input" required>
                    <option value="opcion1">Opción 1</option>
                    <option value="opcion2">Opción 2</option>
                    <option value="opcion3">Opción 3</option>
                </select>
            </div>
            <div class="form-group">
                <label for="textarea-input">Área de texto:</label>
                <textarea id="textarea-input" name="textarea-input" rows="4" required></textarea>
            </div>
            <button type="submit">Enviar</button>
        </form>
    </main>
</body>
</html>
const { Client, GatewayIntentBits } = require('discord.js');
const client = new Client({ intents: [GatewayIntentBits.Guilds, GatewayIntentBits.GuildMessages, GatewayIntentBits.MessageContent] });

const prefix = '!';

client.once('ready', () => {
    console.log('Bot is online!');
});

client.on('messageCreate', message => {
    if (!message.content.startsWith(prefix) || message.author.bot) return;

  const args = message.content.slice(prefix.length).trim().split(/ +/);
    const command = args.shift().toLowerCase();

  if (command === 'saludar') {
        message.channel.send(`¡Hola, ${message.author.username}!`);
    } else if (command === 'hora') {
        const date = new Date();
        message.channel.send(`La hora actual es ${date.toLocaleTimeString()}.`);
    } else if (command === 'adjuntar') {
        message.channel.send('Aquí tienes una imagen:', {
            files: ['https://via.placeholder.com/150']
        });
    } else if (command === 'tarea') {
        // Aquí puedes agregar más tareas personalizadas
        message.channel.send('Ejecutando tarea personalizada...');
    }
});

// Inicia sesión con el token de tu bot
client.login('TU_TOKEN_DEL_BOT');

