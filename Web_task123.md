**Name: GIRI HARSHA VARDHAN TENALI Section: CSM 06 Roll No: 26001250** 

# **Task 1** 

## **Aim:** 

To design and develop a responsive, single-page restaurant website featuring navigation, menu sections, chef profiles, customer testimonials, location details, and a table reservation form using HTML and CSS. 

## **Question:** 

Create a restaurant website with menu sections, chef profiles, restaurant ambience, customer testimonials, opening hours, location details, and table reservation forms. Use a responsive menu and elegant typography. 

## **Source Code:** 

<!DOCTYPE html> <html> <head> <title>VARNIT CAFE</title> <meta charset="UTF-8"> <meta name="viewport" content="width=device-width, initial-scale=1.0"> <style> a{ color: aliceblue; margin: 15px; text-decoration: none; font-size: 18px; letter-spacing: 2px; text-transform: uppercase; 

} nav{ text-align: center; } a:hover{ color: goldenrod; text-transform: uppercase; text-shadow: 0px 0px 2px gold; } body{ background-color: rgb(0, 0, 0); color: aliceblue; text-transform: uppercase; font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sansserif; } header{ background-image: url(cafe.png); padding: 30px; text-transform: uppercase; background-size: cover; background-repeat: no-repeat; } .p1{ background-color: rgba(20, 19, 19, 0.221); 

border-radius: 5px; text-align: center; text-transform: uppercase; font-size: 20px; letter-spacing: 20px; color: goldenrod; text-shadow: 0px 0px 3px  black; } .p2{ font-size: 250px; color: darkgoldenrod; text-transform: uppercase; letter-spacing: 30px; } .p3{ font-size: 10px; letter-spacing: 8px; text-transform: uppercase; } .p4{ color: darkorange; text-transform: uppercase; } .p5{ color: goldenrod; text-transform: uppercase; 

} .p6{ color: gold; font-size: 20px; letter-spacing: 1px; text-transform: uppercase; 

margin-top: 40px; } .p7{ border-radius: 5px; text-transform: uppercase; color: goldenrod; padding: 20px 50px 20px 50px ; background-color: rgba(0, 0, 0, 0.237); background-color: rgba(72, 61, 1, 0.363); } .b1{ background-color:rgba(0, 0, 0, 0.018); color: aliceblue; text-transform: uppercase; border: 0px; text-align: left; margin-left: 200px; } 

.b2{ background-color: rgb(36, 36, 36); border: 0px; text-transform: uppercase; padding: 40px 40px; margin-left: 30px; border-radius: 10px; } .b3{ background-color:rgba(28, 28, 28, 0.356); color: aliceblue; text-transform: uppercase; border: 0px; padding: 100px; margin-top: 50px; text-align: center; margin-left: 150px; } input{ color: grey; background-color: rgba(0, 0, 0, 0.484); padding: 10px 30px; text-transform: uppercase; 

} .b4{ background-color: rgba(218, 165, 32, 0.53); color: aliceblue; font-size: 20px; margin-top: 10px; text-transform: uppercase; padding: 5px 30px; } .b5{ background-color:rgba(28, 28, 28, 0.356); color: aliceblue; border: 0px; text-transform: uppercase; padding-left: 150px; padding-right: 150px; padding-top: 100px; padding-bottom: 100px; margin-top: 50px; text-align: center; margin-left: 150px; } 

footer{ margin: 100px; text-align: center; text-transform: uppercase; } textarea{ background-color: rgba(55, 54, 54, 0.422); color: grey; text-transform: uppercase; padding: 50px; } .m1{ border-radius: 80px; } </style> </head> <body> <header> <nav> <a style="padding-right: 700px;" href="#q1"><span class="p5">VAR</span><span class="p4">NIT</span></a> <a href="#q2">ABOUT</a> <a href="#q3">MENU</a> <a href="#q4">CHEFS</a> <a href="#q5">REVIEWS</a> <a href="#q6">BOOK A TABLE</a> </nav> 

< _center_ > 

<h1 id="q1" class="p2"> 

<p class="p1">VIJYAWADA'S GREAT CAFE</p>VAR<span class="p4">NIT</span> <p class="p3">SINCE-2020</p> 

<p class="p6">Welcome to varnit Cafe in VIJYAWADA. Enjoy simple, tasty food in a dark and relaxing cafe.</p> 

<a href="#q6"><button class="p7">BOOK A TABLE</button ></a></h1> 

</ _center_ > 

</header> 

<main> 

<article> 

<div id="q2" style="text-align: center;"> 

<h1 style="color: goldenrod;">Our Cafe</h1> 

<p>A quiet place for you</p> 

<p>We are located in MG ROAD, VIJYAWADA. Our cafe is designed to be quiet and dark.</p> 

<p>It is a good place to meet friends, read a book, or eat a nice meal. We play soft music and make you feel at home.</p> 

<img src="cafe.png" alt="VARNIT CAFE" width="200"> 

</div> 

</article> 

<hr> 

<article id="q3" class="b"> 

<div style="text-align: center;"> 

- <h1 style="color: goldenrod;">Our Menu</h1> 

<p>Simple food made well</p> 

<button class="b1"> 

<h2 style="color: goldenrod;">Hot Drinks</h2> 

<p>Hot Coffee<br>Fresh and dark coffee <span style="padding-left: 50px; color: goldenrod;">₹150</span></p> 

<p>Milk Tea<br>Sweet and warm tea <span style="padding-left: 70px; 

color: goldenrod;">₹120</span></p> 

</button> 

<button class="b1"> 

<h2 style="color: goldenrod;">Snacks</h2> 

<p>Cheese Sandwich<br>Bread with melted cheese <span style="padding-left: 50px; color: goldenrod;">₹200</span></p> 

<p>Chocolate Cake<br>Soft and sweet<span style="padding-left: 135px; 

color: goldenrod;">₹300</span></p> 

</button> 

<button class="b1"> 

<h2 style="color: goldenrod;">Main Food</h2> 

<p>Chicken Rice<br>Hot rice with cooked chicken <span style="padding-left: 50px; color: goldenrod;">₹450</span></p> 

<p>Veggie Pasta<br>Pasta with red sauce <span style="padding-left: 115px; 

color: goldenrod;">₹350</span></p> 

</button> <hr> <h1 id="q4" style="color: goldenrod;">Our Team</h1> <p style="color: aliceblue;">The people who cook for you</p> <article> <button class="b2"> <img src="MALECHEF.png" alt="cafe" width="50" class="m1"> <h2 class="p5">CHEF MR.V******N</h2> <p style="color: aliceblue;">Head Cook. He loves making hot and fresh food.</p> </button> <button class="b2"> <img src="femalechef.png" alt="cafe" width="50" class="m1"> <h2 class="p5">CHEF MS.S*****A</h2> <p style="color: aliceblue;">Head Cook. SHE loves making hot and fresh food.</p> </button> </article> <hr> <h1 id="q5" style="color: goldenrod;">What People Say</h1> <button class="b3" style="text-align: center;"> <p>"Quiet and beautiful. A very good place in VIJYAWADA."</p> <p style="color: goldenrod;">-HEMANTH</p> </button> <button class="b3" style="text-align: center;"> 

<p>"The cake is the best I have ever had. I will come back."</p> <p style="color: goldenrod;">-ABHIRAM</p> </button> <button class="b3" style="text-align: center;"> <p>"I really like this place. The coffee is very good and the room is nice."</p> <p style="color: goldenrod;">-TGHV</p> </button> </div> </article> <hr> <article id="q6"> <button class="b3"> <h1 class="p5">Find Us</h1> <h3 class="p6">Address:</h3> <p>Road No. 45 , MG ROAD , VIJYAWADA , ANDHRA PRADESH , India</p> <h3 class="p6">Time:</h3> <p>Monday to Friday: 10:00 AM - 10:00 PM</p><br> <p>Saturday & Sunday: 9:00 AM - 11:00 PM</p> <h3 class="p6">Call Us</h3> 

<p>Phone: 040-1234-5678</p> </button> 

<button id="q7"  class="b5"> <form id="p1"> <h1 class="p5">BOOK A TABLE</h1> <label for="name">YOUR NAME</label><br><br> <input class="" id="name" type="text" placeholder="ENTER YOUR NAME" required><br><br> 

<label for="ph">MOBILE NUMBER</label><br><br> 

<input id="ph" type="phone" placeholder="ENTER YOUR PH NUMBER" required><br><br> 

<label for="day">DATE</label><br><br> <input id="day" type="date"  required><br><br> <label for="people">HOW MANY PEOPLE</label><br><br> <input id="people" type="number" placeholder="NO OF PEOPLE?" required><br><br> <input for="btn" type="submit" class="b4"> </form> </button> </article> </main> <footer> <form> <label class="p6" for="qqq">FOR ANY QUARIES</label><br><br> <textarea for="#k1" id="qqq"></textarea><br><br> 

<input class="b4" id="k1" type="submit"> 

</form> 

</footer> 

</body> 

</html> 

OUTPUT: 



<!-- Start of picture text -->
N iT<br>on — ae<br><!-- End of picture text -->

## **Conclusion:** 

The restaurant website was successfully developed using standard web technologies. By combining semantic HTML structuring and custom CSS properties, an elegant and functional single-page layout was achieved. The final design successfully meets the requirements by integrating a responsive navigation menu, structured information sections, and stylized user input forms. 

# **Task 2** 

## **Aim:** 

To create a responsive personal portfolio website displaying educational qualifications, technical skills, hobbies, projects, and contact information, utilizing CSS for styling and layout management. 

## **Question:** 

Create a personal website displaying a profile, educational qualifications, technical skills, hobbies, projects, achievements, resume, and contact information. Use CSS animations, responsive layouts, and interactive navigation effects. 

## **Source Code:** 

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Giri Harshavardhan - Portfolio</title>
  <style>
    body {
      background-color: #f4f4f9;
      color: #333333;
      font-family: Arial, sans-serif;
      margin: 0;
      text-transform: uppercase;
      padding: 0;
    }
    nav {
      background-color: #ffffff;
      text-align: center;
      padding: 15px;
      border-bottom: 2px solid #dddddd;
    }
    nav a {
      text-decoration: none;
      color: #333333;
      margin: 0 15px;
      font-size: 18px;
    }
    nav a:hover {
      color: #0056b3;
      text-decoration: underline;
    }
    section {
      max-width: 800px;
      margin: 40px auto;
```

```
      padding: 20px;
      background-color: #ffffff;
      border: 1px solid #cccccc;
      border-radius: 5px;
    }
    h1 {
      color: #0056b3;
      text-align: center;
      font-size: 32px;
    }
    h2 {
      color: #222222;
      border-bottom: 2px solid #0056b3;
      padding-bottom: 5px;
    }
    h3 {
      color: #444444;
    }
    p {
      line-height: 1.6;
      font-size: 16px;
    }
    .card {
      background-color: #f9f9f9;
      padding: 15px;
      margin-top: 15px;
      border: 1px solid #eeeeee;
    }
    .card:hover {
      background-color: #f1f1f1;
    }
    ul {
      padding-left: 20px;
    }
    li {
      margin-bottom: 8px;
    }
    .btn {
      display: inline-block;
      padding: 10px 20px;
      background-color: #0056b3;
      color: #ffffff;
      text-decoration: none;
      margin-top: 20px;
    }
```

```
    .btn:hover {
      background-color: #003d82;
    }
    .center-text {
      text-align: center;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #222222;
      color: #ffffff;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <nav>
    <a href="#about">About</a>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
  <section id="about">
    <h1>Giri Harshavardhan</h1>
    <p class="center-text">B.Tech CSE (AI & ML) Student | Web Developer</p>
    <p class="center-text">VIJAYAWADA, India</p>
  </section>
  <section id="education">
    <h2>Education</h2>
    <div class="card">
      <h3>DR RVR NRI UNIVERSITY</h3>
      <p>B.Tech in Computer Science and Engineering (AI & ML)</p>
    </div>
    <div class="card">
      <h3>NARAYANA JUNIOR COLLEGE</h3>
      <p>Completed with 875/1000 marks</p>
    </div>
  </section>
  <section id="skills">
    <h2>Technical Skills & Hobbies</h2>
    <div class="card">
      <h3>Technical Skills</h3>
      <ul>
        <li>HTML, CSS, Vanilla JavaScript</li>
        <li>Python & C/C++ Programming</li>
        <li>Generative AI & Prompt Engineering</li>
      </ul>
    </div>
```

```
    <div class="card">
      <h3>Hobbies & Interests</h3>
      <ul>
        <li>Frontend Web Development</li>
        <li>Anime Character Sketching</li>
        <li>Telugu Cinema & Music</li>
      </ul>
    </div>
  </section>
  <section id="projects">
    <h2>Projects & Achievements</h2>
    <div class="card">
      <h3>Web Projects</h3>
      <p>Built responsive frontend interfaces for single-page websites and
application forms using basic HTML & CSS.</p>
    </div>
    <div class="card">
      <h3>Competitive Coding</h3>
      <p>Active participant in Python programming challenges and problem-
solving sprints.</p>
    </div>
  </section>
  <section id="contact">
    <h2>Contact & Resume</h2>
    <div class="card center-text">
      <p>MOBILE:9876543210</p>
      <p>GMAIL-giritenali123@gmail.com</p>
    </div>
  </section>
  <footer>
    <p> 2026 Giri Harshavardhan. Built with Basic HTML & CSS.</p>
  </footer>
</body>
</html>
OUTPUT:
```



<!-- Start of picture text -->
ABOUT EDUCATION SKILLS. PROJECTS CONTACT<br>B.TECH CSE (Al & ML) STUDENT | WEB DEVELOPER<br>\VIUAYAWADA, INDIA<br>EDUCATION<br>DR RVR NRI UNIVERSITY<br>B.TECH IN COMPUTER SCIENCE AND ENGINEERING (Al & ML)<br>NARAYANA JUNIOR COLLEGE<br>(COMPLETED WITH 875/1000 MARKS<br>TECHNICAL SKILLS & HOBBIES<br>TECHNICAL SKILLS<br>+ HTML, CSS, VANILLA JAVASCRIPT<br>+ PYTHON & CIC++ PROGRAMMING<br>+ GENERATIVE Al & PROMPT ENGINEERING<br>HOBBIES & INTERESTS.<br>+ FRONTEND WEB DEVELOPMENT<br>+ ANIME CHARACTER SKETCHING<br>+ TELUGU CINEMA & MUSIC<br>PROJECTS & ACHIEVEMENTS:<br>WEB PROJECTS.<br>BUILT RESPONSIVE FRONTEND INTERFACES FOR SINGLE-PAGE WEBSITES AND APPLICATION<br>FORMS USING BASIC HTML<br>& CSS.<br>COMPETITIVE CODING<br>ACTIVE PARTICIPANT IN PYTHON PROGRAMMING CHALLENGES<br>SPRINTS, AND PROBLEM-SOLVING.<br>CONTACT & RESUME<br>MOBILE:9876543210<br>GMAIL-GIRITENALI123@GMAIL.COM<br><!-- End of picture text -->

## **Conclusion:** 

The personal portfolio website was successfully developed using HTML and CSS. By utilizing semantic structuring and CSS-based design principles, a responsive, visually appealing layout was achieved. The website effectively highlights professional details, educational background, and technical proficiencies, providing a comprehensive online presence. 

# **Task 3** 

## **Aim:** 

To design and develop a responsive college website interface using HTML and CSS, featuring institutional details, department courses, admissions procedures, and campus facilities with interactive navigation and informational cards. 

## **Question:** 

Design a college website displaying institutional information, departments, courses, faculty profiles, admissions procedures, campus facilities, events, and contact details. Create a navigation bar, banner, and responsive information cards. 

## **Source Code:** 

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dr. RVR NRI University</title>
  <style>
    body {
      background-color: #f4f4f9;
      color: #333333;
      font-family: Arial, sans-serif;
      margin: 0;
      text-transform: uppercase;
      padding: 0;
    }
    header {
      background-color: #004080;
      color: #ffffff;
      padding: 25px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 30px;
    }
    nav {
      background-color: #00264d;
      text-align: center;
      padding: 15px;
    }
    nav a {
      text-decoration: none;
      color: #ffffff;
      margin: 0 15px;
```

```
      font-size: 16px;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .banner {
      background-color: #e6f0ff;
      text-align: center;
      padding: 60px 20px;
      border-bottom: 1px solid #cccccc;
    }
    .banner h2 {
      color: #004080;
      margin-top: 0;
    }
    section {
      max-width: 1000px;
      margin: 30px auto;
      padding: 20px;
      background-color: #ffffff;
      border: 1px solid #dddddd;
    }
    h2 {
      color: #004080;
      border-bottom: 2px solid #004080;
      padding-bottom: 5px;
    }
    p {
      line-height: 1.6;
      font-size: 16px;
    }
    .card-container {
      text-align: center;
      margin-top: 20px;
    }
    .card {
      display: inline-block;
      width: 30%;
      min-width: 280px;
      margin: 10px;
      padding: 15px;
      background-color: #f9f9f9;
      border: 1px solid #eeeeee;
      vertical-align: top;
      text-align: left;
    }
```

```
    .card h3 {
      color: #333333;
      margin-top: 0;
    }
    ul {
      padding-left: 20px;
    }
    li {
      margin-bottom: 8px;
      line-height: 1.5;
    }
    footer {
      background-color: #222222;
      color: #ffffff;
      text-align: center;
      padding: 30px;
      margin-top: 50px;
    }
    footer p {
      margin: 5px 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Dr. RVR NRI University</h1>
  </header>
  <nav>
    <a href="#about">About</a>
    <a href="#departments">Departments</a>
    <a href="#admissions">Admissions</a>
    <a href="#facilities">Campus Life</a>
    <a href="#contact">Contact</a>
  </nav>
  <div class="banner">
    <h2>Empowering the Next Generation of Innovators</h2>
    <p>Excellence in Engineering, Technology, and Research.</p>
  </div>
  <section id="about">
    <h2>Institutional Information</h2>
    <p>Welcome to Dr. RVR NRI University. We are dedicated to providing top-
tier education, fostering research, and developing students into future
industry leaders. Our campus provides a robust academic environment backed by
state-of-the-art infrastructure.</p>
  </section>
  <section id="departments">
```

```
    <h2>Departments & Courses</h2>
    <div class="card-container">
      <div class="card">
        <h3>Computer Science & Engineering</h3>
        <p>Specialization in Artificial Intelligence and Machine Learning (AI &
ML). Focuses on modern computing algorithms, data science, and intelligent
systems.</p>
      </div>
      <div class="card">
        <h3>Electronics & Communication</h3>
        <p>Core engineering concepts covering VLSI design, embedded systems,
and modern communication networks.</p>
      </div>
      <div class="card">
        <h3>Mechanical Engineering</h3>
        <p>Advanced studies in robotics, thermodynamics, and sustainable
manufacturing processes.</p>
      </div>
    </div>
  </section>
  <section id="faculty">
    <h2>Faculty Profiles</h2>
    <ul>
      <li><strong>Dr. A. Sharma:</strong> Professor & Head of CSE - 15+ years
of research in Neural Networks.</li>
      <li><strong>Dr. M. Reddy:</strong> Associate Professor - Specialist in
IoT and Embedded Systems.</li>
      <li><strong>Prof. K. Rao:</strong> Assistant Professor - Expert in Cloud
Computing and Data Structures.</li>
    </ul>
  </section>
  <section id="admissions">
    <h2>Admissions Procedure</h2>
    <p>Admissions are strictly merit-based. Prospective students must follow
these steps:</p>
    <ul>
      <li>Submit the online application form along with previous educational
transcripts.</li>
      <li>Provide valid entrance examination scores (e.g., JEE Main).</li>
      <li>Attend the institutional counseling session for seat allocation.</li>
      <li>Complete fee payment and document verification.</li>
    </ul>
  </section>
  <section id="facilities">
    <h2>Campus Facilities & Events</h2>
    <div class="card-container">
      <div class="card">
        <h3>Infrastructure</h3>
        <p>High-speed Wi-Fi, modern laboratories, digital library, and smart
classrooms.</p>
      </div>
      <div class="card">
```

```
        <h3>Sports & Hostels</h3>
        <p>On-campus accommodation, indoor sports complex, and a fully equipped
gymnasium.</p>
      </div>
      <div class="card">
        <h3>Upcoming Events</h3>
        <p>Annual Tech Symposium, Coding Sprints, and Cultural Fest.</p>
      </div>
    </div>
  </section>
  <section id="contact">
    <h2>Contact Details</h2>
    <p><strong>Address:</strong> Dr. RVR NRI University Campus, Andhra Pradesh,
India</p>
    <p><strong>Email:</strong> admissions@drrvrnri.in.edu</p>
    <p><strong>Phone:</strong> +91 98765 43210</p>
  </section>
  <footer>
    <p> 2026 Dr. RVR NRI University.</p>
    <p>2026-2030</p>
  </footer>
</body>
</html>
```

```
OUTPUT:
```

### DR. RVR NRI UNIVERSITY 

EMPOWERING THE NEXT GENERATION OF INNOVATORS 

INSTITUTIONAL INFORMATION 



<!-- Start of picture text -->
DEPARTMENTS & COURSES<br>COMPUTER SCIENCE & ELECTRONICS &<br>ENGINEERING COMMUNICATION<br>MECHANICAL ENGINEERING<br><!-- End of picture text -->

FACULTY PROFILES 

ADMISSIONS PROCEDURE 



<!-- Start of picture text -->
CAMPUS FACILITIES & EVENTS<br>INFRASTRUCTURE<br>‘SPORTS& HOSTELS<br>UPCOMING EVENTS<br><!-- End of picture text -->

CONTACT DETAILS 

## **Conclusion:** 

The college university website was effectively built using standard web technologies. The implementation successfully utilized CSS flexbox-like card layouts and a structured semantic HTML hierarchy to present institutional data, academic departments, and facility details in a clear and responsive format. 

