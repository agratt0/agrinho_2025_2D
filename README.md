# agrinho_2025_2D
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DELLASINGS - Notícias</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
</head>
<body class="font-inter bg-gray-100">
    <div class="container mx-auto p-4 md:p-8">
        <header class="bg-white shadow-lg rounded-lg p-4 mb-8">
            <h1 class="text-4xl md:text-5xl font-extrabold text-center text-blue-800 mb-4">DELLASINGS</h1>
            <nav class="flex flex-wrap justify-center gap-4 text-lg md:text-xl font-semibold">
                <a href="#" class="text-gray-700 hover:text-blue-600 transition duration-300">NOTICIAS</a>
                <a href="#" class="text-gray-700 hover:text-blue-600 transition duration-300">QUE</a>
                <a href="#" class="text-gray-700 hover:text-blue-600 transition duration-300">FRANCO</a>
                <a href="#" class="text-gray-700 hover:text-blue-600 transition duration-300">PANCOLAS</a>
                <a href="#" class="text-gray-700 hover:text-blue-600 transition duration-300">EVABLERANCE</a>
            </nav>
        </header>

        <main class="grid grid-cols-1 lg:grid-cols-3 gap-8">
            <section class="lg:col-span-2 bg-white shadow-lg rounded-lg p-6">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-6 border-b-4 border-blue-500 pb-2">TOP-NEWS</h2>
                <div class="flex flex-col md:flex-row items-center md:items-start gap-6">
                    <div class="w-full md:w-1/2 flex-shrink-0">
                        <img src="https://placehold.co/600x400/ADD8E6/000000?text=Imagem+Destaque" alt="Imagem de Destaque" class="rounded-lg shadow-md w-full h-auto object-cover">
                    </div>
                    <div class="w-full md:w-1/2">
                        <h3 class="text-2xl md:text-3xl font-semibold text-gray-900 mb-3 leading-tight">Título da Notícia Principal Aqui</h3>
                        <p class="text-gray-700 leading-relaxed mb-4">
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                        </p>
                        <p class="text-gray-600 text-sm">Publicado em: 26 de Maio de 2025</p>
                        <a href="#" class="inline-block mt-4 px-6 py-2 bg-blue-600 text-white font-bold rounded-full hover:bg-blue-700 transition duration-300 shadow-md">Leia Mais</a>
                    </div>
                </div>
            </section>

            <aside class="bg-white shadow-lg rounded-lg p-6">
                <h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6 border-b-4 border-green-500 pb-2">Outras Notícias</h2>
                <ul class="space-y-4">
                    <li class="border-b pb-3 last:border-b-0">
                        <h3 class="text-xl font-semibold text-gray-800 mb-1">Título da Notícia Secundária 1</h3>
                        <p class="text-gray-600 text-sm">Breve descrição da notícia secundária. Lorem ipsum dolor sit amet...</p>
                        <a href="#" class="text-blue-500 hover:underline text-sm">Saiba mais</a>
                    </li>
                    <li class="border-b pb-3 last:border-b-0">
                        <h3 class="text-xl font-semibold text-gray-800 mb-1">Título da Notícia Secundária 2</h3>
                        <p class="text-gray-600 text-sm">Breve descrição da notícia secundária. Consectetur adipiscing elit...</p>
                        <a href="#" class="text-blue-500 hover:underline text-sm">Saiba mais</a>
                    </li>
                    <li class="border-b pb-3 last:border-b-0">
                        <h3 class="text-xl font-semibold text-gray-800 mb-1">Título da Notícia Secundária 3</h3>
                        <p class="text-gray-600 text-sm">Breve descrição da notícia secundária. Sed do eiusmod tempor...</p>
                        <a href="#" class="text-blue-500 hover:underline text-sm">Saiba mais</a>
                    </li>
                </ul>
            </aside>
        </main>

        <footer class="bg-gray-800 text-white text-center p-6 mt-8 rounded-lg shadow-lg">
            <p>&copy; 2025 DELLASINGS. Todos os direitos reservados.</p>
            <p class="text-sm mt-2">Desenvolvido com ❤️ e inspiração no seu esboço.</p>
        </footer>
    </div>
</body>
</html>