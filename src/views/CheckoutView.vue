<template>
     <div class="container">
        <h1>Formulário de Checkout</h1>
        <form action="#" method="post">
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="celular">Celular:</label>
            <input type="tel" id="celular" name="celular" required>

            <label for="data_saida">Data de Saída:</label>
            <input type="date" id="data_saida" name="data_saida" required>

            <label>
                <input type="checkbox" id="receber_ofertas" name="receber_ofertas">
                Aceito receber ofertas por mensagem
            </label>

            <button type="submit">Fazer Checkout</button>
        </form>
    </div>
</template>

<style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
        }

        .container {
            max-width: 600px;
            margin: 40px auto 40px auto;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
        }

        label {
            display: block;
            margin-bottom: 5px;
        }

        input[type="text"],
        input[type="tel"],
        input[type="date"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        input[type="checkbox"] {
            margin-bottom: 15px;
        }

        button {
            background-color: #007BFF;
            color: #fff;
            border: none;
            border-radius: 5px;
            padding: 10px 20px;
            cursor: pointer;
        }

        button:hover {
            background-color: #0056b3;
        }
    </style>