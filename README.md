<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Ricky | Robotics & Web Dev</title>
    <style>
        :root {
            --bg-color: #0f172a;
            --card-bg: #1e293b;
            --text-color: #f8fafc;
            --accent-color: #38bdf8; /* Biru Teknologi */
            --secondary-color: #818cf8;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            line-height: 1.6;
        }

        header {
            height: 60vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: linear-gradient(rgba(15, 23, 42, 0.8), rgba(15, 23, 42, 0.8)), 
                        url('https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1000&q=80'); /* Background bertema sirkuit */
            background-size: cover;
        }

        h1 { font-size: 3rem; margin-bottom: 0.5rem; color: var(--accent-color); }
        p.subtitle { font-size: 1.2rem; opacity: 0.8; }

        .container { max-width: 900px; margin: auto; padding: 2rem; }

        .section-title {
            border-left: 4px solid var(--accent-color);
            padding-left: 10px;
            margin-top: 3rem;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }

        .card {
            background: var(--card-bg);
            padding: 1.5rem;
            border-radius: 12px;
            border: 1px solid #334155;
            transition: 0.3s;
        }

        .card:hover { transform: translateY(-5px); border-color: var(--accent-color); }

        .footer {
            text-align: center;
            padding: 3rem 0;
            font-size: 0.9rem;
            opacity: 0.6;
        }

        .btn {
            display: inline-block;
            background: var(--accent-color);
            color: #0f172a;
            padding: 0.8rem 1.5rem;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 1rem;
        }
    </style>
</head>
<body>

<header>
    <h1>Halo, Saya Ricky</h1>
    <p class="subtitle">Robotics Enthusiast | Web Developer Junior</p>
    <a href="#proyek" class="btn">Lihat Karya Saya</a>
</header>

<div class="container">
    
    <section id="about">
        <h2 class="section-title">Tentang Saya</h2>
        <p>Saya adalah seorang pelajar yang berfokus pada dunia **robotika** dan **pengembangan web**. Saya senang merakit sirkuit Arduino, menyolder komponen elektronika, dan membangun antarmuka web yang interaktif.</p>
    </section>

    <section id="skills">
        <h2 class="section-title">Keahlian</h2>
        <div class="skills-grid">
            <div class="card">
                <h3>🤖 Robotika</h3>
                <p>Pemrograman Arduino, Sensor Ultrasonik, Servo, dan Perakitan Sirkuit Elektronika.</p>
            </div>
            <div class="card">
                <h3>💻 Web Dev</h3>
                <p>Membuat struktur web menggunakan HTML5, styling dengan CSS3, dan deployment via Vercel.</p>
            </div>
        </div>
    </section>

    <section id="proyek">
        <h2 class="section-title">Proyek Unggulan</h2>
        <div class="card" style="margin-bottom: 1rem;">
            <h3>Sistem Robotik Mandiri</h3>
            <p>Proyek pengembangan alat bantu menggunakan mikrokontroler untuk efisiensi kerja.</p>
        </div>
        <div class="card">
            <h3>Web Portfolio v1.0</h3>
            <p>Membangun identitas digital menggunakan desain modern dan Dark Mode.</p>
        </div>
    </section>

</div>

<footer class="footer">
    <p>&copy; 2026 Ricky - Cot Girek. Dibuat dengan semangat teknologi.</p>
</footer>

</body>
</html>

