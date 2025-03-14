<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Magazin Online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }

        .product {
            float: left;
            width: 30%;
            padding: 20px;
            margin: 10px;
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .product img {
            width: 100%;
            height: auto;
            border-bottom: 2px solid #ddd;
            margin-bottom: 15px;
        }

        .product h3 {
            color: #333;
        }

        .product p {
            color: #666;
        }

        .product .price {
            font-size: 1.2em;
            color: #28a745;
            font-weight: bold;
            margin: 10px 0;
        }

        .product button {
            background-color: #007bff;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 5px;
            font-size: 16px;
        }

        .product button:hover {
            background-color: #0056b3;
        }

        footer {
            background-color: #333;
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
    <div class="container">
        <h1>Magazin Online</h1>
        <nav>
            <a href="#home" style="color: white; margin: 0 15px; text-decoration: none;">Acasă</a>
            <a href="#shop" style="color: white; margin: 0 15px; text-decoration: none;">Produse</a>
            <a href="#contact" style="color: white; margin: 0 15px; text-decoration: none;">Contact</a>
        </nav>
    </div>
</header>

<div id="shop" class="container">
    <h2 style="text-align: center; margin: 20px 0;">Produse</h2>
    <div class="product">
        <img src="https://via.placeholder.com/200" alt="Produs 1">
        <h3>Produs 1</h3>
        <p>Descriere scurtă a produsului 1.</p>
        <div class="price">150 RON</div>
        <button>Adaugă în coș</button>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/200" alt="Produs 2">
        <h3>Produs 2</h3>
        <p>Descriere scurtă a produsului 2.</p>
        <div class="price">200 RON</div>
        <button>Adaugă în coș</button>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/200" alt="Produs 3">
        <h3>Produs 3</h3>
        <p>Descriere scurtă a produsului 3.</p>
        <div class="price">120 RON</div>
        <button>Adaugă în coș</button>
    </div>
</div>

<footer>
    <p>&copy; 2025 Magazin Online. Toate drepturile rezervate.</p>
</footer>

</body>
</html>
