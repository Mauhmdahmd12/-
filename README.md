# <!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>دورة الذكاء الاصطناعي - تعلم كيف تربح من الذكاء الاصطناعي</title>
    <meta name="description" content="انضم إلى أقوى دورة تدريبية تكشف لك أسرار الربح من الذكاء الاصطناعي خطوة بخطوة. عرض محدود - خصم 95%!">
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;600;700;900&display=swap" rel="stylesheet">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Custom Styles -->
    <style>
        * {
            font-family: 'Cairo', sans-serif;
        }
        
        html {
            scroll-behavior: smooth;
        }
        
        body {
            direction: rtl;
        }
        
        .gradient-text {
            background: linear-gradient(135deg, #a855f7, #ec4899);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .animate-float {
            animation: float 6s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }
        
        .animate-scroll {
            animation: scroll 25s linear infinite;
        }
        
        @keyframes scroll {
            0% { transform: translateX(0); }
            100% { transform: translateX(-50%); }
        }
        
        .backdrop-blur {
            backdrop-filter: blur(16px);
        }
        
        .bg-gradient-radial {
            background: radial-gradient(circle at center, rgba(168, 85, 247, 0.1) 0%, transparent 70%);
        }
    </style>
</head>
<body class="bg-slate-900 text-white">
    <!-- Navigation -->
    <nav class="fixed top-0 left-0 right-0 z-50 bg-slate-900/95 backdrop-blur border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-6 py-4">
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-3 space-x-reverse">
                    <div class="w-10 h-10 bg-gradient-to-br from-purple-500 to-pink-500 rounded-xl flex items-center justify-center">
                        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"></path>
                        </svg>
                    </div>
                    <span class="text-white font-bold text-xl">أكاديمية الذكاء الاصطناعي</span>
                </div>
                
                <div class="hidden md:flex items-center space-x-8 space-x-reverse">
                    <a href="#features" class="text-slate-300 hover:text-white transition-colors">المميزات</a>
                    <a href="#content" class="text-slate-300 hover:text-white transition-colors">المحتوى</a>
                    <a href="#testimonials" class="text-slate-300 hover:text-white transition-colors">التقييمات</a>
                    <a href="#pricing" class="text-slate-300 hover:text-white transition-colors">الأسعار</a>
                </div>
                
                <button class="bg-gradient-to-r from-purple-500 to-pink-500 text-white px-6 py-3 rounded-full font-semibold hover:from-purple-600 hover:to-pink-600 transition-all duration-300">
                    احجز الآن
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="relative min-h-screen flex items-center justify-center overflow-hidden pt-20">
        <div class="absolute inset-0 bg-gradient-to-br from-slate-900 via-purple-900/30 to-slate-900">
            <div class="absolute inset-0 bg-gradient-radial animate-pulse"></div>
        </div>
        
        <!-- Floating Stats -->
        <div class="absolute top-32 left-8 bg-slate-800/80 backdrop-blur border border-slate-700/50 rounded-2xl p-4 text-center animate-float">
            <svg class="text-purple-400 mx-auto mb-2 w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
            </svg>
            <div class="text-white font-semibold">+5000</div>
            <div class="text-slate-400 text-sm">طالب نجح</div>
        </div>
        
        <div class="absolute top-48 right-8 bg-slate-800/80 backdrop-blur border border-slate-700/50 rounded-2xl p-4 text-center animate-float" style="animation-delay: -3s;">
            <div class="flex items-center justify-center mb-2">
                <span class="text-yellow-400">⭐⭐⭐⭐⭐</span>
            </div>
            <div class="text-white font-semibold">4.9/5</div>
            <div class="text-slate-400 text-sm">تقييم الطلاب</div>
        </div>
        
        <!-- Main Content -->
        <div class="relative z-10 text-center max-w-6xl mx-auto px-6">
            <div class="flex items-center justify-center space-x-2 space-x-reverse mb-6">
                <span class="text-2xl">✨</span>
                <span class="text-purple-400 font-semibold">عرض محدود - خصم 95%</span>
                <span class="text-2xl">✨</span>
            </div>
            
            <h1 class="text-5xl md:text-7xl font-bold text-white mb-8 leading-tight">
                🚀 هل أنت مستعد للدخول إلى 
                <span class="gradient-text">عالم الذكاء الاصطناعي</span> 
                وتحقيق دخل حقيقي؟
            </h1>
            
            <p class="text-xl md:text-2xl text-slate-300 mb-12 max-w-4xl mx-auto leading-relaxed">
                ✨ انضم الآن إلى أقوى دورة تدريبية تكشف لك أسرار الربح من الذكاء الاصطناعي 
                خطوة بخطوة، حتى لو كنت مبتدئ تمامًا!
            </p>
            
            <div class="flex flex-col sm:flex-row items-center justify-center gap-6">
                <button class="bg-gradient-to-r from-purple-500 to-pink-500 text-white px-12 py-6 rounded-full text-xl font-bold hover:from-purple-600 hover:to-pink-600 transition-all duration-300 shadow-2xl shadow-purple-500/25 transform hover:scale-105">
                    احجز الآن وتعلم كيف تربح من الذكاء الاصطناعي!
                </button>
                
                <div class="text-center">
                    <div class="text-slate-400 line-through text-lg">$200</div>
                    <div class="text-3xl font-bold text-green-400">$9.99</div>
                    <div class="text-slate-400 text-sm">لفترة محدودة فقط</div>
                </div>
            </div>
            
            <div class="mt-12 flex items-center justify-center space-x-8 space-x-reverse text-slate-400">
                <div class="flex items-center space-x-2 space-x-reverse">
                    <span class="text-green-400">📈</span>
                    <span>نتائج مضمونة</span>
                </div>
                <div class="flex items-center space-x-2 space-x-reverse">
                    <span class="text-purple-400">✨</span>
                    <span>محتوى حصري</span>
                </div>
                <div class="flex items-center space-x-2 space-x-reverse">
                    <span class="text-pink-400">🚀</span>
                    <span>دعم مدى الحياة</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="py-32 bg-slate-900">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-5xl md:text-6xl font-bold text-white mb-6">
                    🔍 ما الذي ستكتشفه داخل 
                    <span class="gradient-text">الدورة؟</span>
                </h2>
                <p class="text-xl text-slate-400 max-w-3xl mx-auto">
                    محتوى شامل ومتكامل يأخذك من الصفر إلى الاحتراف في عالم الذكاء الاصطناعي
                </p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8 hover:bg-slate-800/70 transition-all duration-300 transform hover:-translate-y-2">
                    <div class="w-16 h-16 bg-gradient-to-br from-purple-500/20 to-pink-500/20 border border-purple-500/30 rounded-2xl mb-6 flex items-center justify-center">
                        <span class="text-3xl">🧠</span>
                    </div>
                    <h3 class="text-2xl font-bold text-white mb-4">أدوات الذكاء الاصطناعي</h3>
                    <p class="text-slate-400 leading-relaxed">
                        تعلم استخدام ChatGPT، Midjourney، Canva AI وأدوات أخرى لخلق مصادر دخل متعددة
                    </p>
                </div>
                
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8 hover:bg-slate-800/70 transition-all duration-300 transform hover:-translate-y-2">
                    <div class="w-16 h-16 bg-gradient-to-br from-purple-500/20 to-pink-500/20 border border-purple-500/30 rounded-2xl mb-6 flex items-center justify-center">
                        <span class="text-3xl">💰</span>
                    </div>
                    <h3 class="text-2xl font-bold text-white mb-4">مشاريع رقمية مربحة</h3>
                    <p class="text-slate-400 leading-relaxed">
                        طرق عملية لبناء مشاريع رقمية مدعومة بالذكاء الاصطناعي تحقق دخل حقيقي
                    </p>
                </div>
                
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8 hover:bg-slate-800/70 transition-all duration-300 transform hover:-translate-y-2">
                    <div class="w-16 h-16 bg-gradient-to-br from-purple-500/20 to-pink-500/20 border border-purple-500/30 rounded-2xl mb-6 flex items-center justify-center">
                        <span class="text-3xl">👥</span>
                    </div>
                    <h3 class="text-2xl font-bold text-white mb-4">خدمات مطلوبة في السوق</h3>
                    <p class="text-slate-400 leading-relaxed">
                        كيفية تقديم خدمات عالية الطلب في السوق باستخدام أدوات الذكاء الاصطناعي
                    </p>
                </div>
                
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8 hover:bg-slate-800/70 transition-all duration-300 transform hover:-translate-y-2">
                    <div class="w-16 h-16 bg-gradient-to-br from-purple-500/20 to-pink-500/20 border border-purple-500/30 rounded-2xl mb-6 flex items-center justify-center">
                        <span class="text-3xl">🎯</span>
                    </div>
                    <h3 class="text-2xl font-bold text-white mb-4">استراتيجيات تسويق ذكية</h3>
                    <p class="text-slate-400 leading-relaxed">
                        تعلم كيفية تسويق وبيع منتجات وخدمات تعتمد على الذكاء الاصطناعي
                    </p>
                </div>
                
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8 hover:bg-slate-800/70 transition-all duration-300 transform hover:-translate-y-2">
                    <div class="w-16 h-16 bg-gradient-to-br from-purple-500/20 to-pink-500/20 border border-purple-500/30 rounded-2xl mb-6 flex items-center justify-center">
                        <span class="text-3xl">📚</span>
                    </div>
                    <h3 class="text-2xl font-bold text-white mb-4">دراسات حالة حقيقية</h3>
                    <p class="text-slate-400 leading-relaxed">
                        أمثلة واقعية من طلاب نجحوا في تحقيق دخل من الذكاء الاصطناعي
                    </p>
                </div>
                
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8 hover:bg-slate-800/70 transition-all duration-300 transform hover:-translate-y-2">
                    <div class="w-16 h-16 bg-gradient-to-br from-purple-500/20 to-pink-500/20 border border-purple-500/30 rounded-2xl mb-6 flex items-center justify-center">
                        <span class="text-3xl">⚡</span>
                    </div>
                    <h3 class="text-2xl font-bold text-white mb-4">ملفات جاهزة للاستخدام</h3>
                    <p class="text-slate-400 leading-relaxed">
                        قوالب وأدوات جاهزة يمكنك استخدامها فورًا لبدء مشروعك
                    </p>
                </div>
            </div>
            
            <div class="text-center mt-16">
                <div class="bg-gradient-to-r from-purple-500/10 to-pink-500/10 border border-purple-500/30 rounded-3xl p-8 max-w-4xl mx-auto">
                    <h3 class="text-3xl font-bold text-white mb-4">🎯 هذه الدورة لك إذا كنت:</h3>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mt-8">
                        <div class="flex items-center space-x-3 space-x-reverse">
                            <div class="w-3 h-3 bg-gradient-to-r from-purple-400 to-pink-400 rounded-full flex-shrink-0"></div>
                            <span class="text-slate-300">تريد بدء مشروعك الرقمي بأقل تكلفة</span>
                        </div>
                        <div class="flex items-center space-x-3 space-x-reverse">
                            <div class="w-3 h-3 bg-gradient-to-r from-purple-400 to-pink-400 rounded-full flex-shrink-0"></div>
                            <span class="text-slate-300">تبحث عن طريقة حديثة للربح دون مهارات تقنية معقدة</span>
                        </div>
                        <div class="flex items-center space-x-3 space-x-reverse">
                            <div class="w-3 h-3 bg-gradient-to-r from-purple-400 to-pink-400 rounded-full flex-shrink-0"></div>
                            <span class="text-slate-300">مهتم بالذكاء الاصطناعي وتريد استثماره بطريقة عملية</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Course Content Section -->
    <section id="content" class="py-32 bg-gradient-to-br from-slate-800 to-slate-900">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-5xl md:text-6xl font-bold text-white mb-6">
                    محتوى الدورة <span class="gradient-text">التفصيلي</span>
                </h2>
                <p class="text-xl text-slate-400 max-w-3xl mx-auto">
                    +16 ساعة من المحتوى العملي المكثف مع أكثر من 65 درس تطبيقي
                </p>
            </div>
            
            <!-- Course Stats -->
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6 mb-16">
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-2xl p-6 text-center">
                    <span class="text-3xl mb-3 block">▶️</span>
                    <div class="text-3xl font-bold text-white mb-1">65+</div>
                    <div class="text-slate-400 text-sm">فيديو تعليمي</div>
                </div>
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-2xl p-6 text-center">
                    <span class="text-3xl mb-3 block">⏰</span>
                    <div class="text-3xl font-bold text-white mb-1">16+</div>
                    <div class="text-slate-400 text-sm">ساعة محتوى</div>
                </div>
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-2xl p-6 text-center">
                    <span class="text-3xl mb-3 block">👥</span>
                    <div class="text-3xl font-bold text-white mb-1">5000+</div>
                    <div class="text-slate-400 text-sm">طالب مسجل</div>
                </div>
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-2xl p-6 text-center">
                    <span class="text-3xl mb-3 block">🏆</span>
                    <div class="text-3xl font-bold text-white mb-1">1</div>
                    <div class="text-slate-400 text-sm">شهادة إتمام</div>
                </div>
            </div>
            
            <!-- Course Modules -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8 hover:bg-slate-800/70 transition-all duration-300">
                    <div class="flex items-center justify-between mb-4">
                        <h3 class="text-2xl font-bold text-white">مقدمة في الذكاء الاصطناعي</h3>
                        <div class="text-purple-400 text-2xl font-bold">01</div>
                    </div>
                    <p class="text-slate-400 mb-6 leading-relaxed">
                        فهم أساسيات الذكاء الاصطناعي وكيفية استخدامه في الأعمال
                    </p>
                    <div class="flex items-center justify-between">
                        <div class="flex items-center space-x-4 space-x-reverse text-slate-300">
                            <div class="flex items-center space-x-2 space-x-reverse">
                                <span>⏰</span>
                                <span class="text-sm">2 ساعة</span>
                            </div>
                            <div class="flex items-center space-x-2 space-x-reverse">
                                <span>▶️</span>
                                <span class="text-sm">8 درس</span>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8 hover:bg-slate-800/70 transition-all duration-300">
                    <div class="flex items-center justify-between mb-4">
                        <h3 class="text-2xl font-bold text-white">أدوات ChatGPT للربح</h3>
                        <div class="text-purple-400 text-2xl font-bold">02</div>
                    </div>
                    <p class="text-slate-400 mb-6 leading-relaxed">
                        استخدام ChatGPT لكتابة المحتوى وتقديم الخدمات المربحة
                    </p>
                    <div class="flex items-center justify-between">
                        <div class="flex items-center space-x-4 space-x-reverse text-slate-300">
                            <div class="flex items-center space-x-2 space-x-reverse">
                                <span>⏰</span>
                                <span class="text-sm">3 ساعات</span>
                            </div>
                            <div class="flex items-center space-x-2 space-x-reverse">
                                <span>▶️</span>
                                <span class="text-sm">12 درس</span>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8 hover:bg-slate-800/70 transition-all duration-300">
                    <div class="flex items-center justify-between mb-4">
                        <h3 class="text-2xl font-bold text-white">إنشاء الصور بـ Midjourney</h3>
                        <div class="text-purple-400 text-2xl font-bold">03</div>
                    </div>
                    <p class="text-slate-400 mb-6 leading-relaxed">
                        تعلم إنشاء صور احترافية وبيعها أو استخدامها في مشاريعك
                    </p>
                    <div class="flex items-center justify-between">
                        <div class="flex items-center space-x-4 space-x-reverse text-slate-300">
                            <div class="flex items-center space-x-2 space-x-reverse">
                                <span>⏰</span>
                                <span class="text-sm">2.5 ساعة</span>
                            </div>
                            <div class="flex items-center space-x-2 space-x-reverse">
                                <span>▶️</span>
                                <span class="text-sm">10 درس</span>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8 hover:bg-slate-800/70 transition-all duration-300">
                    <div class="flex items-center justify-between mb-4">
                        <h3 class="text-2xl font-bold text-white">التصميم بـ Canva AI</h3>
                        <div class="text-purple-400 text-2xl font-bold">04</div>
                    </div>
                    <p class="text-slate-400 mb-6 leading-relaxed">
                        إنشاء تصاميم مذهلة للعلامات التجارية والتسويق
                    </p>
                    <div class="flex items-center justify-between">
                        <div class="flex items-center space-x-4 space-x-reverse text-slate-300">
                            <div class="flex items-center space-x-2 space-x-reverse">
                                <span>⏰</span>
                                <span class="text-sm">2 ساعة</span>
                            </div>
                            <div class="flex items-center space-x-2 space-x-reverse">
                                <span>▶️</span>
                                <span class="text-sm">9 درس</span>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8 hover:bg-slate-800/70 transition-all duration-300">
                    <div class="flex items-center justify-between mb-4">
                        <h3 class="text-2xl font-bold text-white">بناء مشروع رقمي كامل</h3>
                        <div class="text-purple-400 text-2xl font-bold">05</div>
                    </div>
                    <p class="text-slate-400 mb-6 leading-relaxed">
                        تطبيق عملي لبناء مشروع مربح من الصفر
                    </p>
                    <div class="flex items-center justify-between">
                        <div class="flex items-center space-x-4 space-x-reverse text-slate-300">
                            <div class="flex items-center space-x-2 space-x-reverse">
                                <span>⏰</span>
                                <span class="text-sm">4 ساعات</span>
                            </div>
                            <div class="flex items-center space-x-2 space-x-reverse">
                                <span>▶️</span>
                                <span class="text-sm">15 درس</span>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8 hover:bg-slate-800/70 transition-all duration-300">
                    <div class="flex items-center justify-between mb-4">
                        <h3 class="text-2xl font-bold text-white">استراتيجيات التسويق والبيع</h3>
                        <div class="text-purple-400 text-2xl font-bold">06</div>
                    </div>
                    <p class="text-slate-400 mb-6 leading-relaxed">
                        كيفية تسويق خدماتك ومنتجاتك وزيادة المبيعات
                    </p>
                    <div class="flex items-center justify-between">
                        <div class="flex items-center space-x-4 space-x-reverse text-slate-300">
                            <div class="flex items-center space-x-2 space-x-reverse">
                                <span>⏰</span>
                                <span class="text-sm">3 ساعات</span>
                            </div>
                            <div class="flex items-center space-x-2 space-x-reverse">
                                <span>▶️</span>
                                <span class="text-sm">11 درس</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-16">
                <div class="bg-gradient-to-r from-purple-500/10 to-pink-500/10 border border-purple-500/30 rounded-3xl p-8 max-w-2xl mx-auto">
                    <h3 class="text-2xl font-bold text-white mb-4">🎁 مكافآت حصرية</h3>
                    <div class="space-y-3">
                        <div class="flex items-center space-x-3 space-x-reverse justify-center">
                            <div class="w-2 h-2 bg-gradient-to-r from-purple-400 to-pink-400 rounded-full"></div>
                            <span class="text-slate-300">قوالب جاهزة للاستخدام الفوري</span>
                        </div>
                        <div class="flex items-center space-x-3 space-x-reverse justify-center">
                            <div class="w-2 h-2 bg-gradient-to-r from-purple-400 to-pink-400 rounded-full"></div>
                            <span class="text-slate-300">مجتمع خاص للطلاب</span>
                        </div>
                        <div class="flex items-center space-x-3 space-x-reverse justify-center">
                            <div class="w-2 h-2 bg-gradient-to-r from-purple-400 to-pink-400 rounded-full"></div>
                            <span class="text-slate-300">جلسات أسئلة وأجوبة مباشرة</span>
                        </div>
                        <div class="flex items-center space-x-3 space-x-reverse justify-center">
                            <div class="w-2 h-2 bg-gradient-to-r from-purple-400 to-pink-400 rounded-full"></div>
                            <span class="text-slate-300">تحديثات مجانية مدى الحياة</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-32 bg-slate-900 overflow-hidden">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-5xl md:text-6xl font-bold text-white mb-6">
                    قصص نجاح <span class="gradient-text">حقيقية</span>
                </h2>
                <p class="text-xl text-slate-400 max-w-3xl mx-auto">
                    اكتشف كيف غيّر طلابنا حياتهم وحققوا دخل حقيقي من الذكاء الاصطناعي
                </p>
            </div>
            
            <!-- Scrolling Testimonials -->
            <div class="relative">
                <div class="absolute right-0 top-0 bottom-0 w-32 bg-gradient-to-l from-slate-900 to-transparent z-10"></div>
                <div class="absolute left-0 top-0 bottom-0 w-32 bg-gradient-to-r from-slate-900 to-transparent z-10"></div>
                
                <div class="flex space-x-6 space-x-reverse animate-scroll">
                    <!-- Testimonial 1 -->
                    <div class="flex-shrink-0 w-96 bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8">
                        <div class="flex items-center space-x-1 space-x-reverse mb-4">
                            <span class="text-yellow-400">⭐⭐⭐⭐⭐</span>
                        </div>
                        <p class="text-slate-300 mb-6 leading-relaxed">
                            "الدورة غيرت حياتي تمامًا! تعلمت كيف أستخدم الذكاء الاصطناعي لإنشاء محتوى وأحقق دخل شهري 2000 دولار."
                        </p>
                        <div class="flex items-center justify-between">
                            <div class="flex items-center space-x-3 space-x-reverse">
                                <div class="text-3xl">👨‍💻</div>
                                <div>
                                    <div class="text-white font-semibold">أحمد محمد</div>
                                    <div class="text-slate-400 text-sm">مطور محتوى • مصر</div>
                                </div>
                            </div>
                            <div class="bg-gradient-to-r from-green-500/20 to-emerald-500/20 border border-green-500/30 rounded-full px-3 py-1">
                                <span class="text-green-400 text-sm font-semibold">+$2000/شهر</span>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Testimonial 2 -->
                    <div class="flex-shrink-0 w-96 bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8">
                        <div class="flex items-center space-x-1 space-x-reverse mb-4">
                            <span class="text-yellow-400">⭐⭐⭐⭐⭐</span>
                        </div>
                        <p class="text-slate-300 mb-6 leading-relaxed">
                            "بفضل الدورة، أصبحت أقدم خدمات التصميم بالذكاء الاصطناعي وزاد دخلي 300%. المحتوى عملي ومفيد جداً."
                        </p>
                        <div class="flex items-center justify-between">
                            <div class="flex items-center space-x-3 space-x-reverse">
                                <div class="text-3xl">👩‍🎨</div>
                                <div>
                                    <div class="text-white font-semibold">فاطمة العلي</div>
                                    <div class="text-slate-400 text-sm">مصممة جرافيك • الإمارات</div>
                                </div>
                            </div>
                            <div class="bg-gradient-to-r from-green-500/20 to-emerald-500/20 border border-green-500/30 rounded-full px-3 py-1">
                                <span class="text-green-400 text-sm font-semibold">+300% زيادة</span>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Testimonial 3 -->
                    <div class="flex-shrink-0 w-96 bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8">
                        <div class="flex items-center space-x-1 space-x-reverse mb-4">
                            <span class="text-yellow-400">⭐⭐⭐⭐⭐</span>
                        </div>
                        <p class="text-slate-300 mb-6 leading-relaxed">
                            "أطلقت مشروعي الرقمي بالكامل باستخدام أدوات الذكاء الاصطناعي. الآن أحقق أرباح شهرية تفوق 5000 دولار."
                        </p>
                        <div class="flex items-center justify-between">
                            <div class="flex items-center space-x-3 space-x-reverse">
                                <div class="text-3xl">👨‍💼</div>
                                <div>
                                    <div class="text-white font-semibold">خالد السعدي</div>
                                    <div class="text-slate-400 text-sm">رائد أعمال • السعودية</div>
                                </div>
                            </div>
                            <div class="bg-gradient-to-r from-green-500/20 to-emerald-500/20 border border-green-500/30 rounded-full px-3 py-1">
                                <span class="text-green-400 text-sm font-semibold">+$5000/شهر</span>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Duplicate testimonials for seamless scroll -->
                    <div class="flex-shrink-0 w-96 bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8">
                        <div class="flex items-center space-x-1 space-x-reverse mb-4">
                            <span class="text-yellow-400">⭐⭐⭐⭐⭐</span>
                        </div>
                        <p class="text-slate-300 mb-6 leading-relaxed">
                            "تعلمت كيف أكتب محتوى عالي الجودة بسرعة مذهلة. الآن أعمل مع عملاء دوليين وأحقق دخل ممتاز."
                        </p>
                        <div class="flex items-center justify-between">
                            <div class="flex items-center space-x-3 space-x-reverse">
                                <div class="text-3xl">👩‍💻</div>
                                <div>
                                    <div class="text-white font-semibold">مريم حسن</div>
                                    <div class="text-slate-400 text-sm">كاتبة محتوى • المغرب</div>
                                </div>
                            </div>
                            <div class="bg-gradient-to-r from-green-500/20 to-emerald-500/20 border border-green-500/30 rounded-full px-3 py-1">
                                <span class="text-green-400 text-sm font-semibold">+$1500/شهر</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="flex-shrink-0 w-96 bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-8">
                        <div class="flex items-center space-x-1 space-x-reverse mb-4">
                            <span class="text-yellow-400">⭐⭐⭐⭐⭐</span>
                        </div>
                        <p class="text-slate-300 mb-6 leading-relaxed">
                            "الدورة علمتني استراتيجيات تسويق متقدمة بالذكاء الاصطناعي. نتائج عملائي تحسنت بشكل كبير."
                        </p>
                        <div class="flex items-center justify-between">
                            <div class="flex items-center space-x-3 space-x-reverse">
                                <div class="text-3xl">👨‍💻</div>
                                <div>
                                    <div class="text-white font-semibold">عمر التميمي</div>
                                    <div class="text-slate-400 text-sm">مسوق رقمي • الأردن</div>
                                </div>
                            </div>
                            <div class="bg-gradient-to-r from-green-500/20 to-emerald-500/20 border border-green-500/30 rounded-full px-3 py-1">
                                <span class="text-green-400 text-sm font-semibold">+250% نتائج</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-16">
                <div class="inline-flex items-center space-x-6 space-x-reverse bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-full px-8 py-4">
                    <div class="flex items-center space-x-2 space-x-reverse">
                        <span class="text-yellow-400">⭐⭐⭐⭐⭐</span>
                        <span class="text-white font-semibold">4.9/5</span>
                    </div>
                    <div class="w-px h-6 bg-slate-600"></div>
                    <div class="text-slate-400">بناءً على +5000 تقييم</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="py-32 bg-gradient-to-br from-slate-800 to-slate-900">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-5xl md:text-6xl font-bold text-white mb-6">
                    🎁 مفاجأة <span class="gradient-text">حصرية</span>
                </h2>
                <p class="text-xl text-slate-400 max-w-3xl mx-auto">
                    عرض محدود لفترة قصيرة - وفر 95% من السعر الأصلي
                </p>
            </div>
            
            <div class="max-w-4xl mx-auto">
                <!-- Timer -->
                <div class="bg-red-500/10 border border-red-500/30 rounded-2xl p-6 mb-12 text-center">
                    <div class="flex items-center justify-center space-x-2 space-x-reverse mb-4">
                        <span class="text-2xl">⏰</span>
                        <span class="text-red-400 font-semibold text-lg">العرض ينتهي قريباً!</span>
                    </div>
                    <div class="text-white text-2xl font-bold">
                        🕒 المقاعد محدودة – احجز مكانك الآن!
                    </div>
                </div>
                
                <!-- Pricing Card -->
                <div class="relative">
                    <!-- Popular Badge -->
                    <div class="absolute -top-4 left-1/2 transform -translate-x-1/2 z-10">
                        <div class="bg-gradient-to-r from-purple-500 to-pink-500 text-white px-6 py-2 rounded-full text-sm font-semibold flex items-center space-x-2 space-x-reverse">
                            <span>👑</span>
                            <span>الأكثر شعبية</span>
                        </div>
                    </div>
                    
                    <div class="bg-slate-800/50 backdrop-blur border-2 border-purple-500/30 rounded-3xl p-8 relative overflow-hidden">
                        <!-- Background Glow -->
                        <div class="absolute -top-10 -right-10 w-40 h-40 bg-purple-500/20 rounded-full blur-3xl"></div>
                        <div class="absolute -bottom-10 -left-10 w-40 h-40 bg-pink-500/20 rounded-full blur-3xl"></div>
                        
                        <div class="relative z-10">
                            <div class="text-center mb-8">
                                <h3 class="text-3xl font-bold text-white mb-4">
                                    دورة الذكاء الاصطناعي الشاملة
                                </h3>
                                
                                <div class="flex items-center justify-center space-x-4 space-x-reverse mb-6">
                                    <div class="text-slate-400 line-through text-2xl">$200</div>
                                    <div class="text-6xl font-bold gradient-text">$9.99</div>
                                </div>
                                
                                <div class="bg-green-500/10 border border-green-500/30 rounded-full px-4 py-2 inline-block mb-6">
                                    <span class="text-green-400 font-semibold">وفر 95% - عرض محدود!</span>
                                </div>
                            </div>
                            
                            <!-- Features -->
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-8">
                                <div class="flex items-center space-x-3 space-x-reverse">
                                    <span class="text-green-400">✅</span>
                                    <span class="text-slate-300">+16 ساعة محتوى تعليمي</span>
                                </div>
                                <div class="flex items-center space-x-3 space-x-reverse">
                                    <span class="text-green-400">✅</span>
                                    <span class="text-slate-300">+65 درس تطبيقي</span>
                                </div>
                                <div class="flex items-center space-x-3 space-x-reverse">
                                    <span class="text-green-400">✅</span>
                                    <span class="text-slate-300">أدوات وقوالب جاهزة</span>
                                </div>
                                <div class="flex items-center space-x-3 space-x-reverse">
                                    <span class="text-green-400">✅</span>
                                    <span class="text-slate-300">دعم مدى الحياة</span>
                                </div>
                                <div class="flex items-center space-x-3 space-x-reverse">
                                    <span class="text-green-400">✅</span>
                                    <span class="text-slate-300">مجتمع خاص للطلاب</span>
                                </div>
                                <div class="flex items-center space-x-3 space-x-reverse">
                                    <span class="text-green-400">✅</span>
                                    <span class="text-slate-300">شهادة إتمام معتمدة</span>
                                </div>
                                <div class="flex items-center space-x-3 space-x-reverse">
                                    <span class="text-green-400">✅</span>
                                    <span class="text-slate-300">تحديثات مجانية</span>
                                </div>
                                <div class="flex items-center space-x-3 space-x-reverse">
                                    <span class="text-green-400">✅</span>
                                    <span class="text-slate-300">ضمان استرداد 30 يوم</span>
                                </div>
                            </div>
                            
                            <!-- CTA Button -->
                            <button class="w-full bg-gradient-to-r from-purple-500 to-pink-500 text-white py-6 rounded-2xl text-xl font-bold hover:from-purple-600 hover:to-pink-600 transition-all duration-300 shadow-2xl shadow-purple-500/25 flex items-center justify-center space-x-3 space-x-reverse transform hover:scale-105">
                                <span>⚡</span>
                                <span>احجز الآن وابدأ رحلتك!</span>
                            </button>
                            
                            <div class="text-center mt-6 text-slate-400 text-sm">
                                💳 دفع آمن • ضمان استرداد 30 يوم • دعم 24/7
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Guarantee -->
                <div class="text-center mt-12">
                    <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-2xl p-6 max-w-2xl mx-auto">
                        <h4 class="text-2xl font-bold text-white mb-4">ضمان استرداد المال 100%</h4>
                        <p class="text-slate-400">
                            إذا لم تكن راضياً تماماً عن الدورة خلال 30 يوم، 
                            سنعيد لك أموالك كاملة دون أي أسئلة.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="py-32 bg-slate-900">
        <div class="max-w-4xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-5xl md:text-6xl font-bold text-white mb-6">
                    أسئلة <span class="gradient-text">شائعة</span>
                </h2>
                <p class="text-xl text-slate-400">
                    إجابات على أكثر الأسئلة شيوعاً حول الدورة
                </p>
            </div>
            
            <div class="space-y-4">
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-2xl overflow-hidden">
                    <button class="w-full p-6 text-right flex items-center justify-between hover:bg-slate-800/70 transition-colors" onclick="toggleFAQ(this)">
                        <span class="text-white font-semibold text-lg">هل أحتاج خبرة سابقة في الذكاء الاصطناعي؟</span>
                        <span class="text-purple-400 text-2xl">+</span>
                    </button>
                    <div class="faq-content hidden">
                        <div class="p-6 pt-0 text-slate-400 leading-relaxed">
                            لا، الدورة مصممة للمبتدئين تماماً. نبدأ من الأساسيات ونتدرج خطوة بخطوة حتى المستوى المتقدم.
                        </div>
                    </div>
                </div>
                
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-2xl overflow-hidden">
                    <button class="w-full p-6 text-right flex items-center justify-between hover:bg-slate-800/70 transition-colors" onclick="toggleFAQ(this)">
                        <span class="text-white font-semibold text-lg">كم من الوقت أحتاج لإكمال الدورة؟</span>
                        <span class="text-purple-400 text-2xl">+</span>
                    </button>
                    <div class="faq-content hidden">
                        <div class="p-6 pt-0 text-slate-400 leading-relaxed">
                            يمكنك إكمال الدورة في 2-4 أسابيع بمعدل ساعة واحدة يومياً. لكن يمكنك التعلم بالسرعة التي تناسبك.
                        </div>
                    </div>
                </div>
                
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-2xl overflow-hidden">
                    <button class="w-full p-6 text-right flex items-center justify-between hover:bg-slate-800/70 transition-colors" onclick="toggleFAQ(this)">
                        <span class="text-white font-semibold text-lg">هل سأحصل على شهادة؟</span>
                        <span class="text-purple-400 text-2xl">+</span>
                    </button>
                    <div class="faq-content hidden">
                        <div class="p-6 pt-0 text-slate-400 leading-relaxed">
                            نعم، ستحصل على شهادة إتمام معتمدة يمكنك إضافتها لسيرتك الذاتية أو ملفك الشخصي على LinkedIn.
                        </div>
                    </div>
                </div>
                
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-2xl overflow-hidden">
                    <button class="w-full p-6 text-right flex items-center justify-between hover:bg-slate-800/70 transition-colors" onclick="toggleFAQ(this)">
                        <span class="text-white font-semibold text-lg">ما هي الأدوات المطلوبة؟</span>
                        <span class="text-purple-400 text-2xl">+</span>
                    </button>
                    <div class="faq-content hidden">
                        <div class="p-6 pt-0 text-slate-400 leading-relaxed">
                            تحتاج فقط لجهاز كمبيوتر أو هاتف ذكي واتصال بالإنترنت. جميع الأدوات المستخدمة مجانية أو لها نسخ مجانية.
                        </div>
                    </div>
                </div>
                
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-2xl overflow-hidden">
                    <button class="w-full p-6 text-right flex items-center justify-between hover:bg-slate-800/70 transition-colors" onclick="toggleFAQ(this)">
                        <span class="text-white font-semibold text-lg">هل يمكنني الوصول للدورة مدى الحياة؟</span>
                        <span class="text-purple-400 text-2xl">+</span>
                    </button>
                    <div class="faq-content hidden">
                        <div class="p-6 pt-0 text-slate-400 leading-relaxed">
                            نعم، بمجرد شرائك للدورة ستحصل على وصول مدى الحياة مع جميع التحديثات المستقبلية مجاناً.
                        </div>
                    </div>
                </div>
                
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-2xl overflow-hidden">
                    <button class="w-full p-6 text-right flex items-center justify-between hover:bg-slate-800/70 transition-colors" onclick="toggleFAQ(this)">
                        <span class="text-white font-semibold text-lg">ماذا لو لم أكن راضياً عن الدورة؟</span>
                        <span class="text-purple-400 text-2xl">+</span>
                    </button>
                    <div class="faq-content hidden">
                        <div class="p-6 pt-0 text-slate-400 leading-relaxed">
                            نقدم ضمان استرداد المال 100% خلال 30 يوم من الشراء. إذا لم تكن راضياً، سنعيد أموالك كاملة.
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action Section -->
    <section class="py-32 bg-gradient-to-br from-slate-900 via-purple-900/30 to-slate-900 relative overflow-hidden">
        <div class="absolute inset-0 bg-gradient-radial animate-pulse"></div>
        
        <div class="max-w-7xl mx-auto px-6 relative z-10">
            <div class="text-center mb-16">
                <h2 class="text-5xl md:text-7xl font-bold text-white mb-6 leading-tight">
                    🕒 المقاعد محدودة – 
                    <span class="gradient-text">احجز مكانك الآن</span> 
                    وابدأ رحلتك نحو مصدر دخل ذكي ومستدام!
                </h2>
            </div>
            
            <!-- Urgency Indicators -->
            <div class="grid grid-cols-1 md:grid-cols-4 gap-6 mb-16">
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-2xl p-6 text-center">
                    <span class="text-3xl mb-3 block">⏰</span>
                    <div class="text-2xl font-bold text-white mb-1">48 ساعة</div>
                    <div class="text-slate-400 text-sm">عرض محدود</div>
                </div>
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-2xl p-6 text-center">
                    <span class="text-3xl mb-3 block">👥</span>
                    <div class="text-2xl font-bold text-white mb-1">27 فقط</div>
                    <div class="text-slate-400 text-sm">مقاعد متبقية</div>
                </div>
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-2xl p-6 text-center">
                    <span class="text-3xl mb-3 block">🏆</span>
                    <div class="text-2xl font-bold text-white mb-1">100%</div>
                    <div class="text-slate-400 text-sm">ضمان النجاح</div>
                </div>
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-2xl p-6 text-center">
                    <span class="text-3xl mb-3 block">⚡</span>
                    <div class="text-2xl font-bold text-white mb-1">مباشر</div>
                    <div class="text-slate-400 text-sm">وصول فوري</div>
                </div>
            </div>
            
            <!-- Final CTA -->
            <div class="text-center">
                <div class="bg-slate-800/50 backdrop-blur border border-slate-700/50 rounded-3xl p-12 max-w-4xl mx-auto">
                    <div class="mb-8">
                        <div class="text-slate-400 line-through text-2xl mb-2">$200</div>
                        <div class="text-6xl font-bold gradient-text mb-4">$9.99</div>
                        <div class="bg-red-500/10 border border-red-500/30 rounded-full px-6 py-2 inline-block">
                            <span class="text-red-400 font-semibold">⏰ العرض ينتهي خلال 48 ساعة!</span>
                        </div>
                    </div>
                    
                    <button class="bg-gradient-to-r from-purple-500 to-pink-500 text-white px-16 py-8 rounded-full text-2xl font-bold hover:from-purple-600 hover:to-pink-600 transition-all duration-300 shadow-2xl shadow-purple-500/25 mb-6 transform hover:scale-105">
                        🔘 احجز الآن وتعلم كيف تربح من الذكاء الاصطناعي!
                    </button>
                    
                    <div class="text-slate-400 text-lg">
                        💳 دفع آمن • ضمان استرداد 30 يوم • وصول فوري
                    </div>
                </div>
            </div>
            
            <!-- Trust Indicators -->
            <div class="text-center mt-16">
                <div class="flex flex-wrap items-center justify-center gap-8 text-slate-400">
                    <div class="flex items-center space-x-2 space-x-reverse">
                        <div class="w-3 h-3 bg-green-400 rounded-full"></div>
                        <span>+5000 طالب راضي</span>
                    </div>
                    <div class="flex items-center space-x-2 space-x-reverse">
                        <div class="w-3 h-3 bg-purple-400 rounded-full"></div>
                        <span>تقييم 4.9/5</span>
                    </div>
                    <div class="flex items-center space-x-2 space-x-reverse">
                        <div class="w-3 h-3 bg-pink-400 rounded-full"></div>
                        <span>ضمان النجاح</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-900 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-6 py-16">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-12">
                <!-- Brand -->
                <div class="md:col-span-2">
                    <div class="flex items-center space-x-3 space-x-reverse mb-6">
                        <div class="w-12 h-12 bg-gradient-to-br from-purple-500 to-pink-500 rounded-xl flex items-center justify-center">
                            <svg class="w-7 h-7 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"></path>
                            </svg>
                        </div>
                        <span class="text-white font-bold text-2xl">أكاديمية الذكاء الاصطناعي</span>
                    </div>
                    <p class="text-slate-400 mb-6 leading-relaxed max-w-md">
                        نحن نؤمن بقوة الذكاء الاصطناعي في تغيير حياة الناس. 
                        مهمتنا هي تعليمك كيفية استخدام هذه التقنيات المتطورة 
                        لتحقيق النجاح المالي والمهني.
                    </p>
                    <div class="space-y-3">
                        <div class="flex items-center space-x-3 space-x-reverse text-slate-400">
                            <span>📧</span>
                            <span>support@ai-academy.com</span>
                        </div>
                        <div class="flex items-center space-x-3 space-x-reverse text-slate-400">
                            <span>📞</span>
                            <span>+1 (555) 123-4567</span>
                        </div>
                        <div class="flex items-center space-x-3 space-x-reverse text-slate-400">
                            <span>📍</span>
                            <span>متاح عالمياً - تعلم من أي مكان</span>
                        </div>
                    </div>
                </div>
                
                <!-- Quick Links -->
                <div>
                    <h3 class="text-white font-semibold mb-4 text-lg">روابط سريعة</h3>
                    <ul class="space-y-3">
                        <li><a href="#" class="text-slate-400 hover:text-white transition-colors">عن الدورة</a></li>
                        <li><a href="#" class="text-slate-400 hover:text-white transition-colors">المحتوى التعليمي</a></li>
                        <li><a href="#" class="text-slate-400 hover:text-white transition-colors">قصص النجاح</a></li>
                        <li><a href="#" class="text-slate-400 hover:text-white transition-colors">الأسعار</a></li>
                        <li><a href="#" class="text-slate-400 hover:text-white transition-colors">الأسئلة الشائعة</a></li>
                    </ul>
                </div>
                
                <!-- Support -->
                <div>
                    <h3 class="text-white font-semibold mb-4 text-lg">الدعم</h3>
                    <ul class="space-y-3">
                        <li><a href="#" class="text-slate-400 hover:text-white transition-colors">مركز المساعدة</a></li>
                        <li><a href="#" class="text-slate-400 hover:text-white transition-colors">تواصل معنا</a></li>
                        <li><a href="#" class="text-slate-400 hover:text-white transition-colors">الشروط والأحكام</a></li>
                        <li><a href="#" class="text-slate-400 hover:text-white transition-colors">سياسة الخصوصية</a></li>
                        <li><a href="#" class="text-slate-400 hover:text-white transition-colors">ضمان الاسترداد</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-slate-800 pt-8">
                <div class="flex flex-col md:flex-row items-center justify-between">
                    <div class="text-slate-400 text-sm mb-4 md:mb-0">
                        © 2024 أكاديمية الذكاء الاصطناعي. جميع الحقوق محفوظة.
                    </div>
                    
                    <div class="flex items-center space-x-6 space-x-reverse">
                        <button class="bg-gradient-to-r from-purple-500 to-pink-500 text-white px-6 py-3 rounded-full font-semibold hover:from-purple-600 hover:to-pink-600 transition-all duration-300 transform hover:scale-105">
                            ابدأ التعلم الآن
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <!-- JavaScript -->
    <script>
        // FAQ Toggle Function
        function toggleFAQ(button) {
            const content = button.nextElementSibling;
            const icon = button.querySelector('span:last-child');
            
            if (content.classList.contains('hidden')) {
                content.classList.remove('hidden');
                icon.textContent = '−';
                icon.style.transform = 'rotate(180deg)';
            } else {
                content.classList.add('hidden');
                icon.textContent = '+';
                icon.style.transform = 'rotate(0deg)';
            }
        }

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Add scroll effect to navbar
        window.addEventListener('scroll', function() {
            const navbar = document.querySelector('nav');
            if (window.scrollY > 100) {
                navbar.style.backgroundColor = 'rgba(15, 23, 42, 0.98)';
            } else {
                navbar.style.backgroundColor = 'rgba(15, 23, 42, 0.95)';
            }
        });
    </script>
</body>
</html>
