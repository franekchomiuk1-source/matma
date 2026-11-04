<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instytut Analizy Matematycznej — Portal Weryfikacji Kompetencji</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for Academic & UI Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts: Inter & Serif for equations/titles -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600;700;800;900&family=Inter:wght@300;400;500;600;700&family=Playfair+Display:ital,wght@0,600;0,700;1,400&family=Roboto+Mono:wght@400;500&display=swap" rel="stylesheet">
    <!-- Canvas Confetti Library -->
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        academic: {
                            50: '#f4f6f9',
                            100: '#e5e9f0',
                            800: '#1e293b',
                            900: '#0f172a',
                            gold: '#d4af37',
                            goldHover: '#b89528'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        mono: ['Roboto Mono', 'monospace'],
                        serif: ['Playfair Display', 'serif'],
                        cinzel: ['Cinzel', 'serif']
                    }
                }
            }
        }
    </script>
    <style>
        .math-symbol {
            font-family: 'Playfair Display', Georgia, serif;
            font-style: italic;
        }
        
        .gold-glow {
            text-shadow: 0 0 20px rgba(212, 175, 55, 0.4), 0 0 40px rgba(212, 175, 55, 0.2);
        }

        .gold-border-glow {
            box-shadow: 0 0 25px rgba(212, 175, 55, 0.25);
        }

        @keyframes pulse-subtle {
            0%, 100% { opacity: 1; transform: scale(1); }
            50% { opacity: 0.85; transform: scale(0.98); }
        }

        .animate-pulse-subtle {
            animation: pulse-subtle 3s infinite ease-in-out;
        }

        .glass-dark {
            background: rgba(15, 23, 42, 0.95);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
        }

        .shimmer {
            position: relative;
            overflow: hidden;
        }
        .shimmer::after {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(
                60deg,
                transparent 30%,
                rgba(255, 255, 255, 0.15) 50%,
                transparent 70%
            );
            transform: rotate(30deg);
            animation: shimmerEffect 4s infinite;
        }
        @keyframes shimmerEffect {
            0% { transform: translate(-100%, -100%) rotate(30deg); }
            100% { transform: translate(100%, 100%) rotate(30deg); }
        }
    </style>
</head>
<body class="bg-slate-950 text-slate-100 font-sans antialiased selection:bg-amber-500 selection:text-slate-950 min-h-screen flex flex-col justify-between overflow-x-hidden">

    <!-- CANVAS DLA TŁA ZAPROSZENIA (GWIAZDY / CZĄSTECZKI) -->
    <canvas id="starCanvas" class="fixed inset-0 pointer-events-none z-40 opacity-0 transition-opacity duration-1000"></canvas>

    <!-- Pasek Górny (Oficjalny Nagłówek Portalu) -->
    <header class="border-b border-slate-800 bg-slate-900/80 backdrop-blur-md sticky top-0 z-30 transition-all duration-500" id="mainHeader">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <div class="w-10 h-10 rounded-lg bg-gradient-to-br from-blue-700 to-indigo-900 flex items-center justify-center shadow-inner border border-blue-500/30">
                    <i class="fa-solid font-mono text-xl font-bold text-blue-200">∫</i>
                </div>
                <div>
                    <span class="text-xs uppercase tracking-widest text-blue-400 font-semibold block leading-none">Międzyuczelniany System</span>
                    <h1 class="text-base font-bold text-slate-100 tracking-tight">Instytut Analizy Matematycznej</h1>
                </div>
            </div>
            <div class="hidden md:flex items-center space-x-6 text-xs text-slate-400">
                <span class="flex items-center gap-1.5"><i class="fa-solid fa-shield-halved text-emerald-400"></i> Certyfikat ISO-9001:2026</span>
                <span class="flex items-center gap-1.5"><i class="fa-solid fa-network-wired text-blue-400"></i> IAM-Node: #884-PL</span>
                <span class="px-2.5 py-1 rounded-full bg-slate-800 border border-slate-700 text-slate-300 font-mono">v4.12.0</span>
            </div>
        </div>
    </header>

    <!-- Główna Zawartość Matematyczna (Strona Podstępna) -->
    <main class="flex-grow flex items-center justify-center p-4 sm:p-6 lg:p-8" id="mathPortalContainer">
        <div class="max-w-3xl w-full bg-slate-900 border border-slate-800 rounded-2xl shadow-2xl p-6 sm:p-10 relative overflow-hidden transition-all duration-500">
            
            <!-- Subtelny pasek stanu naukowego -->
            <div class="flex items-center justify-between pb-6 mb-6 border-b border-slate-800/80 text-xs text-slate-400">
                <div class="flex items-center gap-2">
                    <span class="inline-block w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></span>
                    <span>Weryfikacja Tożsamości Akademickiej</span>
                </div>
                <span class="font-mono text-slate-500">ID Zadania: EXAM-2027-STAT</span>
            </div>

            <!-- Nagłówek Zadania -->
            <div class="mb-8">
                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-md bg-blue-950/60 border border-blue-800/40 text-blue-300 text-xs font-mono mb-3">
                    <i class="fa-solid fa-graduation-cap"></i>
                    <span>Zadanie 2.10 d) — Zakres rozszerzony</span>
                </div>
                <h2 class="text-xl sm:text-2xl font-bold text-slate-100 leading-snug">
                    Test Kompetencji Analitycznych: Oblicz Wartość Wyrażenia
                </h2>
                <p class="text-slate-400 text-sm mt-2">
                    Wykaż, że wartość danego wyrażenia jest liczbą całkowitą (lub wskaż właściwą postać analityczną).
                </p>
            </div>

            <!-- Prezentacja Wzoru Matematycznego -->
            <div class="bg-slate-950 border border-slate-800 rounded-xl p-6 sm:p-8 mb-8 text-center shadow-inner relative group">
                <div class="text-xs uppercase tracking-wider text-slate-500 mb-4 font-mono">Wyrażenie logarytmiczne</div>
                
                <!-- Wzór matematyczny składany stylizowanymi czcionkami -->
                <div class="text-2xl sm:text-3xl md:text-4xl text-slate-100 font-serif tracking-wide py-2 flex items-center justify-center gap-3 flex-wrap">
                    <span>log<sub>3</sub><sup>2</sup>18</span>
                    <span class="text-slate-500">+</span>
                    <span>log<sub>3</sub><sup>2</sup>2</span>
                    <span class="text-slate-500">&minus;</span>
                    <div class="inline-flex items-center gap-2">
                        <span class="text-3xl font-light text-slate-600">(</span>
                        <span>log<sub>3</sub>2 &minus; 2</span>
                        <span class="text-3xl font-light text-slate-600">)</span>
                    </div>
                    <span class="text-slate-500">&middot;</span>
                    <span>log<sub>3</sub>4</span>
                    <span class="text-slate-500">= ?</span>
                </div>
                
                <div class="mt-4 text-xs font-mono text-slate-500"></div>
            </div>

            <!-- Opcje Odpowiedzi -->
            <div class="space-y-3 mb-8" id="optionsContainer">
                <button onclick="handleAnswerSelect('A')" class="w-full text-left p-4 rounded-xl border border-slate-800 bg-slate-800/40 hover:bg-slate-800 hover:border-blue-500/50 transition-all flex items-center justify-between group cursor-pointer">
                    <div class="flex items-center gap-3">
                        <span class="w-8 h-8 rounded-lg bg-slate-800 group-hover:bg-blue-600 group-hover:text-white border border-slate-700 flex items-center justify-center text-sm font-mono text-slate-300 font-bold transition-colors">A</span>
                        <span class="font-mono text-slate-200">W = 4</span>
                    </div>
                    <i class="fa-solid fa-chevron-right text-slate-600 group-hover:text-blue-400 transition-colors text-sm"></i>
                </button>

                <button onclick="handleAnswerSelect('B')" class="w-full text-left p-4 rounded-xl border border-slate-800 bg-slate-800/40 hover:bg-slate-800 hover:border-blue-500/50 transition-all flex items-center justify-between group cursor-pointer">
                    <div class="flex items-center gap-3">
                        <span class="w-8 h-8 rounded-lg bg-slate-800 group-hover:bg-blue-600 group-hover:text-white border border-slate-700 flex items-center justify-center text-sm font-mono text-slate-300 font-bold transition-colors">B</span>
                        <span class="font-mono text-slate-200">W = 4 + 8 log<sub>3</sub>2</span>
                    </div>
                    <i class="fa-solid fa-chevron-right text-slate-600 group-hover:text-blue-400 transition-colors text-sm"></i>
                </button>

                <button onclick="handleAnswerSelect('C')" class="w-full text-left p-4 rounded-xl border border-slate-800 bg-slate-800/40 hover:bg-slate-800 hover:border-blue-500/50 transition-all flex items-center justify-between group cursor-pointer">
                    <div class="flex items-center gap-3">
                        <span class="w-8 h-8 rounded-lg bg-slate-800 group-hover:bg-blue-600 group-hover:text-white border border-slate-700 flex items-center justify-center text-sm font-mono text-slate-300 font-bold transition-colors">C</span>
                        <span class="font-mono text-slate-200">W = 8</span>
                    </div>
                    <i class="fa-solid fa-chevron-right text-slate-600 group-hover:text-blue-400 transition-colors text-sm"></i>
                </button>

                <button onclick="handleAnswerSelect('D')" class="w-full text-left p-4 rounded-xl border border-slate-800 bg-slate-800/40 hover:bg-slate-800 hover:border-blue-500/50 transition-all flex items-center justify-between group cursor-pointer">
                    <div class="flex items-center gap-3">
                        <span class="w-8 h-8 rounded-lg bg-slate-800 group-hover:bg-blue-600 group-hover:text-white border border-slate-700 flex items-center justify-center text-sm font-mono text-slate-300 font-bold transition-colors">D</span>
                        <span class="font-mono text-slate-200">W = 2 log<sub>3</sub>2</span>
                    </div>
                    <i class="fa-solid fa-chevron-right text-slate-600 group-hover:text-blue-400 transition-colors text-sm"></i>
                </button>
            </div>

            <!-- Stopka informacyjna -->
            <div class="text-center text-xs text-slate-500 pt-4 border-t border-slate-800/60 font-mono">
                System Oceny Automatycznej IAM &copy; 2026. Wszelkie prawa zastrzeżone.
            </div>
        </div>
    </main>

    <!-- Pasek dolny (oficjalne dane) -->
    <footer class="border-t border-slate-800/80 bg-slate-900/50 py-3 text-center text-xs text-slate-500 font-mono" id="mainFooter">
        Serwer: node-08.iam-edu.pl | Szyfrowanie SSL 256-bit | Sesja bezpieczna
    </footer>

    <!-- OVERLAY PROCESOWANIA / ŁADOWANIA -->
    <div id="loadingOverlay" class="fixed inset-0 bg-slate-950/90 backdrop-blur-xl z-50 hidden flex-col items-center justify-center p-6 text-center">
        <div class="w-16 h-16 border-4 border-blue-500/20 border-t-blue-500 rounded-full animate-spin mb-6"></div>
        <div class="text-lg font-bold text-slate-100 font-mono mb-2" id="loadingTitle">Przetwarzanie wyników testu...</div>
        <div class="text-xs text-slate-400 font-mono max-w-sm mb-4" id="loadingStatus">
            Analiza rekurencyjna macierzy odpowiedzi...
        </div>
        <div class="w-64 h-1.5 bg-slate-800 rounded-full overflow-hidden">
            <div id="progressBar" class="h-full bg-gradient-to-r from-blue-500 to-indigo-500 w-0 transition-all duration-300"></div>
        </div>
    </div>

    <!-- NIESPODZIANKA: PEŁNOEKRANOWE ZAPROSZENIE NA STUDNIÓWKĘ -->
    <div id="invitationOverlay" class="fixed inset-0 z-50 glass-dark hidden opacity-0 transition-opacity duration-1000 flex flex-col items-center justify-center p-4 sm:p-8 text-center overflow-y-auto">
        <div class="max-w-3xl w-full my-auto py-8 px-4 flex flex-col items-center relative">
            
            <div class="w-16 h-16 sm:w-20 sm:h-20 rounded-full bg-amber-500/10 border-2 border-amber-400/40 flex items-center justify-center mb-6 shadow-2xl animate-pulse-subtle gold-border-glow">
                <i class="fa-solid fa-crown text-3xl sm:text-4xl text-amber-400"></i>
            </div>

            <p class="text-amber-400/90 font-mono text-xs sm:text-sm uppercase tracking-[0.3em] mb-4 font-semibold">
                — Certyfikat Oficjalny —
            </p>

            <h1 class="text-3xl sm:text-5xl md:text-6xl lg:text-7xl font-extrabold font-cinzel text-transparent bg-clip-text bg-gradient-to-r from-amber-200 via-amber-400 to-amber-100 gold-glow leading-tight sm:leading-none mb-6">
                ZAPRASZAMY PANIĄ<br/>NA STUDNIÓWKĘ!
            </h1>

            <div class="w-32 h-0.5 bg-gradient-to-r from-transparent via-amber-400 to-transparent my-4"></div>

            <p class="text-slate-200 text-base sm:text-xl font-serif max-w-xl italic leading-relaxed my-4">
                Weryfikacja matematyczna powiodła się znakomicie! <br class="hidden sm:inline"/>
                To byłoby ogromnym honorem, gdyby zechciała Pani towarzyszyć nam podczas tego wyjątkowego, balowego wieczoru.
            </p>

            <div class="mt-4 mb-8 p-4 sm:p-6 bg-slate-900/80 border border-amber-500/30 rounded-2xl max-w-md w-full text-left space-y-3 font-sans text-xs sm:text-sm text-slate-300 shadow-xl backdrop-blur-md">
                <div class="flex items-center gap-3">
                    <i class="fa-solid fa-calendar-star text-amber-400 text-base w-5 text-center"></i>
                    <span><strong>Data:</strong> 1 Lutego 2027 </span>
                </div>
                <div class="flex items-center gap-3">
                    <i class="fa-solid fa-champagne-glasses text-amber-400 text-base w-5 text-center"></i>
                    <span><strong>Program:</strong> Polonez, wspaniała zabawa & niezapomniana noc</span>
                </div>
                <div class="flex items-center gap-3">
                    <i class="fa-solid fa-heart text-amber-400 text-base w-5 text-center"></i>
                    <span><strong>Wymagany humor:</strong> Znakomity!</span>
                </div>
            </div>

            <div class="flex flex-col sm:flex-row gap-4 w-full max-w-md justify-center items-center">
                <button onclick="acceptInvitation(true)" class="w-full sm:w-auto flex-1 py-4 px-8 rounded-xl bg-gradient-to-r from-amber-500 to-amber-600 hover:from-amber-400 hover:to-amber-500 text-slate-950 font-bold font-sans text-sm sm:text-base tracking-wide shadow-lg hover:shadow-amber-500/30 transform hover:-translate-y-0.5 transition-all shimmer cursor-pointer flex items-center justify-center gap-2">
                    <i class="fa-solid fa-check text-lg"></i>
                    <span>TAK, Z PRZYJEMNOŚCIĄ!</span>
                </button>

                <button onclick="acceptInvitation(false)" class="w-full sm:w-auto flex-1 py-4 px-8 rounded-xl bg-gradient-to-r from-amber-400 to-yellow-500 hover:from-amber-300 hover:to-yellow-400 text-slate-950 font-bold font-sans text-sm sm:text-base tracking-wide shadow-lg hover:shadow-amber-400/30 transform hover:-translate-y-0.5 transition-all shimmer cursor-pointer flex items-center justify-center gap-2">
                    <i class="fa-solid fa-heart text-lg"></i>
                    <span>OCZYWIŚCIE, ŻE TAK!</span>
                </button>
            </div>

            <div id="confirmationMessage" class="hidden mt-6 p-4 rounded-xl bg-emerald-950/80 border border-emerald-500/40 text-emerald-200 font-sans text-sm max-w-md w-full animate-bounce">
                <i class="fa-solid fa-circle-check text-emerald-400 text-lg mr-2"></i>
                <strong>Wspaniale!</strong> Decyzja została zarejestrowana. Widzimy się na balu! 🎉
            </div>

        </div>
    </div>

    <!-- SKRYPT LOGIKI (NAPRAWIONY) -->
    <script>
        function handleAnswerSelect(option) {
            const loadingOverlay = document.getElementById('loadingOverlay');
            const progressBar = document.getElementById('progressBar');
            const loadingStatus = document.getElementById('loadingStatus');

            loadingOverlay.classList.remove('hidden');
            loadingOverlay.classList.add('flex');

            const statuses = [
                "Inicjalizacja algorytmu weryfikacji...",
                "Obliczanie macierzy prawdopodobieństwa...",
                "Sprawdzanie dostępności miejsca na balu...",
                "Generowanie certyfikatu studniówkowego..."
            ];

            let progress = 0;
            let statusIndex = 0;

            const interval = setInterval(() => {
                progress += 25;
                progressBar.style.width = progress + '%';

                if (statusIndex < statuses.length) {
                    loadingStatus.innerText = statuses[statusIndex];
                    statusIndex++;
                }

                if (progress >= 100) {
                    clearInterval(interval);
                    setTimeout(revealInvitation, 400);
                }
            }, 350);
        }

        function revealInvitation() {
            const loadingOverlay = document.getElementById('loadingOverlay');
            const invitationOverlay = document.getElementById('invitationOverlay');
            const starCanvas = document.getElementById('starCanvas');

            loadingOverlay.classList.add('hidden');
            loadingOverlay.classList.remove('flex');

            document.getElementById('mathPortalContainer').style.display = 'none';
            document.getElementById('mainHeader').style.opacity = '0.2';
            document.getElementById('mainFooter').style.opacity = '0.2';

            invitationOverlay.classList.remove('hidden');
            starCanvas.classList.remove('opacity-0');
            starCanvas.classList.add('opacity-100');

            setTimeout(() => {
                invitationOverlay.classList.remove('opacity-0');
                invitationOverlay.classList.add('opacity-100');
            }, 50);

            triggerConfetti();
            initStarCanvas();
        }

        function triggerConfetti() {
            if (typeof confetti === 'function') {
                confetti({
                    particleCount: 120,
                    spread: 80,
                    origin: { y: 0.6 },
                    colors: ['#d4af37', '#fef08a', '#ffffff', '#f59e0b', '#fbbf24']
                });

                setTimeout(() => {
                    confetti({
                        particleCount: 50,
                        angle: 60,
                        spread: 55,
                        origin: { x: 0 },
                        colors: ['#d4af37', '#fef08a', '#ffffff']
                    });
                    confetti({
                        particleCount: 50,
                        angle: 120,
                        spread: 55,
                        origin: { x: 1 },
                        colors: ['#d4af37', '#fef08a', '#ffffff']
                    });
                }, 300);
            }
        }

        function acceptInvitation(isFirstButton) {
            triggerConfetti();
            const confirmationMessage = document.getElementById('confirmationMessage');
            confirmationMessage.classList.remove('hidden');
            
            try {
                const audioCtx = new (window.AudioContext || window.webkitAudioContext)();
                const osc = audioCtx.createOscillator();
                const gain = audioCtx.createGain();
                osc.type = 'triangle';
                osc.frequency.setValueAtTime(523.25, audioCtx.currentTime);
                osc.frequency.exponentialRampToValueAtTime(659.25, audioCtx.currentTime + 0.3);
                gain.gain.setValueAtTime(0.15, audioCtx.currentTime);
                gain.gain.exponentialRampToValueAtTime(0.01, audioCtx.currentTime + 0.5);
                osc.connect(gain);
                gain.connect(audioCtx.destination);
                osc.start();
                osc.stop(audioCtx.currentTime + 0.5);
            } catch(e) {
                // Bezpieczne obejście braku audio
            }
        }

        function initStarCanvas() {
            const canvas = document.getElementById('starCanvas');
            const ctx = canvas.getContext('2d');

            function resize() {
                canvas.width = window.innerWidth;
                canvas.height = window.innerHeight;
            }
            resize();
            window.addEventListener('resize', resize);

            const particles = [];
            const particleCount = 60;

            for (let i = 0; i < particleCount; i++) {
                particles.push({
                    x: Math.random() * canvas.width,
                    y: Math.random() * canvas.height,
                    radius: Math.random() * 2 + 0.5,
                    color: `rgba(212, 175, 55, ${Math.random() * 0.5 + 0.2})`,
                    vy: -(Math.random() * 0.4 + 0.1),
                    vx: (Math.random() - 0.5) * 0.2
                });
            }

            function animate() {
                ctx.clearRect(0, 0, canvas.width, canvas.height);

                particles.forEach(p => {
                    p.y += p.vy;
                    p.x += p.vx;

                    if (p.y < 0) {
                        p.y = canvas.height;
                        p.x = Math.random() * canvas.width;
                    }

                    ctx.beginPath();
                    ctx.arc(p.x, p.y, p.radius, 0, Math.PI * 2);
                    ctx.fillStyle = p.color;
                    ctx.fill();
                });

                requestAnimationFrame(animate);
            }
            animate();
        }
    </script>
</body>
</html>
