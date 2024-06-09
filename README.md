# Eisdiele1
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unbenannte Eisdiele</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff69b4;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            padding: 20px;
        }
        h1 {
            color: #ff69b4;
        }
        .eissorten {
            list-style-type: none;
            padding: 0;
        }
        .eissorten li {
            background-color: #ffebcd;
            border: 1px solid #ddd;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }
        footer {
            background-color: #ff69b4;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Willkommen in unserer Eisdiele</h1>
        <p>Handgemachtes Eis, frisch und einzigartig!</p>
    </header>
    <div class="container">
        <h2>Unsere Eissorten</h2>
        <ul class="eissorten">
            <li>Sternchenoma</li>
            <li>Roblox-Bacon</li>
            <li>Fatmagalaxy</li>
            <li>Mein Rücken ist keine Mailbox</li>
            <li>Erdbeere</li>
            <li>Salmonellen</li>
            <li>Spinat</li>
        </ul>
        <h2>Vorbestellung</h2>
        <p>Da unser Eis handgemacht ist, dauert es ein wenig, bis es fertig ist. Sie können Ihr Eis hier vorbestellen:</p>
        <form action="mailto:info@unbenannte-eisdiele.de" method="post" enctype="text/plain">
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">E-Mail:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="sorten">Gewünschte Eissorten:</label><br>
            <textarea id="sorten" name="sorten" rows="4" required></textarea><br><br>
            <input type="submit" value="Vorbestellen">
        </form>
    </div>
    <footer>
        <p>Adresse: Sternchenoma Allee 190, 41430 Roblox</p>
    </footer>
</body>
</html>

