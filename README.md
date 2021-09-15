# 7P777.github.io


<!DOCTYPE html>
<html>
    <head>
        <title>KUNGFUPANDA VAPE</title>
        <link rel="stylesheet" href="style.css">
    </head>

    <body>
        <header>
            <img src="logo.jpg" class="profile-img">
            <nav>
                <ul>
                    <li><a href="#hero">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <section id="hero">
                <div class="section-inner">
                    <img src="logo.jpg" class="profile-img">
                    <h1>WELCOME</h1>
                </div>
            </section>
            <section id="about">
                <div class="section-inner">
                    <h2>EXHALE the PAST and INHALE the FUTURE</h2>
                   
                </div>
            </section>
            <section id="contact">
                <div class="section-inner">
                    <h3>Contact Us</h3>
                    <p>You Can Reach us Through:</p>
                    <ul>
                        <li><a href="https://twitter.com/Kungfuvape">Twitter</a></li>
                        <li><a href="https://www.Kungfuvape.com/Kungfuvape">Facebook</a></li>
                        <li><a href="https://www.instagram.com/kungfuvape/">Instagram</a></li>
                    </ul>
                    <p>Or, you can <a href="mailto:supportkungfuvape.ph">Send us Email</a>.</p>
                </div>
            </section>
        </main>
        <footer>
            © Copyright Kungfu Vape, 2021
        </footer>
    </body>
</html>






body {
    margin: 0;
    margin-top: 50px;
    font-family: sans-serif;
}

header {
    display: flex;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    height: 50px;
    line-height: 50px;
    background-color: #eee;
}

header * {
    display: inline;
    height: 50px;
}

header ul {
    padding: 0;
}

header li {
    margin-left: 20px;
}

section {
    height: 100vh;
    border: 1px solid black;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    
    background-size: cover; 
    background-position: center center; 
    background-repeat: no-repeat; 
    background-attachment: fixed; 
}

#hero .profile-img {
    width: 300px;
    border-radius: 50%;
}

footer {
    text-align: center;
    padding: 50px;
}

#hero h1 {
    font-size: 4.5em;
    color: #bfbfbf;
}

section h2 {
    font-size: 2em;
    color: #ccddff;
}

section h3 {
    font-size: 5em;
    color: #ffffff;
}

header a {
    text-decoration: none;
    color:#664b00;
}

/* Add everything below here */

#hero {
    background-image: url('vape.jpg');
}

#about {
    background-image: url('fmale.jpg');
}

#contact {
    background-image: linear-gradient(rgba(90,90,90,0.75),rgba(90,90,90,0.75)), url('smoky.jpg');
}


