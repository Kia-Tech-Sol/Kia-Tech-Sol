
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: white;
            line-height: 1.6;
        }

        header {
            padding: 2rem;
            text-align: center;
        }

        header h1 {
            font-size: 3rem;
        }

        header p {
            opacity: 0.8;
            margin-top: 0.5rem;
        }

        nav {
            text-align: center;
            margin: 1rem 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            transition: 0.3s;
        }

        nav a:hover {
            color: #00d4ff;
        }

        section {
            padding: 4rem 2rem;
            max-width: 1000px;
            margin: auto;
        }

        .card {
            background: rgba(255, 255, 255, 0.1);
            padding: 2rem;
            border-radius: 15px;
            backdrop-filter: blur(10px);
            margin-bottom: 2rem;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            margin-top: 15px;
            background: #00d4ff;
            color: black;
            text-decoration: none;
            border-radius: 30px;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn:hover {
            background: white;
        }

        footer {
            text-align: center;
            padding: 2rem;
            opacity: 0.7;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Your Name</h1>
    <p>Cloud | DevOps | Software Developer</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <div class="card">
        <h2>About Me</h2>
        <p>
            I'm passionate about cloud computing, DevOps, and building scalable systems.
            I enjoy solving real-world problems using technology.
        </p>
    </div>
</section>

<section id="projects">
    <div class="card">
        <h2>Project One</h2>
        <p>A brief description of your project.</p>
        <a href="#" class="btn">View Project</a>
    </div>

    <div class="card">
        <h2>Project Two</h2>
        <p>A brief description of your project.</p>
        <a href="#" class="btn">View Project</a>
    </div>
</section>

<section id="contact">
    <div class="card">
        <h2>Contact</h2>
        <p>Email: your@email.com</p>
        <a href="https://github.com/yourusername" class="btn">GitHub</a>
    </div>
</section>

    
