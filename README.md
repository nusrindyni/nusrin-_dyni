
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Nusrin Dyni - Digital Marketing Specialist. Social media marketing, SEO, content strategy and digital growth.">
  <meta name="author" content="Nusrin Dyni">
  <title>Nusrin Dyni | Digital Marketing Specialist</title>

  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">

  <style>
    * { scroll-behavior: smooth; }
    body { font-family: 'DM Sans', sans-serif; }
    .heading { font-family: 'Playfair Display', serif; }
    .gradient-text {
      background: linear-gradient(90deg,#a78bfa,#60a5fa);
      -webkit-background-clip: text;
      color: transparent;
    }
    .glass {
      background: rgba(255,255,255,.06);
      border: 1px solid rgba(255,255,255,.12);
      backdrop-filter: blur(12px);
    }
    .project-card { transition: .3s ease; }
    .project-card:hover { transform: translateY(-6px); }
  </style>
</head>

<body class="bg-[#0b1020] text-white">

  <!-- Navigation -->
  <nav class="fixed top-0 w-full z-50 bg-[#0b1020]/90 backdrop-blur-lg border-b border-white/10">
    <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
      <a href="#home" class="text-xl font-bold tracking-wide">NUSRIN<span class="text-violet-400">.</span></a>
      <div class="hidden md:flex gap-7 text-sm text-gray-300">
        <a href="#about" class="hover:text-violet-400">About</a>
        <a href="#skills" class="hover:text-violet-400">Skills</a>
        <a href="#experience" class="hover:text-violet-400">Experience</a>
        <a href="#projects" class="hover:text-violet-400">Projects</a>
        <a href="#contact" class="hover:text-violet-400">Contact</a>
      </div>
      <a href="#contact" class="bg-violet-600 hover:bg-violet-700 px-4 py-2 rounded-full text-sm">Let's Connect</a>
    </div>
  </nav>

  <!-- Hero -->
  <section id="home" class="min-h-screen flex items-center pt-24 px-6">
    <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-12 items-center w-full">
      <div>
        <p class="text-violet-400 font-semibold tracking-widest uppercase text-sm mb-5">
          Hello, I'm Nusrin Dyni
        </p>
        <h1 class="heading text-5xl md:text-7xl leading-tight mb-6">
          Turning Ideas Into <span class="gradient-text">Digital Growth.</span>
        </h1>
        <p class="text-gray-400 text-lg leading-relaxed mb-8">
          Digital Marketing Specialist passionate about social media strategy,
          creative content, SEO and building meaningful connections between
          brands and their audiences.
        </p>
        <div class="flex flex-wrap gap-4">
          <a href="#projects" class="bg-violet-600 hover:bg-violet-700 px-7 py-3 rounded-full font-semibold">
            Explore My Work
          </a>
          <a href="mailto:nusrindyni3@gmail.com" class="border border-white/30 hover:border-violet-400 px-7 py-3 rounded-full">
            Contact Me
          </a>
        </div>
        <div class="flex gap-6 mt-10 text-sm text-gray-400">
          <a href="https://linkedin.com/in/nusrin-dyni" target="_blank" rel="noopener noreferrer" class="hover:text-violet-400">LinkedIn ↗</a>
          <a href="https://github.com/nusrindyni" target="_blank" rel="noopener noreferrer" class="hover:text-violet-400">GitHub ↗</a>
        </div>
      </div>

      <div class="relative">
        <div class="absolute inset-0 bg-violet-600/20 blur-3xl rounded-full"></div>
        <div class="glass rounded-3xl p-10 relative text-center">
          <div class="w-32 h-32 rounded-full bg-gradient-to-br from-violet-500 to-blue-500 mx-auto flex items-center justify-center text-5xl font-bold mb-6">
            ND
          </div>
          <h2 class="heading text-3xl mb-2">Nusrin Dyni</h2>
          <p class="text-violet-300">Digital Marketing Specialist</p>
          <p class="text-gray-400 text-sm mt-5">Marketing • Creativity • Technology</p>
          <div class="grid grid-cols-2 gap-3 mt-8 text-sm">
            <div class="bg-white/5 rounded-xl p-4">
              <p class="text-violet-300 font-bold">Marketing</p>
              <p class="text-gray-400 mt-1">Strategy & Content</p>
            </div>
            <div class="bg-white/5 rounded-xl p-4">
              <p class="text-violet-300 font-bold">Technology</p>
              <p class="text-gray-400 mt-1">Computer Engineering</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="py-24 px-6 bg-[#10172a]">
    <div class="max-w-5xl mx-auto">
      <p class="text-violet-400 uppercase tracking-widest text-sm mb-3">Get to know me</p>
      <h2 class="heading text-4xl md:text-5xl mb-8">About Me</h2>
      <p class="text-gray-300 leading-8 text-lg">
        I am a Computer Science Engineering graduate with professional
        experience in social media management and digital marketing.
        I enjoy combining creativity, technology and marketing strategy
        to help businesses strengthen their online presence.
      </p>
      <p class="text-gray-400 leading-8 mt-5">
        My interests include social media campaigns, content creation,
        search engine optimization, digital advertising, audience engagement
        and performance analysis. I am continuously learning new tools
        and strategies to grow as a digital marketing professional.
      </p>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills" class="py-24 px-6">
    <div class="max-w-6xl mx-auto">
      <p class="text-violet-400 uppercase tracking-widest text-sm mb-3">What I do</p>
      <h2 class="heading text-4xl md:text-5xl mb-12">My Skills & Expertise</h2>
      <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-5">
        <div class="glass p-7 rounded-2xl">
          <div class="text-3xl mb-4">📱</div>
          <h3 class="font-bold text-xl mb-3">Social Media Marketing</h3>
          <p class="text-gray-400">Social media planning, account management, engagement and brand awareness.</p>
        </div>
        <div class="glass p-7 rounded-2xl">
          <div class="text-3xl mb-4">✍️</div>
          <h3 class="font-bold text-xl mb-3">Content Creation</h3>
          <p class="text-gray-400">Creative captions, content calendars, reels concepts and promotional content.</p>
        </div>
        <div class="glass p-7 rounded-2xl">
          <div class="text-3xl mb-4">🔎</div>
          <h3 class="font-bold text-xl mb-3">SEO</h3>
          <p class="text-gray-400">Keyword research, on-page SEO fundamentals and content optimization.</p>
        </div>
        <div class="glass p-7 rounded-2xl">
          <div class="text-3xl mb-4">📊</div>
          <h3 class="font-bold text-xl mb-3">Marketing Analytics</h3>
          <p class="text-gray-400">Campaign monitoring, performance reporting and audience insights.</p>
        </div>
        <div class="glass p-7 rounded-2xl">
          <div class="text-3xl mb-4">🎯</div>
          <h3 class="font-bold text-xl mb-3">Digital Advertising</h3>
          <p class="text-gray-400">Google Ads concepts, campaign planning and performance-focused marketing.</p>
        </div>
        <div class="glass p-7 rounded-2xl">
          <div class="text-3xl mb-4">💻</div>
          <h3 class="font-bold text-xl mb-3">Technology</h3>
          <p class="text-gray-400">Computer Science background, basic Python and web development knowledge.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Experience -->
  <section id="experience" class="py-24 px-6 bg-[#10172a]">
    <div class="max-w-5xl mx-auto">
      <p class="text-violet-400 uppercase tracking-widest text-sm mb-3">My journey</p>
      <h2 class="heading text-4xl md:text-5xl mb-12">Work Experience</h2>
      <div class="space-y-8 border-l border-violet-500/40 ml-3 pl-8">
        <div class="relative">
          <span class="absolute -left-[38px] top-1 w-4 h-4 bg-violet-500 rounded-full"></span>
          <p class="text-violet-300 text-sm">2024 – Present</p>
          <h3 class="text-xl font-bold mt-2">Freelance Social Media Marketing</h3>
          <p class="text-gray-400 mt-2">Content planning, social media support and digital promotional activities.</p>
        </div>
        <div class="relative">
          <span class="absolute -left-[38px] top-1 w-4 h-4 bg-violet-500 rounded-full"></span>
          <p class="text-violet-300 text-sm">2021 – 2022</p>
          <h3 class="text-xl font-bold mt-2">Social Media Executive – Varada Biz</h3>
          <p class="text-gray-400 mt-2">Social media activities, content coordination and online brand communication.</p>
        </div>
        <div class="relative">
          <span class="absolute -left-[38px] top-1 w-4 h-4 bg-violet-500 rounded-full"></span>
          <p class="text-violet-300 text-sm">2020 – 2021</p>
          <h3 class="text-xl font-bold mt-2">Digital Marketing Executive – Softern Technologies</h3>
          <p class="text-gray-400 mt-2">Digital marketing support and online promotional activities.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="py-24 px-6">
    <div class="max-w-6xl mx-auto">
      <p class="text-violet-400 uppercase tracking-widest text-sm mb-3">Selected work</p>
      <h2 class="heading text-4xl md:text-5xl mb-4">Featured Projects</h2>
      <p class="text-gray-400 mb-12">A selection of marketing concepts and digital work. Add your real campaign examples and results here.</p>

      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
        <article class="project-card glass rounded-2xl overflow-hidden">
          <div class="h-44 bg-gradient-to-br from-violet-700 to-indigo-950 flex items-center justify-center text-5xl">📱</div>
          <div class="p-6">
            <p class="text-violet-300 text-sm">Social Media</p>
            <h3 class="font-bold text-xl mt-2">Social Media Campaigns</h3>
            <p class="text-gray-400 text-sm mt-3">Content ideas, promotional posts and engagement-focused campaign planning.</p>
          </div>
        </article>

        <article class="project-card glass rounded-2xl overflow-hidden">
          <div class="h-44 bg-gradient-to-br from-blue-700 to-slate-950 flex items-center justify-center text-5xl">🎨</div>
          <div class="p-6">
            <p class="text-violet-300 text-sm">Creative Marketing</p>
            <h3 class="font-bold text-xl mt-2">Promotional Designs</h3>
            <p class="text-gray-400 text-sm mt-3">Marketing visuals and promotional concepts for products and services.</p>
          </div>
        </article>

        <article class="project-card glass rounded-2xl overflow-hidden">
          <div class="h-44 bg-gradient-to-br from-fuchsia-700 to-purple-950 flex items-center justify-center text-5xl">🌐</div>
          <div class="p-6">
            <p class="text-violet-300 text-sm">Web Presence</p>
            <h3 class="font-bold text-xl mt-2">Personal Portfolio Website</h3>
            <p class="text-gray-400 text-sm mt-3">Personal branding and portfolio development using web technologies.</p>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- Certifications -->
  <section class="py-24 px-6 bg-[#10172a]">
    <div class="max-w-5xl mx-auto">
      <p class="text-violet-400 uppercase tracking-widest text-sm mb-3">Continuous learning</p>
      <h2 class="heading text-4xl md:text-5xl mb-10">Certifications</h2>
      <div class="grid md:grid-cols-2 gap-4">
        <div class="glass p-5 rounded-xl">✓ Agile Project Management Certification</div>
        <div class="glass p-5 rounded-xl">✓ AI-Powered Performance Ads Certification</div>
        <div class="glass p-5 rounded-xl">✓ Artificial Intelligence and Business Strategy</div>
        <div class="glass p-5 rounded-xl">✓ Google Play Store Listing Certification</div>
      </div>
    </div>
  </section>

  <!-- Education -->
  <section class="py-20 px-6">
    <div class="max-w-5xl mx-auto">
      <p class="text-violet-400 uppercase tracking-widest text-sm mb-3">Academic background</p>
      <h2 class="heading text-4xl mb-8">Education</h2>
      <div class="glass p-7 rounded-2xl">
        <h3 class="text-xl font-bold">Bachelor of Technology – Computer Science Engineering</h3>
        <p class="text-gray-400 mt-2">Ilahia College of Engineering and Technology</p>
        <p class="text-violet-300 mt-2">2016 – 2020</p>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-24 px-6 bg-[#10172a]">
    <div class="max-w-4xl mx-auto text-center">
      <p class="text-violet-400 uppercase tracking-widest text-sm mb-3">Let's work together</p>
      <h2 class="heading text-4xl md:text-6xl mb-6">Let's Create Something Great.</h2>
      <p class="text-gray-400 mb-10">Open to digital marketing opportunities and professional collaborations.</p>
      <div class="flex flex-wrap justify-center gap-4">
        <a href="mailto:nusrindyni3@gmail.com" class="bg-violet-600 hover:bg-violet-700 px-7 py-3 rounded-full">Email Me</a>
        <a href="https://linkedin.com/in/nusrin-dyni" target="_blank" rel="noopener noreferrer" class="border border-white/30 hover:border-violet-400 px-7 py-3 rounded-full">LinkedIn</a>
      </div>
      <p class="text-gray-400 mt-8">Jeddah, Saudi Arabia</p>
    </div>
  </section>

  <footer class="py-7 text-center text-gray-500 text-sm border-t border-white/10">
    © 2026 Nusrin Dyni. All rights reserved.
  </footer>

</body>
</html>
