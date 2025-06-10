# Waste-food-management-system-
WasteZero
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Waste Food Management System</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
</head>
<body class="bg-gray-50 font-sans">
    <!-- Header -->
    <header class="bg-green-700 text-white sticky top-0 z-50 shadow-md">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <div class="flex items-center">
                <img src="https://via.placeholder.com/40" alt="Logo" class="mr-2" aria-hidden="true">
                <h1 class="text-2xl font-bold">WasteZero</h1>
            </div>
            <nav aria-label="Main navigation">
                <ul class="flex space-x-6">
                    <li><a href="#home" class="hover:text-green-200 transition-colors">Home</a></li>
                    <li><a href="#features" class="hover:text-green-200 transition-colors">Features</a></li>
                    <li><a href="#testimonials" class="hover:text-green-200 transition-colors">Testimonials</a></li>
                    <li><a href="#contact" class="hover:text-green-200 transition-colors">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="bg-gradient-to-r from-green-100 to-green-200 py-24">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-5xl font-extrabold mb-6 text-gray-800">Transform Food Waste into Opportunity</h2>
            <p class="text-xl mb-8 text-gray-600 max-w-2xl mx-auto">Join WasteZero to manage surplus food, donate to communities in need, and drive sustainability with our innovative platform.</p>
            <a href="#contact" class="bg-green-600 text-white px-8 py-4 rounded-lg hover:bg-green-700 transition-colors text-lg font-semibold">Start Reducing Waste</a>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-12 text-gray-800">Our Solutions</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-gray-50 p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow">
                    <i class="fas fa-utensils text-4xl text-green-600 mb-4"></i>
                    <h3 class="text-2xl font-semibold mb-4 text-gray-800">Food Donation Network</h3>
                    <p class="text-gray-600">Seamlessly connect restaurants, grocery stores, and individuals with local charities to donate surplus food, reducing waste and feeding those in need.</p>
                </div>
                <div class="bg-gray-50 p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow">
                    <i class="fas fa-clipboard-list text-4xl text-green-600 mb-4"></i>
                    <h3 class="text-2xl font-semibold mb-4 text-gray-800">Smart Inventory Management</h3>
                    <p class="text-gray-600">Track food stock, monitor expiration dates, and receive alerts to prevent waste with our intuitive inventory tools.</p>
                </div>
                <div class="bg-gray-50 p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow">
                    <i class="fas fa-users text-4xl text-green-600 mb-4"></i>
                    <h3 class="text-2xl font-semibold mb-4 text-gray-800">Community Collaboration</h3>
                    <p class="text-gray-600">Engage with a community of businesses and volunteers dedicated to sustainability and zero-waste initiatives.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-20 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-12 text-gray-800">What Our Users Say</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="bg-white p-8 rounded-xl shadow-lg">
                    <p class="text-gray-600 mb-4">"WasteZero helped our restaurant reduce food waste by 40% and connect with local shelters. It's a game-changer!"</p>
                    <p class="font-semibold text-gray-800">Jane Doe, Restaurant Owner</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-lg">
                    <p class="text-gray-600 mb-4">"The inventory tracking feature is fantastic. We now manage our stock better and donate before food expires."</p>
                    <p class="font-semibold text-gray-800">John Smith, Grocery Manager</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-12 text-gray-800">Get in Touch</h2>
            <div class="max-w-lg mx-auto">
                <div class="bg-gray-50 p-8 rounded-xl shadow-lg">
                    <div class="mb-6">
                        <label for="name" class="block text-sm font-medium text-gray-700">Full Name</label>
                        <input type="text" id="name" class="w-full p-3 border rounded-lg focus:ring-2 focus:ring-green-600" placeholder="Your Full Name" required aria-required="true">
                    </div>
                    <div class="mb-6">
                        <label for="email" class="block text-sm font-medium text-gray-700">Email Address</label>
                        <input type="email" id="email" class="w-full p-3 border rounded-lg focus:ring-2 focus:ring-green-600" placeholder="your.email@example.com" required aria-required="true">
                    </div>
                    <div class="mb-6">
                        <label for="organization" class="block text-sm font-medium text-gray-700">Organization (Optional)</label>
                        <input type="text" id="organization" class="w-full p-3 border rounded-lg focus:ring-2 focus:ring-green-600" placeholder="Your Organization">
                    </div>
                    <div class="mb-6">
                        <label for="message" class="block text-sm font-medium text-gray-700">Your Message</label>
                        <textarea id="message" class="w-full p-3 border rounded-lg focus:ring-2 focus:ring-green-600" rows="5" placeholder="Tell us how we can help" required aria-required="true"></textarea>
                    </div>
                    <button class="bg-green-600 text-white px-8 py-3 rounded-lg hover:bg-green-700 transition-colors w-full font-semibold">Send Message</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-green-700 text-white py-10">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">WasteZero</h3>
                    <p class="text-gray-200">Empowering communities to reduce food waste and promote sustainability.</p>
                </div>
                <div>
                    <h3 class="text-xl font-bold mb-4">Quick Links</h3>
                    <ul class="space-y-2">
                        <li><a href="#home" class="hover:text-green-200 transition-colors">Home</a></li>
                        <li><a href="#features" class="hover:text-green-200 transition-colors">Features</a></li>
                        <li><a href="#testimonials" class="hover:text-green-200 transition-colors">Testimonials</a></li>
                        <li><a href="#contact" class="hover:text-green-200 transition-colors">Contact</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-xl font-bold mb-4">Follow Us</h3>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-200 hover:text-white transition-colors"><i class="fab fa-facebook-f text-xl"></i></a>
                        <a href="#" class="text-gray-200 hover:text-white transition-colors"><i class="fab fa-twitter text-xl"></i></a>
                        <a href="#" class="text-gray-200 hover:text-white transition-colors"><i class="fab fa-instagram text-xl"></i></a>
                    </div>
                </div>
            </div>
            <div class="mt-8 text-center">
                <p class="text-gray-200">© 2025 WasteZero. All rights reserved.</p>
            </div>
        </div>
    </footer>
</body>
</html>
