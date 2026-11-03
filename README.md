<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <link rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
  <style>
    
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-image: url('image_1.jpg');
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
  background-color: #091d33;
  color: #fff;
}

/* Main container */
.container {
  width: 94%;
  max-width: 1500px;
  margin: 0 auto;
  padding: 30px 20px 50px;
  text-align: center;
  box-sizing: border-box;
}

/* New Header */
.header {
  width: 94%;
  max-width: 1500px;
  margin: 30px auto 0;
  padding: 40px 50px;

  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 30px;

  background-color: rgba(16, 42, 67, 0.94);
  border: 1px solid rgba(212, 175, 112, 0.4);
  border-radius: 16px;
  box-sizing: border-box;

  box-shadow: 0 8px 30px rgba(0, 0, 0, 0.25);
}

.header-info {
  text-align: left;
  flex: 1;
}

.welcome-text {
  color: #d4af70;
  font-size: 15px;
  letter-spacing: 1px;
  margin: 0 0 12px;
}

.header h1 {
  font-size: 38px;
  margin: 10px 0;
  color: #ffffff;
}

.header h2 {
  font-size: 20px;
  font-weight: normal;
  color: #d4af70;
  margin: 10px 0;
}

.research-fields {
  font-size: 15px;
  color: #e0e0e0;
  line-height: 1.7;
}

.header-quote {
  font-family: Georgia, serif;
  font-style: italic;
  font-size: 17px;
  color: #f0e6d2;
  margin-top: 25px;
  line-height: 1.8;
}

.header-profile {
  width: 180px;
  height: 180px;
  object-fit: cover;
  border-radius: 50%;
  border: 3px solid #d4af70;
  flex-shrink: 0;
}

/* Tabs */
.tab-container {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 10px;
  margin-bottom: 30px;
}

.tab-button {
  background-color: rgba(9, 29, 51, 0.85);
  color: #ffffff;
  border: 1px solid #d4af70;
  padding: 10px 20px;
  cursor: pointer;
  font-size: 16px;
  transition: 0.3s;
  border-radius: 6px;
}

.tab-button:hover {
  background-color: rgba(212, 175, 112, 0.25);
}

.tab-button.active {
  background-color: #d4af70;
  color: #091d33;
  font-weight: bold;
}

/* Tab content */
.tab-content {
  display: none;
  background-color: rgba(20, 36, 56, 0.96);
  padding: 30px;
  border: 1px solid rgba(212, 175, 112, 0.35);
  border-radius: 12px;
  line-height: 1.8;
}

.tab-content.active {
  display: block;
}

.tab-content p {
  font-size: 17px;
  line-height: 1.9;
}

h1, h2, h3 {
  margin-bottom: 20px;
}

p {
  margin-bottom: 10px;
}

.left-align {
  text-align: left;
}

.justify {
  text-align: justify;
}

.section-divider {
  border-top: 1px solid rgba(212, 175, 112, 0.5);
  margin: 25px 0;
}

/* Contact */
.contact-section {
  text-align: center;
  padding: 20px;
}

.contact-section a {
  color: #d4af70;
  text-decoration: none;
  transition: color 0.3s ease;
}

.contact-section a:hover {
  color: #ffffff;
  text-decoration: underline;
}

.social-links {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 30px;
  margin-top: 20px;
  flex-wrap: wrap;
}

.social-links a {
  display: inline-flex;
  align-items: center;
  gap: 9px;
  font-size: 17px;
  font-weight: bold;
}

.social-links a i {
  font-size: 25px;
}

.contact-section p i {
  font-size: 20px;
  margin-right: 8px;
}

/* Mobile */
@media (max-width: 768px) {
  body {
    background-attachment: scroll;
  }

  .header {
    flex-direction: column-reverse;
    text-align: center;
    padding: 30px 20px;
  }

  .header-info {
    text-align: center;
  }

  .header h1 {
    font-size: 30px;
  }

  .header-profile {
    width: 140px;
    height: 140px;
  }

  .container {
    width: 96%;
    padding: 20px 10px 35px;
  }

  .tab-content {
    padding: 20px;
  }

  .tab-button {
    font-size: 14px;
    padding: 10px 12px;
  }
}









    /* --- استایل‌های مربوط به تب‌ها --- */
    .tab-container {
      display: flex;
      justify-content: center;
      margin-bottom: 30px;
      border-bottom: 20px;
    }
    .tab-button {
      background-color: rgba(0, 0, 0, 0.6);
      color: #fff;
      border: 1px solid #fff;
      padding: 10px 20px;
      cursor: pointer;
      font-size: 16px;
      transition: 0.3s;
      margin: 0 5px;
      border-radius: 5px 5px 0 0;
    }
    .tab-button:hover {
      background-color: rgba(255, 255, 255, 0.2);
    }
    .tab-button.active {
      background-color: #fff;
      color: #000;
      font-weight: bold;
    }
    .tab-content {
      display: none; /* در حالت عادی همه بخش‌ها مخفی هستند */
      background-color: rgba(20, 36, 56, 0.96); /* پس‌زمینه تیره برای خوانایی بهتر متن */
      padding: 25px;
      border-radius: 8px;
    }
    .tab-content.active {
      display: block; /* فقط بخش فعال نمایش داده می‌شود */
    }
  </style>
</head>
<body>







<header class="header">
  <div class="header-info">
    <p class="welcome-text">Welcome / خوش آمدید</p>
    <h1>Ashkan Amirnia</h1>
    <!-- <h2>ML Researcher</h2>-->
    <p class="research-fields">
      Reinforcement Learning | Deep Learning | Computer Vision | Production Planning
    </p>
    <p class="header-quote">
      Engineer by training, Researcher by nature,
      Artist at heart.
    </p>
  </div>
  <img src="Ashkan.jpg"
       alt="Ashkan Amirnia"
       class="header-profile">
</header>












 
  <div class="container">
   <!-- <img src="Ashkan.jpg" alt="Profile Picture" class="profile">-->
 <!-- <div class="personal-quote">-->
   <!-- <p>Engineer by training,</p>-->
   <!-- <p>Researcher by nature,</p>-->
   <!-- <p>Artist at heart...</p>-->
  <!-- </div>*/-->
    <!-- دکمه‌های تب‌ها -->
    <div class="tab-container">
      <button class="tab-button active" onclick="openTab(event, 'about')">About Me</button>
      <button class="tab-button" onclick="openTab(event, 'education')">Education</button>
      <button class="tab-button" onclick="openTab(event, 'skills')">Skills</button>
      <button class="tab-button" onclick="openTab(event, 'hobbies')">Hobbies</button>
      <button class="tab-button" onclick="openTab(event, 'notes')">Notes</button>    
    </div>

    <!-- محتوای تب اول: About Me -->
    <div id="about" class="tab-content active">
      <div class="left-align justify">
        <h3>About Me</h3>
        <p>During my teenage years, I discovered a magazine focused on science and technology called Danestaniha. After reading a few editions, I became a fan of the magazine. It not only provided entertainment but also ignited my interest in the world of science and technology. This fascination led me to pursue a degree in electronic engineering at the university, a field closely associated with technology. In my final year of undergraduate studies, I was introduced to Artificial Intelligence (AI), and my interest in this field deepened. Motivated by this passion, I pursued a Master's degree in AI, specializing in real-time computer vision, at Sharif University of Technology. Throughout my years of study, I successfully completed various courses related to AI, including image processing, machine learning, machine vision, computer vision in intelligent environments, parallel programming, data mining, and advanced statistical analysis. After obtaining my master's degree, I garnered valuable experience by working as a machine learning engineer and consultant for several years, contributing to diverse industrial projects. Since the summer of 2022, I have been pursuing my Ph.D. under the supervision of Professor Samira Kivanpour. My research focuses on developing machine learning algorithms for human-robot collaboration disassembly planning. My objective is to develop autonomous models capable of making real-time decisions based on dynamic conditions. In essence, tackling machine learning challenges is not just a job for me; it is a hobby that I truly enjoy.</p>
      </div>
    </div>

    <!-- محتوای تب دوم: Skills -->
<div id="skills" class="tab-content">
  <div class="left-align">
    <h3>My Skills</h3>

    <h4>Technical Skills</h4>
    <ul>
      <li>Applied Machine Learning</li>
      <li>Reinforcement Learning</li>
      <li>Computer Vision</li>
      <li>Recommender Systems and Personalization</li>
      <li>Production Planning</li>
    </ul>

    <h4>Soft Skills</h4>
    <ul>
      <li>Teamwork</li>
      <li>Project Management</li>
      <li>Storytelling</li>
    </ul>
        
      </div>
    </div>


    <!-- محتوای تب سوم: Education -->
    <div id="education" class="tab-content">
      <div class="left-align">
        <h3>Education</h3>
        <ul>
          <li>PhD in Polytechnique montreal 2022-2025</li>
          <li>Master of Engineering in Sharif university 2016-2019</li>
          <li>Bachelor of Science in Shahid chamran university 2012-2016</li>
        </ul>
      </div>
    </div>



    <!-- محتوای تب چهارم: Hobbies -->
    <div id="hobbies" class="tab-content">
      <div class="left-align">

        <h3>Hobbies</h3>
        <ul>
          <li>Painting and drawing</li>
          <li>Taking long walks in nature</li>
          <li>Reading Novels and persian poem books</li>
          <li>Watching movies, listening to music</li>
   
        </ul>
      </div>
    </div>







    <!-- محتوای تب دوم: Notes -->
    <div id="notes" class="tab-content">
      <div class="left-align">
       
        <ul>
         مقصد من رفتن است، با نرسیدن خوشم هر که به مقصد خوش است، مانده ی بن بست هاست

        </ul>
        
      </div>
    </div>







    

    <hr class="section-divider">
    
    <!-- بخش تماس در انتهای صفحه ثابت می‌ماند -->
    


<div class="contact-section">
  <h3>Contact Information</h3>

  <p>
    <a href="mailto:ashkan.amirnia@polymtl.ca">
      <i class="fa-solid fa-envelope"></i>
      ashkan.amirnia@polymtl.ca
    </a>
  </p>

  <div class="social-links">
    <a href="https://www.linkedin.com/in/ashkan-amirnia"
       target="_blank" rel="noopener noreferrer">
      <i class="fa-brands fa-linkedin"></i>
      LinkedIn
    </a>

    <a href="https://scholar.google.com/citations?user=ERXe3A0AAAAJ&amp;hl=en"
       target="_blank" rel="noopener noreferrer">
      <i class="fa-solid fa-graduation-cap"></i>
      Google Scholar
    </a>
  </div>
</div>
</div> <!-- End of main container -->



  <!-- اسکریپت کوتاه جاوااسکریپت برای جابجایی بین تب‌ها -->
  <script>
    function openTab(evt, tabName) {
      // مخفی کردن تمام محتواها
      var i, tabcontent, tabbuttons;
      tabcontent = document.getElementsByClassName("tab-content");
      for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].className = tabcontent[i].className.replace(" active", "");
      }

      // غیرفعال کردن استایل تمام دکمه‌ها
      tabbuttons = document.getElementsByClassName("tab-button");
      for (i = 0; i < tabbuttons.length; i++) {
        tabbuttons[i].className = tabbuttons[i].className.replace(" active", "");
      }

      // نشان دادن محتوای تب کلیک شده و فعال کردن دکمه آن
      document.getElementById(tabName).className += " active";
      evt.currentTarget.className += " active";
    }
  </script>
</body>
</html>
