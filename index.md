<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vasudev Sharma - ML Researcher & Engineer</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link href="styles.css" rel="stylesheet">
</head>
<body>
    <nav class="navbar" id="navbar">
        <div class="nav-content">
            <div class="logo">VS</div>
            <div class="nav-links">
                <a href="#about">About</a>
                <a href="#research">Research</a>
                <a href="#skills">Skills</a>
                <a href="#projects">Projects</a>
                <a href="#contact">Contact</a>
            </div>
        </div>
    </nav>

    <div class="cursor-glow"></div>

    <header class="hero">
        <div class="glowing-dots">
            <div class="dot"></div>
            <div class="dot"></div>
            <div class="dot"></div>
        </div>
        <div class="hero-content">
            <h1 class="glitch" data-text="Vasudev Sharma">Vasudev Sharma</h1>
            <div class="typing-container">
                <span id="typing-text"></span>
                <span class="cursor"></span>
            </div>
        </div>
        <div class="scroll-indicator">
            <div class="mouse"></div>
            <span>Scroll to explore</span>
        </div>
    </header>

    <main>
        <section id="about" class="about-section">
            <div class="section-grid">
                <div class="about-content">
                    <h2 class="section-title">About Me</h2>
                    <p class="gradient-text">ML Researcher & Software Engineer</p>
                    <div class="stats-container">
                        <div class="stat-item">
                            <span class="stat-number">4.3</span>
                            <span class="stat-label">CGPA</span>
                        </div>
                        <div class="stat-item">
                            <span class="stat-number">96%</span>
                            <span class="stat-label">ML Score</span>
                        </div>
                        <div class="stat-item">
                            <span class="stat-number">86%</span>
                            <span class="stat-label">AI Accuracy</span>
                        </div>
                    </div>
                </div>
                <div class="about-image">
                    <div class="image-container">
                        <div class="floating-badge">MSc @ Concordia</div>
                    </div>
                </div>
            </div>
        </section>

        <section id="research" class="research-section">
            <h2 class="section-title">Research Experience</h2>
            <div class="research-grid">
                <div class="research-card" data-tilt>
                    <div class="card-icon"><i class="fas fa-brain"></i></div>
                    <h3>Multimodal Image Analysis</h3>
                    <p>Fine-tuned vision-language models for enhanced histopathology analysis</p>
                    <ul class="tech-tags">
                        <li>PyTorch</li>
                        <li>DINO</li>
                        <li>Transformers</li>
                    </ul>
                </div>
                <div class="research-card" data-tilt>
                    <div class="card-icon"><i class="fas fa-microscope"></i></div>
                    <h3>Cancer Screening AI</h3>
                    <p>86% accuracy in colorectal carcinoma diagnosis using self-supervised learning</p>
                    <ul class="tech-tags">
                        <li>Deep Learning</li>
                        <li>Computer Vision</li>
                        <li>Medical AI</li>
                    </ul>
                </div>
                <div class="research-card" data-tilt>
                    <div class="card-icon"><i class="fas fa-paint-brush"></i></div>
                    <h3>Image Synthesis</h3>
                    <p>Conditional GAN with self-attention for high-quality image generation</p>
                    <ul class="tech-tags">
                        <li>GANs</li>
                        <li>Neural Networks</li>
                        <li>Computer Vision</li>
                    </ul>
                </div>
            </div>
        </section>

        <section id="skills" class="skills-section">
            <h2 class="section-title">Technical Arsenal</h2>
            <div class="skills-container">
                <div class="skill-category">
                    <h3>Machine Learning</h3>
                    <div class="skill-bars">
                        <div class="skill-bar">
                            <span class="skill-name">PyTorch</span>
                            <div class="progress-bar">
                                <div class="progress" style="width: 95%"></div>
                            </div>
                        </div>
                        <div class="skill-bar">
                            <span class="skill-name">TensorFlow</span>
                            <div class="progress-bar">
                                <div class="progress" style="width: 90%"></div>
                            </div>
                        </div>
                        <div class="skill-bar">
                            <span class="skill-name">Computer Vision</span>
                            <div class="progress-bar">
                                <div class="progress" style="width: 85%"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- More skill categories... -->
            </div>
        </section>

        <section id="projects" class="projects-section">
            <h2 class="section-title">Featured Projects</h2>
            <div class="projects-timeline">
                <div class="timeline-item">
                    <div class="timeline-content">
                        <h3>Histopathology Analysis</h3>
                        <p>Advanced image analysis using vision-language models</p>
                        <div class="project-links">
                            <a href="#" class="project-link">View Project</a>
                        </div>
                    </div>
                </div>
                <!-- More timeline items... -->
            </div>
        </section>

        <section id="contact" class="contact-section">
            <h2 class="section-title">Let's Connect</h2>
            <div class="contact-grid">
                <a href="https://linkedin.com/in/vasudev-sharma-341171256" class="contact-card" data-tilt>
                    <i class="fab fa-linkedin"></i>
                    <span>LinkedIn</span>
                </a>
                <a href="https://github.com/Vasudev-Sharma-13" class="contact-card" data-tilt>
                    <i class="fab fa-github"></i>
                    <span>GitHub</span>
                </a>
                <a href="mailto:vsharma13.1998@gmail.com" class="contact-card" data-tilt>
                    <i class="fas fa-envelope"></i>
                    <span>Email</span>
                </a>
            </div>
        </section>
    </main>

    <footer class="footer">
        <div class="footer-content">
            <p>© 2024 Vasudev Sharma</p>
        </div>
    </footer>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/vanilla-tilt/1.7.0/vanilla-tilt.min.js"></script>
    <script src="scripts.js"></script>
</body>
</html>
