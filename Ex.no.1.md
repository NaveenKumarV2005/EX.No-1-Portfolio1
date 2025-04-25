# Ex01 Portfolio
## Date:

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
## HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
</head>
<body>
    <header>
        <div class="name">Naveen Kumar V</div>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="about" class="about">
        <div class="img-con">
                <img src="#" alt="" >
        </div>
        <div class="description">
            <h3>Hi, I am</h3>
            <h1>Naveen Kumar</h1>
            <h4>Fullstack Developer</h4>
            <div class="social-media">
                <a href="#"><i class="fab fa-github"></i></a>
               <a href="#"> <i class="fab fa-linkedin"></i></a>
            </div> 
        
            <div class="abt-btn">
                <button id ="Resume" class="r-btn">Resume</button> 

                <a href="#contact">
                    <button class="c-btn">Contact Me</button>
                </a>
            </div>
        </div>
    </section>

   
    <section id="skills" class="skills">
       
        <div class="skills-container">
            <div class="askill">
                <h2 class="h-1">Skills</h2>
            </div>
            <div class="experience">

            <div class="front">
                <h3>Front-End</h3>
                <ul>
                    <li>HTML</li>
                    <li>CSS</li>
                    <li>JavaScript</li>
                    <li>React</li>
                </ul>
            </div>
            <div class="back">
                <h3>Back-End</h3>
                <ul>
                    <li>Node.js</li>
                    <li>Express.js</li>
                    <li>MongoDB</li>
                    <li>Postgress</li>
                </ul>
            </div>
            <div class="tools">
                <h3>Tools</h3>
                <ul>
                    <li>VS Code</li>
                    <li>GitHub</li>
                    <li>Figma</li>
                    <li>ShortLin</li>
                </ul>
            </div>
        </div>

        </div>
    </section>

    <section id="projects" class="projects">
        <div class="projects-container">
            <div class="aproj">
                <h2 class="h-1">Projects</h2>
            </div>
            <div class="card-info">
            <div class="card">
                <img src="" alt="no">
                <h3>halloween</h3>
                <div class="pro-btn">
                    <a href="#">
                        <button class="g-btn">Github</button>
                    </a>
                    <a href="#">
                        <button class="d-btn">Live Demo</button>
                    </a>
                   
                </div>
            </div>
            <div class="card">
                <img src="" alt="">
                <h3>Amazon-clone</h3>
                <div class="pro-btn">
                    <a href="#">
                        <button class="g-btn">Github</button>
                    </a>
                    <a href="#">
                        <button class="d-btn">Live Demo</button>
                    </a>
                </div>
            </div>
            <div class="card">
                <img src="" alt="">
                <h3>Ai-code-reviewer</h3>
                <div class="pro-btn">
                    <a href="#">
                        <button class="g-btn">Github</button>
                    </a>
                    <a href="#">
                        <button class="d-btn">Live Demo</button>
                    </a>
                </div>
            </div>
        </div>
        </div>
    </section>
    <section class="contact" id="contact">
        <h2 class="section-title">Contact Me</h2>
        <div class="contact-container">
            <div class="contact-info">
                <h3>Let's Connect!</h3>
                <p>
                    Feel free to reach out. Whether you have a project 
                    in mind, want to discuss collaboration, or just 
                    want to say hello, I'm always open to new opportunities.
                </p>
                <div class="contact-socials">
                    <a href="#" class="socialicon">
                        <i class="fab fa-github"></i>
                    </a>
                    <a href="#" class="socialicon">
                        <i class="fab fa-linkedin-in"></i>
                    </a>
                    <a href="#" class="socialicon">
                        <i class="fab fa-twitter"></i>
                    </a>
                </div>
            </div>
            <form class="contact-form">
                <div class="form-group">
                    <label for="name">Name</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="subject">Message</label>
                    <input type="text" id="subject" name="Message" required>
                </div>

                <button type="submit" class="submit-btn">Send Message</button>
            </form>
        </div>
    </section>
    <footer>
        <div class="footer-content">
            <div class="footer-logo">
                <h2>Naveen Kumar</h2>
                <p>
                    Passionate Full Stack Developer creating innovative 
                    digital solutions with a focus on clean, efficient code 
                    and user-centered design.
                </p>
            </div>
            <div class="footer-links">
                <div class="footer-section">
                    <h4>Quick Links</h4>
                    <a href="#about">About</a>
                    <a href="#skills">Experience</a>
                    <a href="#projects">Projects</a>
                    <a href="#contact">Contact</a>
                </div>
                <div class="footer-section">
                    <h4>Resources</h4>
                    <a href="#">Resume</a>
                    <a href="#">Skills</a>
                    <a href="#">Certifications</a>
                    <a href="#">Blog</a>
                </div>
            </div>
            <div class="footer-social">
                <h4>Connect With Me</h4>
                <div class="social-icons">
                    <a href="#" class="social-icon">
                        <i class="fab fa-github"></i>
                    </a>
                    <a href="#" class="social-icon">
                        <i class="fab fa-linkedin-in"></i>
                    </a>
                    <a href="#" class="social-icon">
                        <i class="fab fa-twitter"></i>
                    </a>
                </div>
            </div>
        </div>
        <div class="footer-bottom">
           <a href=""> <p id ="thanks" class="credit">
                Designed and Developed by Naveen Kumar V
            </p>
        </a>
        </div>
    </footer>
    <script src="#"></script>

</body>
</html>
```
## CSS
```
*{
    margin: 0;
    padding:0;
    font-family: 'Courier New', Courier, monospace;
    text-decoration: none;
    list-style: none;
    scroll-behavior: smooth;

}
header{
    margin:20px auto;
    height: 40px;
    width: 650px;
    display:flex;
    align-items: center;
    justify-content: space-between;
    border-radius: 45px;
    background-color:rgb(254, 244, 232);
}

.name{
    font-size:1.2rem;
    padding: 10px;
    font-weight:bold;
    cursor: pointer;
    color:rgb(239, 155, 77);
    transition: transform 0.3s ease;
}

.name:hover{
    transform: scale(1.1); 
}

nav ul{
    display: flex;
    gap: 20px;
    text-wrap: nowrap; 
    list-style: none;
}

nav ul li {
    position: relative;
}

nav ul a{
    color:black;
    text-decoration: none;
    font-size: 1rem;
    padding: 5px 8px;
    transition: color 0.3s ease;
}

nav ul a:hover{
    color: rgb(239, 155, 77);
}

nav ul a::after {
    content: "";
    position: absolute;
    width: 0;
    height: 2px;
    bottom: -2px;
    left: 0;
    background-color: rgb(239, 155, 77);
    transition: width 0.3s ease;
}

nav ul a:hover::after {
    width: 100%;
}
.git-btn {
    padding: 5px;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 20px;
    margin: 10px;
    border-radius: 15px;
    background-color: #f0f0f0;
    color: #333;
    border: none;
    transition: all 0.3s ease;
    cursor: pointer;
}

.git-btn:hover {
    background: linear-gradient(to right, #cba911, #fc7725);
    color: white;
    box-shadow: 0 4px 15px rgba(230, 143, 14, 0.4);
    transform: translateY(-2px);
}
.about {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 100px;
    width: auto;
    position: relative;
}
.img-con {
    width: 600px;
    height: 600px;

}

.img-con img{

    object-fit: cover;
    border-radius: 10%;
}
.img-con img:hover{
   
    transform: scale(1.2px);
    box-shadow: 0 4px 15px rgba(230, 143, 14, 0.4);
}

.description{
    text-align: start;
}
.description h3{
    font-family: 'Courier New', Courier, monospace;
    font-size: 1.5rem;
    font-weight: bold;
    margin-bottom: 10px;
    color: rgb(241, 198, 119)
}
.description h1{
    font-family: 'Courier New', Courier, monospace;
    font-size: 3.5rem;
    font-weight: bold;
    margin-bottom: 10px;
    color: rgb(132, 130, 128)
}
.description h4{
    font-family: 'Courier New', Courier, monospace;
    font-size: 25px;
    font-weight: bold;
    margin-bottom: 10px;
    color: rgb(241, 198, 119)
}
.social-media i{
    margin-right: 10px;
    font-size: 2rem;
    color: rgb(241, 198, 119);
    transition: color 0.3s ease;
    cursor: pointer;
           
}
.abt-btn{
    margin-top: 20px;
    gap:40px
}
.abt-btn .r-btn{
    margin-top: 20px;
    font-size: 1rem;
    padding: 12px 20px;
    background-color: #e0dddd;
    border: none;
    border-radius: 30px;
    color: rgb(241, 198, 119);
    cursor: pointer;
    font-weight: bold;
    transition: all 0.3s ease-in-out;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}

.abt-btn .r-btn:hover{
    background-color: #f0f0f0;
    color: rgb(241, 141, 119);
    transform: scale(1.05);
    box-shadow: 3px 3px 12px rgba(0, 0, 0, 0.2);
}
.abt-btn .c-btn{
    margin-top: 20px;
    font-size: 1rem;
    padding: 12px 20px;
    background-color: #e0dddd;
    border: none;
    border-radius: 30px;
    color: rgb(241, 198, 119);
    cursor: pointer;
    font-weight: bold;
    transition: all 0.3s ease-in-out;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}

.abt-btn .c-btn:hover{
    background-color: #f0f0f0;
    color: rgb(241, 141, 119);
    transform: scale(1.05);
    box-shadow: 3px 3px 12px rgba(0, 0, 0, 0.2);
}

.skills {
    padding: 80px 20px; 
    text-align: center;
}

.skills-container {
    max-width: 900px;
    margin:  0 auto;
    display: flex;
    flex-direction: column;
    gap: 20px;
}

.askill .h-1 {
    font-size: 32px;
    font-weight: bold;
    color: #333;
    margin-bottom: 20px;
}

.experience {
    display: flex;
    justify-content: space-between;
    flex-wrap: warp;
    gap: 20px;
    scroll-behavior: smooth;
}



.front, .back, .tools {
    background-color: rgb(241, 198, 119);
    color: white;
    padding: 50px;
    border-radius: 5px;
    box-shadow: 0 4px 15px rgba(230, 143, 14, 0.4);
    border: #333 2px solid;
    transition: all 0.3s ease;
    margin: 20px 0; 
    display: block; 
    width: 100%; 
    box-sizing: border-box; 
}


.front:hover, .back:hover, .tools:hover {
    background-color: rgb(250, 213, 146);
    box-shadow: 0 6px 20px rgba(230, 143, 14, 0.6);
}


.front h3, .back h3, .tools h3 {
    font-size: 24px;
    font-weight: bold;
    color: rgb(255, 255, 255);
    margin-bottom: 20px;
    position: relative;
    padding-bottom: 10px;
    transition: color 0.3s ease;
}


.front h3:after, .back h3:after, .tools h3:after {
    content: "";
    position: absolute;
    bottom: 0;
    left: 0;
    width: 50px;
    height: 3px;
    background-color: white;
    transition: width 0.3s ease;
}


.front:hover h3, .back:hover h3, .tools:hover h3 {
    color: rgb(80, 80, 80);
}

.front:hover h3:after, .back:hover h3:after, .tools:hover h3:after {
    width: 100px;
    background-color: rgb(80, 80, 80);
}


.front ul li, .back ul li, .tools ul li {
    text-align: start;
    list-style: none;
    transition: transform 0.3s ease, color 0.3s ease;
    padding: 5px 0;
}


.front:hover ul li, .back:hover ul li, .tools:hover ul li {
    transform: translateX(10px);
    color: rgb(80, 80, 80);
}

header {
    margin: 20px auto;
    height: 40px;
    width: 650px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    border-radius: 45px;
    background-color: rgb(254, 244, 232);
}
.projects{
    padding: 80px 20px; 
    text-align: center;
}
.projects-container{
    margin:  0 auto;
    display: flex;
    flex-direction: column;
    gap: 20px;
}
.projects-container.aproj{
    font-size: 32px;
    font-weight: bold;
    color: #333;
    margin-bottom: 20px;
}
.card-info{
    display: flex;
    margin:0 auto;
    gap:10px;
    flex-wrap:wrap;

}

.card{
    margin-top: 20px;
    width: 300px;
    height: 300px;
    background: linear-gradient(135deg, rgb(248, 186, 110), rgb(179, 179, 179)); 
    border-radius: 10px;
    overflow: hidden;
    position: relative;
    box-shadow: 0 4px 15px rgba(32, 31, 31, 0.4);
}
 .card:hover{
    transform: scale(1.1);
    transition: transform 0.3s ease;
}
.card img{
     padding:10px 10px 10px 10px;
     width:250px;
     height:auto;
     background-color: rgb(208, 207, 206);
}
.card img:hover{
    transform: scale(1.1);
    transition: transform 0.3s ease;
}
.card h3{
    text-shadow: #f0f0f0;
    color:#f0f0f0;
     margin-top: 20px;
     font-size: 1.5rem;
}
.pro-btn button {
    margin-top: 20px;
    font-size: 1rem;
    padding: 12px 20px;
    background-color: #e0dddd;
    border: none;
    border-radius: 30px;
    color: rgb(241, 198, 119);
    cursor: pointer;
    font-weight: bold;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}

.pro-btn button:hover {
    background-color: #f0f0f0;
    color: rgb(241, 141, 119);
    transform: scale(1.05);
    box-shadow: 3px 3px 12px rgba(0, 0, 0, 0.2);
}
.contact{
    padding: 80px 20px; 
    text-align: center;
}
.contact-container{
    display:flex;
    max-width: 900px;
    margin:  0 auto;

}
.contact-info{
    position: relative;
    background: linear-gradient(135deg, rgb(248, 186, 110), rgb(179, 179, 179));     
    width:50%;
    text-align: left;
    margin-right: 20px;
    border: #333 2px solid;
    padding: 20px;
    height:300px
}
.section-title{
    font-size: 32px;
    font-weight: bold;
    color: #333;
    margin-bottom: 20px;
}

.contact-info h3{
    font-size: 24px;
    font-weight: bold;
    color: #333;
    margin-bottom: 20px;
}

.contact-info p{
    color: #333;
    margin-bottom: 20px;
    line-height: 1.5;
}
.contact-socials .socialicon {
    text-decoration: none;
}
.contact-socials .socialicon i{ 
    margin-right: 10px;
    font-size: 2rem;
    color: rgb(215, 214, 212);
    transition: color 0.3s ease;
    cursor: pointer;
}

.contact-socials .socialicon:hover i{
    color: rgb(255, 255, 255);
    transform: scale(1.1);
}
.contact-form{
    position: relative;
    background: linear-gradient(135deg, rgb(248, 186, 110), rgb(179, 179, 179));     
    width:50%;
    text-align: left;
    margin-left: 20px;
    border: #333 2px solid;
    padding: 20px;
    height:300px

}
.form-group{
    margin-bottom: 20px;
    position: relative;
    width: 100%;
    
}
.form-group input{
    width: 100%;
    padding: 10px;
    border: black 1px solid;;
    border-radius: 5px;
    box-sizing: border-box;
}
.submit-btn{
    margin-top: 20px;
    font-size: 1rem;
    padding: 12px 20px;
    background-color: #e0dddd;
    border: none;
    border-radius: 30px;
    color: rgb(241, 198, 119);
    cursor: pointer;
    font-weight: bold;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}
.submit-btn:hover {
    background-color: #f0f0f0;
    color: rgb(241, 141, 119);
    transform: scale(1.05);
    box-shadow: 3px 3px 12px rgba(0, 0, 0, 0.2);
}
footer {
    background: linear-gradient(to right, rgb(40, 40, 40), rgb(30, 30, 30));
    color: white;
    padding: 4rem 12%;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.footer-content {
    display: flex;
    justify-content: space-between;
    width: 100%;
    margin-bottom: 3rem;
    gap: 4rem;
}

.footer-logo {
    flex: 1;
}

.footer-logo h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
}

.footer-logo p {
    color: #aaa;
    line-height: 1.6;
}

.footer-links {
    flex: 1;
    display: flex;
    justify-content: space-between;
}

.footer-section {
    display: flex;
    flex-direction: column;
}

.footer-section h4 {
    margin-bottom: 1rem;
    font-size: 1.1rem;
    color: #ddd;
}

.footer-section a {
    color: #aaa;
    text-decoration: none;
    margin-bottom: 0.5rem;
    transition: color 0.3s ease;
}

.footer-section a:hover {
    color: rgb(246, 225, 121);
}

.footer-social {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
}

.social-icons {
    display: flex;
    gap: 1rem;
    margin-top: 1rem;
}

.social-icon {
    color: #aaa;
    font-size: 1.5rem;
    transition: color 0.3s ease, transform 0.3s ease;
}

.social-icon:hover {
    color:rgb(241, 197, 116);
    transform: scale(1.2);
}

.footer-bottom {
    width: 100%;
    border-top: 1px solid rgba(255, 255, 255, 0.1);
    padding-top: 2rem;
    text-align: center;
    color: #888;
}

.footer-bottom p {
    margin-bottom: 0.5rem;
}

.footer-bottom .copyright {
    font-size: 0.9rem;
}

.footer-bottom .credit {
    font-size: 0.8rem;
    color: #666;
}

```
## OUTPUT
![Screenshot_25-4-2025_202318_](https://github.com/user-attachments/assets/3aae7894-81b7-410c-a2da-c63a888914c5)
## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
