<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharo Ministry of Education</title>
  <style>
    /* Global Reset & Styling */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background-color: #f8fafc;
      color: #1e293b;
      line-height: 1.6;
    }

    /* Fixed Top Navigation Header */
    header {
      position: sticky;
      top: 0;
      z-index: 1000;
      background-color: #0f172a;
      box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
    }

    .navbar {
      max-width: 1200px;
      margin: 0 auto;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 1.5rem;
    }

    .brand-logo {
      color: #ffffff;
      font-size: 1.25rem;
      font-weight: 700;
      text-decoration: none;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    /* Top 3 Menu Action Buttons */
    .nav-buttons {
      display: flex;
      gap: 0.75rem;
    }

    .btn {
      padding: 0.6rem 1.2rem;
      border-radius: 6px;
      font-weight: 600;
      font-size: 0.9rem;
      text-decoration: none;
      transition: all 0.2s ease-in-out;
      cursor: pointer;
      border: none;
    }

    .btn-primary {
      background-color: #2563eb;
      color: #ffffff;
    }

    .btn-primary:hover {
      background-color: #1d4ed8;
    }

    .btn-secondary {
      background-color: #334155;
      color: #ffffff;
    }

    .btn-secondary:hover {
      background-color: #475569;
    }

    .btn-accent {
      background-color: #0d9488;
      color: #ffffff;
    }

    .btn-accent:hover {
      background-color: #0f766e;
    }

    /* Hero Section */
    .hero {
      background: linear-gradient(135deg, #1e293b 0%, #0f172a 100%);
      color: #ffffff;
      padding: 5rem 1.5rem;
      text-align: center;
    }

    .hero-content {
      max-width: 800px;
      margin: 0 auto;
    }

    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
      font-weight: 800;
    }

    .hero p {
      font-size: 1.15rem;
      color: #94a3b8;
      margin-bottom: 2rem;
    }

    /* Section Containers */
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 4rem 1.5rem;
    }

    .section-title {
      text-align: center;
      font-size: 2rem;
      font-weight: 700;
      margin-bottom: 0.5rem;
      color: #0f172a;
    }

    .section-subtitle {
      text-align: center;
      color: #64748b;
      margin-bottom: 3rem;
    }

    /* Stats Banner */
    .stats-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1.5rem;
      background: #ffffff;
      padding: 2rem;
      border-radius: 12px;
      box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
      margin-bottom: 4rem;
    }

    .stat-card {
      text-align: center;
    }

    .stat-number {
      font-size: 2.25rem;
      font-weight: 800;
      color: #2563eb;
    }

    .stat-label {
      color: #64748b;
      font-size: 0.9rem;
    }

    /* 10-Picture Gallery Grid */
    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .gallery-card {
      background: #ffffff;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .gallery-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
    }

    .gallery-card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      display: block;
    }

    .gallery-info {
      padding: 1rem;
    }

    .gallery-info h3 {
      font-size: 1rem;
      margin-bottom: 0.25rem;
      color: #0f172a;
    }

    .gallery-info p {
      font-size: 0.85rem;
      color: #64748b;
    }

    /* Footer */
    footer {
      background-color: #0f172a;
      color: #94a3b8;
      padding: 2.5rem 1.5rem;
      text-align: center;
      font-size: 0.9rem;
      margin-top: 4rem;
    }

    footer p {
      margin-bottom: 0.5rem;
    }

    /* Responsive Design for Mobile */
    @media (max-width: 640px) {
      .navbar {
        flex-direction: column;
        gap: 1rem;
      }
      
      .nav-buttons {
        width: 100%;
        justify-content: center;
      }

      .btn {
        padding: 0.5rem 0.8rem;
        font-size: 0.8rem;
      }

      .hero h1 {
        font-size: 1.8rem;
      }
    }
  </style>
</head>
<body>

  <!-- Top Fixed Header & 3 Menu Buttons -->
  <header>
    <div class="navbar">
      <a href="#home" class="brand-logo">🎓 Pharo Education</a>
      <div class="nav-buttons">
        <a href="#home" class="btn btn-primary">Home</a>
        <a href="#stats" class="btn btn-secondary">Programs</a>
        <a href="#gallery" class="btn btn-accent">Gallery</a>
      </div>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="hero-content">
      <h1>Pharo Ministry of Education Portal</h1>
      <p>Empowering learners, advancing institutional excellence, and shaping future leadership through structured digital infrastructure.</p>
      <a href="#gallery" class="btn btn-primary">Explore Campus Life</a>
    </div>
  </section>

  <!-- Main Container -->
  <main class="container">

    <!-- Key Metrics Section -->
    <section id="stats">
      <div class="stats-grid">
        <div class="stat-card">
          <div class="stat-number">12,500+</div>
          <div class="stat-label">Active Students</div>
        </div>
        <div class="stat-card">
          <div class="stat-number">450+</div>
          <div class="stat-label">Certified Educators</div>
        </div>
        <div class="stat-card">
          <div class="stat-number">98%</div>
          <div class="stat-label">Graduation Rate</div>
        </div>
        <div class="stat-card">
          <div class="stat-number">24/7</div>
          <div class="stat-label">Digital Support</div>
        </div>
      </div>
    </section>

    <!-- 10 Pictures Gallery Section -->
    <section id="gallery">
      <h2 class="section-title">Educational Showcase</h2>
      <p class="section-subtitle">A glimpse into our academic initiatives, laboratories, and student activities.</p>

      <div class="gallery-grid">
        <!-- Photo 1 -->
        <div class="gallery-card">
          <img src="https://images.unsplash.com/photo-1523240795612-9a054b0db644?auto=format&fit=crop&w=600&q=80" alt="Students studying">
          <div class="gallery-info">
            <h3>Student Learning</h3>
            <p>Interactive peer discussions and academic collaborative projects.</p>
          </div>
        </div>

        <!-- Photo 2 -->
        <div class="gallery-card">
          <img src="https://images.unsplash.com/photo-1509062522246-3755977927d7?auto=format&fit=crop&w=600&q=80" alt="Classroom lecture">
          <div class="gallery-info">
            <h3>Interactive Classrooms</h3>
            <p>Modern teaching techniques supported by digital tools.</p>
          </div>
        </div>

        <!-- Photo 3 -->
        <div class="gallery-card">
          <img src="https://images.unsplash.com/photo-1524178232363-1fb2b075b655?auto=format&fit=crop&w=600&q=80" alt="Lecture hall">
          <div class="gallery-info">
            <h3>Academic Lectures</h3>
            <p>Comprehensive subject instructions led by experienced educators.</p>
          </div>
        </div>

        <!-- Photo 4 -->
        <div class="gallery-card">
          <img src="https://images.unsplash.com/photo-1532094349884-543bc11b234d?auto=format&fit=crop&w=600&q=80" alt="Science laboratory">
          <div class="gallery-info">
            <h3>Science & Research</h3>
            <p>Hands-on experimentation in advanced science laboratories.</p>
          </div>
        </div>

        <!-- Photo 5 -->
        <div class="gallery-card">
          <img src="https://images.unsplash.com/photo-1521587760476-6c12a4b040da?auto=format&fit=crop&w=600&q=80" alt="Library shelf">
          <div class="gallery-info">
            <h3>Digital Library</h3>
            <p>Extensive collections of reference materials and study spaces.</p>
          </div>
        </div>

        <!-- Photo 6 -->
        <div class="gallery-card">
          <img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=600&q=80" alt="Computer lab">
          <div class="gallery-info">
            <h3>Technology Labs</h3>
            <p>Digital literacy and software engineering training environments.</p>
          </div>
        </div>

        <!-- Photo 7 -->
        <div class="gallery-card">
          <img src="https://images.unsplash.com/photo-1577896851231-70ef18881754?auto=format&fit=crop&w=600&q=80" alt="School library space">
          <div class="gallery-info">
            <h3>Study Resource Hub</h3>
            <p>Quiet study zones dedicated to focused exam preparation.</p>
          </div>
        </div>

        <!-- Photo 8 -->
        <div class="gallery-card">
          <img src="https://images.unsplash.com/photo-1541829070764-84a7d30dd3f3?auto=format&fit=crop&w=600&q=80" alt="University campus ground">
          <div class="gallery-info">
            <h3>Campus Environment</h3>
            <p>Maintained educational facilities designed for optimal learning.</p>
          </div>
        </div>

        <!-- Photo 9 -->
        <div class="gallery-card">
          <img src="https://images.unsplash.com/photo-1523050854058-8df90110c9f1?auto=format&fit=crop&w=600&q=80" alt="Graduation cap">
          <div class="gallery-info">
            <h3>Graduation & Achievements</h3>
            <p>Celebrating student excellence and academic completion.</p>
          </div>
        </div>

        <!-- Photo 10 -->
        <div class="gallery-card">
          <img src="https://images.unsplash.com/photo-1427504494785-3a9ca7044f45?auto=format&fit=crop&w=600&q=80" alt="Group discussion">
          <div class="gallery-info">
            <h3>Leadership Development</h3>
            <p>Developing future executive skills and peer leadership teams.</p>
          </div>
        </div>
      </div>
    </section>

  </main>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 Pharo Ministry of Education. All rights reserved.</p>
    <p>Powered by HTML, CSS, and Netlify continuous integration pipeline.</p>
  </footer>

</body>
</html>
