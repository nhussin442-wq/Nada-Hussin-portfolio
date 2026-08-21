<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Nada Hussin | Textile Engineering</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@300;400;500;600&family=Playfair+Display:wght@500;600&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: 'DM Sans', sans-serif;
    background: #f7f5f1;
    color: #1d1d1b;
    line-height: 1.6;
}

/* NAVIGATION */

nav {
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 1000;
    padding: 22px 7%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: rgba(247,245,241,.92);
    backdrop-filter: blur(12px);
}

.logo {
    font-family: 'Playfair Display', serif;
    font-size: 25px;
    font-weight: 600;
}

nav a {
    color: #1d1d1b;
    text-decoration: none;
    margin-left: 28px;
    font-size: 14px;
}

nav a:hover {
    opacity: .55;
}

/* HERO */

.hero {
    min-height: 100vh;
    padding: 150px 7% 80px;
    display: flex;
    align-items: center;
}

.hero-content {
    max-width: 900px;
}

.small-title {
    text-transform: uppercase;
    letter-spacing: 4px;
    font-size: 12px;
    color: #777;
    margin-bottom: 25px;
}

h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(55px, 9vw, 120px);
    line-height: .95;
    font-weight: 500;
    margin-bottom: 35px;
}

.hero p {
    max-width: 650px;
    font-size: 18px;
    color: #666;
    margin-bottom: 40px;
}

.button {
    display: inline-block;
    padding: 15px 30px;
    background: #1d1d1b;
    color: white;
    text-decoration: none;
    font-size: 13px;
    letter-spacing: 1px;
    transition: .3s;
}

.button:hover {
    transform: translateY(-3px);
    background: #555;
}

/* SECTIONS */

section {
    padding: 110px 7%;
}

.section-title {
    font-family: 'Playfair Display', serif;
    font-size: 52px;
    margin-bottom: 45px;
}

/* ABOUT */

.about {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 80px;
    align-items: start;
}

.about p {
    font-size: 18px;
    color: #666;
}

/* PROJECTS */

.projects {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 22px;
}

.project {
    min-height: 330px;
    padding: 35px;
    background: #e8e2d8;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    transition: .3s;
}

.project:nth-child(2) {
    background: #d9d6cc;
}

.project:nth-child(3) {
    background: #ded1c4;
}

.project:nth-child(4) {
    background: #cfcfc7;
}

.project:hover {
    transform: translateY(-7px);
}

.project span {
    text-transform: uppercase;
    letter-spacing: 2px;
    font-size: 11px;
    margin-bottom: 10px;
}

.project h3 {
    font-family: 'Playfair Display', serif;
    font-size: 30px;
}

/* SKILLS */

.skills {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
}

.skill {
    border: 1px solid #bbb;
    padding: 12px 20px;
    font-size: 13px;
}

/* CONTACT */

.contact {
    background: #1d1d1b;
    color: white;
}

.contact .section-title {
    color: white;
}

.contact p {
    color: #bbb;
    max-width: 600px;
    margin-bottom: 30px;
}

.contact a {
    color: white;
}

/* FOOTER */

footer {
    background: #1d1d1b;
    color: #888;
    padding: 25px 7%;
    font-size: 12px;
    border-top: 1px solid #444;
}

/* MOBILE */

@media (max-width: 700px) {

    nav {
        padding: 18px 5%;
    }

    nav div:last-child {
        display: none;
    }

    .hero {
        padding: 130px 7% 70px;
    }

    .about {
        grid-template-columns: 1fr;
        gap: 35px;
    }

    .projects {
        grid-template-columns: 1fr;
    }

    section {
        padding: 80px 7%;
    }

    .section-title {
        font-size: 40px;
    }
}
</style>
</head>

<body>

<!-- NAVIGATION -->

<nav>

    <div class="logo">
        NH.
    </div>

    <div>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </div>

</nav>


<!-- HERO -->

<section class="hero">

    <div class="hero-content">

        <div class="small-title">
            Textile Engineering · Creative Design
        </div>

        <h1>
            Nada<br>
            Hussin
        </h1>

        <p>
            Textile Engineering graduate with a passion for textile
            printing, creative design and product development.
            Combining technical textile knowledge with modern
            visual design to create innovative and functional ideas.
        </p>

        <a
            class="button"
            href="https://drive.google.com/file/d/1zQh8uhki6JQjfAGkhOvf1gMZtmOE_b1t/view?usp=sharing"
            target="_blank"
        >
            VIEW FULL PORTFOLIO →
        </a>

    </div>

</section>


<!-- ABOUT -->

<section id="about">

    <div class="section-title">
        About Me
    </div>

    <div class="about">

        <p>
            I am a fresh graduate specialized in Textile Engineering,
            with an academic background in textile printing, dyeing
            and finishing.
        </p>

        <p>
            I am interested in combining textile technology,
            creative design and product development to create
            innovative textile applications.
        </p>

    </div>

</section>


<!-- PROJECTS -->

<section id="projects">

    <div class="section-title">
        Selected Projects
    </div>

    <div class="projects">

        <div class="project">

            <span>01 · Textile</span>

            <h3>
                Textile Printing
            </h3>

        </div>


        <div class="project">

            <span>02 · Home Textile</span>

            <h3>
                Rugs & Wall Hangings
            </h3>

        </div>


        <div class="project">

            <span>03 · Product Design</span>

            <h3>
                Beach Collection
            </h3>

        </div>


        <div class="project">

            <span>04 · Graduation Project</span>

            <h3>
                Egyptian Identity
            </h3>

        </div>

    </div>

</section>


<!-- SKILLS -->

<section id="skills">

    <div class="section-title">
        Skills
    </div>

    <div class="skills">

        <div class="skill">
            Textile Printing
        </div>

        <div class="skill">
            Dyeing & Finishing
        </div>

        <div class="skill">
            Textile Engineering
        </div>

        <div class="skill">
            Adobe Photoshop
        </div>

        <div class="skill">
            Adobe Illustrator
        </div>

        <div class="skill">
            Canva
        </div>

        <div class="skill">
            Product Design
        </div>

        <div class="skill">
            Creative Design
        </div>

    </div>

</section>


<!-- CONTACT -->

<section id="contact" class="contact">

    <div class="section-title">
        Let's Work Together
    </div>

    <p>
        Interested in textile engineering, textile printing,
        product development or creative collaborations?
        Feel free to get in touch.
    </p>

    <a
        class="button"
        href="mailto:YOUR-EMAIL@gmail.com"
    >
        CONTACT ME →
    </a>

</section>


<!-- FOOTER -->

<footer>

    © 2026 Nada Hussin · Textile Engineering Graduate

</footer>


</body>
</html>
