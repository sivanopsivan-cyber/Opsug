# Opsug
website created me
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OP SIVAN - Official Website</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
    </style>
</head>
<body class="bg-slate-950 text-slate-100 min-h-screen flex flex-col justify-between selection:bg-purple-500 selection:text-white">
    <!-- Cinematic Opening Splash Overlay with Smoke Portal Effect -->
    <div id="intro-splash" class="fixed inset-0 z-50 bg-slate-950 flex flex-col items-center justify-center transition-all duration-1000 overflow-hidden">
        <div class="absolute inset-0 bg-[radial-gradient(ellipse_at_center,_var(--tw-gradient-stops))] from-purple-900/40 via-slate-950/90 to-slate-950 animate-pulse"></div>
        <div class="relative flex flex-col items-center z-10 scale-100 transition-transform duration-700 px-6 text-center" id="portal-card">
            <h1 class="text-4xl md:text-6xl font-extrabold tracking-widest bg-gradient-to-r from-cyan-400 via-purple-400 to-pink-500 bg-clip-text text-transparent mb-3 drop-shadow-[2px_2px_rgba(255,0,85,0.7)]">OP SIVAN</h1>
            <p class="text-purple-300 text-xs md:text-sm tracking-[0.3em] uppercase font-bold mb-8">FREE FIRE GAMING HUB</p>
            <div class="flex justify-center w-full max-w-sm">
                <button onclick="enterWebsite()" class="w-full py-4 bg-gradient-to-r from-purple-600 via-indigo-600 to-pink-600 hover:from-purple-500 hover:to-pink-500 rounded-2xl text-base font-extrabold text-white transition shadow-[0_0_30px_rgba(168,85,247,0.5)] transform hover:-translate-y-0.5">
                    ENTER WEBSITE
                </button>
            </div>
        </div>
    </div>

    <script>
        function enterWebsite() {
            const card = document.getElementById('portal-card');
            const splash = document.getElementById('intro-splash');
            card.style.transform = 'scale(1.1)';
            card.style.opacity = '0';
            splash.style.opacity = '0';
            setTimeout(() => {
                splash.style.display = 'none';
            }, 600);
        }

        function triggerOpen() {
            window.open('https://sub4unlock.com/S/2731v', '_blank');
        }
    </script>

    <!-- Header / Nav -->
    <header class="border-b border-slate-900 bg-slate-950/80 backdrop-blur sticky top-0 z-40">
        <div class="max-w-6xl mx-auto px-6 py-4 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-purple-600 to-pink-600 flex items-center justify-center font-extrabold text-lg shadow-lg shadow-purple-900/50">
                    OS
                </div>
                <span class="font-extrabold tracking-wider text-lg bg-gradient-to-r from-white to-slate-300 bg-clip-text text-transparent">OP SIVAN</span>
            </div>
            <nav class="hidden md:flex items-center space-x-8 text-sm font-semibold text-slate-400">
                <a href="#about" class="hover:text-purple-400 transition">About</a>
                <a href="#games" class="hover:text-purple-400 transition">Downloads</a>
                <a href="https://sub4unlock.com/S/2731v" target="_blank" class="text-purple-400 hover:text-purple-300 transition">Sub4Unlock</a>
            </nav>
            <a href="https://sub4unlock.com/S/2731v" target="_blank" class="bg-purple-600 hover:bg-purple-500 text-white text-sm font-bold py-2.5 px-5 rounded-xl transition shadow-lg shadow-purple-900/30">
                Open App
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <main class="flex-grow">
        <section class="max-w-6xl mx-auto px-6 py-20 flex flex-col items-center text-center">
            <div class="inline-flex items-center space-x-2 bg-purple-950/60 border border-purple-500/30 px-4 py-2 rounded-full text-purple-300 text-xs font-bold uppercase tracking-wider mb-6 shadow-inner">
                <span class="w-2 h-2 rounded-full bg-purple-400 animate-ping"></span>
                <span>Official Free Fire Hub</span>
            </div>
            <h1 class="text-4xl md:text-7xl font-extrabold tracking-tight mb-6 max-w-4xl">
                Welcome to <span class="bg-gradient-to-r from-purple-400 via-pink-500 to-cyan-400 bg-clip-text text-transparent">OP SIVAN Website</span>
            </h1>
            <p class="text-slate-400 text-base md:text-lg max-w-2xl mb-10 leading-relaxed">
                Exclusive Free Fire custom matches, downloads, and community highlights by OP SIVAN.
            </p>
            <div class="flex flex-col sm:flex-row gap-4 w-full sm:w-auto">
                <button onclick="triggerOpen()" class="bg-gradient-to-r from-purple-600 via-indigo-600 to-pink-600 hover:from-purple-500 hover:to-pink-500 text-white font-extrabold py-4 px-8 rounded-2xl transition shadow-[0_0_25px_rgba(168,85,247,0.4)]">
                    GET STARTED / DOWNLOAD
                </button>
            </div>
        </section>

        <!-- Games Section -->
        <section id="games" class="max-w-6xl mx-auto px-6 py-16 border-t border-slate-900">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-extrabold mb-4">Featured Games & Downloads</h2>
                <p class="text-slate-400 max-w-xl mx-auto">Access your exclusive downloads and gaming content right here.</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-4 max-w-6xl mx-auto gap-6">
                <div class="bg-gradient-to-br from-purple-900/40 to-slate-900 border border-purple-500/30 p-6 rounded-2xl flex flex-col justify-between">
                    <div>
                        <div class="text-purple-400 font-bold text-xs mb-2">EXCLUSIVE APP</div>
                        <h3 class="text-xl font-bold mb-3">OLD FF DOWNLOAD WITH OUT KEY</h3>
                        <p class="text-slate-300 text-xs mb-6">Get direct access to the latest version via Sub4Unlock.</p>
                    </div>
                    <button onclick="triggerOpen()" class="bg-purple-600 hover:bg-purple-500 text-center text-white font-semibold py-2.5 px-4 rounded-xl transition shadow-lg shadow-purple-900/30 text-sm">Download Now</button>
                </div>
                <div class="bg-gradient-to-br from-indigo-900/40 to-slate-900 border border-indigo-500/30 p-6 rounded-2xl flex flex-col justify-between">
                    <div>
                        <div class="text-indigo-400 font-bold text-xs mb-2">EXCLUSIVE APP</div>
                        <h3 class="text-xl font-bold mb-3">OLD FF DOWNLOAD</h3>
                        <p class="text-slate-300 text-xs mb-6">Alternative link access via Sub4Unlock.</p>
                    </div>
                    <button onclick="window.open('https://sub4unlock.com/S/47337', '_blank')" class="bg-indigo-600 hover:bg-indigo-500 text-center text-white font-semibold py-2.5 px-4 rounded-xl transition shadow-lg shadow-indigo-900/30 text-sm">Download Now</button>
                </div>
                <div class="bg-gradient-to-br from-pink-900/40 to-slate-900 border border-pink-500/30 p-6 rounded-2xl flex flex-col justify-between">
                    <div>
                        <div class="text-pink-400 font-bold text-xs mb-2">EXCLUSIVE APP</div>
                        <h3 class="text-xl font-bold mb-3">SECOND OLD FF KEY</h3>
                        <p class="text-slate-300 text-xs mb-6">Access the nostalgic registration portal directly.</p>
                    </div>
                    <button onclick="window.open('https://register.nostalgicffindia.online/', '_blank')" class="bg-pink-600 hover:bg-pink-500 text-center text-white font-semibold py-2.5 px-4 rounded-xl transition shadow-lg shadow-pink-900/30 text-sm">Download Now</button>
                </div>
                <div class="bg-gradient-to-br from-cyan-900/40 to-slate-900 border border-cyan-500/30 p-6 rounded-2xl flex flex-col justify-between">
                    <div>
                        <div class="text-cyan-400 font-bold text-xs mb-2">EXCLUSIVE APP</div>
                        <h3 class="text-xl font-bold mb-3">SKIN TOOL</h3>
                        <p class="text-slate-300 text-xs mb-6">Explore custom skins and mods via KenModz.</p>
                    </div>
                    <button onclick="window.open('https://kenmodz.com/', '_blank')" class="bg-cyan-600 hover:bg-cyan-500 text-center text-white font-semibold py-2.5 px-4 rounded-xl transition shadow-lg shadow-cyan-900/30 text-sm">Download Now</button>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="border-t border-slate-900 bg-slate-950 py-8 text-center text-sm text-slate-500">
        <div class="max-w-6xl mx-auto px-6 flex flex-col sm:flex-row items-center justify-between gap-4">
            <p>&copy; 2026 OP SIVAN. All rights reserved.</p>
            <div class="flex space-x-6">
                <a href="https://sub4unlock.com/S/2731v" target="_blank" class="hover:text-purple-400 transition">App Download</a>
                <a href="#about" class="hover:text-purple-400 transition">About</a>
            </div>
        </div>
    </footer>
</body>
</html>
```
