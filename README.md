<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SHADOW | Personal Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts (Cairo & Inter) -->
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;800;900&family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Cairo', sans-serif;
            background-color: #0a0a0c;
            color: #e2e8f0;
        }
        .glow-text {
            text-shadow: 0 0 15px rgba(255, 255, 255, 0.2);
        }
        .dark-card {
            background: rgba(18, 18, 22, 0.7);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }
        .dark-card:hover {
            border-color: rgba(255, 255, 255, 0.25);
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.8);
        }
        .custom-scrollbar::-webkit-scrollbar {
            width: 5px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #0f0f13;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #27272a;
            border-radius: 5px;
        }
    </style>
</head>
<body class="selection:bg-zinc-800 selection:text-white min-h-screen flex flex-col justify-between">

    <!-- Header / Navbar -->
    <nav class="w-full py-6 px-8 flex justify-between items-center border-b border-zinc-800/50 max-w-6xl mx-auto">
        <div class="text-2xl font-black tracking-widest text-white uppercase glow-text">
            S H A D O W<span class="text-zinc-500">.</span>
        </div>
        <div class="flex items-center gap-6 text-sm text-zinc-400 font-semibold">
            <a href="#about" class="hover:text-white transition">عني</a>
            <a href="#projects" class="hover:text-white transition">المشاريع</a>
            <a href="#links" class="hover:text-white transition">التواصل</a>
        </div>
    </nav>

    <!-- Main Container -->
    <main class="max-w-4xl mx-auto px-6 py-12 flex-grow flex flex-col justify-center">

        <!-- Hero Section -->
        <section class="text-center my-12 space-y-6">
            <div class="relative inline-block">
                <div class="w-32 h-32 mx-auto rounded-full overflow-hidden border-2 border-zinc-700 shadow-2xl relative z-10">
                    <img src="https://cdn.phototourl.com/free/2026-09-20-87b0d80a-93d5-4343-b1ac-2e615a471ee0.png" alt="Shadow Avatar" class="w-full h-full object-cover">
                </div>
                <div class="absolute inset-0 bg-white/5 rounded-full blur-xl -z-10"></div>
            </div>
            
            <h1 class="text-4xl md:text-6xl font-black text-white tracking-tight">
                WELCOME TO <span class="text-zinc-500">THE SHADOW</span> ZONE
            </h1>
            <p class="text-zinc-400 text-lg max-w-xl mx-auto font-medium leading-relaxed">
                مساحة شخصية تجمع كل ما يتعلق بمشاريعي، أفكاري التقنية، وهويتي الرقمية.
            </p>
            
            <div class="pt-4 flex justify-center gap-4">
                <a href="#projects" class="px-6 py-3 bg-white text-black font-bold rounded-lg hover:bg-zinc-200 transition shadow-lg">
                    عرض المشاريع 🔥
                </a>
                <a href="#links" class="px-6 py-3 border border-zinc-700 text-zinc-300 font-bold rounded-lg hover:bg-zinc-900 hover:text-white transition">
                    روابط التواصل 🔗
                </a>
            </div>
        </section>

        <!-- Divider -->
        <div class="w-full border-t border-zinc-800/60 my-12"></div>

        <!-- Projects Section -->
        <section id="projects" class="space-y-8">
            <div class="text-right">
                <h2 class="text-2xl font-bold text-white flex items-center gap-3">
                    <i class="fa-solid fa-code text-zinc-500"></i> المشاريع المميزة
                </h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <!-- Lucia Ultra Card -->
                <div class="dark-card p-6 rounded-xl transition duration-300 flex flex-col justify-between">
                    <div class="space-y-4">
                        <div class="flex justify-between items-start">
                            <span class="px-3 py-1 bg-zinc-800 text-xs text-zinc-300 font-mono rounded-full border border-zinc-700">Telethon / Gemini AI</span>
                            <span class="text-zinc-500 text-sm">2026</span>
                        </div>
                        <h3 class="text-xl font-bold text-white">L U C I A   U L T R A 🖤</h3>
                        <p class="text-zinc-400 text-sm leading-relaxed">
                            مساعدة شخصية وبوت يوزر بوت ذكي متكامل يعمل بذكاء اصطناعي، ونظام رد تلقائي دائم، ولوحة تحكم شاملة.
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t border-zinc-800/80 flex justify-between items-center text-sm">
                        <span class="text-emerald-400 font-semibold flex items-center gap-1.5">
                            <span class="w-2 h-2 bg-emerald-500 rounded-full animate-pulse"></span> شغال بامتياز
                        </span>
                        <a href="https://t.me/LUCIA_AI2026_bot" target="_blank" class="text-zinc-300 hover:text-white font-bold flex items-center gap-1">
                            معاينة <i class="fa-solid fa-arrow-up-right-from-square text-xs"></i>
                        </a>
                    </div>
                </div>

                <!-- Custom Portfolio Card -->
                <div class="dark-card p-6 rounded-xl transition duration-300 flex flex-col justify-between">
                    <div class="space-y-4">
                        <div class="flex justify-between items-start">
                            <span class="px-3 py-1 bg-zinc-800 text-xs text-zinc-300 font-mono rounded-full border border-zinc-700">HTML / Tailwind</span>
                            <span class="text-zinc-500 text-sm">2026</span>
                        </div>
                        <h3 class="text-xl font-bold text-white">Shadow Space Website 🌐</h3>
                        <p class="text-zinc-400 text-sm leading-relaxed">
                            الموقع الشخصي الرسمي المصمم بالطابع المظلم الفاخر للتعريف بالحساب والمشاريع الخاصة.
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t border-zinc-800/80 flex justify-between items-center text-sm">
                        <span class="text-zinc-400 font-semibold">موقع شخصي</span>
                        <span class="text-zinc-500">النسخة 1.0</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Divider -->
        <div class="w-full border-t border-zinc-800/60 my-12"></div>

        <!-- Links / Social Section -->
        <section id="links" class="space-y-8">
            <div class="text-right">
                <h2 class="text-2xl font-bold text-white flex items-center gap-3">
                    <i class="fa-solid fa-link text-zinc-500"></i> قنوات التواصل والروابط
                </h2>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <a href="https://t.me/" target="_blank" class="dark-card p-4 rounded-lg flex items-center justify-between hover:bg-zinc-800/50 transition">
                    <div class="flex items-center gap-3">
                        <i class="fa-brands fa-telegram text-2xl text-sky-400"></i>
                        <span class="font-bold text-white">Telegram</span>
                    </div>
                    <i class="fa-solid fa-chevron-left text-zinc-600"></i>
                </a>

                <a href="https://tiktok.com/" target="_blank" class="dark-card p-4 rounded-lg flex items-center justify-between hover:bg-zinc-800/50 transition">
                    <div class="flex items-center gap-3">
                        <i class="fa-brands fa-tiktok text-2xl text-pink-500"></i>
                        <span class="font-bold text-white">TikTok</span>
                    </div>
                    <i class="fa-solid fa-chevron-left text-zinc-600"></i>
                </a>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="w-full py-6 text-center text-zinc-600 text-sm border-t border-zinc-900">
        <p>© 2026 SHADOW. All rights reserved. Powered by Lucia AI 🖤</p>
    </footer>

    <!-- Floating Lucia Widget (Chat Overlay) -->
    <div class="fixed bottom-6 right-6 z-50">
        <!-- Chat Button -->
        <button id="luciaToggle" class="w-14 h-14 bg-zinc-900 border border-zinc-700 text-white rounded-full flex items-center justify-center shadow-2xl hover:scale-105 transition duration-200 relative group">
            <img src="https://cdn.phototourl.com/free/2026-09-20-87b0d80a-93d5-4343-b1ac-2e615a471ee0.png" class="w-full h-full rounded-full object-cover">
            <span class="absolute -top-1 -right-1 w-3.5 h-3.5 bg-emerald-500 border-2 border-black rounded-full"></span>
        </button>

        <!-- Chat Box Window -->
        <div id="luciaBox" class="hidden absolute bottom-20 right-0 w-80 md:w-96 dark-card border border-zinc-700 rounded-2xl shadow-2xl overflow-hidden flex flex-col h-[420px]">
            <!-- Chat Header -->
            <div class="p-4 bg-zinc-900/90 border-b border-zinc-800 flex justify-between items-center">
                <div class="flex items-center gap-3">
                    <div class="w-8 h-8 rounded-full overflow-hidden border border-zinc-700">
                        <img src="https://cdn.phototourl.com/free/2026-09-20-87b0d80a-93d5-4343-b1ac-2e615a471ee0.png" class="w-full h-full object-cover">
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-white leading-none">Lucia AI</h4>
                        <span class="text-[10px] text-zinc-400">مساعدة شادو الخاصة ✨</span>
                    </div>
                </div>
                <button id="closeLucia" class="text-zinc-400 hover:text-white text-lg px-2">&times;</button>
            </div>

            <!-- Chat Messages -->
            <div id="chatMessages" class="p-4 flex-grow overflow-y-auto space-y-3 custom-scrollbar text-xs">
                <div class="bg-zinc-800/80 p-3 rounded-xl rounded-tr-none text-zinc-200 border border-zinc-700/50 max-w-[85%]">
                    🌸 أهلاً بيك في موقع شادو الرسمي! أنا لوسيا، مساعدة شادو الرقمية. تقدر تسيبلي أي رسالة أو استفسار وهشيلها لشادو فوراً 🖤
                </div>
            </div>

            <!-- Chat Input -->
            <div class="p-3 bg-zinc-900/90 border-t border-zinc-800 flex gap-2">
                <input type="text" id="userInput" placeholder="اكتب رسالتك لشادو..." class="flex-grow bg-zinc-800 text-white text-xs px-3 py-2 rounded-lg border border-zinc-700 focus:outline-none focus:border-zinc-500">
                <button id="sendBtn" class="bg-white text-black font-bold px-3 py-2 rounded-lg text-xs hover:bg-zinc-200 transition">إرسال</button>
            </div>
        </div>
    </div>

    <!-- JavaScript logic -->
    <script>
        const luciaToggle = document.getElementById('luciaToggle');
        const luciaBox = document.getElementById('luciaBox');
        const closeLucia = document.getElementById('closeLucia');
        const sendBtn = document.getElementById('sendBtn');
        const userInput = document.getElementById('userInput');
        const chatMessages = document.getElementById('chatMessages');

        luciaToggle.addEventListener('click', () => {
            luciaBox.classList.toggle('hidden');
        });

        closeLucia.addEventListener('click', () => {
            luciaBox.classList.add('hidden');
        });

        function sendMessage() {
            const text = userInput.value.trim();
            if (!text) return;

            // Render User Message
            const userBubble = document.createElement('div');
            userBubble.className = "bg-white text-black font-semibold p-3 rounded-xl rounded-tl-none border border-zinc-200 max-w-[85%] mr-auto text-xs";
            userBubble.innerText = text;
            chatMessages.appendChild(userBubble);

            userInput.value = '';
            chatMessages.scrollTop = chatMessages.scrollHeight;

            // Lucia Auto-Response Simulation
            setTimeout(() => {
                const luciaBubble = document.createElement('div');
                luciaBubble.className = "bg-zinc-800/80 p-3 rounded-xl rounded-tr-none text-zinc-200 border border-zinc-700/50 max-w-[85%] text-xs";
                luciaBubble.innerText = "من عيوني! سجلت رسالتك وهتوصل لشادو أول ما يدخل 🖤✨";
                chatMessages.appendChild(luciaBubble);
                chatMessages.scrollTop = chatMessages.scrollHeight;
            }, 800);
        }

        sendBtn.addEventListener('click', sendMessage);
        userInput.addEventListener('keypress', (e) => {
            if (e.key === 'Enter') sendMessage();
        });
    </script>
</body>
</html>
