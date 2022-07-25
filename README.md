# firstone
first one project test

<!DOCTYPE html>
<html lang="en">
    <head>
        <link rel="stylesheet" href="rule7.css">
        <link rel="stylesheet" href="all.min.css">
        <link rel="stylesheet" href="path/to/font-awesome/css/font-awesome.min.css"/>
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css" 
        integrity="sha384-oS3vJWv+0UjzBfQzYUhtDYW+Pj2yciDJxpsK1OYPAYjqT085Qq/1cq5FLXAZQ7Ay" crossorigin="anonymous" />
        <meta charset="UTF-8">
        <meta name="description" content="MY poftfolio in freecodecamp"/>
        <meta name="keywords" content="My own portfolio">
        <meta name="author" content="Younes">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
        <nav id="navbar" class="nav">
            <ul class="nav-list">
                <li>
                    <a id="profile-link" href="#welcome-section" target="_blank">about</a>
                </li>
                <li>
                    <a href="#project">Work</a>
                </li>
                <li>
                    <a href="#contact">Contact</a>
                </li>
            </ul>
        </nav>
        <section id="welcome-section" class="welcome-section">
            <h1>Hey I am Younes</h1>
            <p>a web developer im trying to finish my responsive web design certificate it's really <strong>HARD</strong> to be here </p>
        </section>
        <section id="projects" class="project-section">
            <h2 class="project-section-header">these are some of my projects</h2>
            <div class="project-grid">
                <a href="https://codepen.io/freeCodeCamp/full/zNqgVx" target="_blank" class="project project-tile">
                    <img class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/tribute.jpg" alt="project">
                    <p class="project-title">
                      <span class="code">&lt;</span>
                      Tribute Page
                      <span class="code">&gt;</span>
                    </p>
                  </a>
                  <a href="https://codepen.io/freeCodeCamp/full/qRZeGZ" target="_blank" class="project project-tile">
                    <img class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/random-quote-machine.png" alt="project">
                    <p class="project-title">
                      <span class="code">&lt;</span>
                      Random Quote Machine
                      <span class="code">&gt;</span>
                    </p>
                  </a>
                  <a href="https://codepen.io/freeCodeCamp/full/mVEJag" target="_blank" class="project project-tile">
                    <img class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/map.jpg" alt="project">
                    <p class="project-title">
                      <span class="code">&lt;</span>
                      Map Data Across the Globe
                      <span class="code">&gt;</span>
                    </p>
                  </a>
                  <a href="https://codepen.io/freeCodeCamp/full/wGqEga" target="_blank" class="project project-tile">
                    <img class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/wiki.png" alt="project">
                    <p class="project-title">
                      <span class="code">&lt;</span>
                      Wikipedia Viewer
                      <span class="code">&gt;</span>
                    </p>
                  </a>
                  <a href="https://codepen.io/freeCodeCamp/full/KzXQgy" target="_blank" class="project project-tile">
                    <img class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/tic-tac-toe.png" alt="project">
                    <p class="project-title">
                      <span class="code">&lt;</span>
                      Tic Tac Toe Game
                      <span class="code">&gt;</span>
                    </p>
                  </a>
            </div>
            <a href="https://codepen.io/FreeCodeCamp/" class="btn btn-show-all" target="_blank">Show all<i class="fas fa-chevron-right"></i></a>
 
        </section>
        <section id="contact" class="contact-section">
            <div class="contact-section-header">
                <h2>Let's work together...</h2>
                <p>How do you take your coffe?</p>
            </div>
            <div class="contact-links">
                <a href="https://www.facebook.com/profile.php?id=100072148533083" target="_blank" class="tbn contact-details">
                  
                  <i class="fa-brands fa-facebook"></i>
                </i>" facebook"
                </a>
                <a href="https://github.com/younespro1337" class="btn contact-details" >
                  <i class="fa-brands fa-github-square"></i>
                  " github"
                </a>
                <a href="https://twitter.com/younesraymond1" target="_blank" class="btn contact-details" >
                  <i class="fa-brands fa-twitter"></i>
                  " twitter"
                </a>
                <a href="https://mail.google.com/mail/u/0/#" class="btn contact-details">
                  <i class="fa-solid fa-inbox"></i>
                  "@ Send me mail"
                </a>
                <a href="tel:+212682018371" class="btn contact-details">
                  <i class="fa-solid fa-mobile-button"></i>
                  "Call me"
                </a>
            </div>
        </section>

        <footer>
          <p>** this is my profile-link in freecodecamp it's not my profil 100% 

          </p>
          <p> i want to thank freeCodeCamp platform for everything <a href="https://www.freecodecamp.org/" target="_blank" class="freecodecamp">FreeCodeCamp</a> is the best platform for learn coding </p>
        </footer>
    
        
    </body>
</html>

   file .css
   :root{
    --main-white: #f0f0f0;
    --main-red: #be3144;
    --main-blue: #45567d;
    --main-gray: #303041;

}


*{
    margin: 0px;
    padding: 0;
}

body{
    width: 100%;
    font-family: 'Poppins', sans-serif;
    font-size: 1.8rem;
    font-weight: 400;
    line-height: var(--main-white);

}
ul{
    display: flex;
    justify-content: space-around;
    padding: 20px;
    list-style-type: auto;
    margin: 0;
    padding: 0;
    width: 100%;
    height: 50px;
}

a:hover{
    color:skyblue;
    margin-right: 10px;
    border-radius: 10%;
    font-weight: bold;
    box-shadow: #3a3d40;

    
}


.nav{
   background-color:red;
   top: 0;
   justify-content: center; 
   border-radius: 12px;
}
.nav-list{
    color: red;
    padding: 20px;

}
.fix{
    color: black;
    background-color: whitesmoke;
    margin: 0;
    padding: 0;
}

.fix:hover{
    color: var(--main-blue);
    background-color: whitesmoke;
    border-radius:2px red 70%;
    margin-right: 1px;
    padding: auto;
}


.welcome-section{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100vh;
    background-color: black;
    background-image: linear-gradient(62deg, #3a3d40 0%, #181719 100%);

}
h1{
    color: azure;
    justify-content: space-between;

    display: block;
    font-size: 6rem;
}
h1, h2{
    font-family: 'Raleway', sans-serif;
    font-weight: 700;
    text-align: center;

}
/* *, *::before, *::after{
    box-sizing: inherit;

} */

.projects-section{
    text-align: center;
    padding: 10rem 2rem;
    background: black;

}
.projects-section-header{
    max-width: 640px;
    margin: 0 auto 6rem auto;
    border-bottom: 0.2rem solid var( --main-white);
}

h2{
    font-size: 4.2rem;

}

.projects-grid{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    grid-gap: 4rem;
    width: 100%;
    max-width: 1280px;
    margin: 0 auto;
    margin-bottom: 6rem;
}

.projects{
    background: var(--main-gray);
    box-shadow: 1px 1px 2px rgba(0 0 0 / 50%);
    border-radius: 2px;
}

a{
    text-decoration: none;
    color: black;
    display: inline;
    justify-content: space-between;

}
.project-image{
    height: calc(100 - 6.8rem);
    width: 100%;
    object-fit: cover;

}

img{
    display: flex;
    width: 100%;
    border-radius: 30px;
}

.code{
    color: black;
    transition: color 0.3s ease-out;

}

p.project-title{
    height: 100%;
    width: 100%;
    background-color: #f9f5f5;
    font-size: 2rem;
    padding: 2rem 0.5rem;
    color: var(--main-gray);
    border-radius: 40px;

}
.fab{
    font-family: "Font Awesome 5 Brands";
}

/* #header{
    padding-top: 20px;
    position: sticky;
    top: 0;
    justify-content:space-between;
} */
.contact-details{
    font-size: 2.4rem;
    text-shadow: 2px 2px 1px #1f1f1f;
    transition: transform 0.3s ease-out;
}
@media (max-width:768px) {
    p{
        width: 80%;
    }
    
}

p{
    padding-top: 15px;
    font-family: sans-serif;
    font-weight: 400;
    color: whitesmoke;
    width: 80%;
    justify-content: space-between;
    text-align: center;
}

strong:hover{
    color: black;
    background-color: whitesmoke;
    margin: 1px;
    border-radius: 50%;
}
@media (max-width: 768px){
    nav{
        flex-direction: column;
    }
}

footer p{
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Verdana, sans-serif;
    height: 100%;
    width: 100%;
    margin-top: 30px;
    color: #181719;
    background-color: rgb(230, 223, 237);
    border-radius: 30px;
}


   
