<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="AHzCapital is a leading venture capital firm investing in transformative technologies like AI, blockchain, and decentralized systems.">
    <title>AHzCapital | Transformative Venture Capital</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="font-sans text-gray-300 bg-gray-900">
    <!-- Navigation -->
    <nav class="bg-gray-800 text-white sticky top-0 z-50 shadow-lg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center py-4">
                <a href="#" class="text-2xl font-bold">AHzCapital</a>
                <ul class="flex space-x-6 text-lg">
                    <li><a href="#about" class="hover:text-teal-400 transition">About</a></li>
                    <li><a href="#focus" class="hover:text-teal-400 transition">Focus</a></li>
                    <li><a href="#portfolio" class="hover:text-teal-400 transition">Portfolio</a></li>
                    <li><a href="#contact" class="hover:text-teal-400 transition">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="h-[80vh] bg-gradient-to-r from-gray-900 via-gray-700 to-gray-900 relative">
        <div class="absolute inset-0 bg-cover bg-center opacity-50" style="background-image: url('https://cdn.pixabay.com/photo/2024/03/13/19/06/ai-generated-8631634_1280.jpg');" alt="Futuristic cityscape"></div>
        <div class="relative flex items-center justify-center h-full text-center text-white">
            <div class="max-w-4xl">
                <h1 class="text-5xl font-bold mb-4">AHzCapital</h1>
                <p class="text-xl mb-6">Investing in the Tech that will host the future, investing in the winners</p>
                <a href="#portfolio" class="px-6 py-3 bg-teal-500 text-white rounded-lg shadow hover:bg-teal-400 transition">Discover Our Portfolio</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-gray-800">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-white mb-6">About Us</h2>
            <p class="text-lg text-gray-300 leading-relaxed">
                AHzCapital is a leading Private venture capital firm specializing in transformative technologies. We invest with a long term vision in the future of artificial intelligence, blockchain infrastructure, and decentralized protocols and Layers that will Host the new  world and makke it a better place. 
            </p>
        </div>
    </section>

    <!-- Focus Section -->
    <section id="focus" class="py-16 bg-gray-800">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-white mb-6">Investment Focus</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-gray-700 shadow-lg rounded-lg p-6 hover:shadow-xl transition">
                    <h3 class="text-xl font-bold mb-2 text-white">AI/ML Infrastructure</h3>
                    <p class="text-gray-300">Next-generation machine learning platforms and AI-first companies.</p>
                </div>
                <div class="bg-gray-700 shadow-lg rounded-lg p-6 hover:shadow-xl transition">
                    <h3 class="text-xl font-bold mb-2 text-white">Blockchain Protocol</h3>
                    <p class="text-gray-300">Blockchain infrastructure</p>
                </div>
                <div class="bg-gray-700 shadow-lg rounded-lg p-6 hover:shadow-xl transition">
                    <h3 class="text-xl font-bold mb-2 text-white">Web3 Ecosystem</h3>
                    <p class="text-gray-300">Decentralized applications and infrastructure.</p>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-16 bg-gray-800 text-gray-300">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-white mb-6">Portfolio Investments</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="bg-gray-700 p-6 rounded-lg shadow-md hover:shadow-xl transition">
                    <h3 class="text-xl font-bold mb-2 text-white">DeepMind Analytics</h3>
                    <p class="text-gray-300">AI-powered predictive analytics platform.</p>
                </div>
                <div class="bg-gray-700 p-6 rounded-lg shadow-md hover:shadow-xl transition">
                    <h3 class="text-xl font-bold mb-2 text-white"><a href="https://quilibrium.com" target="_blank" class="hover:underline">Quilibrium</a></h3>
                    <p class="text-gray-300">The Interent Layer | The Layer of everything</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-gray-800">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-white mb-6">Contact Us</h2>
            <form class="bg-gray-700 p-6 rounded-lg shadow-lg space-y-4">
                <div>
                    <label for="name" class="block text-gray-300 font-bold">Name</label>
                    <input type="text" id="name" name="name" class="w-full border border-gray-600 bg-gray-800 text-gray-300 rounded-lg p-2" placeholder="Your Name">
                </div>
                <div>
                    <label for="email" class="block text-gray-300 font-bold">Email</label>
                    <input type="email" id="email" name="email" class="w-full border border-gray-600 bg-gray-800 text-gray-300 rounded-lg p-2" placeholder="Your Email">
                </div>
                <div>
                    <label for="message" class="block text-gray-300 font-bold">Message</label>
                    <textarea id="message" name="message" class="w-full border border-gray-600 bg-gray-800 text-gray-300 rounded-lg p-2" rows="4" placeholder="Your Message"></textarea>
                </div>
                <button type="submit" class="px-6 py-3 bg-teal-500 text-white rounded-lg shadow hover:bg-teal-400 transition">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-gray-400 py-6">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <p>&copy; 2025 AHzCapital. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
