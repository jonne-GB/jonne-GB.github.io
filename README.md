<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>jonne goudberg</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fdfdfd;
            color: #000000;
        }

        header {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(244, 242, 242, 0.5)),
            color: #fff;
            text-align: center;
            padding: 100px 20px;
        }

        header h1 {
            font-size: 4em;
            margin: 0;
            animation: fadeInDown 1s ease-in-out;
        }

        header p {
            font-size: 1.5em;
            margin-top: 10px;
            animation: fadeInUp 1s ease-in-out;
        }

        @keyframes fadeInDown {
            from { opacity: 0; transform: translateY(-50px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(50px); }
            to { opacity: 1; transform: translateY(0); }
        }

        nav {
            background-color: #161616;
            color: #fff;
            text-align: center;
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: 600;
            padding: 10px 20px;
            display: inline-block;
            transition: background-color 0.3s, color 0.3s;
        }

        nav ul li a:hover {
            background-color: #161616;
            border-radius: 5px;
        }

        .container {
            max-width: 1200px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
        }

        .about, .projects, .skills, .contact {
            margin-bottom: 50px;
        }

        .about h2, .projects h2, .skills h2, .contact h2 {
            font-size: 2.5em;
            color: #161616;
            border-bottom: 3px solid #161616;
            padding-bottom: 10px;
            margin-bottom: 30px;
        }

        .about p, .contact p {
            font-size: 1.2em;
            line-height: 1.8;
        }

        .skills ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
        }

        .skills ul li {
            background-color: #ffffff;
            padding: 10px 20px;
            border-radius: 5px;
            font-weight: 600;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
        }

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .project-card {
            background-color: #ffffff;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }

        .project-card:hover {
            transform: scale(1.05);
        }

        .project-image {
            height: 200px;
            background-color: #ffffff;
            background-size: cover;
            background-position: center;
        }

        .project-content {
            padding: 20px;
        }

        .project-content h3 {
            margin-top: 0;
            font-size: 1.5em;
        }

        .project-content p {
            font-size: 1em;
            line-height: 1.6;
        }

        .contact-form {
            display: flex;
            flex-direction: column;
        }

        .contact-form input, .contact-form textarea {
            padding: 15px;
            margin-bottom: 20px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1em;
            width: 100%;
            box-sizing: border-box;
        }

        .contact-form button {
            padding: 15px;
            background-color: #000000;
            color: #fff;
            border: none;
            border-radius: 5px;
            font-size: 1.2em;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .contact-form button:hover {
            background-color: #555;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #000000;
            color: #fff;
        }

        footer p {
            margin: 0;
            font-size: 1em;
        }
    </style>
</head>
<body>

    <header>
        <h1>jonne goudberg</h1>
        <p>profesional chatgpt user</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <div class="container">

        <section id="about" class="about">
            <h2>About Me</h2>
            <p>hi i'm jonne and i am very lazy that is why i use chatgpt for everything that i do, even this webpage is mostly made by chatgpt.</p>
        </section>

        <section id="skills" class="skills">
            <h2>Skills</h2>
            <ul>
                <li>chatgpt</li>
                <li>making dogwatter content</li>
                <li>editing</li>
                <li>making games</li>
                <li>watching yt</li>
            </ul>
        </section>

        <section id="projects" class="projects">
            <h2>Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <div class="project-image" style="background-image: url('https://source.unsplash.com/random/800x600');"></div>
                    <div class="project-content">
                        <h3>Project 1</h3>
                        <p>making a game in unity, at 14 years of age.</p>
                        <p>(the game is still a work in progress)</p>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image" style="background-image: url('https://source.unsplash.com/random/800x600?2');"></div>
                    <div class="project-content">
                        <h3>Project 2</h3>
                        <p>making my clothing brand.</p>
                        <p>(also still a work in progress)</p>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-content">
                        <h3>Project 3</h3>
                        <p>idk, im getting lazy.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="contact" class="contact">
            <h2>Contact</h2>
            <p>If you'd like to get in touch, feel free to send me a message using the form below:</p>
            <form class="contact-form">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>

    </div>

    <footer>
        <p>&copy; 2024 jonne goudberg. All rights reserved.</p>
    </footer>

</body>
</html>
