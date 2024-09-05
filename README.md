<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio Website</title>


  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" />


  <link rel="stylesheet" href="styles.css" />
</head>
<style>
  /* Google Fonts(Poppins) */
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap");

* {
  font-family: "Poppins", sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.hero {
  position: absolute;
  height: 100vh;
  width: 100%;
  background: #6d8654;
}

nav {
  width: 100%;
  height:100px;
  margin: 2px;
  padding: 20px 50px 20px 50px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  text-transform: uppercase;
  background-color: #0093E9;
background-image: linear-gradient(160deg, #0093E9 0%, #80D0C7 100%);

  position:fixed;
  top:0px;
  margin:2px;
}

nav .logo {
  width: 120px;
  cursor: pointer;
}

nav ul li {
  display: inline-flex;
  list-style: none;
  margin: 10px 15px;
}

nav ul li a {
  text-decoration: none;
  font-size: 18px;
  color: beige;
  font-weight: 500;
  transition: all 0.3s ease;
}

nav ul li a:hover {
  color: black;
}

.btn {
  text-decoration: none;
  background: #be9a81;
  color: #fff;
  padding: 10px 18px;
  font-weight: 500;
  border-radius: 5px;
  transition: all 0.3s ease;
}

.btn:hover {
  transform: scale(0.9);
  background-color: black;
}

.info {
  width:100%;
  background-color: #8BC6EC;
  background-image: linear-gradient(135deg, #8BC6EC 0%, #9599E2 100%);
  padding: 200px 100px 100px 100px;
   
  
}

.info h1 p {
  font-size: 70px;
  color: #d9dcdd;
  flex: auto;

}

.info h1 span {
  color: #be9a81;
}

.info p h4 {
  color: #a1a1a1;
  line-height: 22px;
}

.info .btn {
  display: inline-block;
  margin: 30px 0;
}


.images {
  width: 45%;
  height: 65%;
  position: absolute;
  bottom: 100px;
  right: 100px;
  flex: auto;
  margin-right: 40px;
  margin-bottom: 30px;

}

.images img {
  height: 100%;
  position: absolute;
  left: 70%;
  bottom: 0;
  transform: translateX(-50%);
  transition: all 1s;
}

.images:hover .bg {
  bottom: 40px;
}

.images:hover .girl {
  left: 54%;
}



/* Experience Section */
.experience {
  background: #d9dcdd;
  color: #F5F5DC;

  padding: 50px;
  text-align: center;
}

.experience h2 {
  font-size: 28px;
  color: #6d8654;
}

.experience-item {
  margin: 20px 0;
}

.experience-item h3 {
  font-size: 20px;
  color: #6d8654;
}

.experience-item p {
  font-size: 16px;
  color: #a1a1a1;
}

/* Project Section */

.project-card {
  height: 100;
  width: 500px;
  inline-size: none;

  background-color: #f8f3f3;
  border: 1px solid #444;
  border-radius: 5px;
  padding: 20px;
  margin: 20px;
  transition: transform 0.3s, box-shadow 0.3s;
}

.project-card:hover {
  transform: scale(1.05);
  box-shadow: 0 0 10px green;
}

.projects {

  background: #be9a81;
  padding: 50px;
  text-align: center;
  display: flex;
  justify-content: space-between;
}

.projects h2 {
  font-size: 28px;
  color: #fff;
}

.project-item {
  margin: 20px 0;
}

.project-item h3 {
  font-size: 20px;
  color: #fff;
}

.project-item p {
  font-size: 16px;
  color: #d9dcdd;
}

/* Skills Section */
.skills {
  background: #6d8654;
  padding: 40px 0;
  padding: 50px;
  justify-content: space-between;
}

.skills h2 {
  font-size: 28px;
  color: #fff;
}

.skills ul {
  list-style: none;
  display: flex;
  justify-content: space-around;
  text-align: center;
}

.skills li {
  font-size: 20px;
  color: #6d8654;
  margin: 10px 0;
  border: 1px solid #444;
  border-radius: 50px;
  padding: 20px;
  margin: 20px;
  transition: transform 0.3s, box-shadow 0.3s;
  background-color: #f8f3f3;
}

/* Contact */
.icons {
  margin-left: 50px;

}

.icons a {
  font-size: 50px;
  margin-right: 20px;
  color: #b0b656;
  transition: all 0.3s ease;
}

.icons div {
  margin-left: 8%;
}

.icons a:hover {
  color: black;
}

.icons h2 {
  font-size: 28px;
  color: #be9a81;


}
#name {
  font-size: 70px;
  font-weight: 600;
  font-family: 'Roboto', sans-serif;
  color: #b393d3;
  text-transform: uppercase;
}



.button-92 {
  background-image: linear-gradient(#0dccea, #0d70ea);
  border: 0;
  border-radius: 4px;
  box-shadow: rgba(0, 0, 0, .3) 0 5px 15px;
  box-sizing: border-box;
  color: #fff;
  cursor: pointer;
  font-family: Montserrat,sans-serif;
  font-size: .9em;
  margin: 5px;
  padding: 10px 15px;
  text-align: center;
  position:absolute;
  left:80%;

}
#myimage{
  position:absolute;
  top:120px;
  left:88%;
  width:170px;
  height:260px;

}
</style>

<body>
  
    <nav>
      <h1 id="name1"> G. Kondaswamy</h1>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#projects">Project</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#icons">Contact</a></li>
      </ul>
    
    </nav>
  
    <div class="info">
      <h1>I'm a CSE Student </h1><br>
      <p>
        &nbsp &nbsp &nbsp &nbsp  &nbsp &nbsp I am currently in my third year pursuing a B.Tech degree in Computer
        Engineering Technology <br> has always been a passion of mine and I find great joy in learning about its various
        aspects. <br>I have a good foundation in programming languages such as C, Java, HTML and CSS. <br>
        Additionally, I have some good knowledge of cloud computing with GCP. 💻🌐 <br>
        <button class="button-92">Download CV</button><img id="myimage" src="https://portal.nbkrsac.in/stupic/26722.jpeg">
      </p>
      
    </div>

    <section class="experience" id="experience">
      <h2>Experience</h2>
      <div class="experience-item">
        <h3>Java Developer Intern</h3>
        <p>LetsGrowMore- Sept 2023 (4 weeks)</p>
        <p>Worked on back-end and app development projects using Java</p>
        <p> Projects I worked on-
          <br>1. Currency Converter 2. Text Editor
        </p>
      </div>
      <div class="experience-item">
        <h3>Lead </h3>
        <p>BroCode Coding Club (Present Lead)</p>
        <p> Working on helping our group of programmers learn and work together.<br> Creating a close community of tech
          fans.</p>
      </div>

    </section>

    <section class="projects" id="projects">
      <h2>Projects</h2>
      <div class="project-card">
        <h3>Tic Tac Toe Game</h3>
        <p>developed using Java <br> and can be played between two people</p><br>
        <a href="#" class="btn"><i class='bx bxl-github'></i> View on GitHub</a>
      </div>
      <div class="project-card">
        <h3>Search Engine</h3>
        <p>developed using Java <br>helps find and organize information from the internet</p><br>
        <a href="#" class="btn"><i class='bx bxl-github'></i> View on GitHub</a>
      </div>
    </section>


    <section class="skills" id="skills">
      <h2>Skills</h2>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>Java</li>
        <li>Cloud Computing (GCP)</li>
      </ul>
    </section>

    <div class="icons" id="icons">
      <h2>Contact</h2>
      <div>
        <a href="#"><i class="fab fa-linkedin-in"></i></a>
        <a href="#"><i class="fab fa-twitter"></i></a>
        <a href="#"><i class="fab fa-whatsapp"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
      </div>
    </div>

    
  </div>




</body>

</html>
