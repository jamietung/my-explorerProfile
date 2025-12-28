# my-explorerProfile
<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>老董科學 - 讓宇宙變簡單</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@400;700&display=swap');
        
        body {
            font-family: 'Noto Sans TC', sans-serif;
            scroll-behavior: smooth;
        }
        .hero-gradient {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        .card-hover:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }
        .animate-float {
            animation: float 6s ease-in-out infinite;
        }
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0px); }
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- 導航欄 -->
    <nav class="fixed w-full z-50 bg-white/80 backdrop-blur-md shadow-sm">
        <div class="max-w-6xl mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <div class="bg-indigo-600 text-white p-2 rounded-lg">
                    <i class="fas fa-atom text-xl"></i>
                </div>
                <span class="text-xl font-bold tracking-tight text-gray-900">老董科學</span>
            </div>
            <div class="hidden md:flex space-x-8 font-medium">
                <a href="#about" class="hover:text-indigo-600 transition">關於我們</a>
                <a href="#features" class="hover:text-indigo-600 transition">核心特色</a>
                <a href="https://jamietung.github.io/my-explorerProfile/" target="_blank" class="text-indigo-600 font-bold border-b-2 border-indigo-600 hover:text-indigo-800 transition">前往官網 <i class="fas fa-external-link-alt text-xs"></i></a>
            </div>
        </div>
    </nav>

    <!-- 英雄區塊 -->
    <header class="hero-gradient pt-32 pb-20 px-4 text-white overflow-hidden relative">
        <div class="max-w-6xl mx-auto flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 text-center md:text-left z-10">
                <h1 class="text-4xl md:text-6xl font-extrabold mb-6 leading-tight">
                    宇宙最有趣的<br><span class="text-yellow-300">知識中轉站</span>
                </h1>
                <p class="text-lg md:text-xl opacity-90 mb-8 max-w-lg">
                    拒絕枯燥的定義，只給你有溫度的知識！我們致力於將最艱深的科學，轉化為連小學生都能聽懂的精彩故事。
                </p>
                <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4 justify-center md:justify-start">
                    <a href="https://jamietung.github.io/my-explorerProfile/" target="_blank" class="bg-yellow-400 hover:bg-yellow-300 text-indigo-900 font-bold py-3 px-8 rounded-full transition shadow-lg flex items-center justify-center">
                        立即進入探索基地 <i class="fas fa-rocket ml-2"></i>
                    </a>
                    <a href="#about" class="bg-white/20 hover:bg-white/30 backdrop-blur text-white font-bold py-3 px-8 rounded-full transition border border-white/50">
                        了解理念
                    </a>
                </div>
            </div>
            <div class="md:w-1/2 mt-12 md:mt-0 flex justify-center relative">
                <div class="animate-float text-9xl text-yellow-300/20 absolute -top-10">
                    <i class="fas fa-user-astronaut"></i>
                </div>
                <div class="bg-white/10 p-8 rounded-3xl backdrop-blur-xl border border-white/20 shadow-2xl">
                    <img src="https://images.unsplash.com/photo-1451187580459-43490279c0fa?auto=format&fit=crop&q=80&w=600" alt="宇宙科學" class="rounded-2xl shadow-lg border-4 border-white/30 max-w-full h-auto">
                </div>
            </div>
        </div>
    </header>

    <!-- 核心理念 -->
    <section id="about" class="py-20 px-4 bg-white">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-3xl font-bold mb-10 text-gray-900 underline decoration-indigo-500 decoration-4 underline-offset-8">
                什麼是「老董科學」？
            </h2>
            <div class="bg-indigo-50 p-8 rounded-2xl border-l-8 border-indigo-500 shadow-sm italic text-xl text-gray-700 mb-10">
                「如果一個科學概念不能解釋給小學生聽，那就代表我們還不夠了解它。」
            </div>
            <p class="text-gray-600 leading-relaxed text-lg">
                這是一個由科學愛好者「老董」親自打造的科普探索基地。我們相信科學不應該關在實驗室裡，也不應該只出現在考試卷上。科學是我們對宇宙發出的第一個「為什麼」。
            </p>
        </div>
    </section>

    <!-- 特色介紹 -->
    <section id="features" class="py-20 px-4 bg-gray-50">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-3xl font-bold text-center mb-16">我們如何讓科學變有趣？</h2>
            <div class="grid md:grid-cols-3 gap-8">
                
                <!-- 特色 1 -->
                <div class="bg-white p-8 rounded-2xl shadow-md card-hover border-b-4 border-blue-500">
                    <div class="w-16 h-16 bg-blue-100 text-blue-600 rounded-2xl flex items-center justify-center text-3xl mb-6">
                        <i class="fas fa-magic"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4 text-gray-900">降維打擊</h3>
                    <p class="text-gray-600">專門處理像是「量子力學」這種聽起來很恐怖的名詞。我們把概念變成樂高積木，讓你一眼看穿真相。</p>
                </div>

                <!-- 特色 2 -->
                <div class="bg-white p-8 rounded-2xl shadow-md card-hover border-b-4 border-green-500">
                    <div class="w-16 h-16 bg-green-100 text-green-600 rounded-2xl flex items-center justify-center text-3xl mb-6">
                        <i class="fas fa-calculator"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4 text-gray-900">數學新視角</h3>
                    <p class="text-gray-600">數學是觀察世界的「另一雙眼睛」。我們不教算術，我們教你如何用數學在生活中贏得優勢。</p>
                </div>

                <!-- 特色 3 -->
                <div class="bg-white p-8 rounded-2xl shadow-md card-hover border-b-4 border-purple-500">
                    <div class="w-16 h-16 bg-purple-100 text-purple-600 rounded-2xl flex items-center justify-center text-3xl mb-6">
                        <i class="fas fa-comments"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4 text-gray-900">大師小劇場</h3>
                    <p class="text-gray-600">想看牛頓跟愛因斯坦吵架？透過趣味的時空對話，讓科學巨頭親自教你最硬核的科學知識。</p>
                </div>

            </div>
        </div>
    </section>

    <!-- 呼籲行動 -->
    <section id="contact" class="py-20 px-4">
        <div class="max-w-4xl mx-auto bg-indigo-900 rounded-3xl p-10 md:p-16 text-center text-white shadow-2xl relative overflow-hidden">
            <div class="absolute top-0 right-0 p-4 opacity-10 text-9xl">
                <i class="fas fa-lightbulb"></i>
            </div>
            <h2 class="text-3xl font-bold mb-6">準備好讓大腦超進化了嗎？</h2>
            <p class="text-indigo-200 text-lg mb-10">
                點擊下方按鈕，直接進入我們的科學個人化檔案，查看更多精彩專案！
            </p>
            <div class="flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-4">
                <a href="https://jamietung.github.io/my-explorerProfile/" target="_blank" class="bg-pink-500 hover:bg-pink-400 text-white font-bold py-3 px-10 rounded-full transition flex items-center justify-center shadow-lg">
                    <i class="fas fa-door-open mr-2"></i> 進入老董科學官網
                </a>
                <button onclick="showMessage('宇宙探險即將開始！')" class="bg-white text-indigo-900 font-bold py-3 px-8 rounded-full transition flex items-center justify-center">
                    <i class="fas fa-heart mr-2"></i> 給予鼓勵
                </button>
            </div>
        </div>
    </section>

    <!-- 頁尾 -->
    <footer class="bg-gray-900 text-gray-400 py-10 px-4 text-center">
        <div class="mb-6">
            <a href="https://jamietung.github.io/my-explorerProfile/" target="_blank" class="text-white hover:text-indigo-400 transition font-bold">老董科學官方基地</a>
        </div>
        <p>© 2025 老董科學 - 用好奇心點燃科學之火</p>
        <div class="mt-4 flex justify-center space-x-6 text-xl">
            <a href="https://jamietung.github.io/my-explorerProfile/" target="_blank" class="hover:text-white"><i class="fas fa-globe"></i></a>
            <a href="#" class="hover:text-white"><i class="fab fa-github"></i></a>
            <a href="#" class="hover:text-white"><i class="fas fa-envelope"></i></a>
        </div>
    </footer>

    <!-- 提示框 -->
    <div id="toast" class="fixed bottom-10 left-1/2 transform -translate-x-1/2 bg-gray-800 text-white px-6 py-3 rounded-full shadow-2xl hidden z-50 transition-all duration-300">
        <span id="toast-message"></span>
    </div>

    <script>
        function showMessage(msg) {
            const toast = document.getElementById('toast');
            const toastMsg = document.getElementById('toast-message');
            toastMsg.innerText = msg;
            toast.classList.remove('hidden');
            toast.classList.add('animate-bounce');
            
            setTimeout(() => {
                toast.classList.add('hidden');
                toast.classList.remove('animate-bounce');
            }, 3000);
        }
    </script>
</body>
</html>
