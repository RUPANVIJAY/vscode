<!DOCTYPE html>

<html class="scroll-smooth" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Rupan Vijay | Portfolio</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&amp;family=Source+Serif+4:ital,wght@0,400;0,600;1,400&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "tertiary-container": "#191c1e",
                    "on-secondary-fixed-variant": "#005236",
                    "surface-container-lowest": "#ffffff",
                    "on-error-container": "#93000a",
                    "inverse-primary": "#bec6e0",
                    "on-primary-container": "#7c839b",
                    "tertiary-fixed-dim": "#c4c7c9",
                    "surface-container-high": "#dce9ff",
                    "surface-container-low": "#eff4ff",
                    "surface": "#f8f9ff",
                    "on-tertiary-fixed-variant": "#444749",
                    "on-primary-fixed": "#131b2e",
                    "on-secondary-fixed": "#002113",
                    "on-background": "#0b1c30",
                    "background": "#f8f9ff",
                    "tertiary-fixed": "#e0e3e5",
                    "on-error": "#ffffff",
                    "secondary-container": "#6cf8bb",
                    "on-tertiary-fixed": "#191c1e",
                    "error-container": "#ffdad6",
                    "on-tertiary-container": "#818486",
                    "on-surface": "#0b1c30",
                    "surface-container-highest": "#d3e4fe",
                    "secondary-fixed": "#6ffbbe",
                    "outline": "#76777d",
                    "secondary": "#006c49",
                    "on-surface-variant": "#45464d",
                    "on-secondary-container": "#00714d",
                    "surface-container": "#e5eeff",
                    "surface-bright": "#f8f9ff",
                    "primary": "#000000",
                    "surface-variant": "#d3e4fe",
                    "on-primary-fixed-variant": "#3f465c",
                    "tertiary": "#000000",
                    "primary-container": "#131b2e",
                    "on-secondary": "#ffffff",
                    "primary-fixed": "#dae2fd",
                    "on-tertiary": "#ffffff",
                    "inverse-on-surface": "#eaf1ff",
                    "on-primary": "#ffffff",
                    "surface-dim": "#cbdbf5",
                    "secondary-fixed-dim": "#4edea3",
                    "surface-tint": "#565e74",
                    "primary-fixed-dim": "#bec6e0",
                    "error": "#ba1a1a",
                    "inverse-surface": "#213145",
                    "outline-variant": "#c6c6cd"
            },
            "borderRadius": {
                    "DEFAULT": "0.125rem",
                    "lg": "0.25rem",
                    "xl": "0.5rem",
                    "full": "0.75rem"
            },
            "spacing": {
                    "stack-sm": "8px",
                    "stack-lg": "48px",
                    "gutter": "16px",
                    "stack-md": "24px",
                    "section-gap": "80px",
                    "container-margin": "20px"
            },
            "fontFamily": {
                    "display-lg": ["Inter"],
                    "body-md": ["\"Source Serif 4\""],
                    "label-caps": ["Inter"],
                    "headline-md": ["Inter"],
                    "label-sm": ["Inter"],
                    "body-lg": ["\"Source Serif 4\""],
                    "display-lg-mobile": ["Inter"]
            },
            "fontSize": {
                    "display-lg": ["48px", {"lineHeight": "52px", "letterSpacing": "-0.04em", "fontWeight": "800"}],
                    "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}],
                    "label-caps": ["12px", {"lineHeight": "16px", "letterSpacing": "0.1em", "fontWeight": "600"}],
                    "headline-md": ["24px", {"lineHeight": "32px", "letterSpacing": "-0.02em", "fontWeight": "700"}],
                    "label-sm": ["14px", {"lineHeight": "20px", "fontWeight": "500"}],
                    "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                    "display-lg-mobile": ["36px", {"lineHeight": "40px", "letterSpacing": "-0.03em", "fontWeight": "800"}]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .reveal-up {
            opacity: 0;
            transform: translateY(20px);
            transition: all 0.8s cubic-bezier(0.22, 1, 0.36, 1);
        }
        .reveal-up.active {
            opacity: 1;
            transform: translateY(0);
        }
        .pulse-emerald {
            box-shadow: 0 0 0 0 rgba(16, 185, 129, 0.7);
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(16, 185, 129, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(16, 185, 129, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(16, 185, 129, 0); }
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-background text-on-background selection:bg-secondary-container selection:text-on-secondary-container overflow-x-hidden">
<!-- TopAppBar -->
<header class="fixed top-0 left-0 right-0 z-50 bg-surface border-b border-outline-variant flex justify-between items-center w-full px-gutter h-16 transition-opacity duration-200">
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-primary cursor-pointer hover:opacity-80 transition-opacity">menu</span>
<span class="font-label-caps text-label-caps tracking-widest text-primary">RUPAN VIJAY</span>
</div>
<div class="hidden md:flex gap-8 items-center">
<a class="font-label-caps text-label-caps text-primary hover:opacity-80 transition-opacity" href="#">HOME</a>
<a class="font-label-caps text-label-caps text-on-surface-variant hover:opacity-80 transition-opacity" href="#">EDUCATION</a>
<a class="font-label-caps text-label-caps text-on-surface-variant hover:opacity-80 transition-opacity" href="#">SKILLS</a>
<a class="font-label-caps text-label-caps text-on-surface-variant hover:opacity-80 transition-opacity" href="#">CONTACT</a>
</div>
<div class="flex items-center gap-2">
<div class="w-2 h-2 rounded-full bg-[#10B981] pulse-emerald"></div>
<span class="font-label-sm text-label-sm text-on-surface-variant hidden sm:inline">Available for internships</span>
</div>
</header>
<main class="mt-16 pb-24 md:pb-0">
<!-- Hero Section -->
<section class="min-h-[707px] flex flex-col justify-center items-center px-gutter text-center py-section-gap">
<div class="max-w-4xl mx-auto space-y-stack-md">
<span class="font-label-caps text-label-caps text-on-primary-container tracking-[0.2em] reveal-up">B.TECH MECHANICAL ENGINEERING • VIT CHENNAI</span>
<h1 class="font-display-lg-mobile md:font-display-lg text-display-lg-mobile md:text-display-lg text-primary leading-tight reveal-up" style="transition-delay: 100ms;">
                    Education is the <br/> <span class="italic font-body-lg text-on-surface-variant">premise of progress</span>
</h1>
<p class="font-body-lg text-body-lg text-on-surface-variant max-w-2xl mx-auto reveal-up" style="transition-delay: 200ms;">
                    Hello, I'm M. Rupan Vijay, a 2nd year student bridging the gap between classical mechanical principles and the digital future of engineering.
                </p>
<div class="pt-stack-md reveal-up" style="transition-delay: 300ms;">
<a class="px-10 py-4 bg-primary text-on-primary font-label-caps text-label-caps tracking-widest hover:bg-on-surface-variant transition-colors inline-block" href="#about">
                        EXPLORE BIO
                    </a>
</div>
</div>
</section>
<!-- Dynamic Visual Split -->
<section class="grid grid-cols-1 md:grid-cols-12 w-full max-w-[1440px] mx-auto px-gutter gap-stack-lg items-center py-section-gap">
<div class="md:col-span-7 aspect-[4/5] bg-surface-container-high overflow-hidden reveal-up">
<img class="w-full h-full object-cover grayscale" data-alt="A cinematic, high-contrast portrait of a young professional Indian male engineering student in a minimalist modern architectural setting. He is wearing a crisp white shirt, standing against a backdrop of clean concrete lines and soft natural daylight. The image has a premium, editorial aesthetic with sharp focus and a neutral color palette that emphasizes clarity and visionary intent." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDnkFOOYAreLJZJ67cKu44X50I2xmWqiGH778W-Ovq35VEuf4MIuKsmdJRp0oGfo7DTDwZg61VAy7BWJ9RB6xJQq9BhzZq2gqhMLqgBSBHDj-UejOKGt-a2aC62upjpusvLJzam1TA52euCHmwU2CMGP3LhmItRChJmjGOsLnYVcWbc3EE6wycIIErhqdYqxwcg4dyDb38087AwNmsoaAjE1pbz5SlTQ8dfuVJxTwrvekv0SFUgPPA6Mpih9bPXtvnxpqelklnuBZU"/>
</div>
<div class="md:col-span-5 space-y-stack-md reveal-up" id="about">
<h2 class="font-label-caps text-label-caps text-on-surface-variant tracking-widest">ABOUT THE JOURNEY</h2>
<h3 class="font-headline-md text-headline-md text-primary">Mechanical precision meets visionary thinking.</h3>
<p class="font-body-md text-body-md text-on-surface-variant">
                    Currently pursuing my Undergraduate degree at VIT Chennai, I've dedicated my second year to exploring the intersections of fluid dynamics and sustainable energy solutions. My academic journey is fueled by a belief that engineering isn't just about building machines; it's about refining the systems that drive human progress.
                </p>
<div class="space-y-stack-sm pt-stack-sm">
<div class="flex items-center gap-4 py-4 border-b border-outline-variant opacity-20"></div>
<div class="flex justify-between items-center py-4 border-b border-outline-variant/30">
<span class="font-label-sm text-label-sm text-on-surface">Institution</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">VIT Chennai</span>
</div>
<div class="flex justify-between items-center py-4 border-b border-outline-variant/30">
<span class="font-label-sm text-label-sm text-on-surface">Specialization</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">Mechanical Engineering</span>
</div>
<div class="flex justify-between items-center py-4 border-b border-outline-variant/30">
<span class="font-label-sm text-label-sm text-on-surface">Status</span>
<span class="font-label-sm text-label-sm text-on-surface-variant">2nd Year Undergraduate</span>
</div>
</div>
</div>
</section>
<!-- Philosophy Grid -->
<section class="bg-surface-container-low py-section-gap">
<div class="max-w-[1140px] mx-auto px-gutter">
<div class="grid grid-cols-1 md:grid-cols-3 gap-stack-lg">
<div class="space-y-stack-sm reveal-up">
<div class="w-12 h-12 flex items-center justify-center bg-primary text-on-primary">
<span class="material-symbols-outlined">architecture</span>
</div>
<h4 class="font-headline-md text-headline-md text-primary pt-4">Rigorous Fundamentals</h4>
<p class="font-body-md text-body-md text-on-surface-variant">Deep diving into the physics of materials and thermodynamics to build a rock-solid foundation for future innovations.</p>
</div>
<div class="space-y-stack-sm reveal-up" style="transition-delay: 100ms;">
<div class="w-12 h-12 flex items-center justify-center bg-primary text-on-primary">
<span class="material-symbols-outlined">precision_manufacturing</span>
</div>
<h4 class="font-headline-md text-headline-md text-primary pt-4">Technical Prowess</h4>
<p class="font-body-md text-body-md text-on-surface-variant">Mastering CAD tools and simulation environments to translate complex theoretical concepts into functional digital twins.</p>
</div>
<div class="space-y-stack-sm reveal-up" style="transition-delay: 200ms;">
<div class="w-12 h-12 flex items-center justify-center bg-primary text-on-primary">
<span class="material-symbols-outlined">school</span>
</div>
<h4 class="font-headline-md text-headline-md text-primary pt-4">Lifelong Progress</h4>
<p class="font-body-md text-body-md text-on-surface-variant">Embracing the 'Education First' mantra by constantly staying ahead of industry trends and evolving technological paradigms.</p>
</div>
</div>
</div>
</section>
<!-- Newsletter/Contact CTA -->
<section class="py-section-gap px-gutter text-center">
<div class="max-w-2xl mx-auto space-y-stack-md reveal-up">
<h2 class="font-display-lg-mobile text-display-lg-mobile text-primary">Let's collaborate on the future.</h2>
<p class="font-body-lg text-body-lg text-on-surface-variant">Interested in mechanical design, research collaborations, or just a professional conversation? Reach out.</p>
<form class="mt-stack-lg flex flex-col sm:flex-row gap-4">
<div class="flex-grow relative">
<label class="absolute -top-3 left-0 font-label-caps text-[10px] text-on-surface-variant tracking-widest">EMAIL ADDRESS</label>
<input class="w-full bg-transparent border-b-2 border-primary focus:outline-none py-3 font-body-md text-body-md rounded-none placeholder:opacity-30" placeholder="hello@example.com" type="email"/>
</div>
<button class="px-8 py-3 bg-primary text-on-primary font-label-caps text-label-caps tracking-widest hover:opacity-90 transition-opacity">CONNECT</button>
</form>
</div>
</section>
</main>
<!-- BottomNavBar (Mobile Only) -->
<nav class="md:hidden fixed bottom-0 w-full flex justify-around items-center bg-surface border-t border-outline-variant py-2 px-gutter z-50">
<div class="flex flex-col items-center justify-center bg-primary-container text-on-primary-container rounded-full px-4 py-1 transition-transform duration-150 scale-95 active:scale-90">
<span class="material-symbols-outlined" data-icon="home">home</span>
<span class="font-label-sm text-label-sm">Home</span>
</div>
<div class="flex flex-col items-center justify-center text-on-surface-variant px-4 py-1 hover:bg-surface-container-low transition-transform duration-150 scale-95 active:scale-90">
<span class="material-symbols-outlined" data-icon="school">school</span>
<span class="font-label-sm text-label-sm">Education</span>
</div>
<div class="flex flex-col items-center justify-center text-on-surface-variant px-4 py-1 hover:bg-surface-container-low transition-transform duration-150 scale-95 active:scale-90">
<span class="material-symbols-outlined" data-icon="architecture">architecture</span>
<span class="font-label-sm text-label-sm">Skills</span>
</div>
<div class="flex flex-col items-center justify-center text-on-surface-variant px-4 py-1 hover:bg-surface-container-low transition-transform duration-150 scale-95 active:scale-90">
<span class="material-symbols-outlined" data-icon="mail">mail</span>
<span class="font-label-sm text-label-sm">Contact</span>
</div>
</nav>
<!-- Footer (Desktop) -->
<footer class="hidden md:block py-12 border-t border-outline-variant">
<div class="max-w-[1140px] mx-auto px-gutter flex justify-between items-center">
<span class="font-label-caps text-label-caps text-on-surface-variant">© 2024 RUPAN VIJAY</span>
<div class="flex gap-8">
<a class="font-label-caps text-label-caps text-on-surface-variant hover:text-primary transition-colors" href="#">LINKEDIN</a>
<a class="font-label-caps text-label-caps text-on-surface-variant hover:text-primary transition-colors" href="#">GITHUB</a>
<a class="font-label-caps text-label-caps text-on-surface-variant hover:text-primary transition-colors" href="#">RESEARCHGATE</a>
</div>
</div>
</footer>
<script>
        // Simple Intersection Observer for scroll reveals
        const observerOptions = {
            threshold: 0.1
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('active');
                }
            });
        }, observerOptions);

        document.querySelectorAll('.reveal-up').forEach((el) => observer.observe(el));

        // Micro-interaction for hover states
        document.querySelectorAll('button, a').forEach(el => {
            el.addEventListener('mouseenter', () => {
                el.style.transform = 'translateY(-2px)';
            });
            el.addEventListener('mouseleave', () => {
                el.style.transform = 'translateY(0px)';
            });
        });
    </script>
</body></html>
