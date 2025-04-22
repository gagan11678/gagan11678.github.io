<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gagandeep Thind | Data Scientist & Quantitative Analyst</title>

  <!-- Tailwind CSS CDN -->
  <link
    href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css"
    rel="stylesheet"
  />
  <!-- Google Font -->
  <link
    href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap"
    rel="stylesheet"
  />
  <style>
    body {
      font-family: 'Inter', sans-serif;
    }
    /* Scroll‑reveal animation */
    [data-reveal] {
      opacity: 0;
      transform: translateY(30px);
      transition: all 0.6s ease-out;
    }
    [data-reveal].active {
      opacity: 1;
      transform: translateY(0);
    }
  </style>
</head>
<body class="bg-gray-50 text-gray-800 leading-relaxed">
  <!-- ========== HEADER ========= -->
  <header class="bg-white shadow-md sticky top-0 z-50">
    <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl sm:text-3xl font-extrabold text-indigo-600">
        Gagandeep Thind
      </h1>
      <nav class="hidden sm:flex space-x-6 text-lg">
        <a href="#projects" class="hover:text-indigo-600">Projects</a>
        <a href="#skills" class="hover:text-indigo-600">Skills</a>
        <a href="#contact" class="hover:text-indigo-600">Contact</a>
      </nav>
    </div>
  </header>

  <!-- ========== HERO ========= -->
  <section id="about" class="max-w-6xl mx-auto px-6 py-20 flex flex-col-reverse md:flex-row items-center gap-12">
    <div class="md:w-1/2" data-reveal>
      <h2 class="text-4xl sm:text-5xl font-extrabold mb-6">
        Hi, I’m <span class="text-indigo-600">Gagan</span> 👋
      </h2>
      <p class="text-xl mb-4">
        MSc Data Science candidate <span class="hidden md:inline">(University of Calgary)</span>
        obsessed with turning messy financial & operational data into crisp, actionable insights.
        I blend <strong>real‑time ML</strong>, <strong>AWS DevOps</strong>, and a dash of storytelling to drive smarter decisions.
      </p>
      <div class="mt-6">
        <a
          href="mailto:gaganthind@gmail.com"
          class="inline-block bg-indigo-600 text-white px-6 py-3 rounded-xl shadow hover:bg-indigo-700 transition"
        >Let’s Talk</a>
      </div>
    </div>
    <div class="md:w-1/2 flex justify-center" data-reveal>
      <img
        src="https://avatars.githubusercontent.com/u/000000?v=4"
        alt="Portrait of Gagandeep Thind"
        class="w-64 h-64 object-cover rounded-full shadow-2xl border-4 border-indigo-600"
      />
    </div>
  </section>

  <!-- ========== PROJECTS ========= -->
  <section id="projects" class="bg-white py-16">
    <div class="max-w-6xl mx-auto px-6">
      <h2 class="text-3xl sm:text-4xl font-bold mb-12 text-center">Featured Projects</h2>

      <div class="grid gap-10 md:grid-cols-2 lg:grid-cols-3">
        <!-- Project Card 1 -->
        <article class="bg-gray-100 rounded-3xl shadow p-6" data-reveal>
          <h3 class="text-2xl font-semibold mb-2">QuantEdge</h3>
          <p class="mb-3">
            Real‑time full‑stack trading & risk intelligence system combining XGBoost/LSTM signals, VaR monitoring, and a Streamlit dashboard.
          </p>
          <ul class="text-sm list-disc list-inside space-y-1 mb-4 text-gray-700">
            <li>Live ML predictions (5‑min OHLCV)</li>
            <li>AWS & GitHub Actions automation</li>
            <li>PostgreSQL + Power BI analytics</li>
          </ul>
          <a
            href="https://github.com/your‑repo/quantedge"
            class="text-indigo-600 font-semibold hover:underline"
            target="_blank" rel="noopener"
          >View Code →</a>
        </article>

        <!-- Project Card 2 -->
        <article class="bg-gray-100 rounded-3xl shadow p-6" data-reveal>
          <h3 class="text-2xl font-semibold mb-2">Magnificent 7 Sentiment Pipeline</h3>
          <p class="mb-3">
            AWS‑native ingestion & FinBERT sentiment scoring for real‑time news on Apple, Microsoft, Alphabet, Amazon, Meta, Nvidia, and Tesla.
          </p>
          <ul class="text-sm list-disc list-inside space-y-1 mb-4 text-gray-700">
            <li>EC2 + DynamoDB deduplication logic</li>
            <li>SageMaker SARIMAX retraining</li>
            <li>QuickSight dashboards</li>
          </ul>
          <a href="https://github.com/your‑repo/magnificent7" class="text-indigo-600 font-semibold hover:underline" target="_blank" rel="noopener">View Code →</a>
        </article>

        <!-- Project Card 3 -->
        <article class="bg-gray-100 rounded-3xl shadow p-6" data-reveal>
          <h3 class="text-2xl font-semibold mb-2">Anime‑Inspired Fitness Builder</h3>
          <p class="mb-3">
            A Python + Streamlit app that generates personalized workout plans (Baki, Goku, Fubuki) and tracks progress via Google Sheets.
          </p>
          <ul class="text-sm list-disc list-inside space-y-1 mb-4 text-gray-700">
            <li>Tailored mobility & strength routine</li>
            <li>Plotly interactive charts</li>
            <li>Deployed on Streamlit Cloud</li>
          </ul>
          <a href="https://github.com/your‑repo/anime-fitness" class="text-indigo-600 font-semibold hover:underline" target="_blank" rel="noopener">View Code →</a>
        </article>
      </div>
    </div>
  </section>

  <!-- ========== SKILLS ========= -->
  <section id="skills" class="py-16">
    <div class="max-w-6xl mx-auto px-6">
      <h2 class="text-3xl sm:text-4xl font-bold mb-10 text-center">Technical Toolkit</h2>

      <div class="flex flex-wrap justify-center gap-3" data-reveal>
        <span class="px-4 py-2 bg-gray-200 rounded-full">Python</span>
        <span class="px-4 py-2 bg-gray-200 rounded-full">SQL (PostgreSQL, MySQL)</span>
        <span class="px-4 py-2 bg-gray-200 rounded-full">AWS (S3, Lambda, SageMaker, EC2)</span>
        <span class="px-4 py-2 bg-gray-200 rounded-full">TensorFlow & PyTorch</span>
        <span class="px-4 py-2 bg-gray-200 rounded-full">Time‑Series (SARIMAX, ETS)</span>
        <span class="px-4 py-2 bg-gray-200 rounded-full">Docker & GitHub Actions</span>
        <span class="px-4 py-2 bg-gray-200 rounded-full">Power BI / Tableau</span>
      </div>
    </div>
  </section>

  <!-- ========== CONTACT ========= -->
  <section id="contact" class="bg-indigo-600 text-white py-16" data-reveal>
    <div class="max-w-3xl mx-auto px-6 text-center">
      <h2 class="text-3xl sm:text-4xl font-bold mb-4">Let’s connect!</h2>
      <p class="mb-8">Open to Data Science & Quant roles starting <strong>May 2025</strong>. Remote or Calgary‑based.</p>
      <a
        href="mailto:gaganthind@gmail.com"
        class="inline-block bg-white text-indigo-600 font-semibold px-8 py-3 rounded-xl shadow-lg hover:bg-gray-100 transition"
      >Email Me</a>
      <div class="mt-10 flex justify-center gap-8 text-lg">
        <a href="https://linkedin.com/in/gagandeep-thind" target="_blank" rel="noopener" class="hover:text-gray-300">LinkedIn</a>
        <a href="https://github.com/gagan11678" target="_blank" rel="noopener" class="hover:text-gray-300">GitHub</a>
        <a href="https://medium.com/@gaganthind" target="_blank" rel="noopener" class="hover:text-gray-300">Blog</a>
      </div>
    </div>
  </section>

  <!-- ========== FOOTER ========= -->
  <footer class="bg-gray-900 text-gray-400 py-6 text-center text-sm">
    © 2025 Gagandeep Thind — Built with Tailwind CSS & pure HTML.
  </footer>

  <!-- ========== Reveal Script ========= -->
  <script>
    // Simple scroll‑reveal without external libs
    const revealElements = document.querySelectorAll('[data-reveal]');
    const observer = new IntersectionObserver(
      (entries) => {
        entries.forEach((entry) => {
          if (entry.isIntersecting) {
            entry.target.classList.add('active');
            observer.unobserve(entry.target);
          }
        });
      },
      { threshold: 0.1 }
    );
    revealElements.forEach((el) => observer.observe(el));
  </script>
</body>
</html>
