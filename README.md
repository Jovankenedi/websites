<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechFix Pro - Computer Repair Services</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .hero-gradient {
            background: linear-gradient(135deg, #2563eb 0%, #1e40af 100%);
        }
        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .testimonial-card {
            transition: all 0.3s ease;
        }
        .testimonial-card:hover {
            transform: scale(1.03);
        }
        .contact-input:focus {
            outline: none;
            box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.3);
        }
    </style>
</head>
<body class="font-sans antialiased text-gray-800">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <div class="flex-shrink-0 flex items-center">
                        <i class="fas fa-laptop-code text-blue-600 text-2xl mr-2"></i>
                        <span class="text-xl font-bold text-blue-600">TechFix Pro</span>
                    </div>
                </div>
                <div class="hidden md:ml-6 md:flex md:items-center md:space-x-8">
                    <a href="#services" class="text-gray-900 hover:text-blue-600 px-3 py-2 text-sm font-medium">Services</a>
                    <a href="#pricing" class="text-gray-900 hover:text-blue-600 px-3 py-2 text-sm font-medium">Pricing</a>
                    <a href="#about" class="text-gray-900 hover:text-blue-600 px-3 py-2 text-sm font-medium">About</a>
                    <a href="#testimonials" class="text-gray-900 hover:text-blue-600 px-3 py-2 text-sm font-medium">Testimonials</a>
                    <a href="#contact" class="bg-blue-600 text-white px-4 py-2 rounded-md text-sm font-medium hover:bg-blue-700 transition duration-300">Book Now</a>
                </div>
                <div class="-mr-2 flex items-center md:hidden">
                    <button id="mobile-menu-button" class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none">
                        <i class="fas fa-bars"></i>
                    </button>
                </div>
            </div>
        </div>
        
        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden md:hidden">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#services" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Services</a>
                <a href="#pricing" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Pricing</a>
                <a href="#about" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">About</a>
                <a href="#testimonials" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Testimonials</a>
                <a href="#contact" class="block w-full text-center bg-blue-600 text-white px-4 py-2 rounded-md text-base font-medium hover:bg-blue-700 transition duration-300">Book Now</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-gradient text-white">
        <div class="max-w-7xl mx-auto py-24 px-4 sm:px-6 lg:px-8">
            <div class="lg:grid lg:grid-cols-2 lg:gap-8 items-center">
                <div class="mb-12 lg:mb-0">
                    <h1 class="text-4xl md:text-5xl font-extrabold tracking-tight mb-6">
                        Expert Computer Repair Services
                    </h1>
                    <p class="text-xl md:text-2xl mb-8 opacity-90">
                        Fast, reliable, and affordable solutions for all your tech problems. Serving the community since 2010.
                    </p>
                    <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
                        <a href="#contact" class="bg-white text-blue-600 px-6 py-3 rounded-md text-lg font-semibold hover:bg-gray-100 transition duration-300 text-center">
                            Get a Free Quote
                        </a>
                        <a href="tel:+1234567890" class="border-2 border-white px-6 py-3 rounded-md text-lg font-semibold hover:bg-white hover:text-blue-600 transition duration-300 text-center">
                            <i class="fas fa-phone mr-2"></i> (123) 456-7890
                        </a>
                    </div>
                </div>
                <div class="relative">
                    <img src="https://images.unsplash.com/photo-1558494949-ef010cbdcc31?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=774&q=80" 
                         alt="Computer repair" 
                         class="rounded-lg shadow-2xl w-full h-auto">
                    <div class="absolute -bottom-6 -right-6 bg-yellow-400 text-gray-900 px-6 py-3 rounded-lg shadow-lg">
                        <div class="text-sm font-semibold">24/7 Emergency Service</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="bg-gray-50 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div class="p-4">
                    <div class="text-4xl font-bold text-blue-600 mb-2">10+</div>
                    <div class="text-gray-600 font-medium">Years Experience</div>
                </div>
                <div class="p-4">
                    <div class="text-4xl font-bold text-blue-600 mb-2">5,000+</div>
                    <div class="text-gray-600 font-medium">Happy Customers</div>
                </div>
                <div class="p-4">
                    <div class="text-4xl font-bold text-blue-600 mb-2">24/7</div>
                    <div class="text-gray-600 font-medium">Support Available</div>
                </div>
                <div class="p-4">
                    <div class="text-4xl font-bold text-blue-600 mb-2">1 hr</div>
                    <div class="text-gray-600 font-medium">Response Time</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">
                    Our Computer Services
                </h2>
                <p class="mt-4 max-w-2xl text-xl text-gray-600 mx-auto">
                    Comprehensive solutions for all your computer needs
                </p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="service-card bg-white rounded-lg shadow-md overflow-hidden transition duration-300 ease-in-out">
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="flex-shrink-0 bg-blue-100 p-3 rounded-full">
                                <i class="fas fa-desktop text-blue-600 text-xl"></i>
                            </div>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">Hardware Repair</h3>
                        <p class="text-gray-600 mb-4">
                            From screen replacements to motherboard repairs, we fix all hardware issues with precision and care.
                        </p>
                        <ul class="space-y-2 text-gray-600">
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Laptop & Desktop Repairs</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Component Replacement</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Diagnostic Services</span>
                            </li>
                        </ul>
                    </div>
                </div>
                
                <!-- Service 2 -->
                <div class="service-card bg-white rounded-lg shadow-md overflow-hidden transition duration-300 ease-in-out">
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="flex-shrink-0 bg-blue-100 p-3 rounded-full">
                                <i class="fas fa-shield-alt text-blue-600 text-xl"></i>
                            </div>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">Virus Removal</h3>
                        <p class="text-gray-600 mb-4">
                            Protect your data and restore your computer's performance with our thorough virus removal services.
                        </p>
                        <ul class="space-y-2 text-gray-600">
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Malware & Spyware Removal</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>System Optimization</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Preventative Measures</span>
                            </li>
                        </ul>
                    </div>
                </div>
                
                <!-- Service 3 -->
                <div class="service-card bg-white rounded-lg shadow-md overflow-hidden transition duration-300 ease-in-out">
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="flex-shrink-0 bg-blue-100 p-3 rounded-full">
                                <i class="fas fa-database text-blue-600 text-xl"></i>
                            </div>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">Data Recovery</h3>
                        <p class="text-gray-600 mb-4">
                            Accidentally deleted files? Hard drive crashed? We specialize in recovering your precious data.
                        </p>
                        <ul class="space-y-2 text-gray-600">
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Deleted File Recovery</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Hard Drive Recovery</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>RAID Recovery</span>
                            </li>
                        </ul>
                    </div>
                </div>
                
                <!-- Service 4 -->
                <div class="service-card bg-white rounded-lg shadow-md overflow-hidden transition duration-300 ease-in-out">
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="flex-shrink-0 bg-blue-100 p-3 rounded-full">
                                <i class="fas fa-network-wired text-blue-600 text-xl"></i>
                            </div>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">Network Solutions</h3>
                        <p class="text-gray-600 mb-4">
                            Home or office network setup, troubleshooting, and optimization for seamless connectivity.
                        </p>
                        <ul class="space-y-2 text-gray-600">
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Wi-Fi Setup & Optimization</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Network Security</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Business Network Solutions</span>
                            </li>
                        </ul>
                    </div>
                </div>
                
                <!-- Service 5 -->
                <div class="service-card bg-white rounded-lg shadow-md overflow-hidden transition duration-300 ease-in-out">
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="flex-shrink-0 bg-blue-100 p-3 rounded-full">
                                <i class="fas fa-tools text-blue-600 text-xl"></i>
                            </div>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">PC Tune-Up</h3>
                        <p class="text-gray-600 mb-4">
                            Give your computer a new lease on life with our comprehensive tune-up service.
                        </p>
                        <ul class="space-y-2 text-gray-600">
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>System Cleaning</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Software Updates</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Performance Optimization</span>
                            </li>
                        </ul>
                    </div>
                </div>
                
                <!-- Service 6 -->
                <div class="service-card bg-white rounded-lg shadow-md overflow-hidden transition duration-300 ease-in-out">
                    <div class="p-6">
                        <div class="flex items-center mb-4">
                            <div class="flex-shrink-0 bg-blue-100 p-3 rounded-full">
                                <i class="fas fa-home text-blue-600 text-xl"></i>
                            </div>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">On-Site Support</h3>
                        <p class="text-gray-600 mb-4">
                            Can't bring your computer to us? We'll come to you with our convenient on-site service.
                        </p>
                        <ul class="space-y-2 text-gray-600">
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Home & Office Visits</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Business IT Support</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Emergency Services</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">
                    Transparent Pricing
                </h2>
                <p class="mt-4 max-w-2xl text-xl text-gray-600 mx-auto">
                    No hidden fees. Quality service at fair prices.
                </p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Basic Plan -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                    <div class="px-6 py-8 border-b border-gray-200">
                        <h3 class="text-2xl font-bold text-gray-900">Basic Service</h3>
                        <div class="mt-4 flex items-baseline">
                            <span class="text-4xl font-extrabold text-blue-600">$49</span>
                            <span class="ml-1 text-lg font-medium text-gray-500">/service</span>
                        </div>
                        <p class="mt-4 text-gray-600">
                            Perfect for minor issues and diagnostics
                        </p>
                    </div>
                    <div class="px-6 pt-6 pb-8">
                        <ul class="space-y-4">
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Virus & Malware Removal</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Software Installation</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Basic Hardware Check</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>System Optimization</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>1 Month Warranty</span>
                            </li>
                        </ul>
                        <div class="mt-8">
                            <button class="w-full bg-blue-600 text-white px-6 py-3 rounded-md text-lg font-semibold hover:bg-blue-700 transition duration-300">
                                Choose Plan
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Premium Plan -->
                <div class="bg-white rounded-lg shadow-xl overflow-hidden transform scale-105">
                    <div class="bg-blue-600 px-6 py-4">
                        <p class="text-white font-semibold">Most Popular</p>
                    </div>
                    <div class="px-6 py-8 border-b border-gray-200">
                        <h3 class="text-2xl font-bold text-gray-900">Premium Service</h3>
                        <div class="mt-4 flex items-baseline">
                            <span class="text-4xl font-extrabold text-blue-600">$99</span>
                            <span class="ml-1 text-lg font-medium text-gray-500">/service</span>
                        </div>
                        <p class="mt-4 text-gray-600">
                            Comprehensive solutions for most computer issues
                        </p>
                    </div>
                    <div class="px-6 pt-6 pb-8">
                        <ul class="space-y-4">
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>All Basic Services Included</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Hardware Repairs</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Data Recovery (Basic)</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Network Troubleshooting</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>3 Months Warranty</span>
                            </li>
                        </ul>
                        <div class="mt-8">
                            <button class="w-full bg-blue-600 text-white px-6 py-3 rounded-md text-lg font-semibold hover:bg-blue-700 transition duration-300">
                                Choose Plan
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Business Plan -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                    <div class="px-6 py-8 border-b border-gray-200">
                        <h3 class="text-2xl font-bold text-gray-900">Business Support</h3>
                        <div class="mt-4 flex items-baseline">
                            <span class="text-4xl font-extrabold text-blue-600">$199</span>
                            <span class="ml-1 text-lg font-medium text-gray-500">/month</span>
                        </div>
                        <p class="mt-4 text-gray-600">
                            Ongoing IT support for small businesses
                        </p>
                    </div>
                    <div class="px-6 pt-6 pb-8">
                        <ul class="space-y-4">
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>All Premium Services Included</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Unlimited Remote Support</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>Priority Service</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>On-Site Visits (2/month)</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fas fa-check text-green-500 mt-1 mr-2"></i>
                                <span>6 Months Warranty</span>
                            </li>
                        </ul>
                        <div class="mt-8">
                            <button class="w-full bg-blue-600 text-white px-6 py-3 rounded-md text-lg font-semibold hover:bg-blue-700 transition duration-300">
                                Choose Plan
                            </button>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="mt-12 text-center">
                <p class="text-gray-600">
                    Need something custom? <a href="#contact" class="text-blue-600 font-medium hover:underline">Contact us</a> for a personalized quote.
                </p>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:grid lg:grid-cols-2 lg:gap-16 items-center">
                <div class="mb-12 lg:mb-0">
                    <img src="https://images.unsplash.com/photo-1581092918056-0c4c3acd3789?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=774&q=80" 
                         alt="Computer technician" 
                         class="rounded-lg shadow-xl w-full h-auto">
                </div>
                <div>
                    <h2 class="text-3xl font-extrabold text-gray-900 mb-6">
                        About TechFix Pro
                    </h2>
                    <p class="text-gray-600 mb-6">
                        Founded in 2010 by John Smith, TechFix Pro has grown from a small home-based business to the leading computer repair service in the area. Our mission is to provide honest, reliable, and affordable computer repair services to both residential and business customers.
                    </p>
                    <p class="text-gray-600 mb-6">
                        What sets us apart is our commitment to customer satisfaction. We don't just fix computers - we build relationships. Our technicians are not only highly skilled but also patient and willing to explain technical issues in plain English.
                    </p>
                    <div class="bg-blue-50 p-6 rounded-lg">
                        <div class="flex">
                            <div class="flex-shrink-0">
                                <i class="fas fa-award text-blue-600 text-2xl"></i>
                            </div>
                            <div class="ml-4">
                                <h4 class="text-lg font-bold text-gray-900">Certified Technicians</h4>
                                <p class="mt-1 text-gray-600">
                                    All our technicians are A+ certified and undergo continuous training to stay current with the latest technologies.
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">
                    What Our Customers Say
                </h2>
                <p class="mt-4 max-w-2xl text-xl text-gray-600 mx-auto">
                    Don't just take our word for it - hear from our satisfied clients
                </p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="testimonial-card bg-white p-8 rounded-lg shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="flex-shrink-0">
                            <img class="h-12 w-12 rounded-full" src="https://randomuser.me/api/portraits/women/32.jpg" alt="Sarah Johnson">
                        </div>
                        <div class="ml-4">
                            <h4 class="text-lg font-bold text-gray-900">Sarah Johnson</h4>
                            <div class="flex items-center mt-1">
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">
                        "I thought I had lost all my family photos when my laptop crashed. TechFix Pro recovered everything and had my computer running better than ever. Worth every penny!"
                    </p>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="testimonial-card bg-white p-8 rounded-lg shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="flex-shrink-0">
                            <img class="h-12 w-12 rounded-full" src="https://randomuser.me/api/portraits/men/54.jpg" alt="Michael Chen">
                        </div>
                        <div class="ml-4">
                            <h4 class="text-lg font-bold text-gray-900">Michael Chen</h4>
                            <div class="flex items-center mt-1">
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">
                        "As a small business owner, I rely on my computers. When our server went down, TechFix Pro had us back up and running in no time. Their business support plan has been a lifesaver."
                    </p>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="testimonial-card bg-white p-8 rounded-lg shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="flex-shrink-0">
                            <img class="h-12 w-12 rounded-full" src="https://randomuser.me/api/portraits/women/68.jpg" alt="Emily Rodriguez">
                        </div>
                        <div class="ml-4">
                            <h4 class="text-lg font-bold text-gray-900">Emily Rodriguez</h4>
                            <div class="flex items-center mt-1">
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">
                        "The technician was so patient with me, explaining everything in terms I could understand. Fixed my virus problem and showed me how to avoid it in the future. Highly recommend!"
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:grid lg:grid-cols-2 lg:gap-16">
                <div class="mb-12 lg:mb-0">
                    <h2 class="text-3xl font-extrabold text-gray-900 mb-6">
                        Get in Touch
                    </h2>
                    <p class="text-gray-600 mb-8">
                        Have a question or need service? Fill out the form and we'll get back to you within 1 business day. For immediate assistance, please call us directly.
                    </p>
                    
                    <div class="space-y-6">
                        <div class="flex">
                            <div class="flex-shrink-0 bg-blue-100 p-3 rounded-full">
                                <i class="fas fa-map-marker-alt text-blue-600"></i>
                            </div>
                            <div class="ml-4">
                                <h4 class="text-lg font-bold text-gray-900">Our Location</h4>
                                <p class="mt-1 text-gray-600">123 Tech Street, Suite 101<br>San Francisco, CA 94107</p>
                            </div>
                        </div>
                        
                        <div class="flex">
                            <div class="flex-shrink-0 bg-blue-100 p-3 rounded-full">
                                <i class="fas fa-phone-alt text-blue-600"></i>
                            </div>
                            <div class="ml-4">
                                <h4 class="text-lg font-bold text-gray-900">Phone Number</h4>
                                <p class="mt-1 text-gray-600">(123) 456-7890</p>
                            </div>
                        </div>
                        
                        <div class="flex">
                            <div class="flex-shrink-0 bg-blue-100 p-3 rounded-full">
                                <i class="fas fa-envelope text-blue-600"></i>
                            </div>
                            <div class="ml-4">
                                <h4 class="text-lg font-bold text-gray-900">Email Address</h4>
                                <p class="mt-1 text-gray-600">support@techfixpro.com</p>
                            </div>
                        </div>
                        
                        <div class="flex">
                            <div class="flex-shrink-0 bg-blue-100 p-3 rounded-full">
                                <i class="fas fa-clock text-blue-600"></i>
                            </div>
                            <div class="ml-4">
                                <h4 class="text-lg font-bold text-gray-900">Business Hours</h4>
                                <p class="mt-1 text-gray-600">Monday - Friday: 9am - 6pm<br>Saturday: 10am - 4pm<br>Emergency service available 24/7</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div>
                    <div class="bg-white shadow-xl rounded-lg p-8">
                        <h3 class="text-2xl font-bold text-gray-900 mb-6">Request Service</h3>
                        <form id="contactForm">
                            <div class="mb-6">
                                <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Full Name</label>
                                <input type="text" id="name" name="name" class="contact-input w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-blue-500 focus:border-blue-500" required>
                            </div>
                            <div class="mb-6">
                                <label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email Address</label>
                                <input type="email" id="email" name="email" class="contact-input w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-blue-500 focus:border-blue-500" required>
                            </div>
                            <div class="mb-6">
                                <label for="phone" class="block text-sm font-medium text-gray-700 mb-1">Phone Number</label>
                                <input type="tel" id="phone" name="phone" class="contact-input w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-blue-500 focus:border-blue-500" required>
                            </div>
                            <div class="mb-6">
                                <label for="service" class="block text-sm font-medium text-gray-700 mb-1">Service Needed</label>
                                <select id="service" name="service" class="contact-input w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-blue-500 focus:border-blue-500" required>
                                    <option value="">Select a service</option>
                                    <option value="Hardware Repair">Hardware Repair</option>
                                    <option value="Virus Removal">Virus Removal</option>
                                    <option value="Data Recovery">Data Recovery</option>
                                    <option value="Network Solutions">Network Solutions</option>
                                    <option value="PC Tune-Up">PC Tune-Up</option>
                                    <option value="On-Site Support">On-Site Support</option>
                                    <option value="Other">Other</option>
                                </select>
                            </div>
                            <div class="mb-6">
                                <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Describe Your Issue</label>
                                <textarea id="message" name="message" rows="4" class="contact-input w-full px-4 py-3 border border-gray-300 rounded-md focus:ring-blue-500 focus:border-blue-500" required></textarea>
                            </div>
                            <div class="mb-6">
                                <div class="flex items-start">
                                    <div class="flex items-center h-5">
                                        <input id="emergency" name="emergency" type="checkbox" class="focus:ring-blue-500 h-4 w-4 text-blue-600 border-gray-300 rounded">
                                    </div>
                                    <div class="ml-3 text-sm">
                                        <label for="emergency" class="font-medium text-gray-700">Check if this is an emergency</label>
                                    </div>
                                </div>
                            </div>
                            <div>
                                <button type="submit" class="w-full bg-blue-600 text-white px-6 py-3 rounded-md text-lg font-semibold hover:bg-blue-700 transition duration-300">
                                    Submit Request
                                </button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">
                    Frequently Asked Questions
                </h2>
                <p class="mt-4 max-w-2xl text-xl text-gray-600 mx-auto">
                    Answers to common questions about our services
                </p>
            </div>
            
            <div class="max-w-3xl mx-auto">
                <div class="space-y-6">
                    <!-- FAQ 1 -->
                    <div class="bg-white shadow rounded-lg overflow-hidden">
                        <button class="faq-toggle w-full flex justify-between items-center p-6 text-left focus:outline-none">
                            <h3 class="text-lg font-medium text-gray-900">How long does a typical repair take?</h3>
                            <i class="fas fa-chevron-down text-blue-600 transition-transform duration-300"></i>
                        </button>
                        <div class="faq-content px-6 pb-6 hidden">
                            <p class="text-gray-600">
                                Most repairs are completed within 24-48 hours. Simple software issues can often be resolved the same day, while more complex hardware repairs may take 2-3 days depending on parts availability. We offer expedited service for an additional fee if you need your device back sooner.
                            </p>
                        </div>
                    </div>
                    
                    <!-- FAQ 2 -->
                    <div class="bg-white shadow rounded-lg overflow-hidden">
                        <button class="faq-toggle w-full flex justify-between items-center p-6 text-left focus:outline-none">
                            <h3 class="text-lg font-medium text-gray-900">Do you offer any warranty on repairs?</h3>
                            <i class="fas fa-chevron-down text-blue-600 transition-transform duration-300"></i>
                        </button>
                        <div class="faq-content px-6 pb-6 hidden">
                            <p class="text-gray-600">
                                Yes! We stand behind all our work. Labor is covered by a 90-day warranty, and parts come with the manufacturer's warranty (typically 1 year). If the same issue reoccurs within the warranty period, we'll fix it at no additional charge.
                            </p>
                        </div>
                    </div>
                    
                    <!-- FAQ 3 -->
                    <div class="bg-white shadow rounded-lg overflow-hidden">
                        <button class="faq-toggle w-full flex justify-between items-center p-6 text-left focus:outline-none">
                            <h3 class="text-lg font-medium text-gray-900">Can you recover data from a computer that won't turn on?</h3>
                            <i class="fas fa-chevron-down text-blue-600 transition-transform duration-300"></i>
                        </button>
                        <div class="faq-content px-6 pb-6 hidden">
                            <p class="text-gray-600">
                                In most cases, yes. As long as the hard drive or SSD is physically intact, we can usually recover your data. We have specialized equipment that allows us to access drives even when the computer itself isn't functioning. Success rates are typically over 90% for logical failures and about 70% for physical damage cases.
                            </p>
                        </div>
                    </div>
                    
                    <!-- FAQ 4 -->
                    <div class="bg-white shadow rounded-lg overflow-hidden">
                        <button class="faq-toggle w-full flex justify-between items-center p-6 text-left focus:outline-none">
                            <h3 class="text-lg font-medium text-gray-900">What areas do you serve for on-site support?</h3>
                            <i class="fas fa-chevron-down text-blue-600 transition-transform duration-300"></i>
                        </button>
                        <div class="faq-content px-6 pb-6 hidden">
                            <p class="text-gray-600">
                                We provide on-site service within a 20-mile radius of our downtown location at no additional charge. For locations beyond this area, we charge a small travel fee based on distance. Our technicians are fully equipped with tools and common replacement parts to handle most repairs during the initial visit.
                            </p>
                        </div>
                    </div>
                    
                    <!-- FAQ 5 -->
                    <div class="bg-white shadow rounded-lg overflow-hidden">
                        <button class="faq-toggle w-full flex justify-between items-center p-6 text-left focus:outline-none">
                            <h3 class="text-lg font-medium text-gray-900">How do I know if I need a repair or should just buy a new computer?</h3>
                            <i class="fas fa-chevron-down text-blue-600 transition-transform duration-300"></i>
                        </button>
                        <div class="faq-content px-6 pb-6 hidden">
                            <p class="text-gray-600">
                                As a general rule, if the repair cost is less than half the price of a comparable new device, repair is usually the better option. We offer free evaluations and will always give you an honest assessment of whether repair makes financial sense. Many computers can be significantly upgraded to extend their useful life at a fraction of the cost of replacement.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="bg-blue-600 text-white">
        <div class="max-w-7xl mx-auto py-16 px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl font-extrabold mb-6">
                Ready to Get Your Computer Fixed?
            </h2>
            <p class="text-xl mb-8 max-w-3xl mx-auto opacity-90">
                Don't let computer problems slow you down. Contact us today for fast, reliable service.
            </p>
            <div class="flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-4">
                <a href="#contact" class="bg-white text-blue-600 px-8 py-4 rounded-md text-lg font-semibold hover:bg-gray-100 transition duration-300">
                    Request Service Now
                </a>
                <a href="tel:+1234567890" class="border-2 border-white px-8 py-4 rounded-md text-lg font-semibold hover:bg-white hover:text-blue-600 transition duration-300">
                    <i class="fas fa-phone mr-2"></i> Call Us: (123) 456-7890
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white">
        <div class="max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-lg font-semibold mb-4">TechFix Pro</h3>
                    <p class="text-gray-400">
                        Your trusted partner for computer repair and IT solutions.
                    </p>
                    <div class="flex space-x-4 mt-4">
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i class="fab fa-twitter"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i class="fab fa-linkedin-in"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-lg font-semibold mb-4">Services</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">Hardware Repair</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Virus Removal</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Data Recovery</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Network Solutions</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">PC Tune-Up</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-semibold mb-4">Company</h3>
                    <ul class="space-y-2">
                        <li><a href="#about" class="text-gray-400 hover:text-white">About Us</a></li>
                        <li><a href="#testimonials" class="text-gray-400 hover:text-white">Testimonials</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Careers</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Blog</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-white">Contact</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-semibold mb-4">Support</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">Help Center</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Terms of Service</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Privacy Policy</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Shipping Policy</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Returns & Warranty</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="mt-12 pt-8 border-t border-gray-800 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 text-sm">
                    &copy; 2023 TechFix Pro. All rights reserved.
                </p>
                <div class="mt-4 md:mt-0">
                    <img src="https://via.placeholder.com/300x50?text=Payment+Methods" alt="Payment methods" class="h-8">
                </div>
            </div>
        </div>
    </footer>

    <!-- Success Modal -->
    <div id="successModal" class="fixed inset-0 z-50 flex items-center justify-center hidden">
        <div class="absolute inset-0 bg-black opacity-50"></div>
        <div class="bg-white rounded-lg shadow-xl max-w-md w-full mx-4 z-50">
            <div class="p-6 text-center">
                <div class="mx-auto flex items-center justify-center h-12 w-12 rounded-full bg-green-100 mb-4">
                    <i class="fas fa-check text-green-600 text-xl"></i>
                </div>
                <h3 class="text-lg font-medium text-gray-900 mb-2">Request Submitted!</h3>
                <p class="text-gray-600 mb-6">
                    Thank you for contacting TechFix Pro. We've received your service request and will get back to you within 1 business day.
                </p>
                <button id="closeModal" class="w-full bg-blue-600 text-white px-4 py-2 rounded-md text-sm font-medium hover:bg-blue-700 transition duration-300">
                    Close
                </button>
            </div>
        </div>
    </div>

    <script>
        // Mobile menu toggle
        document.getElementById('mobile-menu-button').addEventListener('click', function() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // FAQ toggle functionality
        document.querySelectorAll('.faq-toggle').forEach(button => {
            button.addEventListener('click', function() {
                const content = this.nextElementSibling;
                const icon = this.querySelector('i');
                
                content.classList.toggle('hidden');
                icon.classList.toggle('rotate-180');
            });
        });

        // Form submission
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // In a real application, you would send the form data to a server here
            // For this demo, we'll just show the success modal
            
            const modal = document.getElementById('successModal');
            modal.classList.remove('hidden');
            
            // Reset form
            this.reset();
        });

        // Close modal
        document.getElementById('closeModal').addEventListener('click', function() {
            const modal = document.getElementById('successModal');
            modal.classList.add('hidden');
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                if (targetElement) {
                    // Close mobile menu if open
                    const mobileMenu = document.getElementById('mobile-menu');
                    mobileMenu.classList.add('hidden');
                    
                    // Scroll to target
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html>
