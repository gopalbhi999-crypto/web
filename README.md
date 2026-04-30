<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gopal's Education Portal</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
            background-color: #f4f7f6;
            margin: 0;
            padding: 50px;
        }
        h1 {
            color: #333;
        }
        .container {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            display: inline-block;
        }
        .btn-group {
            margin-top: 20px;
        }
        .btn {
            display: block;
            width: 200px;
            padding: 15px;
            margin: 10px auto;
            text-decoration: none;
            color: white;
            font-weight: bold;
            border-radius: 5px;
            transition: transform 0.2s, background-color 0.2s;
        }
        /* Alag-alag rang buttons ke liye */
        .physics { background-color: #3498db; }
        .chemistry { background-color: #e67e22; }
        .maths { background-color: #2ecc71; }

        .btn:hover {
            transform: scale(1.05);
            opacity: 0.9;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Namaste, Main Hoon Gopal</h1>
        <p>Meri PDF files download karne ke liye niche buttons par click karein:</p>

        <div class="btn-group">
            <a href="physics.pdf" class="btn physics" target="_blank">Physics PDF</a>
            <a href="chemistry.pdf" class="btn chemistry" target="_blank">Chemistry PDF</a>
            <a href="maths.pdf" class="btn maths" target="_blank">Maths PDF</a>
        </div>
    </div>

</body>
</html>
