- 👋 Hi, I’m @beto5820
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
beto5820/beto5820 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>App de Vendas Afiliado</title>
    <style>
        /* CSS incorporado */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }

        #product-list {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            padding: 20px;
            justify-content: center;
        }

        .product {
            border: 1px solid #ccc;
            padding: 15px;
            width: 200px;
            text-align: center;
            border-radius: 5px;
        }

        .product img {
            max-width: 100%;
            height: auto;
        }

        button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <header>
        <h1>App de Vendas Afiliado</h1>
    </header>
    
    <section id="product-list">
        <!-- Lista de produtos será carregada aqui -->
    </section>

    <footer>
        <p>&copy; 2024 - App de Vendas Afiliado</p>
    </footer>

    <script>
        // JavaScript incorporado
        document.addEventListener('DOMContentLoaded', () => {
            const productList = document.getElementById('product-list');

            // Lista de produtos de exemplo
            const products = [
                {
                    id: 1,
                    name: "Produto Exemplo 1",
                    price: "R$ 99,90",
                    imageUrl: "https://via.placeholder.com/150",
                    affiliateLink: "https://www.example.com/produto1"
                },
                {
                    id: 2,
                    name: "Produto Exemplo 2",
                    price: "R$ 59,90",
                    imageUrl: "https://via.placeholder.com/150",
                    affiliateLink: "https://www.example.com/produto2"
                }
            ];

            // Exibe produtos na página
            function displayProducts(products) {
                productList.innerHTML = ''; // Limpa a lista de produtos
                products.forEach(product => {
                    const productElement = document.createElement('div');
                    productElement.classList.add('product');
                    productElement.innerHTML = `
                        <img src="${product.imageUrl}" alt="${product.name}">
                        <h2>${product.name}</h2>
                        <p>${product.price}</p>
                        <a href="${product.affiliateLink}" target="_blank">
                            <button>Comprar</button>
                        </a>
                    `;
                    productList.appendChild(productElement);
                });
            }

            // Chama a função para exibir os produtos
            displayProducts(products);
        });
    </script>
</body>
</html>

--->
