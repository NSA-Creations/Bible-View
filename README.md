<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Romans 12 Bible Blog - Nsabimana Shadrach</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" />
    <link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='90'>✝</text></svg>" type="image/svg+xml" />
    <meta name="description" content="Romans 12 Bible Blog by Nsabimana Shadrach - A visually stunning and spiritually transformative experience with rich content, references, and motion backgrounds." />
    <meta name="keywords" content="Bible, Romans 12, Christian blog, spiritual transformation, Nsabimana Shadrach, Bible commentary, scripture references" />
    <meta name="author" content="Nsabimana Shadrach" />
    <meta property="og:title" content="Romans 12 Bible Blog - Nsabimana Shadrach" />
    <meta property="og:description" content="Explore Romans 12 with high-quality animations, references, motion backgrounds, and interactive features." />
    <meta property="og:type" content="website" />
    <meta property="og:url" content="https://example.com/romans12" />
    <meta property="og:image" content="https://example.com/logo.png" />
    <style>
        /* Base Styles */
        :root {
            --gold: #FFD700;
            --deep-blue: #1a2a6c;
            --light-bg: linear-gradient(135deg, #f8f9fa, #e9ecef);
            --bg-dark: #0a0f2f;
            --bg-dark-transparent: rgba(10, 15, 47, 0.85);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body,
        html {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            scroll-behavior: smooth;
            background: var(--light-bg);
            color: #333;
            overflow-x: hidden;
            min-height: 100vh;
            position: relative;
        }

        /* Motion Background */
        body::before {
            content: "";
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            background: radial-gradient(circle at center, #1a2a6c 0%, #0a0f2f 70%);
            z-index: -3;
            animation: slowPulse 20s ease-in-out infinite alternate;
        }

        @keyframes slowPulse {
            0% {
                filter: brightness(1);
                transform: scale(1);
            }
            100% {
                filter: brightness(1.2);
                transform: scale(1.05);
            }
        }

        /* Subtle moving stars background */
        body::after {
            content: "";
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            background: url('https://cdn.pixabay.com/photo/2016/11/29/03/53/star-1867616_1280.png') repeat;
            background-size: 50px 50px;
            opacity: 0.15;
            animation: starMove 120s linear infinite;
            z-index: -2;
        }

        @keyframes starMove {
            from {
                background-position: 0 0;
            }
            to {
                background-position: 10000px 0;
            }
        }

        /* Header Styles */
        header {
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
            padding: 20px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: var(--bg-dark-transparent);
            box-shadow: 0 2px 15px rgba(0, 0, 0, 0.6);
            backdrop-filter: blur(10px);
            color: var(--gold);
        }

        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            display: flex;
            align-items: center;
            gap: 10px;
            cursor: default;
            user-select: none;
        }

        .logo-icon {
            font-size: 2.4rem;
            color: var(--gold);
            text-shadow: 0 0 6px #ffd700aa;
        }

        /* Navigation */
        nav ul {
            display: flex;
            gap: 25px;
            list-style: none;
        }

        nav a {
            text-decoration: none;
            color: var(--gold);
            font-weight: 600;
            position: relative;
            padding: 5px 0;
            transition: color 0.3s;
        }

        nav a::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--gold);
            transition: width 0.3s;
        }

        nav a:hover,
        nav a.active {
            color: #fff;
        }

        nav a:hover::after,
        nav a.active::after {
            width: 100%;
        }

        /* Section Styles */
        section {
            min-height: 100vh;
            padding: 100px 20px 80px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            position: relative;
            max-width: 900px;
            margin: 0 auto;
            opacity: 0;
            transform: translateY(30px);
            transition: opacity 0.8s ease, transform 0.8s ease;
            background: var(--bg-dark-transparent);
            border-radius: 20px;
            box-shadow: 0 0 40px rgba(255, 215, 0, 0.3);
            color: #fff;
            backdrop-filter: blur(12px);
        }

        section.active {
            opacity: 1;
            transform: translateY(0);
        }

        h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            background: linear-gradient(to right, var(--gold), #fff);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 0 10px #ffd700bb;
        }

        h2 {
            font-size: 2.8rem;
            margin-bottom: 30px;
            color: var(--gold);
            text-shadow: 0 0 8px #ffd700cc;
        }

        p {
            font-size: 1.25rem;
            line-height: 1.8;
            max-width: 800px;
            margin-bottom: 25px;
        }

        /* Verse Styles */
        .verse-container {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            padding: 30px;
            margin: 40px 0;
            box-shadow: 0 5px 15px rgba(255, 215, 0, 0.3);
            max-width: 800px;
            backdrop-filter: blur(8px);
            border: 1px solid rgba(255, 215, 0, 0.5);
            position: relative;
            font-style: italic;
            color: #fff;
        }

        .verse {
            font-size: 1.4rem;
            line-height: 1.6;
            position: relative;
            padding-left: 40px;
            padding-right: 40px;
        }

        .verse::before,
        .verse::after {
            content: '"';
            font-size: 3rem;
            color: var(--gold);
            position: absolute;
            opacity: 0.4;
            font-weight: 900;
            font-family: serif;
        }

        .verse::before {
            top: 0;
            left: 10px;
        }

        .verse::after {
            bottom: -10px;
            right: 10px;
        }

        .verse-ref {
            display: block;
            text-align: right;
            margin-top: 15px;
            font-style: normal;
            font-weight: 700;
            color: var(--gold);
            text-shadow: 0 0 6px #ffd700cc;
        }

        /* References container */
        .reference {
            font-size: 0.9rem;
            color: #ccc;
            margin-top: 5px;
            font-style: normal;
            max-width: 800px;
            text-align: center;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            user-select: text;
        }

        /* Cursor Effects */
        .cursor {
            position: fixed;
            width: 32px;
            height: 32px;
            border-radius: 50%;
            background: rgba(255, 215, 0, 0.8);
            transform: translate(-50%, -50%);
            pointer-events: none;
            z-index: 9999;
            mix-blend-mode: difference;
            transition: transform 0.15s ease, background 0.3s ease;
            box-shadow: 0 0 8px #ffd700aa;
        }

        .cursor-follower {
            position: fixed;
            width: 12px;
            height: 12px;
            background: var(--gold);
            border-radius: 50%;
            transform: translate(-50%, -50%);
            pointer-events: none;
            z-index: 9998;
            transition: width 0.3s ease, height 0.3s ease;
            box-shadow: 0 0 10px #ffd700dd;
        }

        /* Animation Effects */
        .animate-section {
            animation: fadeInUp 1s forwards;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 30px;
            font-size: 1rem;
            color: #bbb;
            background: var(--bg-dark-transparent);
            border-top: 1px solid rgba(255, 215, 0, 0.3);
            user-select: none;
        }

        /* Responsive Design */
        @media (max-width: 900px) {
            header {
                flex-direction: column;
                gap: 15px;
                padding: 15px 20px;
            }

            h1 {
                font-size: 2.5rem;
            }

            h2 {
                font-size: 2rem;
            }

            nav ul {
                gap: 15px;
            }
        }

        @media (max-width: 600px) {
            .verse {
                font-size: 1.2rem;
            }

            nav ul {
                flex-wrap: wrap;
                justify-content: center;
            }
        }

        /* Motion Picture Container */
        .motion-video-container {
            max-width: 900px;
            width: 100%;
            margin: 40px auto;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 0 40px rgba(255, 215, 0, 0.4);
        }

        video {
            width: 100%;
            height: auto;
            display: block;
            filter: brightness(0.85);
            border-radius: 20px;
        }
    </style>
</head>
<body>
    <!-- Custom Cursor Elements -->
    <div class="cursor"></div>
    <div class="cursor-follower"></div>

    <!-- Header with Logo -->
    <header>
        <div class="logo">
            <span class="logo-icon" aria-hidden="true">✝</span>
            <span>Romans 12</span>
        </div>
        <nav>
            <ul>
                <li><a href="#intro" class="active">Home</a></li>
                <li><a href="#living-sacrifice">Sacrifice</a></li>
                <li><a href="#non-conformity">Non-Conformity</a></li>
                <li><a href="#renewal">Renewal</a></li>
                <li><a href="#gifts">Spiritual Gifts</a></li>
                <li><a href="#love-action">Love in Action</a></li>
                <li><a href="#application">Application</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Introduction Section -->
        <section id="intro" class="active animate-section" tabindex="0" aria-label="Introduction to Romans 12">
            <h1>Romans 12: Transformative Living</h1>
            <p>A stunning Bible blog experience by Nsabimana Shadrach</p>
            <div class="verse-container" aria-label="Romans 12:2 Verse">
                <p class="verse">"Do not conform to the pattern of this world, but be transformed by the renewing of your mind. Then you will be able to test and approve what God's will is—his good, pleasing and perfect will."</p>
                <span class="verse-ref">Romans 12:2 (NIV)</span>
                <div class="reference">Reference: <a href="https://www.bibleref.com/Romans/12/Romans-chapter-12.html" target="_blank" rel="noopener noreferrer" style="color:#ffd700;">BibleRef.com Commentary</a></div>
            </div>
            <div class="motion-video-container" aria-hidden="true">
                <video autoplay muted loop playsinline>
                    <source src="https://cdn.videvo.net/videvo_files/video/free/2017-11/small_watermarked/171103_03_Aurora_01_preview.webm" type="video/webm" />
                    <source src="https://cdn.videvo.net/videvo_files/video/free/2017-11/small_watermarked/171103_03_Aurora_01_preview.mp4" type="video/mp4" />
                    Your browser does not support the video tag.
                </video>
            </div>
        </section>

        <!-- Living Sacrifice Section -->
        <section id="living-sacrifice" tabindex="0" aria-label="Living Sacrifice">
            <h2>Living Sacrifice</h2>
            <p>True worship transcends ritual—it's the daily offering of our entire being to God. Paul's call to be a "living sacrifice" represents a radical shift from temple sacrifices to personal surrender.</p>
            <div class="verse-container" aria-label="Romans 12:1 Verse">
                <p class="verse">"Therefore, I urge you, brothers and sisters, in view of God's mercy, to offer your bodies as a living sacrifice, holy and pleasing to God—this is your true and proper worship."</p>
                <span class="verse-ref">Romans 12:1 (NIV)</span>
                <div class="reference">Reference: <a href="https://www.biblestudytools.com/commentaries/matthew-henry-concise/romans/12.html" target="_blank" rel="noopener noreferrer" style="color:#ffd700;">Matthew Henry Commentary</a></div>
            </div>
        </section>

        <!-- Non-Conformity Section -->
        <section id="non-conformity" tabindex="0" aria-label="Non-Conformity">
            <h2>Sacred Non-Conformity</h2>
            <p>In a world of constant pressure to conform, Romans 12 calls Christians to counter-cultural transformation. This isn't mere rejection but proactive alignment with God's design.</p>
            <div class="verse-container" aria-label="Romans 12:2a Verse">
                <p class="verse">"Do not conform to the pattern of this world, but be transformed by the renewing of your mind."</p>
                <span class="verse-ref">Romans 12:2a (NIV)</span>
                <div class="reference">Reference: <a href="https://enduringword.com/bible-commentary/romans-12/" target="_blank" rel="noopener noreferrer" style="color:#ffd700;">Enduring Word Commentary</a></div>
            </div>
        </section>

        <!-- Renewal of Mind Section -->
        <section id="renewal" tabindex="0" aria-label="Renewal of Mind">
            <h2>Renewed Thinking</h2>
            <p>Transformation begins at the deepest level—our thought patterns. Renewed thinking enables discernment of God's perfect will, creating a foundation for Christ-centered living.</p>
            <div class="verse-container" aria-label="Romans 12:2b Verse">
                <p class="verse">"Then you will be able to test and approve what God's will is—his good, pleasing and perfect will."</p>
                <span class="verse-ref">Romans 12:2b (NIV)</span>
                <div class="reference">Reference: <a href="https://www.bibleref.com/Romans/12/Romans-chapter-12.html" target="_blank" rel="noopener noreferrer" style="color:#ffd700;">BibleRef.com Explanation</a></div>
            </div>
        </section>

        <!-- Spiritual Gifts Section -->
        <section id="gifts" tabindex="0" aria-label="Spiritual Gifts">
            <h2>Spiritual Gifts in the Body</h2>
            <p>God equips every believer with unique spiritual gifts to serve and build up the church. Romans 12:3-8 encourages humility and faithful use of these gifts for the common good.</p>
            <div class="verse-container" aria-label="Romans 12:3-8 Verses">
                <p class="verse">"For by the grace given me I say to every one of you: Do not think of yourself more highly than you ought, but rather think of yourself with sober judgment... We have different gifts, according to the grace given to each of us."</p>
                <span class="verse-ref">Romans 12:3-8 (NIV)</span>
                <div class="reference">Reference: <a href="https://www.workingpreacher.org/commentaries/revised-common-lectionary/ordinary-21/commentary-on-romans-121-8-5" target="_blank" rel="noopener noreferrer" style="color:#ffd700;">Working Preacher Commentary</a></div>
            </div>
        </section>

        <!-- Love in Action Section -->
        <section id="love-action" tabindex="0" aria-label="Love in Action">
            <h2>Love in Action</h2>
            <p>Paul outlines genuine love as the foundation of Christian living — sincere, zealous, patient, and humble. We are called to bless enemies and overcome evil with good.</p>
            <div class="verse-container" aria-label="Romans 12:9-21 Verses">
                <p class="verse">"Love must be sincere. Hate what is evil; cling to what is good... Bless those who persecute you; bless and do not curse... Do not be overcome by evil, but overcome evil with good."</p>
                <span class="verse-ref">Romans 12:9-21 (NIV)</span>
                <div class="reference">Reference: <a href="https://www.biblegateway.com/passage/?search=Romans+12&version=NIV" target="_blank" rel="noopener noreferrer" style="color:#ffd700;">Bible Gateway NIV</a></div>
            </div>
        </section>

        <!-- Practical Application Section -->
        <section id="application" tabindex="0" aria-label="Practical Application">
            <h2>Practical Christianity</h2>
            <p>Romans 12 challenges us to live out our faith with humility, love, and service. It is a call to embody God’s mercy in everyday life and relationships.</p>
            <div class="verse-container" aria-label="Summary Verse">
                <p class="verse">"Therefore, I urge you, brothers and sisters, in view of God's mercy, to offer your bodies as a living sacrifice... Be devoted to one another in love."</p>
                <span class="verse-ref">Romans 12:1, 10 (NIV)</span>
            </div>
        </section>
    </main>

    <footer>
        &copy; 2025 Nsabimana Shadrach Bible Blog | Transformative Truths from Romans 12
    </footer>

    <script>
        // Intersection Observer for section animations
        const sections = document.querySelectorAll('section');

        const observer = new IntersectionObserver(
            (entries) => {
                entries.forEach((entry) => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('active');
                    }
                });
            },
            { threshold: 0.15 }
        );

        sections.forEach((section) => {
            observer.observe(section);
        });

        // Custom Cursor Implementation
        const cursor = document.querySelector('.cursor');
        const follower = document.querySelector('.cursor-follower');

        document.addEventListener('mousemove', (e) => {
            cursor.style.left = e.clientX + 'px';
            cursor.style.top = e.clientY + 'px';

            setTimeout(() => {
                follower.style.left = e.clientX + 'px';
                follower.style.top = e.clientY + 'px';
            }, 100);
        });

        // Interactive hover effects
        document.querySelectorAll('a, .verse-container').forEach((element) => {
            element.addEventListener('mouseenter', () => {
                cursor.style.transform = 'scale(3)';
                cursor.style.background = 'rgba(255, 215, 0, 0.7)';
                follower.style.width = '20px';
                follower.style.height = '20px';
            });

            element.addEventListener('mouseleave', () => {
                cursor.style.transform = 'scale(1)';
                cursor.style.background = 'rgba(255, 215, 0, 0.8)';
                follower.style.width = '12px';
                follower.style.height = '12px';
            });
        });

        // Smooth scrolling for navigation with active link update
        const navLinks = document.querySelectorAll('nav a');
        navLinks.forEach((anchor) => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                const targetSection = document.querySelector(targetId);

                window.scrollTo({
                    top: targetSection.offsetTop - 80,
                    behavior: 'smooth',
                });

                navLinks.forEach((link) => link.classList.remove('active'));
                this.classList.add('active');
            });
        });

        // Update active nav link on scroll
        window.addEventListener('scroll', () => {
            let current = '';
            sections.forEach((section) => {
                const sectionTop = section.offsetTop - 100;
                if (pageYOffset >= sectionTop) {
                    current = section.getAttribute('id');
                }
            });
            navLinks.forEach((link) => {
                link.classList.remove('active');
                if (link.getAttribute('href') === '#' + current) {
                    link.classList.add('active');
                }
            });
        });
    </script>
</body>
</html>
