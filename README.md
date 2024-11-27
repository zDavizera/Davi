<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biblioteca Online</title>
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
            padding: 1rem;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 1rem;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 1rem;
            background-color: #fff;
        }
        .book-list {
            display: flex;
            flex-wrap: wrap;
        }
        .book {
            border: 1px solid #ddd;
            margin: 1rem;
            padding: 1rem;
            width: 200px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Biblioteca Online</h1>
        <nav>
            <ul>
                <li><a href="#">Início</a></li>
                <li><a href="#">Livros</a></li>
                <li><a href="#">Sobre</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>
    <div class="container">
        <h2>Livros Disponíveis</h2>
        <div class="book-list">
            <div class="book">
                <h3>Título do Livro
