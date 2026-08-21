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
    background: rgba(247,245,241,.94);
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
    padding: 130px 7% 80px;
    display: flex;
    align-items: center;
}

.hero-layout {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 80px;
}

.hero-text {
    flex: 1;
    max-width: 650px;
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
    font-size: clamp(55px, 8vw, 110px);
    line-height: .92;
    font-weight: 500;
    margin-bottom: 35px;
}

.hero p {
    max-width: 600px;
    font-size: 18px;
    color: #666;
}


/* PROFILE IMAGE */

.hero-image {
    width: 400px;
    height: 520px;
    flex-shrink: 0;
    overflow: hidden;
    border-radius: 200px 200px 25px 25px;
    box-shadow: 0 25px 60px rgba(0,0,0,.13);
    background: #e8e2d8;
}

.hero-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center center;
    display: block;
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
}

.about p {
    font-size: 18px;
    color: #666;
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
    transition: .3s;
}

.skill:hover {
    background: #1d1d1b;
    color: white;
}


/* PORTFOLIO */

.portfolio {
    background: #e8e2d8;
}

.portfolio-box {
    max-width: 850px;
}

.portfolio p {
    color: #666;
    font-size: 18px;
    margin-bottom: 30px;
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


/* CONTACT */

.contact {
    background: #1d1d1b;
    color: white;
}

.contact .section-title {
    color: white;
}

.contact-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 60px;
}

.contact-intro {
    color: #bbb;
    font-size: 18px;
    max-width: 500px;
}

.contact-info {
    display: flex;
    flex-direction: column;
    gap: 22px;
}

.contact-item {
    color: #ddd;
    font-size: 15px;
}

.contact-item strong {
    color: white;
    font-weight: 500;
}

.contact-item a {
    color: #ddd;
    text-decoration: none;
}

.contact-item a:hover {
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

@media (max-width: 800px) {

    nav {
        padding: 18px 5%;
    }

    nav div:last-child {
        display: none;
    }

    .hero {
        padding: 120px 7% 70px;
    }

    .hero-layout {
        flex-direction: column-reverse;
        align-items: flex-start;
        gap: 45px;
    }

    .hero-image {
        width: 280px;
        height: 360px;
        align-self: center;
    }

    h1 {
        font-size: 65px;
    }

    .about {
        grid-template-columns: 1fr;
        gap: 35px;
    }

    .contact-content {
        grid-template-columns: 1fr;
        gap: 40px;
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
        <a href="#skills">Skills</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
    </div>

</nav>


<!-- HERO -->

<section class="hero">

    <div class="hero-layout">


        <div class="hero-text">

            <div class="small-title">
                Textile Engineering · Creative Design
            </div>

            <h1>
                Nada<br>
                Hussin
            </h1>

            <p>
                Textile Engineering graduate with a passion for
                textile printing, creative design and product
                development. Combining technical textile knowledge
                with modern visual design to create innovative
                and functional ideas.
            </p>

        </div>


        <div class="hero-image">

            <img
                src="profile.png"
                alt="Nada Hussin"
            >

        </div>


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


<!-- PORTFOLIO -->

<section id="portfolio" class="portfolio">

    <div class="portfolio-box">

        <div class="section-title">
            Portfolio
        </div>

        <p>
            Explore my complete portfolio, including my academic work,
            textile projects, creative work and graduation project.
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


<!-- CONTACT -->

<section id="contact" class="contact">

    <div class="section-title">
        Contact Me
    </div>

    <div class="contact-content">


        <div class="contact-intro">

            I am open to new opportunities, collaborations,
            internships and creative projects in the textile field.

        </div>


        <div class="contact-info">


            <div class="contact-item">

                <strong>Email</strong><br>

                <a href="mailto:nhussin442@gmail.com">
                    nhussin442@gmail.com
                </a>

            </div>


            <div class="contact-item">

                <strong>Phone</strong><br>

                <a href="tel:01095578083">
                    01095578083
                </a>

            </div>


            <div class="contact-item">

                <strong>LinkedIn</strong><br>

                <a
                    href="https://www.linkedin.com/in/nada-hussin-7693862a0"
                    target="_blank"
                >
                    linkedin.com/in/nada-hussin-7693862a0
                </a>

            </div>


            <div class="contact-item">

                <strong>Location</strong><br>

                Gesr El Suez, El Haykstep, Cairo, Egypt

            </div>


        </div>

    </div>

</section>


<!-- FOOTER -->

<footer>

    © 2026 Nada Hussin · Textile Engineering 

</footer>


</body>
</html>
