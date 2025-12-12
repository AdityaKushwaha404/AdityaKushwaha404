<!-- README: Improved layout, spacing, and styles -->
<style>
  :root{
    --accent: #006989;
    --card-bg: rgba(255,255,255,0.06);
    --card-border: rgba(255,255,255,0.12);
    --muted: #9aa8ad;
    --max-width: 900px;
    --radius: 18px;
  }
  body{font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Fira Code', 'Helvetica Neue', Arial, sans-serif}
  .center{display:flex;flex-direction:column;align-items:center;}
  .hero-title{font-size:48px;font-weight:800;margin:6px 0;color:var(--accent);text-align:center}
  .typing{margin-top:8px}
  .hero-img{width:100%;max-width:850px;border-radius:22px;background:rgba(255,255,255,0.06);border:1px solid var(--card-border);padding:6px;backdrop-filter:blur(12px);box-shadow:0 6px 24px rgba(0,0,0,0.12)}
  .card{max-width:var(--max-width);width:100%;background:var(--card-bg);border-radius:var(--radius);padding:22px;border:1px solid var(--card-border);backdrop-filter:blur(10px);margin:18px 0}
  .muted{color:var(--muted)}
  .tech-grid{display:flex;flex-wrap:wrap;justify-content:center;gap:14px;align-items:center}
  .tech-grid img{height:56px;transition:transform .28s ease,filter .28s ease}
  .tech-grid img:hover{transform:translateY(-6px) scale(1.06);filter:brightness(1.05)}
  @keyframes float{0%{transform:translateY(0)}50%{transform:translateY(-8px)}100%{transform:translateY(0)}}
  .float{animation:float 3.2s ease-in-out infinite}
  .projects{display:flex;flex-direction:column;gap:12px;align-items:center}
  .project-item{width:100%;border-radius:14px;padding:18px;background:rgba(255,255,255,0.04);border:1px solid var(--card-border)}
  .links{display:flex;gap:10px;flex-wrap:wrap;justify-content:center;margin-top:8px}
  .contact a{color:var(--accent);text-decoration:none;font-weight:600}
  @media (max-width:640px){.hero-title{font-size:36px}.hero-img{max-width:90%}}
</style>

<div class="center">
  <!-- NAME / HERO -->
  <h1 class="hero-title">Hi, I’m Aditya Kushwaha</h1>

  <div class="typing">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=2600&pause=900&color=006989&center=true&vCenter=true&width=900&lines=Full-Stack+Engineer;Focused+on+Scalable+and+Secure+Applications" alt="Typing Animation" />
  </div>

  <div style="width:100%;display:flex;justify-content:center;margin-top:10px">
    <img class="hero-img" src="https://raw.githubusercontent.com/AdityaKushwaha404/AdityaKushwaha404/main/assets/Bannerr.png" alt="Banner" />
  </div>

  <!-- ABOUT -->
  <div class="card">
    <strong>About Me</strong>
    <p class="muted" style="margin-top:8px;line-height:1.6">
      Aspiring full-stack developer building scalable, secure, and user-centered web applications. I focus on React.js, Next.js, Tailwind CSS, and modern UI/UX principles to deliver clean, responsive, and accessible interfaces aligned with WCAG best practices. On the backend I work with Node.js, Express.js, and FastAPI, and I have hands-on experience with databases and cloud integrations.
    </p>
    <p class="muted" style="margin-top:6px">Currently pursuing B.Tech (Information Technology) at Harcourt Butler Technical University, Kanpur.</p>
  </div>

  <!-- TECH STACK -->
  <div style="text-align:center;max-width:var(--max-width);width:100%">
    <strong>Animated Tech Stack</strong>
    <p class="muted" style="margin-top:6px">Glassmorphism • Motion icons</p>
    <div class="tech-grid" style="margin-top:12px">
      <!-- Languages -->
      <img class="float" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/JavaScript.svg" alt="JavaScript" />
      <img class="float" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/TypeScript.svg" alt="TypeScript" />
      <img class="float" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/CPP.svg" alt="C++" />
      <img class="float" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/Python-Dark.svg" alt="Python" />
      <!-- Frameworks -->
      <img class="float" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/React-Dark.svg" alt="React" />
      <img class="float" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/NextJS-Dark.svg" alt="Next.js" />
      <img class="float" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/NodeJS-Dark.svg" alt="Node.js" />
      <img class="float" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/ExpressJS-Dark.svg" alt="Express" />
      <img class="float" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/FastAPI.svg" alt="FastAPI" />
      <img class="float" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/TailwindCSS-Dark.svg" alt="Tailwind" />
      <!-- Databases -->
      <img class="float" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/MongoDB.svg" alt="MongoDB" />
      <img class="float" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/MySQL-Dark.svg" alt="MySQL" />
      <img class="float" src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/Supabase-Dark.svg" alt="Supabase" />
    </div>
  </div>

  <!-- PROJECTS -->
  <div style="width:100%;max-width:var(--max-width);margin-top:18px">
    <strong>Featured Projects</strong>
    <div class="projects" style="margin-top:12px">
      <div class="project-item">
        <strong>AgriChain – Blockchain-based Agricultural Supply Chain Platform</strong>
        <p style="margin:8px 0"><img src="https://skillicons.dev/icons?i=react,fastapi,mongodb,tailwind" height="36" alt="stack" /></p>
        <p class="muted" style="line-height:1.45;margin-top:6px">Built a decentralized supply chain system with blockchain-powered product traceability, Web3.js-based QR verification, secure authentication, Razorpay payments, and scalable FastAPI lifecycle APIs. Designed with a responsive, accessibility-first interface.</p>
      </div>

      <div class="project-item">
        <strong>Rabbit – Digital Marketplace Web App</strong>
        <p style="margin:8px 0"><img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,react" height="36" alt="stack" /></p>
        <p class="muted" style="line-height:1.45;margin-top:6px">Developed secure REST APIs for product, cart, and order workflows using Node.js, Express.js and MongoDB. Built a modern, responsive UI with strong UX focus and efficient global state management.</p>
      </div>
    </div>
  </div>

  <!-- ACHIEVEMENTS -->
  <div class="card" style="text-align:center">
    <strong>Achievements</strong>
    <p style="margin-top:10px"><img src="https://img.shields.io/badge/HackWithUttarPradesh-1st_Place-006989?style=for-the-badge" /> <img src="https://img.shields.io/badge/SIH_Internal_Hackathon-Winner-006989?style=for-the-badge" /></p>
    <p class="muted" style="margin-top:8px">Winner of major engineering hackathons for execution, system design, and engineering depth.</p>
  </div>

  <!-- CONTACTS -->
  <div style="margin-bottom:28px;text-align:center;max-width:var(--max-width);width:100%">
    <strong>Get in touch</strong>
    <div class="links contact" style="margin-top:10px">
      <a href="https://aditya-kushwaha.vercel.app">Portfolio</a>
      <a href="https://www.linkedin.com/in/adityakushwaha1503">LinkedIn</a>
      <a href="https://github.com/AdityaKushwaha404">GitHub</a>
      <a href="mailto:kushwahaaditya431@gmail.com">Email</a>
      <span class="muted">+91 7905915437</span>
    </div>
  </div>
</div>
<!-- NAME -->
<h1 align="center" style="
  font-size: 56px;
  font-weight: 800;
  margin-bottom: 4px;
">
  Hi, I’m Aditya Kushwaha
</h1>



<br/>

<!-- ANIMATED TYPING BANNER -->
<p align="center">
  <img 
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=30&duration=2600&pause=900&color=006989&center=true&vCenter=true&width=900&lines=Full-Stack+Engineer;Focused+on+Scalable+and+Secure+Applications"
    alt="Typing Animation"
    style="margin-top: 10px;"
  />
</p>


<!-- GLASS HERO IMAGE -->
<p align="center">
  <img 
    width="850"
    src="https://raw.githubusercontent.com/AdityaKushwaha404/AdityaKushwaha404/main/assets/Bannerr.png"
    style="
      border-radius: 22px;
      backdrop-filter: blur(14px);
      background: rgba(255,255,255,0.12);
      border: 1px solid rgba(255,255,255,0.18);
      padding: 6px;
      opacity: 0.96;
      margin-top: 10px;
    "
  />
</p>


About Me
<div align="center"> <div style=" max-width: 850px; padding: 25px; background: rgba(255,255,255,0.10); border-radius: 18px; backdrop-filter: blur(12px); border: 1px solid rgba(255,255,255,0.15); "> Aspiring full-stack developer skilled in building scalable, secure, and user-centered web applications. Strong expertise in React.js, Next.js, Tailwind CSS, and modern UI/UX principles, focused on delivering clean, responsive, and accessible interfaces aligned with WCAG and usability best practices. Experienced in backend development using Node.js, Express.js, FastAPI, and database systems, with a solid understanding of object-oriented design, software development practices, and cloud integrations.

Currently pursuing B.Tech (Information Technology) at Harcourt Butler Technical University, Kanpur.

</div> </div>
Animated Tech Stack
Glassmorphism + Motion Icons
<div align="center" style="margin-top: 20px;"> <!-- Languages --> <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/JavaScript.svg" height="55" style="margin:10px; animation:float 3s ease-in-out infinite;" /> <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/TypeScript.svg" height="55" style="margin:10px; animation:float 3.2s ease-in-out infinite;" /> <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/CPP.svg" height="55" style="margin:10px; animation:float 2.8s ease-in-out infinite;" /> <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/Python-Dark.svg" height="55" style="margin:10px; animation:float 3.4s ease-in-out infinite;" /> <!-- Frameworks --> <br/> <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/React-Dark.svg" height="55" style="margin:12px; animation:float 3.1s ease-in-out infinite;" /> <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/NextJS-Dark.svg" height="55" style="margin:12px; animation:float 3.6s ease-in-out infinite;" /> <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/NodeJS-Dark.svg" height="55" style="margin:12px; animation:float 2.9s ease-in-out infinite;" /> <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/ExpressJS-Dark.svg" height="55" style="margin:12px; animation:float 3.7s ease-in-out infinite;" /> <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/FastAPI.svg" height="55" style="margin:12px; animation:float 3.3s ease-in-out infinite;" /> <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/TailwindCSS-Dark.svg" height="55" style="margin:12px; animation:float 2.7s ease-in-out infinite;" /> <!-- Databases --> <br/> <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/MongoDB.svg" height="55" style="margin:12px; animation:float 3.5s ease-in-out infinite;" /> <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/MySQL-Dark.svg" height="55" style="margin:12px; animation:float 3.1s ease-in-out infinite;" /> <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/Supabase-Dark.svg" height="55" style="margin:12px; animation:float 3.8s ease-in-out infinite;" /> </div> <!-- Animation Keyframe --> <style> @keyframes float { 0% { transform: translateY(0px); } 50% { transform: translateY(-10px); } 100% { transform: translateY(0px); } } </style>
Featured Projects
Glassmorphic Cards

(CV projects only)

<div align="center"> <!-- AgriChain Card --> <div style=" width: 90%; margin: 20px 0; padding: 25px; border-radius: 18px; background: rgba(255,255,255,0.12); border: 1px solid rgba(255,255,255,0.18); backdrop-filter: blur(14px); ">
AgriChain – Blockchain-based Agricultural Supply Chain Platform
<p> <img src="https://skillicons.dev/icons?i=react,fastapi,mongodb,tailwind" height="55" /> </p>

Built a decentralized supply chain system with blockchain-powered product traceability, Web3.js-based QR verification, secure authentication, automated Razorpay payments, and scalable lifecycle APIs using FastAPI.
Designed with a responsive, accessibility-first interface optimized for farmers and consumers.

</div> <!-- Rabbit Card --> <div style=" width: 90%; margin: 20px 0; padding: 25px; border-radius: 18px; background: rgba(255,255,255,0.12); border: 1px solid rgba(255,255,255,0.18); backdrop-filter: blur(14px); ">
Rabbit – Digital Marketplace Web App
<p> <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,react" height="55" /> </p>

Developed secure REST APIs for product, cart, and order workflows using Node.js, Express.js, and MongoDB.
Built a modern, responsive UI with strong attention to UX detail and implemented efficient global state management.

</div> </div>
Achievements
<p align="center"> <img src="https://img.shields.io/badge/HackWithUttarPradesh-1st_Place-006989?style=for-the-badge" /> <img src="https://img.shields.io/badge/SIH_Internal_Hackathon-Winner-006989?style=for-the-badge" /> </p>

Winner of major engineering hackathons for strong execution, system design, and engineering depth.



Portfolio: https://aditya-kushwaha.vercel.app

LinkedIn: https://www.linkedin.com/in/adityakushwaha1503

GitHub: https://github.com/AdityaKushwaha404

Email: kushwahaaditya431@gmail.com

Phone: +91 7905915437
