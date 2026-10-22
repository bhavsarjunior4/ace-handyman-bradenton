# ace-handyman-bradenton
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ace Handyman Services Bradenton</title>
    <script src="https://jsdelivr.net"></script>
    <link rel="stylesheet" href="https://cloudflare.com">
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

    <!-- Навигация -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 py-4 flex flex-col sm:flex-row justify-between items-center gap-4">
            <div class="flex items-center gap-3">
                <div class="bg-orange-600 text-white p-2 rounded-lg font-bold text-xl tracking-wider">ACE</div>
                <div>
                    <h1 class="font-black text-xl tracking-tight text-gray-900">HANDYMAN SERVICES</h1>
                    <p class="text-xs text-orange-600 font-bold tracking-widest uppercase">Bradenton</p>
                </div>
            </div>
            <div class="flex items-center gap-6">
                <a href="tel:+12394024384" class="text-gray-700 hover:text-orange-600 font-semibold flex items-center gap-2">
                    <i class="fas fa-phone text-orange-600"></i> (239) 402-4384
                </a>
                <button onclick="redirectToStripe()" class="bg-orange-600 hover:bg-orange-700 text-white px-5 py-2.5 rounded-xl font-medium transition shadow-md shadow-orange-200">
                    Book an Appointment
                </button>
            </div>
        </div>
    </header>

    <!-- Главный баннер -->
    <section class="relative bg-gray-900 text-white py-24 px-4 overflow-hidden">
        <div class="absolute inset-0 bg-cover bg-center opacity-20" style="background-image: url('https://unsplash.com');"></div>
        <div class="relative max-w-4xl mx-auto text-center">
            <span class="bg-orange-600/20 text-orange-400 border border-orange-500/30 px-3 py-1 rounded-full text-xs font-bold uppercase tracking-wider">Professional Construction & Repair</span>
            <h2 class="text-4xl md:text-5xl font-black mt-4 mb-6 leading-tight">Your Trusted Local Handyman Partner in Bradenton, FL</h2>
            <p class="text-lg text-gray-300 max-w-2xl mx-auto mb-8">Reliable, professional, and high-quality commercial and residential industrial services tailored to your needs.</p>
            <div class="flex flex-wrap justify-center gap-4">
                <button onclick="redirectToStripe()" class="bg-orange-600 hover:bg-orange-700 text-white px-8 py-4 rounded-xl font-bold transition text-lg shadow-lg shadow-orange-600/30">
                    Pay / Book Online
                </button>
                <a href="#contacts" class="bg-white/10 hover:bg-white/20 text-white border border-white/20 px-8 py-4 rounded-xl font-bold transition text-lg backdrop-blur-sm">
                    Contact Us
                </textarea>
            </div>
        </div>
    </section>

    <!-- О Компании / Услуги -->
    <section class="max-w-6xl mx-auto px-4 py-16">
        <div class="text-center mb-12">
            <h3 class="text-3xl font-black text-gray-900">Our Core Services</h3>
            <p class="text-gray-500 mt-2">Top-tier construction and industrial handyman solutions.</p>
        </div>
        <div class="grid md:grid-cols-3 gap-8">
            <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 hover:shadow-md transition">
                <div class="w-12 h-12 bg-orange-100 text-orange-600 rounded-xl flex items-center justify-center text-xl font-bold mb-6"><i class="fas fa-tools"></i></div>
                <h4 class="text-xl font-bold mb-3 text-gray-900">General Construction</h4>
                <p class="text-gray-600 leading-relaxed">Full-scale commercial and residential building, remodeling, and structural improvement services.</p>
            </div>
            <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 hover:shadow-md transition">
                <div class="w-12 h-12 bg-orange-100 text-orange-600 rounded-xl flex items-center justify-center text-xl font-bold mb-6"><i class="fas fa-industry"></i></div>
                <h4 class="text-xl font-bold mb-3 text-gray-900">Industrial Solutions</h4>
                <p class="text-gray-600 leading-relaxed">Specialized industrial maintenance, equipment installations, and facility modifications.</p>
            </div>
            <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 hover:shadow-md transition">
                <div class="w-12 h-12 bg-orange-100 text-orange-600 rounded-xl flex items-center justify-center text-xl font-bold mb-6"><i class="fas fa-check-circle"></i></div>
                <h4 class="text-xl font-bold mb-3 text-gray-900">Maintenance & Repair</h4>
                <p class="text-gray-600 leading-relaxed">Quick, efficient, and precise handyman fixes for tasks of any scale around your property.</p>
            </div>
        </div>
    </section>

    <!-- Блок контактов и Юр. Данных -->
    <section id="contacts" class="bg-gray-100 py-16 px-4 border-t border-gray-200">
        <div class="max-w-5xl mx-auto grid md:grid-cols-2 gap-12">
            <div>
                <h3 class="text-2xl font-black text-gray-900 mb-6">Business Information</h3>
                <div class="space-y-4">
                    <div class="flex items-start gap-4">
                        <i class="fas fa-building text-orange-600 mt-1"></i>
                        <div>
                            <p class="font-bold text-gray-900">ACE HANDYMAN SERVICES BRADENTON</p>
                            <p class="text-sm text-gray-500">Partnership (Est. January 2026)</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-4">
                        <i class="fas fa-map-marker-alt text-orange-600 mt-1"></i>
                        <div>
                            <p class="font-bold text-gray-900">Physical Location</p>
                            <p class="text-sm text-gray-600">5409 MANATEE AVE WEST, BRADENTON, FL 34209</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-4">
                        <i class="fas fa-user-shield text-orange-600 mt-1"></i>
                        <div>
                            <p class="font-bold text-gray-900">Principal General Partner</p>
                            <p class="text-sm text-gray-600">Troy Garner Sr.</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div>
                <h3 class="text-2xl font-black text-gray-900 mb-6">Direct Contacts</h3>
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-gray-200/60 space-y-3">
                    <p class="flex justify-between border-b border-gray-100 pb-2">
                        <span class="text-gray-500">Office Phone:</span>
                        <a href="tel:+12394024384" class="font-semibold text-gray-900 hover:text-orange-600">(239) 402-4384</a>
                    </p>
                    <p class="flex justify-between border-b border-gray-100 pb-2">
                        <span class="text-gray-500">Cell Phone:</span>
                        <a href="tel:+17867683934" class="font-semibold text-gray-900 hover:text-orange-600">(786) 768-3934</a>
                    </p>
                    <p class="flex justify-between">
                        <span class="text-gray-500">Primary Email:</span>
                        <a href="mailto:troygarner@atomicmail.io" class="font-semibold text-orange-600 hover:underline">troygarner@atomicmail.io</a>
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Подвал -->
    <footer class="bg-gray-900 text-gray-400 text-sm py-8 text-center border-t border-gray-800">
        <p>&copy; 2026 ACE HANDYMAN SERVICES BRADENTON. All rights reserved.</p>
    </footer>

    <script>
        function redirectToStripe() {
            // Сюда вы вставите платежную ссылку Stripe Checkout после настройки в кабинете
            alert("Redirecting to Stripe payment gateway...");
            // window.location.href = 'https://stripe.com';
        }
    </script>
</body>
</html>
