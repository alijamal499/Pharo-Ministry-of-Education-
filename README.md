<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Your Name | Portfolio</title>
    <meta
      name="description"
      content="Portfolio website for a developer, designer, and problem solver."
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <header class="header">
      <nav class="nav container">
        <a href="#home" class="logo">Your<span>Name</span></a>
        <button class="nav-toggle" aria-label="Open menu">
          <span></span>
          <span></span>
          <span></span>
        </button>
        <div class="nav-links">
          <a href="#about">About</a>
          <a href="#skills">Skills</a>
          <a href="#projects">Projects</a>
          <a href="#contact">Contact</a>
          <a href="#contact" class="btn btn-small">Hire Me</a>
        </div>
      </nav>
    </header>

    <main>
      <section id="home" class="hero">
        <div class="container hero-inner">
          <div class="hero-content">
            <p class="eyebrow">Hello, I’m</p>
            <h1>
              <span class="typing-text" data-text="Your Name"></span>
            </h1>
            <p class="tagline">
              I build <span>modern web experiences</span> that are fast,
              functional, and user-focused.
            </p>
            <div class="hero-actions">
              <a href="#projects" class="btn">View Projects</a>
              <a href="#contact" class="btn btn-secondary">Contact Me</a>
            </div>
            <div class="socials">
              <a href="https://github.com/yourusername" target="_blank" rel="noreferrer">
                GitHub
              </a>
              <a href="https://linkedin.com/in/yourprofile" target="_blank" rel="noreferrer">
                LinkedIn
              </a>
              <a href="mailto:you@example.com">Email</a>
            </div>
          </div>

          <div class="hero-visual">
            <div class="profile-card">
              <div class="profile-glow"></div>
              <div class="profile-image">
                <img
                  src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?auto=format&fit=crop&w=900&q=80"
                  alt="Profile"
                />
              </div>
              <div class="profile-badge">
                <span>Available for work</span>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section id="about" class="section">
        <div class="container">
          <div class="section-heading">
            <p class="eyebrow">About Me</p>
            <h2>Building useful products and meaningful experiences.</h2>
          </div>

          <div class="about-grid">
            <div class="about-card">
              <h3>Who I am</h3>
              <p>
                I’m a passionate developer focused on clean code, thoughtful
                design, and solving real user problems. I enjoy turning ideas
                into reliable digital products that people actually enjoy using.
              </p>
            </div>

            <div class="about-card">
              <h3>What I do</h3>
              <p>
                I design and develop responsive websites, web apps, and
                interactive interfaces using modern tools and best practices.
                Whether it’s frontend work or full-stack problem solving, I like
                building polished solutions from concept to launch.
              </p>
            </div>

            <div class="about-card">
              <h3>How I work</h3>
              <p>
                I believe in clear communication, iterative development, and
                creating experiences that balance usability, performance, and
                business goals.
              </p>
            </div>
          </div>
        </div>
      </section>

      <section id="skills" class="section alt">
        <div class="container">
          <div class="section-heading">
            <p class="eyebrow">Skills</p>
            <h2>Tools and technologies I use.</h2>
          </div>

          <div class="skills-grid">
            <div class="skill-card">
              <h3>Frontend</h3>
              <ul>
                <li>HTML5</li>
                <li>CSS3</li>
                <li>JavaScript</li>
                <li>React</li>
                <li>Tailwind CSS</li>
              </ul>
            </div>

            <div class="skill-card">
              <h3>Backend</h3>
              <ul>
                <li>Node.js</li>
                <li>Express</li>
                <li>REST APIs</li>
                <li>Authentication</li>
                <li>Database Design</li>
              </ul>
            </div>

            <div class="skill-card">
              <h3>Tools</h3>
              <ul>
                <li>Git & GitHub</li>
                <li>VS Code</li>
                <li>Figma</li>
                <li>Postman</li>
                <li>Docker</li>
              </ul>
            </div>

            <div class="skill-card">
              <h3>Workflow</h3>
              <ul>
                <li>Responsive Design</li>
                <li>UI/UX Thinking</li>
                <li>Problem Solving</li>
                <li>Agile Collaboration</li>
                <li>Performance Optimization</li>
              </ul>
            </div>
          </div>
        </div>
      </section>

      <section id="projects" class="section">
        <div class="container">
          <div class="section-heading">
            <p class="eyebrow">Projects</p>
            <h2>Selected work I’m proud of.</h2>
          </div>

          <div class="projects-grid">
            <article class="project-card">
              <div class="project-image project-one"></div>
              <div class="project-content">
                <h3>E-Commerce Dashboard</h3>
                <p>
                  A complete admin dashboard for tracking sales, inventory, and
                  user activity with clear analytics and a clean UI.
                </p>
                <div class="project-tags">
                  <span>React</span>
                  <span>Node.js</span>
                  <span>MongoDB</span>
                </div>
                <div class="project-links">
                  <a href="#">Live Demo</a>
                  <a href="#">Source Code</a>
                </div>
              </div>
            </article>

            <article class="project-card">
              <div class="project-image project-two"></div>
              <div class="project-content">
                <h3>Learning Platform</h3>
                <p>
                  An educational platform built for content discovery, course
                  enrollment, and user progression with engaging interactions.
                </p>
                <div class="project-tags">
                  <span>JavaScript</span>
                  <span>CSS</span>
                  <span>API</span>
                </div>
                <div class="project-links">
                  <a href="#">Live Demo</a>
                  <a href="#">Source Code</a>
                </div>
              </div>
            </article>

            <article class="project-card">
              <div class="project-image project-three"></div>
              <div class="project-content">
                <h3>Startup Landing Page</h3>
                <p>
                  A modern startup website focused on conversions, storytelling,
                  and strong product positioning.
                </p>
                <div class="project-tags">
                  <span>HTML</span>
                  <span>CSS</span>
                  <span>JavaScript</span>
                </div>
                <div class="project-links">
                  <a href="#">Live Demo</a>
                  <a href="#">Source Code</a>
                </div>
              </div>
            </article>
          </div>
        </div>
      </section>

      <section class="section stats">
        <div class="container stats-grid">
          <div class="stat">
            <strong data-count="3">0</strong>
            <span>Years Experience</span>
          </div>
          <div class="stat">
            <strong data-count="20">0</strong>
            <span>Projects Completed</span>
          </div>
          <div class="stat">
            <strong data-count="8">0</strong>
            <span>Technologies</span>
          </div>
          <div class="stat">
            <strong data-count="100">0</strong>
            <span>Client Satisfaction</span>
          </div>
        </div>
      </section>

      <section id="contact" class="section contact">
        <div class="container">
          <div class="section-heading">
            <p class="eyebrow">Contact</p>
            <h2>Let’s build something great together.</h2>
          </div>

          <div class="contact-box">
            <form class="contact-form" id="contactForm">
              <div class="input-group">
                <label for="name">Name</label>
                <input type="text" id="name" placeholder="Your name" required />
              </div>

              <div class="input-group">
                <label for="email">Email</label>
                <input
                  type="email"
                  id="email"
                  placeholder="you@example.com"
                  required
                />
              </div>

              <div class="input-group">
                <label for="message">Message</label>
                <textarea
                  id="message"
                  rows="6"
                  placeholder="Write your message here..."
                  required
                ></textarea>
              </div>

              <button type="submit" class="btn">Send Message</button>
            </form>

            <div class="contact-info">
              <h3>Get in touch</h3>
              <p>
                I’m open to freelance work, collaborations, and full-time
                opportunities.
              </p>

              <ul>
                <li>Email: <a href="mailto:you@example.com">you@example.com</a></li>
                <li>Phone: <a href="tel:+1234567890">+1 (234) 567-890</a></li>
                <li>Location: Your City, Country</li>
              </ul>
            </div>
          </div>
        </div>
      </section>
    </main>

    <footer class="footer">
      <div class="container footer-inner">
        <p>© <span id="year"></span> Your Name. All rights reserved.</p>
        <div class="footer-links">
          <a href="https://github.com/yourusername" target="_blank" rel="noreferrer">GitHub</a>
          <a href="https://linkedin.com/in/yourprofile" target="_blank" rel="noreferrer">LinkedIn</a>
        </div>
      </div>
    </footer>

    <script src="script.js"></script>
  </body>
</html>
