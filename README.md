<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Analyst Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.15/dist/tailwind.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Arial', sans-serif;
        }
    </style>
</head>

<body class="bg-gray-100">
    <!-- Navigation Bar -->
    <nav class="bg-blue-500 p-4 text-white">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-semibold">Data Analyst Portfolio</h1>
            <ul class="flex space-x-4">
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- About Section -->
    <section id="about" class="py-16">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-semibold mb-4">About Me</h2>
            <p class="text-gray-700">I am a passionate data analyst with expertise in data visualization and statistical analysis. I enjoy transforming raw data into meaningful insights.</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="bg-gray-200 py-16">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-semibold mb-4">Projects</h2>
            <!-- Add your projects here -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white p-4 shadow-md rounded">
                    <h3 class="text-xl font-semibold mb-2">Project 1</h3>
                    <p class="text-gray-700">Description of the project goes here.</p>
                </div>
                <div class="bg-white p-4 shadow-md rounded">
                    <h3 class="text-xl font-semibold mb-2">Project 2</h3>
                    <p class="text-gray-700">Description of the project goes here.</p>
                </div>
                <div class="bg-white p-4 shadow-md rounded">
                    <h3 class="text-xl font-semibold mb-2">Project 3</h3>
                    <p class="text-gray-700">Description of the project goes here.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-semibold mb-4">Contact Me</h2>
            <p class="text-gray-700">Feel free to get in touch with me. Email: example@example.com</p>
        </div>
    </section>

    <script src="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.15/dist/tailwind.min.js"></script>
</body>

</html>
