<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Easy Travel - التنقل الذكي في المغرب</title>
    <!-- Tailwind CSS CDN للسرعة والخفة -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body { font-family: 'Cairo', sans-serif; }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header / Navbar -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2 space-x-reverse">
                <!-- Logo Mockup -->
                <div class="w-10 h-10 bg-blue-600 rounded-full flex items-center justify-center text-white font-bold text-lg">
                    <span class="text-green-400">🚗</span>
                </div>
                <span class="text-xl font-bold text-blue-900">Easy <span class="text-green-600">Travel</span></span>
            </div>
            <nav class="hidden md:flex space-x-6 space-x-reverse text-sm font-medium">
                <a href="#" class="text-blue-600 hover:text-blue-800">الرئيسية</a>
                <a href="#tracking" class="hover:text-blue-600">تتبع الرحلة</a>
                <a href="#drivers" class="hover:text-blue-600">السائقين</a>
                <a href="#support" class="hover:text-blue-600">الشكايات والدعم</a>
            </nav>
            <div>
                <a href="#book" class="bg-green-600 hover:bg-green-700 text-white px-4 py-2 rounded-lg text-sm font-semibold shadow">احجز الآن</a>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-gradient-to-r from-blue-900 to-blue-700 text-white py-16 px-4 text-center">
        <div class="max-w-3xl mx-auto">
            <h1 class="text-3xl md:text-5xl font-bold mb-4">تنقل بكل أمان وسلاسة في جميع مدن المغرب</h1>
            <p class="text-blue-100 mb-8 text-sm md:text-base">خدمة نقل داخلية متطورة، تتبع حي، ودفع آمن عبر Wafacash وبطاقات الائتمان.</p>
            
            <!-- Quick Booking Box -->
            <div id="book" class="bg-white p-4 rounded-xl shadow-lg text-gray-800 text-right">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-4">
                    <div>
                        <label class="block text-xs font-bold text-gray-600 mb-1">من (نقطة الانطلاق)</label>
                        <input type="text" placeholder="مثال: سلا، الرباط..." class="w-full p-2 border rounded-lg text-sm focus:ring-2 focus:ring-blue-500">
                    </div>
                    <div>
                        <label class="block text-xs font-bold text-gray-600 mb-1">إلى (الوجهة)</label>
                        <input type="text" placeholder="أدخل وجهتك..." class="w-full p-2 border rounded-lg text-sm focus:ring-2 focus:ring-blue-500">
                    </div>
                </div>
                <button class="w-full bg-blue-600 hover:bg-blue-700 text-white py-3 rounded-lg font-bold text-sm transition">ابحث عن سائق الآن</button>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-12 px-4 max-w-7xl mx-auto">
        <h2 class="text-2xl font-bold text-center mb-8 text-blue-900">لماذا اختيار Easy Travel؟</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <div class="bg-white p-6 rounded-xl shadow-sm border text-center">
                <div class="text-3xl mb-3">📍</div>
                <h3 class="font-bold text-lg mb-2">تتبع مباشر</h3>
                <p class="text-sm text-gray-600">تتبع رحلتك خطوة بخطوة من نقطة الانطلاق حتى الوصول بأمان تام.</p>
            </div>
            <div class="bg-white p-6 rounded-xl shadow-sm border text-center">
                <div class="text-3xl mb-3">💳</div>
                <p class="text-sm text-gray-600">دفع مرن وآمن عبر Wafacash، CashPlus أو بطاقات الائتمان البنكية.</p>
                <h3 class="font-bold text-lg mb-2">طرق دفع متعددة</h3>
            </div>
            <div class="bg-white p-6 rounded-xl shadow-sm border text-center">
                <div class="text-3xl mb-3">🎁</div>
                <h3 class="font-bold text-lg mb-2">مكافآت للسائقين</h3>
                <p class="text-sm text-gray-600">بونص 100 درهم لكل سائق يكمل 30 رحلة بنجاح مع خدمة متميزة.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-400 py-6 text-center text-xs">
        <p>&copy; 2026 Easy Travel Morocco. جميع الحقوق محفوظة.</p>
    </footer>

</body>
</html>
