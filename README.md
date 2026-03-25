<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NextGen Exporters | Global Telugu Network</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600;700;900&display=swap');
        
        body {
            font-family: 'Outfit', sans-serif;
            scroll-behavior: smooth;
        }

        .brand-navy { color: #0f172a; }
        .bg-brand-navy { background-color: #0f172a; }
        .brand-gold { color: #ca8a04; }
        .bg-brand-gold { background-color: #ca8a04; }

        /* Custom Bright Colors from your Philosophy Graphic */
        .color-vision { background-color: #facc15; } /* Yellow */
        .color-hearing { background-color: #ef4444; } /* Red */
        .color-physical { background-color: #3b82f6; } /* Blue */
        .color-intellectual { background-color: #f97316; } /* Orange */
        .color-speech { background-color: #22c55e; } /* Green */

        .glass {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(241, 245, 249, 1);
        }

        .hero-pattern {
            background-color: #f8fafc;
            background-image: radial-gradient(#cbd5e1 0.5px, transparent 0.5px);
            background-size: 24px 24px;
        }

        .btn-bounce {
            transition: transform 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }
        .btn-bounce:hover {
            transform: scale(1.05);
        }

        .modal-overlay {
            background: rgba(15, 23, 42, 0.8);
            display: none;
            position: fixed;
            inset: 0;
            z-index: 100;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .img-fallback {
            background-color: #e2e8f0;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #64748b;
            font-weight: bold;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body class="bg-white text-slate-900 leading-tight overflow-x-hidden">

    <!-- Navigation -->
    <nav class="fixed top-0 w-full z-50 glass border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <div class="flex items-center gap-3">
                    <img src="WhatsApp Image 2026-03-25 at 1.38.11 PM.jpeg" alt="NextGen Logo" class="h-12 w-auto" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                    <div class="hidden h-10 w-10 bg-brand-navy rounded-full items-center justify-center text-white font-bold">NG</div>
                    <span class="text-xl font-black brand-navy tracking-tight hidden sm:block">NEXTGEN <span class="brand-gold">EXPORTERS</span></span>
                </div>
                
                <div class="hidden lg:flex items-center space-x-8 font-semibold text-sm">
                    <a href="#about" class="hover:brand-gold transition-colors">About</a>
                    <a href="#founder" class="hover:brand-gold transition-colors">Founder</a>
                    <a href="#sectors" class="hover:brand-gold transition-colors">Sectors</a>
                    <a href="#membership" class="bg-brand-gold text-white px-6 py-3 rounded-full btn-bounce shadow-lg">Join @ ₹299</a>
                </div>

                <button class="lg:hidden p-2" onclick="toggleMenu()" aria-label="Toggle Menu">
                    <i data-lucide="menu" id="menu-icon"></i>
                </button>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-nav" class="hidden lg:hidden bg-white border-b border-slate-200 p-6 space-y-4">
            <a href="#about" class="block font-bold" onclick="toggleMenu()">About Community</a>
            <a href="#founder" class="block font-bold" onclick="toggleMenu()">The Founder</a>
            <a href="#sectors" class="block font-bold" onclick="toggleMenu()">Sectors</a>
            <a href="#membership" class="block bg-brand-navy text-white text-center py-4 rounded-xl font-bold" onclick="toggleMenu()">Join Community @ ₹299</a>
        </div>
    </nav>

    <!-- Hero -->
    <header class="hero-pattern pt-32 pb-20 lg:pt-52 lg:pb-32">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div class="space-y-8">
                    <div class="inline-flex items-center gap-2 bg-yellow-100 text-yellow-700 px-4 py-2 rounded-full text-xs font-black uppercase tracking-widest">
                        <i data-lucide="globe" class="w-4 h-4"></i> Built for Telugu Entrepreneurs
                    </div>
                    <h1 class="text-5xl lg:text-7xl font-black brand-navy leading-[0.95]">
                        Build a Global <span class="text-blue-600 underline decoration-yellow-400">Export</span> Business
                    </h1>
                    <p class="text-xl text-slate-600 max-w-xl font-medium leading-relaxed">
                        NextGen Exporters is a global network of Telugu entrepreneurs learning, building, and scaling export businesses together.
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4 pt-4">
                        <a href="#membership" class="bg-brand-navy text-white px-10 py-5 rounded-2xl font-black text-xl text-center shadow-2xl btn-bounce">Join @ ₹299/yr</a>
                        <a href="#workshop" class="bg-white border-4 border-brand-navy text-brand-navy px-10 py-5 rounded-2xl font-black text-xl text-center btn-bounce">Reserve Seat</a>
                    </div>
                    <p class="text-sm font-bold text-slate-400 flex items-center gap-2">
                        <i data-lucide="shield-check" class="text-green-500"></i> Built by a Telugu founder. Designed for exporters worldwide.
                    </p>
                </div>
                <div class="relative group">
                    <div class="absolute -inset-4 bg-brand-gold/20 rounded-[3rem] blur-2xl group-hover:blur-3xl transition-all"></div>
                    <div class="relative bg-white rounded-[2.5rem] overflow-hidden shadow-2xl border-8 border-white">
                        <img src="WhatsApp Image 2026-03-25 at 1.38.11 PM.jpeg" alt="NextGen Main Branding" class="w-full h-auto object-contain" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <div class="hidden h-96 w-full img-fallback">NextGen Exporters Logo</div>
                    </div>
                </div>
            </div>
        </div>
    </header>

    <!-- Philosophy: Challenged Aspired Professional -->
    <section class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-slate-50 rounded-[3rem] p-8 lg:p-20 border border-slate-200">
                <div class="grid lg:grid-cols-2 gap-16 items-center">
                    <div>
                        <h2 class="text-4xl font-black brand-navy mb-8">Profit with Purpose</h2>
                        <div class="space-y-6">
                            <div class="flex gap-6 items-start">
                                <div class="w-12 h-12 color-physical rounded-2xl flex items-center justify-center text-white flex-shrink-0 shadow-lg">
                                    <i data-lucide="hand"></i>
                                </div>
                                <div>
                                    <h4 class="text-xl font-bold brand-navy mb-1">Execution Mindset</h4>
                                    <p class="text-slate-600">Turning Indian manufacturing strength into global healthcare solutions.</p>
                                </div>
                            </div>
                            <div class="flex gap-6 items-start">
                                <div class="w-12 h-12 color-hearing rounded-2xl flex items-center justify-center text-white flex-shrink-0 shadow-lg">
                                    <i data-lucide="ear"></i>
                                </div>
                                <div>
                                    <h4 class="text-xl font-bold brand-navy mb-1">Market Awareness</h4>
                                    <p class="text-slate-600">Listening to global demands and identifying gaps in 120+ countries.</p>
                                </div>
                            </div>
                            <div class="flex gap-6 items-start">
                                <div class="w-12 h-12 color-vision rounded-2xl flex items-center justify-center text-white flex-shrink-0 shadow-lg">
                                    <i data-lucide="eye"></i>
                                </div>
                                <div>
                                    <h4 class="text-xl font-bold brand-navy mb-1">Clear Global Vision</h4>
                                    <p class="text-slate-600">Bridging the gap between beginners and real export opportunities.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="relative">
                        <img src="WhatsApp Image 2026-03-25 at 2.01.20 PM.jpeg" alt="Philosophy Graphic" class="w-full h-auto rounded-full shadow-2xl border-8 border-white" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <div class="hidden h-80 w-80 rounded-full mx-auto img-fallback">Challenged Aspired Professional Graphic</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Section -->
    <section id="about" class="py-24 bg-brand-navy text-white relative overflow-hidden">
        <div class="absolute inset-0 opacity-10 pointer-events-none">
            <svg class="h-full w-full" viewBox="0 0 100 100" preserveAspectRatio="none">
                <defs><pattern id="grid" width="10" height="10" patternUnits="userSpaceOnUse"><path d="M 10 0 L 0 0 0 10" fill="none" stroke="white" stroke-width="0.5"/></pattern></defs>
                <rect width="100" height="100" fill="url(#grid)" />
            </svg>
        </div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="max-w-3xl">
                <h2 class="text-4xl lg:text-5xl font-black mb-8">Bridging the Gap in Telugu Trade</h2>
                <p class="text-xl text-slate-400 mb-12">No unified export-focused Telugu network. No structured guidance. No ecosystem connecting beginners with real global opportunities. Until now.</p>
                
                <div class="grid sm:grid-cols-2 gap-8">
                    <div class="p-8 rounded-3xl bg-white/5 border border-white/10">
                        <i data-lucide="users-2" class="w-10 h-10 brand-gold mb-6"></i>
                        <h4 class="text-xl font-bold mb-4">Unified Network</h4>
                        <p class="text-slate-400">Connecting Telugu entrepreneurs in US, UK, Africa, and the Middle East.</p>
                    </div>
                    <div class="p-8 rounded-3xl bg-white/5 border border-white/10">
                        <i data-lucide="map" class="w-10 h-10 text-blue-500 mb-6"></i>
                        <h4 class="text-xl font-bold mb-4">Global Trade Map</h4>
                        <p class="text-slate-400">Structured guidance for international trade, from licenses to payments.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Founder Section -->
    <section id="founder" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-slate-50 rounded-[3rem] overflow-hidden border border-slate-200">
                <div class="grid lg:grid-cols-2">
                    <div class="h-full bg-slate-200">
                        <img src="WhatsApp Image 2026-03-25 at 1.38.19 PM.jpeg" alt="Akhil Kumar Poannam" class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-700" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                        <div class="hidden h-[600px] w-full img-fallback">Portrait: Akhil Kumar Poannam</div>
                    </div>
                    <div class="p-12 lg:p-20 flex flex-col justify-center">
                        <h2 class="text-4xl font-black brand-navy mb-8 leading-tight">Built from Ground Reality, Not Theory</h2>
                        <div class="space-y-6 text-slate-600 text-lg">
                            <p><span class="font-bold brand-navy">Akhil Kumar Poannam</span> is the Founder & CEO of Akhil Global Exports. He works at the intersection of accessibility, global trade, and healthcare.</p>
                            <p>For 5 years, he has focused on reducing the cost of prosthetics in Africa from $5000 to under $1000 using Indian manufacturing strength.</p>
                            <div class="p-6 bg-brand-gold/10 rounded-2xl border-l-8 border-brand-gold">
                                <p class="brand-navy font-bold italic">"Exports is not a 60-day game. It’s a 60-year opportunity."</p>
                            </div>
                            <div class="pt-8">
                                <img src="WhatsApp Image 2026-03-25 at 1.38.29 PM.jpeg" alt="Akhil Global Exports Logo" class="h-16 w-auto mb-4" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                                <div class="hidden h-16 w-48 img-fallback mb-4 text-xs">Akhil Global Exports Logo</div>
                                <p class="text-xs font-black uppercase tracking-widest text-slate-400">Parent Organization</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Sectors -->
    <section id="sectors" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-4xl lg:text-5xl font-black brand-navy">What We Do</h2>
                <p class="text-slate-500 font-medium mt-4">High-growth sectors powered by the NextGen ecosystem.</p>
            </div>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="p-10 rounded-[2.5rem] bg-blue-50 hover:bg-blue-600 hover:text-white transition-all group">
                    <i data-lucide="heart-pulse" class="w-12 h-12 text-blue-600 group-hover:text-white mb-6"></i>
                    <h4 class="text-2xl font-black mb-2">Healthcare</h4>
                    <p class="opacity-80">Prosthetics, assistive technology, and pharma trade.</p>
                </div>
                <div class="p-10 rounded-[2.5rem] bg-orange-50 hover:bg-orange-600 hover:text-white transition-all group">
                    <i data-lucide="factory" class="w-12 h-12 text-orange-600 group-hover:text-white mb-6"></i>
                    <h4 class="text-2xl font-black mb-2">Manufacturing</h4>
                    <p class="opacity-80">Industrial components and ready-to-use goods.</p>
                </div>
                <div class="p-10 rounded-[2.5rem] bg-green-50 hover:bg-green-600 hover:text-white transition-all group">
                    <i data-lucide="sprout" class="w-12 h-12 text-green-600 group-hover:text-white mb-6"></i>
                    <h4 class="text-2xl font-black mb-2">Agriculture</h4>
                    <p class="opacity-80">Scaling Indian organic produce to global tables.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Membership Card -->
    <section id="membership" class="py-24 bg-slate-50">
        <div class="max-w-4xl mx-auto px-4">
            <div class="bg-brand-navy rounded-[3rem] p-10 lg:p-20 text-white relative overflow-hidden shadow-2xl">
                <div class="absolute top-0 right-0 w-64 h-64 bg-brand-gold opacity-10 blur-3xl rounded-full translate-x-1/2 -translate-y-1/2"></div>
                
                <div class="relative z-10 text-center">
                    <h2 class="text-4xl lg:text-6xl font-black mb-4">NextGen Membership</h2>
                    <div class="text-6xl lg:text-8xl font-black text-brand-gold mb-8">₹299 <span class="text-2xl text-slate-500 font-bold italic">/ Year</span></div>
                    
                    <div class="grid sm:grid-cols-2 gap-x-12 gap-y-6 text-left mb-12">
                        <div class="flex items-center gap-3">
                            <i data-lucide="check-circle" class="text-brand-gold"></i>
                            <span class="font-bold">Daily Export Insights</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <i data-lucide="check-circle" class="text-brand-gold"></i>
                            <span class="font-bold">Country-wise Opportunities</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <i data-lucide="check-circle" class="text-brand-gold"></i>
                            <span class="font-bold">High-demand Product Ideas</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <i data-lucide="check-circle" class="text-brand-gold"></i>
                            <span class="font-bold">Govt. Schemes & Benefits</span>
                        </div>
                    </div>

                    <div class="bg-brand-gold/20 p-6 rounded-3xl border border-brand-gold/30 mb-12">
                        <p class="text-brand-gold font-black uppercase tracking-widest text-sm mb-2">Founding Benefit</p>
                        <p class="text-xl font-bold">FREE Access to Batch 1 Live Workshop (April 4 & 5)</p>
                    </div>

                    <button onclick="showSuccess()" class="w-full bg-brand-gold text-white py-6 rounded-3xl text-2xl font-black shadow-xl btn-bounce">Join the Ecosystem Now</button>
                    <p class="mt-6 text-slate-500 font-bold uppercase text-xs tracking-widest">Secure Payment via Razorpay</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Workshop Details -->
    <section id="workshop" class="py-24 bg-white border-t border-slate-200">
        <div class="max-w-4xl mx-auto px-4 text-center">
            <h2 class="text-4xl font-black brand-navy mb-4">Batch 1 – Founding Workshop</h2>
            <p class="text-xl text-slate-500 font-medium mb-12">Intensive training for the next generation of Telugu exporters.</p>
            
            <div class="grid sm:grid-cols-2 gap-8 mb-12">
                <div class="p-8 rounded-[2rem] bg-slate-50 border border-slate-200">
                    <i data-lucide="calendar" class="w-10 h-10 brand-gold mx-auto mb-4"></i>
                    <h5 class="text-xl font-black brand-navy">April 4 & April 5</h5>
                    <p class="text-slate-500 font-bold">Founding Dates</p>
                </div>
                <div class="p-8 rounded-[2rem] bg-slate-50 border border-slate-200">
                    <i data-lucide="clock" class="w-10 h-10 brand-gold mx-auto mb-4"></i>
                    <h5 class="text-xl font-black brand-navy">7:00 PM – 10:00 PM</h5>
                    <p class="text-slate-500 font-bold">Evening Sessions</p>
                </div>
            </div>

            <div class="space-y-4">
                <div class="text-4xl lg:text-5xl font-black brand-navy opacity-10 leading-none">REAL LIFE EXPORTS</div>
                <div class="text-4xl lg:text-5xl font-black brand-gold opacity-20 leading-none">PROFITABLE PRODUCTS</div>
                <div class="text-4xl lg:text-5xl font-black brand-navy opacity-10 leading-none">PAYMENT SAFETY</div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-50 border-t border-slate-200 pt-20 pb-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col lg:flex-row justify-between items-start gap-12 mb-20">
                <div class="max-w-sm">
                    <img src="WhatsApp Image 2026-03-25 at 1.38.11 PM.jpeg" alt="NextGen Logo" class="h-12 w-auto mb-6" onerror="this.style.display='none';">
                    <p class="text-slate-500 font-medium leading-relaxed">Built for Telugu entrepreneurs. Designed for global markets. A subsidiary of Akhil Global Exports.</p>
                </div>
                <div class="grid grid-cols-2 sm:grid-cols-3 gap-16">
                    <div>
                        <h6 class="font-black brand-navy uppercase text-xs tracking-widest mb-6">Company</h6>
                        <ul class="space-y-4 font-bold text-slate-500 text-sm">
                            <li><a href="#about" class="hover:brand-gold">About</a></li>
                            <li><a href="#founder" class="hover:brand-gold">Founder</a></li>
                            <li><a href="#sectors" class="hover:brand-gold">Sectors</a></li>
                        </ul>
                    </div>
                    <div>
                        <h6 class="font-black brand-navy uppercase text-xs tracking-widest mb-6">Program</h6>
                        <ul class="space-y-4 font-bold text-slate-500 text-sm">
                            <li><a href="#membership" class="hover:brand-gold">Membership</a></li>
                            <li><a href="#workshop" class="hover:brand-gold">Workshop</a></li>
                            <li><a href="#" class="hover:brand-gold">FAQ</a></li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="pt-10 border-t border-slate-200 text-center">
                <p class="text-slate-400 text-xs font-black uppercase tracking-[0.2em]">&copy; 2026 Akhil Global Exports. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Success Modal -->
    <div id="modal" class="modal-overlay" onclick="closeModal()">
        <div class="bg-white p-12 rounded-[3rem] max-w-md w-full text-center shadow-2xl" onclick="event.stopPropagation()">
            <div class="w-24 h-24 bg-green-100 text-green-600 rounded-full flex items-center justify-center mx-auto mb-8 shadow-inner">
                <i data-lucide="check" class="w-12 h-12"></i>
            </div>
            <h3 class="text-3xl font-black brand-navy mb-4">Registration Opening!</h3>
            <p class="text-slate-600 mb-8 font-medium">Thank you for your interest in the ₹299 membership. In a live environment, you would now be redirected to Razorpay.</p>
            <button onclick="closeModal()" class="w-full bg-brand-navy text-white py-4 rounded-2xl font-black uppercase tracking-widest">Back to Website</button>
        </div>
    </div>

    <script>
        // Init Icons
        lucide.createIcons();

        // Mobile Nav Toggle
        function toggleMenu() {
            const nav = document.getElementById('mobile-nav');
            const icon = document.getElementById('menu-icon');
            nav.classList.toggle('hidden');
        }

        // Modal Logic
        function showSuccess() {
            document.getElementById('modal').style.display = 'flex';
        }

        function closeModal() {
            document.getElementById('modal').style.display = 'none';
        }

        // Smooth Appearance on Scroll
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('opacity-100', 'translate-y-0');
                    entry.target.classList.remove('opacity-0', 'translate-y-10');
                }
            });
        }, { threshold: 0.1 });

        document.querySelectorAll('section').forEach(section => {
            section.classList.add('transition-all', 'duration-1000', 'opacity-0', 'translate-y-10');
            observer.observe(section);
        });
    </script>
</body>
</html>
