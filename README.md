<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Purgo Cleaning Services - Sparkling Clean Guaranteed</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Configure Tailwind for Inter font -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        'purgo-blue': '#3B82F6', // A clean, bright blue (blue-500)
                        'purgo-dark': '#1E3A8A', // Darker blue for contrast (blue-800)
                        'purgo-light': '#EFF6FF', // Very light blue for backgrounds
                    }
                }
            }
        }
    </script>
    <!-- Load Lucide icons (for modern icons) -->
    <script type="module">
        import { createIcons, CheckCircle, Home, Factory, Zap, Sparkles, Star, Phone, Mail, MapPin, MessageCircle } from 'https://cdn.jsdelivr.net/npm/lucide@latest/dist/esm/lucide.js';
        document.addEventListener('DOMContentLoaded', () => {
            createIcons({ icons: { CheckCircle, Home, Factory, Zap, Sparkles, Star, Phone, Mail, MapPin, MessageCircle } });
        });
    </script>
    <style>
        /* Custom scroll-snap for a smoother, single-page experience (optional) */
        .scroll-section {
            scroll-snap-align: start;
        }
    </style>
</head>
<body class="font-sans bg-gray-50 text-gray-800">

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-50 bg-white shadow-lg">
        <nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <!-- Logo/Brand -->
            <a href="#" class="flex items-center space-x-2">
                <i data-lucide="sparkles" class="w-6 h-6 text-purgo-blue fill-purgo-blue/20"></i>
                <span class="text-2xl font-bold text-purgo-dark tracking-tight">Purgo Cleaning Services</span>
            </a>
            
            <!-- Contact CTA (using the Nigerian number) -->
            <a href="#booking" class="hidden sm:inline-flex items-center bg-purgo-blue text-white font-semibold py-2 px-4 rounded-lg shadow-md hover:bg-purgo-dark transition duration-300 transform hover:scale-105">
                <i data-lucide="phone" class="w-4 h-4 mr-2"></i>
                Call Now: +234 903 912 4537
            </a>
            
            <!-- Mobile Menu Placeholder -->
            <button class="sm:hidden p-2 rounded-lg text-purgo-dark hover:bg-gray-100 transition duration-150">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
                </svg>
            </button>
        </nav>
    </header>

    <!-- 1. Hero Section -->
    <section class="scroll-section bg-purgo-light pt-16 pb-20 sm:pt-24 sm:pb-32">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <div class="max-w-3xl mx-auto">
                <p class="text-purgo-blue text-lg font-semibold mb-3">Your Partner in Spotless Spaces, Nigeria</p>
                <h1 class="text-4xl sm:text-6xl font-extrabold text-purgo-dark leading-tight mb-6">
                    Sparkling Clean Guaranteed, <span class="block sm:inline text-purgo-blue">So You Can Relax.</span>
                </h1>
                <p class="text-xl text-gray-600 mb-10">
                    Purgo Cleaning Services delivers professional, reliable cleaning for homes and businesses in Ibadan and across Nigeria. We use eco-friendly products and tailored plans to meet your exact needs.
                </p>
                <a href="#booking" class="inline-flex items-center justify-center bg-purgo-blue text-white text-lg font-bold py-4 px-8 rounded-xl shadow-2xl shadow-purgo-blue/40 hover:bg-purgo-dark transition duration-300 transform hover:scale-105">
                    Book Your First Clean Now!
                </a>
            </div>
            <!-- Placeholder for a clean image/illustration -->
            <div class="mt-12">
                 <img class="w-full max-w-xl mx-auto rounded-xl shadow-2xl border-4 border-white" 
                      src="https://placehold.co/1200x600/3B82F6/FFFFFF?text=Professional+Nigerian+Cleaning+Team" 
                      alt="Professional cleaning illustration placeholder" 
                      onerror="this.onerror=null; this.src='https://placehold.co/1200x600/3B82F6/FFFFFF?text=Purgo+Clean+Team'"
                 />
            </div>
        </div>
    </section>

    <!-- 2. Services Section -->
    <section id="services" class="scroll-section py-20 sm:py-28 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl sm:text-4xl font-bold text-purgo-dark text-center mb-4">Our Premium Cleaning Services</h2>
            <p class="text-xl text-gray-600 text-center max-w-2xl mx-auto mb-12">We offer flexible cleaning solutions designed to fit your schedule and lifestyle.</p>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Service 1: Residential -->
                <div class="bg-purgo-light p-6 rounded-2xl shadow-lg border border-purgo-blue/20 transition duration-300 hover:shadow-xl hover:scale-[1.01]">
                    <i data-lucide="home" class="w-8 h-8 text-purgo-blue mb-4"></i>
                    <h3 class="text-xl font-bold text-purgo-dark mb-3">Residential Cleaning</h3>
                    <p class="text-gray-700">Regular weekly, bi-weekly, or monthly cleaning schedules tailored for your home. Enjoy peace of mind in a pristine environment.</p>
                    <a href="#booking" class="mt-4 text-purgo-blue font-semibold inline-flex items-center">
                        Learn More &rarr;
                    </a>
                </div>

                <!-- Service 2: Commercial -->
                <div class="bg-purgo-light p-6 rounded-2xl shadow-lg border border-purgo-blue/20 transition duration-300 hover:shadow-xl hover:scale-[1.01]">
                    <i data-lucide="factory" class="w-8 h-8 text-purgo-blue mb-4"></i>
                    <h3 class="text-xl font-bold text-purgo-dark mb-3">Commercial Spaces</h3>
                    <p class="text-gray-700">Professional office, retail, and workspace cleaning. Maintain a healthy, impressive environment for your employees and clients.</p>
                    <a href="#booking" class="mt-4 text-purgo-blue font-semibold inline-flex items-center">
                        Learn More &rarr;
                    </a>
                </div>

                <!-- Service 3: Deep Cleaning -->
                <div class="bg-purgo-light p-6 rounded-2xl shadow-lg border border-purgo-blue/20 transition duration-300 hover:shadow-xl hover:scale-[1.01]">
                    <i data-lucide="zap" class="w-8 h-8 text-purgo-blue mb-4"></i>
                    <h3 class="text-xl font-bold text-purgo-dark mb-3">Move-In/Out & Deep Cleans</h3>
                    <p class="text-gray-700">Intensive, detailed cleaning for special occasions, post-renovation, or end-of-tenancy requirements. We cover every corner.</p>
                    <a href="#booking" class="mt-4 text-purgo-blue font-semibold inline-flex items-center">
                        Learn More &rarr;
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- 3. Why Choose Us Section (Features) -->
    <section class="scroll-section py-20 sm:py-28 bg-purgo-dark text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl sm:text-4xl font-bold text-center mb-4 text-white">The Purgo Difference</h2>
            <p class="text-xl text-purgo-light text-center max-w-2xl mx-auto mb-12">We focus on reliability, quality, and your total satisfaction.</p>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Feature 1 -->
                <div class="text-center p-4">
                    <i data-lucide="check-circle" class="w-10 h-10 mx-auto mb-4 text-purgo-blue bg-white rounded-full p-1"></i>
                    <h3 class="text-lg font-semibold mb-2">Vetted Professionals</h3>
                    <p class="text-gray-300 text-sm">Every team member is trained, insured, and background-checked for your security.</p>
                </div>
                <!-- Feature 2 -->
                <div class="text-center p-4">
                    <i data-lucide="sparkles" class="w-10 h-10 mx-auto mb-4 text-purgo-blue bg-white rounded-full p-1"></i>
                    <h3 class="text-lg font-semibold mb-2">Eco-Friendly Focus</h3>
                    <p class="text-gray-300 text-sm">Using sustainable and safe cleaning products for a healthier home and planet.</p>
                </div>
                <!-- Feature 3 -->
                <div class="text-center p-4">
                    <i data-lucide="zap" class="w-10 h-10 mx-auto mb-4 text-purgo-blue bg-white rounded-full p-1"></i>
                    <h3 class="text-lg font-semibold mb-2">Flexible Scheduling</h3>
                    <p class="text-gray-300 text-sm">Book, change, or cancel appointments easily via phone or online form.</p>
                </div>
                <!-- Feature 4 -->
                <div class="text-center p-4">
                    <i data-lucide="star" class="w-10 h-10 mx-auto mb-4 text-purgo-blue bg-white rounded-full p-1"></i>
                    <h3 class="text-lg font-semibold mb-2">100% Satisfaction</h3>
                    <p class="text-gray-300 text-sm">If you're not happy, we'll return and re-clean the area for free—guaranteed.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. Testimonials Section (Updated with Nigerian Names/Locations) -->
    <section class="scroll-section py-20 sm:py-28 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl sm:text-4xl font-bold text-purgo-dark text-center mb-4">What Our Clients Say</h2>
            <p class="text-xl text-gray-600 text-center max-w-2xl mx-auto mb-12">Trusted by homes and businesses in Ibadan, Lagos, and beyond.</p>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <!-- Testimonial 1: Commercial (Lagos) -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-md border-t-4 border-purgo-blue">
                    <div class="flex text-yellow-500 mb-3">
                        <i data-lucide="star" class="w-5 h-5 fill-yellow-500"></i>
                        <i data-lucide="star" class="w-5 h-5 fill-yellow-500"></i>
                        <i data-lucide="star" class="w-5 h-5 fill-yellow-500"></i>
                        <i data-lucide="star" class="w-5 h-5 fill-yellow-500"></i>
                        <i data-lucide="star" class="w-5 h-5 fill-yellow-500"></i>
                    </div>
                    <p class="italic text-gray-700 mb-4">"Purgo is simply the best cleaning service we've ever used. Punctual, meticulous, and always leaving our office spotless. Highly recommend for any commercial space!"</p>
                    <p class="font-semibold text-purgo-dark">— Bayo A., Lekki, Lagos</p>
                </div>
                <!-- Testimonial 2: Residential Deep Clean (Abuja) -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-md border-t-4 border-purgo-blue">
                    <div class="flex text-yellow-500 mb-3">
                        <i data-lucide="star" class="w-5 h-5 fill-yellow-500"></i>
                        <i data-lucide="star" class="w-5 h-5 fill-yellow-500"></i>
                        <i data-lucide="star" class="w-5 h-5 fill-yellow-500"></i>
                        <i data-lucide="star" class="w-5 h-5 fill-yellow-500"></i>
                        <i data-lucide="star" class="w-5 h-5 fill-yellow-500"></i>
                    </div>
                    <p class="italic text-gray-700 mb-4">"The residential deep clean was transformative! I felt like I moved into a brand new home. The team was professional and paid attention to every detail."</p>
                    <p class="font-semibold text-purgo-dark">— Nkechi O., Garki, Abuja</p>
                </div>
                <!-- Testimonial 3: Regular Residential (Ibadan) -->
                <div class="bg-gray-50 p-6 rounded-xl shadow-md border-t-4 border-purgo-blue">
                    <div class="flex text-yellow-500 mb-3">
                        <i data-lucide="star" class="w-5 h-5 fill-yellow-500"></i>
                        <i data-lucide="star" class="w-5 h-5 fill-yellow-500"></i>
                        <i data-lucide="star" class="w-5 h-5 fill-yellow-500"></i>
                        <i data-lucide="star" class="w-5 h-5 fill-yellow-500"></i>
                        <i data-lucide="star" class="w-5 h-5 fill-yellow-500"></i>
                    </div>
                    <p class="italic text-gray-700 mb-4">"I love the fact that they use non-toxic, eco-friendly products. It gives me peace of mind, and the results are consistently exceptional. Five stars!"</p>
                    <p class="font-semibold text-purgo-dark">— Kunle S., Jericho, Ibadan</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. Booking/Contact Form Section (CTA) -->
    <section id="booking" class="scroll-section py-20 sm:py-28 bg-purgo-blue/90">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-white p-8 sm:p-12 rounded-2xl shadow-2xl">
                <h2 class="text-3xl font-bold text-purgo-dark text-center mb-4">Ready for a Sparkling Home?</h2>
                <p class="text-lg text-gray-600 text-center mb-8">Fill out the form below for a custom, no-obligation quote, or contact us directly.</p>
                
                <div class="flex justify-center space-x-4 mb-8">
                    <a href="tel:+2349039124537" class="flex items-center text-purgo-dark hover:text-purgo-blue font-medium">
                        <i data-lucide="phone" class="w-5 h-5 mr-2"></i> +234 903 912 4537
                    </a>
                    <a href="mailto:ng.purgo@gmail.com" class="flex items-center text-purgo-dark hover:text-purgo-blue font-medium">
                        <i data-lucide="mail" class="w-5 h-5 mr-2"></i> ng.purgo@gmail.com
                    </a>
                </div>

                <form class="space-y-6">
                    <div>
                        <label for="name" class="block text-sm font-medium text-gray-700">Full Name</label>
                        <input type="text" id="name" name="name" placeholder="Adetola Johnson" required
                               class="mt-1 block w-full px-4 py-3 border border-gray-300 rounded-lg shadow-sm focus:border-purgo-blue focus:ring-purgo-blue">
                    </div>
                    <div>
                        <label for="email" class="block text-sm font-medium text-gray-700">Email Address</label>
                        <input type="email" id="email" name="email" placeholder="you@example.com" required
                               class="mt-1 block w-full px-4 py-3 border border-gray-300 rounded-lg shadow-sm focus:border-purgo-blue focus:ring-purgo-blue">
                    </div>
                    <div>
                        <label for="service" class="block text-sm font-medium text-gray-700">Type of Service Needed</label>
                        <select id="service" name="service" required
                                class="mt-1 block w-full px-4 py-3 border border-gray-300 rounded-lg shadow-sm focus:border-purgo-blue focus:ring-purgo-blue appearance-none bg-white">
                            <option value="">Select a service...</option>
                            <option value="residential">Residential Regular Clean</option>
                            <option value="commercial">Commercial/Office Clean</option>
                            <option value="deep">Deep/Move-In/Out Clean</option>
                            <option value="other">Other</option>
                        </select>
                    </div>
                    <div>
                        <label for="message" class="block text-sm font-medium text-gray-700">Tell us about your needs</label>
                        <textarea id="message" name="message" rows="4" placeholder="e.g., 3 bedrooms, once every two weeks..." required
                                  class="mt-1 block w-full px-4 py-3 border border-gray-300 rounded-lg shadow-sm focus:border-purgo-blue focus:ring-purgo-blue"></textarea>
                    </div>
                    <button type="submit" class="w-full inline-flex items-center justify-center bg-purgo-dark text-white text-lg font-bold py-3 px-4 rounded-lg shadow-md hover:bg-purgo-blue transition duration-300 transform hover:scale-[1.01]">
                        Submit for Quote
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center sm:text-left">
            <div class="grid grid-cols-1 sm:grid-cols-3 gap-8">
                <!-- Col 1: Brand -->
                <div>
                    <h4 class="text-xl font-bold mb-4 text-purgo-blue">Purgo Cleaning Services</h4>
                    <p class="text-sm text-gray-400">
                        Reliable and professional cleaning solutions for a healthier, happier space. Located in Ibadan, serving Nigeria.
                    </p>
                </div>
                <!-- Col 2: Quick Links -->
                <div>
                    <h4 class="text-lg font-semibold mb-4">Quick Links</h4>
                    <ul class="space-y-2 text-sm">
                        <li><a href="#" class="text-gray-400 hover:text-purgo-blue transition duration-150">Home</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-purgo-blue transition duration-150">Services</a></li>
                        <li><a href="#booking" class="text-gray-400 hover:text-purgo-blue transition duration-150">Get Quote</a></li>
                    </ul>
                </div>
                <!-- Col 3: Contact Info (UPDATED) -->
                <div>
                    <h4 class="text-lg font-semibold mb-4">Contact Purgo</h4>
                    <!-- Phone -->
                    <a href="tel:+2349039124537" class="text-sm text-gray-400 flex items-center mb-2 hover:text-purgo-blue transition duration-150">
                        <i data-lucide="phone" class="w-4 h-4 mr-2 text-purgo-blue"></i>
                        +234 903 912 4537
                    </a>
                    <!-- WhatsApp -->
                    <a href="https://wa.me/2349039124537" target="_blank" class="text-sm text-gray-400 flex items-center mb-2 hover:text-purgo-blue transition duration-150">
                        <i data-lucide="message-circle" class="w-4 h-4 mr-2 text-purgo-blue"></i>
                        WhatsApp Us
                    </a>
                    <!-- Email -->
                    <a href="mailto:ng.purgo@gmail.com" class="text-sm text-gray-400 flex items-center mb-2 hover:text-purgo-blue transition duration-150">
                        <i data-lucide="mail" class="w-4 h-4 mr-2 text-purgo-blue"></i>
                        ng.purgo@gmail.com
                    </a>
                    <!-- Address -->
                    <p class="text-sm text-gray-400 flex items-start mt-3">
                        <i data-lucide="map-pin" class="w-4 h-4 mr-2 text-purgo-blue mt-1 flex-shrink-0"></i>
                        Jericho, Ibadan, Nigeria.
                    </p>
                </div>
            </div>
            
            <div class="mt-10 pt-8 border-t border-gray-700 text-center">
                <p class="text-sm text-gray-500">&copy; 2025 Purgo Cleaning Services. All rights reserved.</p>
            </div>
        </div>
    </footer>

</body>
</html>
