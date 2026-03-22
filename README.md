# tre2021743.github.io/
# index.html
# doubleuofficial.online/
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>DoubleU | Official Music, Albums, and Artist Website</title>

    <!-- SEO Meta Tags -->
    <meta name="description" content="DoubleU — genre‑bending artist blending atmospheric soundscapes with modern electronic energy. Listen to Faded 405, explore essential tracks, and contact for booking & press.">
    <meta name="keywords" content="DoubleU, DoubleU artist, Faded 405, electronic music, indie electronic, producer, artist website, new album 2026">
    <meta name="author" content="DoubleU">
    <meta name="robots" content="index, follow">

    <!-- Open Graph (Social Sharing) -->
    <meta property="og:title" content="DoubleU — Official Artist Website">
    <meta property="og:description" content="Listen to Faded 405 and explore essential tracks from DoubleU.">
    <meta property="og:image" content="https://images.unsplash.com/photo-1614613535308-eb5fbd3d2c17?auto=format&fit=crop&w=800&q=80">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://tre2021743.github.io/">

    <!-- Twitter Card -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="DoubleU — Official Artist Website">
    <meta name="twitter:description" content="Listen to Faded 405 and explore essential tracks from DoubleU.">
    <meta name="twitter:image" content="https://images.unsplash.com/photo-1614613535308-eb5fbd3d2c17?auto=format&fit=crop&w=800&q=80">
    <!-- Favicon -->
    <link rel="icon" type="image/x-icon" href="/favicon.ico">

    <!-- Structured Data (Google Knowledge Panel Boost) -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "MusicGroup",
      "name": "DoubleU",
      "url": "https://tre2021743.github.io/",
      "image": "https://images.unsplash.com/photo-1614613535308-eb5fbd3d2c17?auto=format&fit=crop&w=800&q=80",
      "genre": "Electronic",
      "description": "DoubleU is a 2026 electronic artist blending atmospheric soundscapes with modern production.",
      "album": {
        "@type": "MusicAlbum",
        "name": "Faded 405",
        "datePublished": "2026"
      },
      "sameAs": [
        "https://www.youtube.com/@DoubleUOTB/featured",
        "https://artists.spotify.com/c/artist/78gVqbaxxYAd9aLEZJ49YG",
        "https://artists.apple.com/ui/profile/artist/ami:identity:45917dc7f16e466e868bebaf98ae66d8"
      ]
    }
    </script>

    <style>
        :root {
        /* Keep existing variables, but we'll modify the bg usage */
        --bg-color: #0a0a0a;
        --text-color: #f5f5f7;
        --accent-main: #007bff; 
        --card-bg: rgba(22, 22, 22, 0.9); /* Added transparency for glass effect */
        --nav-bg: rgba(10, 10, 10, 0.8);
        --font-stack: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    }

    body {
        font-family: var(--font-stack);
        /* Set the background image here */
        background: 
            linear-gradient(rgba(10, 10, 10, 0.7), rgba(10, 10, 10, 0.7)), 
            url('IMG_0082.PNG');
        background-size: cover;
        background-position: center;
        background-attachment: fixed; /* Keeps image still while scrolling */
        background-repeat: no-repeat;
        color: var(--text-color);
        line-height: 1.6;
        overflow-x: hidden;
    }

        a { text-decoration: none; color: inherit; transition: 0.3s; }

        .container { width: 100%; max-width: 1100px; margin: 0 auto; padding: 0 20px; }

        nav {
            position: fixed; top: 0; width: 100%; z-index: 1000;
            padding: 20px 0; transition: 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            backdrop-filter: blur(20px);
        }
        nav.scrolled { background: var(--nav-bg); padding: 15px 0; border-bottom: 1px solid #222; }
        .nav-content { display: flex; justify-content: space-between; align-items: center; }
        .logo { font-weight: 900; letter-spacing: -1px; font-size: 1.2rem; }
        .nav-links a { margin-left: 30px; font-size: 0.9rem; opacity: 0.7; font-weight: 500; }
        .nav-links a:hover { opacity: 1; color: var(--accent-main); }

        .reveal { opacity: 0; transform: translateY(30px); transition: all 0.8s cubic-bezier(0.2, 1, 0.3, 1); }
        .reveal.active { opacity: 1; transform: translateY(0); }

        .hero { padding: 180px 0 100px; text-align: center; }
        .artist-name {
            font-size: clamp(3.5rem, 12vw, 7rem); font-weight: 900;
            text-transform: uppercase; letter-spacing: -5px;
            background: linear-gradient(to bottom, #ffffff, #777);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .subtitle { font-size: 1.1rem; opacity: 0.5; letter-spacing: 4px; text-transform: uppercase; margin-top: 10px; }

        section { margin-bottom: 120px; }
        .section-title { font-size: 1.8rem; margin-bottom: 40px; text-transform: uppercase; letter-spacing: 1px; }

        .release-card {
            display: flex; background: var(--card-bg); border-radius: 24px;
            overflow: hidden; border: 1px solid #222; align-items: center;
        }
        .release-cover { flex: 1; max-width: 500px; aspect-ratio: 1/1; background: #222; }
        .release-cover img { width: 100%; height: 100%; object-fit: cover; }
        .release-info { flex: 1.2; padding: 60px; }
        .label { color: var(--accent-main); font-size: 0.7rem; font-weight: 800; text-transform: uppercase; letter-spacing: 2px; margin-bottom: 10px; display: block; }
        .album-title { font-size: 3.5rem; line-height: 1; margin-bottom: 20px; }
        .btn-primary {
            display: inline-block; padding: 16px 45px; background: var(--accent-main);
            color: white; border-radius: 50px; font-weight: 700; border: none; cursor: pointer;
        }

        .tracks-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 15px; }
        .track-item {
            background: var(--card-bg); padding: 22px; border-radius: 12px;
            display: flex; align-items: center; border: 1px solid #222;
        }
        .track-item:hover { border-color: var(--accent-main); transform: translateX(8px); background: #1c1c1c; }
        .track-num { font-weight: 900; opacity: 0.2; margin-right: 20px; }

        .contact-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 60px; }
        input, textarea {
            width: 100%; padding: 18px; background: #1a1a1a; border: 1px solid #333;
            border-radius: 10px; color: white; margin-bottom: 15px;
        }
        footer { padding: 100px 0; border-top: 1px solid #222; text-align: center; opacity: 0.4; }

        @media (max-width: 850px) {
            .release-card, .contact-grid { flex-direction: column; display: block; }
            .release-info { padding: 40px 25px; text-align: center; }
            .nav-links { display: none; }
        }
    </style>
</head>

<body>

    <nav id="navbar">
        <div class="container nav-content">
            <div class="logo">DOUBLEU</div>
            <div class="nav-links">
                <a href="#music">Music</a>
                <a href="https://www.youtube.com/@DoubleUOTB/featured" target="_blank">YouTube</a>
                <a href="https://artists.spotify.com/c/artist/78gVqbaxxYAd9aLEZJ49YG" target="_blank">Spotify</a>
                <a href="https://artists.apple.com/ui/profile/artist/ami:identity:45917dc7f16e466e868bebaf98ae66d8" target="_blank">Apple Music</a>
                <a href="#contact">Contact</a>
            </div>
        </div>
    </nav>

    <header class="hero container">
        <h1 class="artist-name">DoubleU</h1>
        <p class="subtitle">Official Artist Website</p>
    </header>

    <main class="container">
        
        <section id="music">
            <div class="release-card reveal">
                <div class="release-cover">
                    <img src="https://images.unsplash.com/photo-1614613535308-eb5fbd3d2c17?auto=format&fit=crop&w=600&q=60" alt="Faded 405 album cover by DoubleU">
                </div>
                <div class="release-info">
                    <span class="label">Latest Release</span>
                    <h2 class="album-title">Faded 405</h2>
                    <p style="margin-bottom: 30px; opacity: 0.7;">The 2026 album capturing the pulse of the highway and the glow of the city.</p>
                    <a href="https://www.youtube.com/@DoubleUOTB/featured" class="btn-primary" target="_blank">Listen Now</a>
                </div>
            </div>
        </section>

        <section>
            <h2 class="section-title">Essential Tracks</h2>
            <div class="tracks-grid">
                <div class="track-item reveal"><span class="track-num">01</span> Shadow Work</div>
                <div class="track-item reveal"><span class="track-num">02</span> Velocity</div>
                <div class="track-item reveal"><span class="track-num">03</span> Midnight Echo</div>
                <div class="track-item reveal"><span class="track-num">04</span> Static Dreams</div>
                <div class="track-item reveal"><span class="track-num">05</span> Ghost Theory</div>
                <div class="track-item reveal"><span class="track-num">06</span> Undercurrent</div>
            </div>
        </section>

        <section id="contact">
            <div class="contact-grid reveal">
                <div>
                    <h2 style="font-size: 2.5rem; margin-bottom: 20px;">Contact</h2>
                    <p style="opacity: 0.6;">Booking & Press inquiries.</p>
                    <p style="margin-top: 20px; color: var(--accent-main);">mgmt@doubleumusic.com</p>
                </div>
                <form>
                    <input type="text" placeholder="Name">
                    <input type="email" placeholder="Email">
                    <textarea placeholder="Message" style="height: 120px;"></textarea>
                    <button type="submit" class="btn-primary" style="width: 100%;">Send</button>
                </form>
            </div>
        </section>
    </main>

    <footer>
        <p>© 2026 DoubleU. Designed for the sound of tomorrow.</p>
    </footer>

    <script>
        window.addEventListener('scroll', () => {
            const nav = document.getElementById('navbar');
            if (window.scrollY > 50) {
                nav.classList.add('scrolled');
            } else {
                nav.classList.remove('scrolled');
            }
        });

        const observerOptions = { threshold: 0.1 };
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('active');
                }
            });
        }, observerOptions);

        document.querySelectorAll('.release-card, .track-item, .contact-grid').forEach(el => {
            el.classList.add('reveal');
            observer.observe(el);
        });
    </script
  </html>
</body>
</html>
