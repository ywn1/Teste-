# Teste-The HTML structure and styling for the "Up Ultra Performance" webpage look well-organized and visually appealing. Here is the complete code encapsulated in a file:

```html name=index.html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Up Ultra Performance</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        .hero {
            background-image: url('https://via.placeholder.com/1500x600');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 80px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 3em;
        }

        .products {
            display: flex;
            justify-content: space-around;
            margin: 40px 0;
        }

        .product {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
            width: 30%;
            text-align: center;
        }

        .product img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }

        .product h2 {
            font-size: 1.5em;
            color: #333;
        }

        .cta {
            text-align: center;
            margin: 40px 0;
        }

        .cta button {
            padding: 15px 30px;
            font-size: 1.2em;
            color: white;
            background-color: #333;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .cta button:hover {
            background-color: #555;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .social-links {
            list-style: none;
            padding: 0;
        }

        .social-links li {
            display: inline;
            margin: 0 10px;
        }

        .social-links a {
            color: white;
            text-decoration: none;
            font-size: 1.5em;
        }

        .form-container {
            background-color: #fff;
            padding: 40px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            width: 80%;
            max-width: 600px;
            border-radius: 8px;
        }

        .form-container input,
        .form-container textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        .form-container button {
            width: 100%;
            padding: 15px;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .form-container button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>

<header>
    <h1>Up Ultra Performance</h1>
</header>

<div class="hero">
    <h1>Transforme seu desempenho com Up Ultra Performance!</h1>
    <p>Potencialize seus resultados com nossos produtos de alta qualidade.</p>
</div>

<div class="products">
    <div class="product">
        <img src="https://via.placeholder.com/400x300" alt="Produto 1">
        <h2>Produto 1</h2>
        <p>Descrição do produto 1.</p>
    </div>
    <div class="product">
        <img src="https://via.placeholder.com/400x300" alt="Produto 2">
        <h2>Produto 2</h2>
        <p>Descrição do produto 2.</p>
    </div>
    <div class="product">
        <img src="https://via.placeholder.com/400x300" alt="Produto 3">
        <h2>Produto 3</h2>
        <p>Descrição do produto 3.</p>
    </div>
</div>

<div class="cta">
    <button>Compre Agora</button>
</div>

<section class="form-container">
    <h2>Fale Conosco</h2>
    <form action="#" method="post">
        <input type="text" name="nome" placeholder="Seu nome" required>
        <input type="email" name="email" placeholder="Seu e-mail" required>
        <textarea name="mensagem" placeholder="Sua mensagem" rows="4" required></textarea>
        <button type="submit">Enviar</button>
    </form>
</section>

<footer>
    <p>&copy; 2025 Up Ultra Performance. Todos os direitos reservados.</p>
    <ul class="social-links">
        <li><a href="https://www.instagram.com" target="_blank">Instagram</a></li>
        <li><a href="https://www.facebook.com" target="_blank">Facebook</a></li>
    </ul>
</footer>

</body>
</html>
```
