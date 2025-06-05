<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Site</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6; /* Light gray background */
        }
        .container {
            max-width: 1200px;
        }
    </style>
</head>
<body class="antialiased text-gray-800">
    <!-- Header Section -->
    <header class="bg-gradient-to-r from-blue-600 to-indigo-700 text-white p-4 shadow-lg rounded-b-lg">
        <div class="container mx-auto flex justify-between items-center px-4">
            <h1 class="text-3xl font-bold rounded-lg p-2">My Awesome Site</h1>
            <nav>
                <ul class="flex space-x-6">
                    <li><a href="#" class="hover:text-blue-200 transition duration-300 ease-in-out font-medium">Home</a></li>
                    <li><a href="#about" class="hover:text-blue-200 transition duration-300 ease-in-out font-medium">About</a></li>
                    <li><a href="#contact" class="hover:text-blue-200 transition duration-300 ease-in-out font-medium">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Main Content Section -->
    <main class="container mx-auto mt-8 p-4">
        <section id="about" class="bg-white p-8 rounded-xl shadow-lg mb-8">
            <h2 class="text-4xl font-semibold mb-6 text-center text-gray-900">Welcome to Our Site!</h2>
            <div class="grid md:grid-cols-2 gap-8 items-center">
                <div class="space-y-4">
                    <p class="text-lg leading-relaxed text-gray-700">
                        This is a placeholder for basic information about your site. You can describe its purpose, what it offers, and what makes it unique.
                        Feel free to expand this section with more details about your mission, vision, or any services/products you provide.
                    </p>
                    <p class="text-lg leading-relaxed text-gray-700">
                        Our goal is to provide valuable content and a great user experience. We are constantly working to improve and expand our offerings to meet your needs.
                        Thank you for visiting!
                    </p>
                </div>
                <div class="relative w-full h-64 md:h-80 rounded-xl overflow-hidden shadow-md">
                    <!-- Placeholder Image with alt text for accessibility -->
                    <img
                        src="https://placehold.co/600x400/2563eb/ffffff?text=Site+Information"
                        alt="Placeholder image for site information"
                        class="w-full h-full object-cover rounded-xl"
                        onerror="this.onerror=null;this.src='https://placehold.co/600x400/ccc/333?text=Image+Unavailable';"
                    >
                </div>
            </div>
        </section>

        <section id="contact" class="bg-white p-8 rounded-xl shadow-lg">
            <h2 class="text-3xl font-semibold mb-6 text-center text-gray-900">Contact Us</h2>
            <div class="flex flex-col items-center">
                <p class="text-lg text-gray-700 mb-4">
                    If you have any questions or need further information, please don't hesitate to reach out.
                </p>
                <div class="flex items-center space-x-3 bg-blue-100 p-4 rounded-lg shadow-inner">
                    <svg class="w-6 h-6 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8m-2 1a2 2 0 00-2-2H7a2 2 0 00-2 2v6a2 2 0 002 2h10a2 2 0 002-2V9z"></path></svg>
                    <span class="text-xl font-medium text-blue-800">Email: <a href="mailto:githubpages20124j01@outlook.com" class="text-blue-600 hover:underline">githubpages20124j01@outlook.com</a></span>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer Section -->
    <footer class="bg-gray-800 text-white p-4 mt-8 shadow-inner rounded-t-lg">
        <div class="container mx-auto text-center text-sm px-4">
            &copy; 2024 My Awesome Site. All rights reserved.
        </div>
    </footer>
</body>
</html>
