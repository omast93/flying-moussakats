<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flying Moussakats - Athens Ultimate Frisbee</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Poppins -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;900&display=swap" rel="stylesheet">
    
    <!-- Favicon (Team Logo) -->
    <link rel="icon" href="https://i.imgur.com/2RQ5hYh.png">

    <style>
        body { font-family: 'Poppins', sans-serif; scroll-behavior: smooth; }
        .text-gradient { background: linear-gradient(45deg, #3b82f6, #a855f7); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .fade-in-section { opacity: 0; transform: translateY(20px); transition: opacity 0.6s ease-out, transform 0.6s ease-out; }
        .fade-in-section.is-visible { opacity: 1; transform: translateY(0); }
        .gemini-button::after { content: '✨'; margin-left: 0.5rem; }
    </style>
</head>
<body class="bg-gray-900 text-gray-200">

    <!-- Header -->
    <header id="header" class="bg-gray-900 bg-opacity-80 backdrop-blur-md fixed top-0 left-0 right-0 z-50 transition-all duration-300">
        <div class="container mx-auto px-6 py-3 flex justify-between items-center">
            <a href="#" class="flex items-center gap-3 text-2xl font-bold text-white tracking-wider">
                <!-- LOGO -->
                <img src="https://i.imgur.com/2RQ5hYh.png" alt="Flying Moussakats Logo" class="h-12">
                <span>Flying <span class="text-blue-400">Moussakats</span></span>
            </a>
            <nav class="hidden md:flex space-x-8">
                <a href="#about" class="hover:text-blue-400 transition-colors">About</a>
                <a href="#team" class="hover:text-blue-400 transition-colors">The Team</a>
                <a href="#training" class="hover:text-blue-400 transition-colors">Training Hub</a>
                <a href="#gallery" class="hover:text-blue-400 transition-colors">Gallery</a>
                <a href="#join" class="hover:text-blue-400 transition-colors">Join Us</a>
            </nav>
            <a href="#join" class="hidden md:block bg-blue-600 hover:bg-blue-700 text-white font-semibold py-2 px-5 rounded-lg shadow-lg transition-transform transform hover:scale-105">
                Get In Touch
            </a>
            <button id="mobile-menu-button" class="md:hidden text-white focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden">
            <a href="#about" class="block py-2 px-6 text-sm hover:bg-gray-800">About</a>
            <a href="#team" class="block py-2 px-6 text-sm hover:bg-gray-800">The Team</a>
            <a href="#training" class="block py-2 px-6 text-sm hover:bg-gray-800">Training Hub</a>
            <a href="#gallery" class="block py-2 px-6 text-sm hover:bg-gray-800">Gallery</a>
            <a href="#join" class="block py-2 px-6 text-sm hover:bg-gray-800">Join Us</a>
        </div>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Hero Section con Video de Fondo -->
        <section class="h-screen relative flex items-center justify-center text-center overflow-hidden">
            <!-- Contenedor del video -->
            <div class="absolute top-0 left-0 w-full h-full z-0">
                <video playsinline autoplay muted loop class="w-full h-full object-cover">
                    <!-- VIDEO RESTAURADO A IMGUR Y CON MUTE PARA AUTOPLAY -->
                    <source src="https://i.imgur.com/8lOf53v.mp4" type="video/mp4">
                    Your browser does not support HTML5 video.
                </video>
                <!-- Capa oscura sobre el video para que el texto sea legible -->
                <div class="absolute top-0 left-0 w-full h-full bg-black opacity-50"></div>
            </div>
            
            <!-- Contenido de la sección (título, texto, botones) -->
            <div class="relative z-10 px-4">
                <h1 class="text-5xl md:text-7xl font-black text-white uppercase tracking-tighter">
                    Defying Gravity <br class="hidden md:block"> on the <span class="text-gradient">Athenian Riviera</span>
                </h1>
                <p class="mt-4 text-lg md:text-xl max-w-3xl mx-auto text-gray-300">
                    We are the Flying Moussakats, Athens' most active and passionate Ultimate Frisbee team. We live for the layout, the sky, and the perfect throw.
                </p>
                <div class="mt-8 flex justify-center gap-4">
                    <a href="#join" class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-8 rounded-lg shadow-xl transition-transform transform hover:scale-105 text-lg">
                        Join The Team
                    </a>
                    <a href="#about" class="bg-gray-700 hover:bg-gray-600 text-white font-bold py-3 px-8 rounded-lg shadow-xl transition-transform transform hover:scale-105 text-lg">
                        Learn More
                    </a>
                </div>
            </div>
        </section>

        <!-- About Us Section -->
        <section id="about" class="py-20 fade-in-section">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-4xl font-bold text-white">Our Story</h2>
                    <p class="text-blue-400 font-semibold mt-2">More Than Just a Team</p>
                </div>
                <div class="flex flex-col md:flex-row items-center gap-10">
                    <div class="md:w-1/2">
                        <img src="https://placehold.co/600x400/374151/ffffff?text=Team+Huddle" alt="Team discussing strategy" class="rounded-xl shadow-2xl w-full">
                    </div>
                    <div class="md:w-1/2">
                        <h3 class="text-2xl font-bold text-white mb-4">From a Beach Dream to a Competitive Force</h3>
                        <p class="mb-4 text-gray-300 leading-relaxed">
                            Founded over fifteen years ago by a group of international enthusiasts, our team has become a cornerstone of Ultimate in Greece. Our name, the <strong class="text-white">Flying Moussakats</strong>, is a playful nod to our Greek home and our agile, cat-like reflexes on the field.
                        </p>
                        <p class="text-gray-300 leading-relaxed">
                            We train on the beautiful beaches of Paleo Faliro, where the sand and sea inspire our dynamic style of play. We're a diverse mix of locals and expats, united by our love for the sport and the spirit of the game.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- The Team Section -->
        <section id="team" class="py-20 bg-gray-800 fade-in-section">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-4xl font-bold text-white">The Spirit of the Moussakats</h2>
                    <p class="text-purple-400 font-semibold mt-2">Commitment, Community, Competition</p>
                </div>
                <div class="grid md:grid-cols-3 gap-8 text-center">
                    <div class="bg-gray-900 p-8 rounded-xl shadow-lg transform hover:-translate-y-2 transition-transform">
                        <div class="text-purple-400 mb-4">
                            <svg class="w-16 h-16 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197M15 21v-1a6 6 0 00-5.197-5.975M15 21h3a2 2 0 002-2v-2a2 2 0 00-2-2h-3m-6.045-4.472A4 4 0 0112 11.25a4 4 0 014.045-1.722"></path></svg>
                        </div>
                        <h3 class="text-xl font-bold text-white mb-2">International Community</h3>
                        <p class="text-gray-400">Our strength comes from our diversity. We welcome players from all over the world, creating a rich and supportive family.</p>
                    </div>
                    <div class="bg-gray-900 p-8 rounded-xl shadow-lg transform hover:-translate-y-2 transition-transform">
                        <div class="text-purple-400 mb-4">
                            <svg class="w-16 h-16 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                        </div>
                        <h3 class="text-xl font-bold text-white mb-2">High-Energy Play</h3>
                        <p class="text-gray-400">We are known for our fast-paced, athletic style. Beach training gives us an edge in stamina and agility that we bring to every game.</p>
                    </div>
                    <div class="bg-gray-900 p-8 rounded-xl shadow-lg transform hover:-translate-y-2 transition-transform">
                         <div class="text-purple-400 mb-4">
                             <svg class="w-16 h-16 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"></path></svg>
                        </div>
                        <h3 class="text-xl font-bold text-white mb-2">Spirit of the Game</h3>
                        <p class="text-gray-400">We compete hard but always with respect. Fair play and sportsmanship are the principles we live and play by.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Training Hub Section -->
        <section id="training" class="py-20 fade-in-section">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-4xl font-bold text-white">Training Hub</h2>
                    <p class="text-blue-400 font-semibold mt-2">Drills and Strategies</p>
                </div>
                <div class="max-w-4xl mx-auto bg-gray-800 rounded-xl shadow-2xl p-8">
                    <div class="mb-6">
                        <label class="block text-lg font-semibold text-white mb-2">Select a category to get started:</label>
                        <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                            <button onclick="showDrill('throwing-content')" class="bg-purple-600 hover:bg-purple-700 text-white font-bold py-2 px-4 rounded-lg transition">Throwing</button>
                            <button onclick="showDrill('cutting-content')" class="bg-purple-600 hover:bg-purple-700 text-white font-bold py-2 px-4 rounded-lg transition">Cutting</button>
                            <button onclick="showDrill('defense-content')" class="bg-purple-600 hover:bg-purple-700 text-white font-bold py-2 px-4 rounded-lg transition">Defense</button>
                            <button onclick="showDrill('strategy-content')" class="bg-purple-600 hover:bg-purple-700 text-white font-bold py-2 px-4 rounded-lg transition">Strategy</button>
                        </div>
                    </div>
                    <div id="drill-output" class="mt-6 bg-gray-900 p-6 rounded-lg min-h-[200px] prose prose-invert max-w-none prose-p:text-gray-300 prose-headings:text-white prose-strong:text-white">
                        <!-- Contenido manual se mostrará aquí -->
                    </div>

                    <!-- Contenido Oculto -->
                    <div id="manual-content" class="hidden">
                        <div id="throwing-content">
                            <h2 class="text-2xl font-bold text-white">🔥 THROWING — Sharpen Those Blades</h2>
                            <p>Alright Flying Moussakats, let’s get those throws crispy like a perfectly baked Moussaka!</p>
                            <p>Here are two spicy drills to level up your throwing game:</p>
                            <h3 class="text-xl font-bold mt-4">Drill 1: Athens Accuracy Gauntlet</h3>
                            <p><strong>🎯 Objective:</strong> Improve throwing precision across all angles and distances.</p>
                            <p><strong>🏗️ Setup:</strong> Line of cones every 7 yards, each with a different throw type (backhand, forehand, hammer, scoober). Cutters run lateral routes 10 yards beyond last cone.</p>
                            <p><strong>🚀 Execution:</strong> Start at cone 1, hit a moving cutter with the assigned throw. Sprint to next cone, repeat. Hit all throws in sequence.</p>
                            <p><strong>🔥 Pro Tip:</strong> Add a mark or defender for game-like pressure.</p>
                            <h3 class="text-xl font-bold mt-4">Drill 2: Moving Throw Matrix</h3>
                            <p><strong>🎯 Objective:</strong> Throw accurately on the move while leading a cutter.</p>
                            <p><strong>🏗️ Setup:</strong> 3x3 grid. Handler in the center square, other players in outer squares.</p>
                            <p><strong>🚀 Execution:</strong> Handler calls a square; cutter makes a cut. Handler must hit them in stride, staying in their own square. Swap roles after each throw.</p>
                            <p><strong>🔥 Pro Tip:</strong> Limit steps or add stall count to increase intensity.</p>
                        </div>
                        <div id="cutting-content">
                            <h2 class="text-2xl font-bold text-white">⚡ CUTTING — Get Open or Go Home</h2>
                            <p>Time to shake defenders like they just saw Zeus in a disc jersey.</p>
                            <p>Here are two cutting drills that’ll boost your footwork, timing, and separation:</p>
                            <h3 class="text-xl font-bold mt-4">Drill 1: Double-Cut Dash</h3>
                            <p><strong>🎯 Objective:</strong> Train explosive change of direction and cut timing.</p>
                            <p><strong>🏗️ Setup:</strong> L-shaped cones (10m straight, then 5m lateral).</p>
                            <p><strong>🚀 Execution:</strong> Sprint straight, plant hard, and explode sideways. Receive disc in stride, reset, repeat.</p>
                            <p><strong>🔥 Pro Tip:</strong> Keep your center of gravity low for quicker cuts.</p>
                            <h3 class="text-xl font-bold mt-4">Drill 2: Triangle Cutter Circuit</h3>
                            <p><strong>🎯 Objective:</strong> Develop multi-angle cuts in fluid motion.</p>
                            <p><strong>🏗️ Setup:</strong> Three cones in triangle (horizontal, deep, under).</p>
                            <p><strong>🚀 Execution:</strong> Cut horizontal → deep → under. Final under cut ends with a catch. Rotate roles.</p>
                            <p><strong>🔥 Pro Tip:</strong> Add a passive defender to work on timing and spacing.</p>
                        </div>
                        <div id="defense-content">
                            <h2 class="text-2xl font-bold text-white">🛡️ DEFENSE — Lockdown Mode Activated</h2>
                            <p>Alright Moussakats, time to put the clamps on!</p>
                            <p>These two drills will level up your defensive reads, reactions, and body control:</p>
                            <h3 class="text-xl font-bold mt-4">Drill 1: Mirror Madness</h3>
                            <p><strong>🎯 Objective:</strong> Improve defensive agility and mirroring.</p>
                            <p><strong>🏗️ Setup:</strong> 1v1 inside a 5x5m box.</p>
                            <p><strong>🚀 Execution:</strong> Offense moves freely — cuts, fakes, etc. Defender mirrors every move without fouling. Switch roles after 30–45 seconds.</p>
                            <p><strong>🔥 Pro Tip:</strong> Watch the hips or chest, not the feet.</p>
                            <h3 class="text-xl font-bold mt-4">Drill 2: Force the Sideline</h3>
                            <p><strong>🎯 Objective:</strong> Master the art of applying an effective force.</p>
                            <p><strong>🏗️ Setup:</strong> One handler, one marker. Use sideline as boundary.</p>
                            <p><strong>🚀 Execution:</strong> Marker applies force (home or away). Handler tries to break it — if they do, reset and try again.</p>
                            <p><strong>🔥 Pro Tip:</strong> Keep your stance wide, hands active, and hips low.</p>
                        </div>
                        <div id="strategy-content">
                             <h2 class="text-2xl font-bold text-white">🧠 STRATEGY — Think Like a Champion</h2>
                             <p>Moussakats don’t just run — they outsmart.</p>
                             <p>These drills help build collective rhythm, decision-making, and tactical awareness:</p>
                             <h3 class="text-xl font-bold mt-4">Drill 1: Mini Scrimmage with Constraints</h3>
                             <p><strong>🎯 Objective:</strong> Boost quick thinking and adaptive play.</p>
                             <p><strong>🏗️ Setup:</strong> 4v4 or 5v5, small field, special rules (e.g. no deep throws, 5-second stall).</p>
                             <p><strong>🚀 Execution:</strong> Play under constraints to simulate different game states. Rotate players and change rules every few minutes.</p>
                             <p><strong>🔥 Pro Tip:</strong> Debrief after each game to identify smart plays and poor decisions.</p>
                             <h3 class="text-xl font-bold mt-4">Drill 2: Zone Breaker Simulation</h3>
                             <p><strong>🎯 Objective:</strong> Learn to break through zone defenses with structured movement.</p>
                             <p><strong>🏗️ Setup:</strong> One team sets up a 3-person cup. Offense positions 2 handlers, 2 poppers, 1 deep.</p>
                             <p><strong>🚀 Execution:</strong> Swing the disc and move into soft spots. Use quick resets and patient throws.</p>
                             <p><strong>🔥 Pro Tip:</strong> Poppers must communicate — hand signals help.</p>
                        </div>
                    </div>

                </div>
            </div>
        </section>
        
        <!-- Gallery Section -->
        <section id="gallery" class="py-20 bg-gray-800 fade-in-section">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-4xl font-bold text-white">Moments in Motion</h2>
                    <p class="text-blue-400 font-semibold mt-2">Capturing the Action</p>
                </div>
                <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                    <div class="grid gap-4">
                        <div>
                            <img class="h-auto max-w-full rounded-lg shadow-lg transform hover:scale-105 transition-transform" src="https://placehold.co/500x750/374151/ffffff?text=Greatest" alt="Player catching the disc">
                        </div>
                        <div>
                            <img class="h-auto max-w-full rounded-lg shadow-lg transform hover:scale-105 transition-transform" src="https://placehold.co/500x300/374151/ffffff?text=Layout+Catch" alt="Player making a layout catch">
                        </div>
                    </div>
                    <div class="grid gap-4">
                        <div>
                            <img class="h-auto max-w-full rounded-lg shadow-lg transform hover:scale-105 transition-transform" src="https://placehold.co/500x350/374151/ffffff?text=Team+Cheer" alt="Team celebrating a point">
                        </div>
                        <div>
                            <img class="h-auto max-w-full rounded-lg shadow-lg transform hover:scale-105 transition-transform" src="https://placehold.co/500x700/374151/ffffff?text=Sky+Battle" alt="Two players jumping for the disc">
                        </div>
                    </div>
                    <div class="grid gap-4">
                        <div>
                            <img class="h-auto max-w-full rounded-lg shadow-lg transform hover:scale-105 transition-transform" src="https://placehold.co/500x700/374151/ffffff?text=Huck" alt="Player throwing a long pass (huck)">
                        </div>
                        <div>
                            <img class="h-auto max-w-full rounded-lg shadow-lg transform hover:scale-105 transition-transform" src="https://placehold.co/500x350/374151/ffffff?text=Defense" alt="An intense defensive play">
                        </div>
                    </div>
                     <div class="grid gap-4">
                        <div>
                            <img class="h-auto max-w-full rounded-lg shadow-lg transform hover:scale-105 transition-transform" src="https://placehold.co/500x300/374151/ffffff?text=Beach+Practice" alt="Team practicing on the beach">
                        </div>
                        <div>
                            <img class="h-auto max-w-full rounded-lg shadow-lg transform hover:scale-105 transition-transform" src="https://placehold.co/500x750/374151/ffffff?text=Victory" alt="Team photo after a win">
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Join Us Section -->
        <section id="join" class="py-20 fade-in-section">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-4xl font-bold text-white">Ready to Fly?</h2>
                <p class="mt-4 text-lg max-w-2xl mx-auto text-gray-300">
                    Whether you're a seasoned veteran or have never touched a disc, we're always looking for new members with a positive attitude and a passion for sport. Come to one of our open practices!
                </p>
                <div class="mt-8 flex justify-center flex-wrap gap-4">
                    <a href="mailto:contact@flyingmoussakats.gr?subject=Interested%20in%20Joining" 
                       class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-8 rounded-lg shadow-xl transition-transform transform hover:scale-105 text-lg inline-block">
                        Contact Us & Join
                    </a>
                    <button id="recipe-button" class="gemini-button bg-purple-600 hover:bg-purple-700 text-white font-bold py-3 px-8 rounded-lg shadow-xl transition-transform transform hover:scale-105 text-lg inline-block">
                        Get a Post-Game Moussaka Recipe
                    </button>
                </div>
                <p class="mt-4 text-sm text-gray-400">Drop us an email, or generate a recipe while you think about it!</p>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-900">
    <div class="container mx-auto px-6 py-8">
        <div class="flex flex-col md:flex-row justify-between items-center text-center md:text-left">
            <div class="mb-4 md:mb-0">
                <p class="text-lg font-bold">Flying Moussakats Ultimate</p>
                <p class="text-gray-400">Athens, Greece</p>
            </div>
            <div class="flex justify-center space-x-6 mb-4 md:mb-0">
                <a href="https://www.instagram.com/flyingmoussakats/" class="text-gray-400 hover:text-white transition-colors">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.024.06 1.378.06 3.808s-.012 2.784-.06 3.808c-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.024.048-1.378.06-3.808.06s-2.784-.012-3.808-.06c-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.048-1.024-.06-1.378-.06-3.808s.012-2.784.06-3.808c.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 016.345 2.525c.636-.247 1.363-.416 2.427.465C9.795 2.013 10.148 2 12.315 2zm-1.16 2.32c-1.042.043-1.65.2-2.122.385a3.06 3.06 0 00-1.15.748 3.06 3.06 0 00-.748 1.15c-.185.472-.342 1.08-.385 2.122-.043 1.007-.054 1.35-.054 3.73s.011 2.723.054 3.73c.043 1.042.2 1.65.385 2.122a3.06 3.06 0 00.748 1.15 3.06 3.06 0 001.15.748c.472.185 1.08.342 2.122.385 1.007.043 1.35.054 3.73.054s2.723-.011 3.73-.054c1.042-.043 1.65-.2 2.122-.385a3.06 3.06 0 001.15-.748 3.06 3.06 0 00.748-1.15c.185-.472.342-1.08.385-2.122.043-1.007.054-1.35.054-3.73s-.011-2.723-.054-3.73c-.043-1.042-.2-1.65-.385-2.122a3.06 3.06 0 00-.748-1.15 3.06 3.06 0 00-1.15-.748c-.472-.185-1.08-.342-2.122-.385-1.007-.043-1.35-.054-3.73-.054s-2.723.011-3.73.054zm2.88 1.624a4.348 4.348 0 100 8.696 4.348 4.348 0 000-8.696zM12 15.15a3.15 3.15 0 110-6.3 3.15 3.15 0 010 6.3zm3.438-7.908a1.031 1.031 0 11-2.062 0 1.031 1.031 0 012.062 0z" clip-rule="evenodd" /></svg>
                </a>
                <a href="https://www.tiktok.com/@flying_moussakats" class="text-gray-400 hover:text-white transition-colors">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                        <path d="M12.525 10.36v-2.05h1.762c.07-.468.275-1.258.9-1.916 1.488-1.618 3.32-1.758 3.96-1.785.064 0 .125.006.185.018v2.66c-.1.012-.2.018-.3.018-.895 0-1.428.16-2.006.764-.526.56-.777 1.25-.8 1.932H20v3.42c-2.458-.052-4.008.06-4.996.386-1.19.388-2.164 1.13-2.9 2.22-.72 1.054-1.1 2.3-1.1 3.733V22h-4.2V11.23c-.93.18-2.06.66-3.08 1.776-.79 1.066-1.19 2.22-1.19 3.255V22H2V12.09c0-1.52.4-2.88 1.2-4.05 1-1.39 2.37-2.28 4-2.812A11.026 11.026 0 0112.525 2z"/>
                    </svg>
                </a>
            </div>
            <div class="text-sm text-gray-500">
                &copy; 2024 Flying Moussakats. All Rights Reserved.
            </div>
        </div>
    </div>
</footer>

    <!-- Recipe Modal -->
    <div id="recipe-modal" class="hidden fixed inset-0 bg-black bg-opacity-70 z-50 flex items-center justify-center p-4">
        <div class="bg-gray-800 rounded-2xl shadow-2xl w-full max-w-2xl max-h-[90vh] overflow-y-auto p-8 relative">
            <button onclick="closeModal()" class="absolute top-4 right-4 text-gray-400 hover:text-white">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
            </button>
            <div id="modal-content" class="prose prose-invert max-w-none prose-p:text-gray-300 prose-headings:text-white prose-strong:text-white">
                <!-- RECETA DE MOUSSAKA INTEGRADA Y CORREGIDA -->
                <h2 class="text-3xl font-bold text-center mb-4">The Ultimate Flying Moussakats Fuel-Up!</h2>
                <p class="text-center text-lg mb-6">After a tough game of layouts and skies, you've earned a champion's meal. Time to build the legendary Greek casserole that's as epic as your greatest plays!</p>
                
                <h3 class="text-2xl font-semibold mt-6 mb-3">The Players (Ingredients)</h3>
                
                <strong>For the Meat Sauce (The Offensive Line):</strong>
                <ul class="list-disc list-inside mt-2 mb-4">
                    <li>2 tbsp olive oil</li>
                    <li>1 kg (2.2 lbs) ground beef or lamb (for power!)</li>
                    <li>2 large onions, finely chopped</li>
                    <li>3-4 cloves garlic, minced</li>
                    <li>1 can (400g / 14 oz) chopped tomatoes</li>
                    <li>2 tbsp tomato paste</li>
                    <li>1/2 cup dry red wine (optional, but adds depth)</li>
                    <li>1 tsp cinnamon (the secret weapon!)</li>
                    <li>1/2 tsp allspice</li>
                    <li>Salt and freshly ground black pepper to taste</li>
                    <li>A handful of fresh parsley, chopped</li>
                </ul>

                <strong>For the Veggie Layers (The Midfield):</strong>
                <ul class="list-disc list-inside mt-2 mb-4">
                    <li>3-4 large eggplants, sliced 1 cm thick</li>
                    <li>2-3 large potatoes, peeled and sliced 1 cm thick</li>
                    <li>Olive oil for frying/baking</li>
                    <li>Salt</li>
                </ul>

                <strong>For the Béchamel Topping (The Glorious End Zone Spike):</strong>
                 <ul class="list-disc list-inside mt-2 mb-4">
                    <li>1.5 liters (6 cups) milk</li>
                    <li>150g (10 tbsp) butter</li>
                    <li>150g (1.2 cups) all-purpose flour</li>
                    <li>A pinch of nutmeg</li>
                    <li>2 egg yolks</li>
                    <li>150g (1.5 cups) grated Graviera or Parmesan cheese</li>
                    <li>Salt and white pepper</li>
                </ul>
                
                <h3 class="text-2xl font-semibold mt-6 mb-3">The Game Plan (Instructions)</h3>
                
                <ol class="list-decimal list-inside space-y-4">
                    <li><strong>Prep your Veggies:</strong> Lay the eggplant and potato slices on baking sheets. Brush with olive oil, sprinkle with salt, and bake at 200°C (400°F) for about 20 minutes, until softened and slightly browned. This is way easier than frying! Set aside.</li>
                    <li><strong>Build the Meat Sauce:</strong> In a large pot, heat the 2 tbsp of olive oil. Sauté the onions until soft, then add the garlic for another minute. Add the ground meat and cook until browned. Drain any excess fat. Pour in the wine and let it evaporate. Stir in the tomato paste, canned tomatoes, cinnamon, allspice, salt, and pepper. Simmer for about 30 minutes, until the sauce has thickened. Stir in the fresh parsley at the end.</li>
                    <li><strong>Craft the Legendary Béchamel:</strong> In a saucepan, melt the butter over medium heat. Whisk in the flour and cook for 1-2 minutes to create a roux. Gradually pour in the warm milk, whisking constantly to avoid lumps. Continue to cook, stirring, until the sauce thickens. Remove from heat. Season with salt, pepper, and nutmeg. Let it cool slightly, then whisk in the egg yolks and the grated cheese.</li>
                    <li><strong>Assemble Your Masterpiece:</strong> Preheat your oven to 180°C (350°F). In a large baking dish, create the layers. Start with a layer of potatoes, followed by a layer of eggplants. Top with the entire meat sauce mixture. Add another layer of eggplants. Finally, pour the glorious béchamel sauce over the top, spreading it evenly.</li>
                    <li><strong>Bake to Glory:</strong> Bake for 45-60 minutes, or until the top is a beautiful golden-brown color. <strong>CRUCIAL STEP:</strong> Let the moussaka rest for at least 30-40 minutes before serving. This allows it to set, so you can cut perfect, clean slices. Don't skip this, or you'll have a delicious mess!</li>
                    <li><strong>Victory Meal:</strong> Cut into squares, serve, and enjoy your well-deserved, epic Moussaka!</li>
                </ol>
            </div>
        </div>
    </div>

    <script>
        // Lógica del Training Hub Manual
        function showDrill(contentId) {
            const drillOutput = document.getElementById('drill-output');
            const contentToShow = document.getElementById(contentId).innerHTML;
            drillOutput.innerHTML = contentToShow;
        }

        // --- Moussaka Recipe Modal Logic ---
        document.getElementById('recipe-button').addEventListener('click', () => {
            const modal = document.getElementById('recipe-modal');
            modal.classList.remove('hidden');
        });

        function closeModal() {
            document.getElementById('recipe-modal').classList.add('hidden');
        }

        // --- Standard Page Logic ---
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuButton.addEventListener('click', () => mobileMenu.classList.toggle('hidden'));
        document.querySelectorAll('#mobile-menu a, #mobile-menu-button').forEach(link => {
            link.addEventListener('click', () => {
                if(link.tagName === 'A') {
                   mobileMenu.classList.add('hidden');
                }
            });
        });

        window.addEventListener('scroll', () => {
            const header = document.getElementById('header');
            if (window.scrollY > 50) {
                header.classList.add('py-2');
                header.classList.remove('py-3');
            } else {
                header.classList.add('py-3');
                header.classList.remove('py-2');
            }
        });
        
        const sections = document.querySelectorAll('.fade-in-section');
        const observer = new IntersectionObserver(entries => {
            entries.forEach(entry => {
                if (entry.isIntersecting) entry.target.classList.add('is-visible');
            });
        }, { threshold: 0.1 });
        sections.forEach(section => observer.observe(section));

    </script>
</body>
</html>
