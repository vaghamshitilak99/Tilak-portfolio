<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tilak Vaghamshi | Business Operations Specialist</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primary: #0f172a;
            --accent: #2563eb;
            --bg-light: #f8fafc;
            --white: #ffffff;
            --text-main: #1e293b;
            --text-muted: #64748b;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; scroll-behavior: smooth; }

        body {
            font-family: 'Inter', -apple-system, sans-serif;
            background-color: var(--bg-light);
            color: var(--text-main);
            line-height: 1.6;
        }

        nav {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            padding: 1rem 10%;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 1px 10px rgba(0,0,0,0.05);
        }

        .nav-links a {
            text-decoration: none;
            color: var(--text-main);
            margin-left: 2rem;
            font-weight: 500;
            transition: color 0.3s;
        }

        .nav-links a:hover { color: var(--accent); }

        .hero {
            padding: 12rem 10% 6rem;
            background: var(--white);
            text-align: center;
        }

        .hero h1 { font-size: 3.5rem; color: var(--primary); margin-bottom: 1rem; }
        .hero p { font-size: 1.2rem; color: var(--text-muted); max-width: 800px; margin: 0 auto 2rem; }

        .btn-group { display: flex; justify-content: center; gap: 1rem; flex-wrap: wrap; }

        .primary-btn { 
            background: var(--accent); 
            color: white; 
            padding: 0.8rem 2rem; 
            border-radius: 8px; 
            text-decoration: none; 
            font-weight: bold; 
            transition: 0.3s; 
            border: 2px solid var(--accent);
        }

        .secondary-btn { 
            background: transparent; 
            color: var(--accent); 
            padding: 0.8rem 2rem; 
            border-radius: 8px; 
            text-decoration: none; 
            font-weight: bold; 
            transition: 0.3s; 
            border: 2px solid var(--accent);
        }

        .primary-btn:hover, .secondary-btn:hover { transform: translateY(-3px); box-shadow: 0 4px 12px rgba(37, 99, 235, 0.2); }

        .section-padding { padding: 6rem 10%; }
        .section-title { font-size: 2.25rem; text-align: center; margin-bottom: 3rem; color: var(--primary); }

        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            background: var(--primary);
            color: white;
            padding: 4rem 10%;
            text-align: center;
        }

        .stat-item h2 { font-size: 2.5rem; color: var(--accent); }

        .exp-card {
            background: var(--white);
            padding: 2.5rem;
            border-radius: 12px;
            margin-bottom: 2rem;
            box-shadow: 0 10px 15px -3px rgba(0,0,0,0.1);
            border-left: 5px solid var(--accent);
        }

        .exp-header { display: flex; justify-content: space-between; flex-wrap: wrap; margin-bottom: 1rem; }
        .role { color: var(--accent); font-weight: bold; font-size: 1.1rem; }
        .company { color: var(--primary); font-weight: 700; }

        .bullet-list { list-style: none; margin-top: 1rem; }
        .bullet-list li { margin-bottom: 0.8rem; padding-left: 1.5rem; position: relative; }
        .bullet-list li::before { content: "•"; color: var(--accent); position: absolute; left: 0; font-weight: bold; }

        .skill-bar-container { margin-bottom: 1.5rem; }
        .skill-label { display: flex; justify-content: space-between; margin-bottom: 0.5rem; font-weight: 600; }
        .bar-bg { background: #e2e8f0; height: 8px; border-radius: 10px; }
        .bar-fill { background: var(--accent); height: 100%; border-radius: 10px; }

        .details-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; }
        .detail-box { background: var(--white); padding: 2.5rem; border-radius: 12px; box-shadow: 0 4px 6px rgba(0,0,0,0.05); }

        .contact-section { background: var(--primary); color: white; border-radius: 20px; padding: 4rem; text-align: center; }

        @media (max-width: 768px) {
            .hero h1 { font-size: 2.5rem; }
            .nav-links { display: none; }
            .section-padding { padding: 4rem 5%; }
        }
    </style>
</head>
<body>

    <nav>
        <div style="font-size: 1.4rem; font-weight: 800; color: var(--primary);">TILAK VAGHAMSHI</div>
        <div class="nav-links">
            <a href="#about">About</a>
            <a href="#experience">Experience</a>
            <a href="#skills">Skills</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <section class="hero" id="about">
        <h1>Tilak Vaghamshi</h1>
        <p><strong>Business Operations Analyst | 3.2 Years at TCS eServe</strong></p>
        <p>Expert in process automation and mortgage regulatory compliance. [cite_start]I specialize in turning complex data into streamlined, high-accuracy workflows[cite: 1, 4, 11].</p>
        
        <div class="btn-group">
            <a href="mailto:vaghamshitilak99@gmail.com" class="primary-btn"><i class="fas fa-paper-plane"></i> Hire Me</a>
            <a href="TILAK_VAGHAMSHI_CV.pdf" download class="secondary-btn"><i class="fas fa-download"></i> Download CV</a>
        </div>
    </section>

    <div class="stats-container">
        [cite_start]<div class="stat-item"><h2>99%+</h2><p>Accuracy Rate [cite: 5, 15]</p></div>
        [cite_start]<div class="stat-item"><h2>40%</h2><p>Manual Entry Reduced [cite: 8, 17]</p></div>
        [cite_start]<div class="stat-item"><h2>35%</h2><p>Error Reduction [cite: 16, 49]</p></div>
        [cite_start]<div class="stat-item"><h2>30%</h2><p>Faster Approvals [cite: 9, 20]</p></div>
    </div>

    <section class="section-padding" id="experience">
        <h2 class="section-title">Professional Experience</h2>
        
        <div class="exp-card">
            <div class="exp-header">
                <div><span class="role">Researcher</span> | [cite_start]<span class="company">TCS eServe (Rocket Companies, Inc.) [cite: 14]</span></div>
                <div class="text-muted">June 2024 — Present | [cite_start]Gandhinagar [cite: 14]</div>
            </div>
            <ul class="bullet-list">
                [cite_start]<li>Manage 45+ research profiles daily with 99%+ validation accuracy[cite: 5, 15, 48].</li>
                [cite_start]<li>Reduced inter-department coordination errors by 35% through software implementation[cite: 16, 49, 85].</li>
                [cite_start]<li>Achieved 25% improvement in response speed via redesigned workflows[cite: 16, 49, 85].</li>
                [cite_start]<li>Automated documentation, eliminating 40% of manual data entry[cite: 17, 50, 86].</li>
            </ul>
        </div>

        <div class="exp-card">
            <div class="exp-header">
                <div><span class="role">Process Associate</span> | [cite_start]<span class="company">TCS eServe (Mr. Cooper) [cite: 18]</span></div>
                <div class="text-muted">Dec 2023 — June 2024 | [cite_start]Gandhinagar [cite: 18, 51]</div>
            </div>
            <ul class="bullet-list">
                [cite_start]<li>Processed 500+ monthly foreclosure documents with 99%+ accuracy[cite: 5, 19, 52].</li>
                [cite_start]<li>Deployed IT-driven solutions cutting approval time by 30%[cite: 9, 20, 53].</li>
                [cite_start]<li>Conducted compliance audits across 150+ documents to resolve discrepancies[cite: 21, 54, 90].</li>
                [cite_start]<li>Trained 10+ team members, reducing ramp-up time by 3 weeks[cite: 22, 55, 91].</li>
            </ul>
        </div>
    </section>

    <section class="section-padding" id="skills">
        <h2 class="section-title">Technical Expertise</h2>
        <div class="details-grid">
            <div class="detail-box">
                [cite_start]<h3>Proficiencies [cite: 29, 30]</h3>
                <div class="skill-bar-container">
                    <div class="skill-label"><span>Advanced Excel (Macros/VBA)</span><span>95%</span></div>
                    <div class="bar-bg"><div class="bar-fill" style="width: 95%;"></div></div>
                </div>
                <div class="skill-bar-container">
                    <div class="skill-label"><span>Tally ERP 9</span><span>90%</span></div>
                    <div class="bar-bg"><div class="bar-fill" style="width: 90%;"></div></div>
                </div>
                <div class="skill-bar-container">
                    <div class="skill-label"><span>Compliance Auditing</span><span>100%</span></div>
                    <div class="bar-bg"><div class="bar-fill" style="width: 100%;"></div></div>
                </div>
            </div>
            <div class="detail-box">
                [cite_start]<h3>Key Recognitions [cite: 35, 69, 105]</h3>
                <ul class="bullet-list">
                    [cite_start]<li>AI Idea Igniter Award (2025) [cite: 35]</li>
                    [cite_start]<li>Elevate Wings Award (2025) [cite: 69]</li>
                    [cite_start]<li>US Regulatory Compliance Certified (2025) [cite: 34]</li>
                    [cite_start]<li>Service & Commitment Award (2024) [cite: 105]</li>
                </ul>
            </div>
        </div>
    </section>

    <section class="section-padding" id="contact">
        <div class="contact-section">
            <h2>Global Mobility Ready</h2>
            <p><strong>Passport Status:</strong> Active</p>
            <p>Open to opportunities in <strong>Australia</strong> and the Asian Timezone.</p>
            <p>Immediate Joiner | Currently in Ahmedabad, Gujarat</p>
            <br>
            [cite_start]<p><i class="fas fa-phone"></i> +91 8733885500 [cite: 2, 73]</p>
            <a href="mailto:vaghamshitilak99@gmail.com" class="primary-btn" style="margin-top: 2rem;">Email Me Directly</a>
        </div>
    </section>

    <footer style="text-align: center; padding: 2rem; color: var(--text-muted); font-size: 0.9rem;">
        &copy; 2026 Tilak Vaghamshi | [cite_start]BBA Graduate - JG University [cite: 32, 64, 100]
    </footer>

</body>
</html>
