<!DOCTYPE html>
<html lang="hi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gargo.net - Aditya Ki Taraf Se Best Websites</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- Phosphor Icons -->
    <script src="https://unpkg.com/@phosphor-icons/web"></script>
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Poppins', 'sans-serif'],
                    },
                    colors: {
                        primary: '#4F46E5', 
                        secondary: '#9333EA', 
                    }
                }
            }
        }
    </script>
    <style>
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #1e293b; }
        ::-webkit-scrollbar-thumb { background: #4F46E5; border-radius: 4px; }
        ::-webkit-scrollbar-thumb:hover { background: #4338ca; }
    </style>
</head>
<body class="bg-slate-900 text-slate-100 font-sans antialiased selection:bg-primary selection:text-white">

    <!-- Navigation Bar -->
    <nav class="fixed w-full z-50 bg-slate-900/90 backdrop-blur-md border-b border-slate-800 transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <!-- Logo -->
                <div class="flex-shrink-0 flex items-center gap-2 cursor-pointer" onclick="window.scrollTo(0,0)">
                    <i class="ph-fill ph-code text-4xl text-primary"></i>
                    <span class="font-bold text-2xl tracking-tight bg-clip-text text-transparent bg-gradient-to-r from-primary to-secondary">
                        Gargo.net
                    </span>
                </div>
                
                <!-- Desktop Menu -->
                <div class="hidden md:flex space-x-8 items-center">
                    <a href="#home" class="text-slate-300 hover:text-white transition-colors duration-200">Home</a>
                    <a href="#services" class="text-slate-300 hover:text-white transition-colors duration-200">Main Kya Karta Hu?</a>
                    <a href="#about" class="text-slate-300 hover:text-white transition-colors duration-200">Mere Baare Mein</a>
                    <a href="#contact" class="bg-primary hover:bg-indigo-500 text-white px-6 py-2.5 rounded-full font-medium transition-all duration-300 shadow-[0_0_15px_rgba(79,70,229,0.4)]">
                        Baat Karein
                    </a>
                </div>

                <!-- Mobile Menu Button -->
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-slate-300 hover:text-white focus:outline-none p-2">
                        <i class="ph ph-list text-3xl" id="menu-icon"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Menu Panel -->
        <div id="mobile-menu" class="hidden md:hidden bg-slate-800 border-b border-slate-700">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3 text-center">
                <a href="#home" class="block px-3 py-2 rounded-md text-base font-medium text-slate-300 hover:text-white hover:bg-slate-700">Home</a>
                <a href="#services" class="block px-3 py-2 rounded-md text-base font-medium text-slate-300 hover:text-white hover:bg-slate-700">Main Kya Karta Hu?</a>
                <a href="#about" class="block px-3 py-2 rounded-md text-base font-medium text-slate-300 hover:text-white hover:bg-slate-700">Mere Baare Mein</a>
                <a href="#contact" class="block px-3 py-2 mt-4 text-center rounded-md text-base font-medium bg-primary text-white hover:bg-indigo-500">Baat Karein</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="relative pt-32 pb-20 lg:pt-48 lg:pb-32 overflow-hidden">
        <div class="absolute top-0 left-1/2 -translate-x-1/2 w-full h-full max-w-7xl pointer-events-none">
            <div class="absolute top-20 left-10 w-72 h-72 bg-primary rounded-full mix-blend-multiply filter blur-[128px] opacity-40"></div>
            <div class="absolute top-20 right-10 w-72 h-72 bg-secondary rounded-full mix-blend-multiply filter blur-[128px] opacity-40"></div>
        </div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 text-center">
            <div class="inline-flex items-center gap-2 px-4 py-2 rounded-full bg-slate-800/50 border border-slate-700 mb-8 backdrop-blur-sm text-sm text-slate-300">
                <span class="flex h-2 w-2 relative">
                    <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-green-400 opacity-75"></span>
                    <span class="relative inline-flex rounded-full h-2 w-2 bg-green-500"></span>
                </span>
                Hi, Main Aditya hu 👋
            </div>
            
            <h1 class="text-5xl md:text-7xl font-bold tracking-tight mb-6">
                Boring Websites Ka Zamana Gaya,<br>
                <span class="text-transparent bg-clip-text bg-gradient-to-r from-primary via-purple-500 to-secondary">
                    Chalo Kuch Zabardast Banate Hain!
                </span>
            </h1>
            
            <p class="mt-4 text-xl text-slate-400 max-w-2xl mx-auto mb-10 leading-relaxed">
                Bhai seedhi baat hai, aajkal website sirf dikhne mein achi nahi honi chahiye, wo fast aur smooth chalni bhi chahiye. Main Gargo.net pe aisi hi premium websites code karta hu jo aapke business ko sach mein faida pahunchaye.
            </p>
            
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <a href="#services" class="px-8 py-4 text-lg font-semibold rounded-full text-white bg-primary hover:bg-indigo-500 transition-all duration-300 shadow-lg shadow-primary/30 hover:-translate-y-1">
                    Mera Kaam Dekho
                </a>
                <a href="#contact" class="px-8 py-4 text-lg font-semibold rounded-full text-slate-300 bg-slate-800 hover:bg-slate-700 border border-slate-700 transition-all duration-300 hover:-translate-y-1">
                    Mujhse Baat Karo
                </a>
            </div>
        </div>
    </section>

    <!-- Services Section
