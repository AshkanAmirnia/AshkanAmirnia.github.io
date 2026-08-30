<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ashkan Amirnia</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-image: url('image_1.jpg'); /* Replace 'background.jpg' with your background image path */
      background-size: cover;
      background-position: center;
      background-attachment: fixed; /* ثابت نگه داشتن پس‌زمینه هنگام اسکرول */
      color: #fff;
    }
    .header {
      padding: 20px;
      text-align: center;
      background-color: rgba(0, 0, 0, 0.5);
    }
    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 30px 50px 50px 50px;
      text-align: center;
    }
    img.profile {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      margin-bottom: 20px;
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
      border-top: 1px solid #fff;
      margin-top: 20px;
      margin-bottom: 20px;
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
      background-color: rgba(0, 0, 0, 0.6); /* پس‌زمینه تیره برای خوانایی بهتر متن */
      padding: 25px;
      border-radius: 8px;
    }
    .tab-content.active {
      display: block; /* فقط بخش فعال نمایش داده می‌شود */
    }
  </style>
</head>
<body>
  <div class="header">
    <h1>Welcome / خوش آمدید</h1>
  </div>
 
  <div class="container">
    <img src="Ashkan.jpg" alt="Profile Picture" class="profile">

    <!-- دکمه‌های تب‌ها -->
    <div class="tab-container">
      <button class="tab-button active" onclick="openTab(event, 'about')">About Me</button>
      <button class="tab-button" onclick="openTab(event, 'skills')">Skills</button>
      <button class="tab-button" onclick="openTab(event, 'hobbies')">Hobbies</button>
      <button class="tab-button" onclick="openTab(event, 'education')">Education</button>
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
        <ul>
          <li>Applied machine learning</li>
          <li>Reinforcement learning</li>
          <li>Production planning</li>
          <li>Computer vision</li>
          <li>Recommender systems and personalization</li>
          <li>Teamwork</li>
          <li>Project management</li>
          <li>Storytelling</li>
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




    <!-- محتوای تب دوم: Notes -->
    <div id="notes" class="tab-content">
      <div class="left-align">
       
        <ul>
         مقصد من رفتن است، با نرسیدن خوشم / هر که به مقصد خوش است، مانده ی بن بست هاست

        </ul>
        
      </div>
    </div>







    

    <hr class="section-divider">
    
    <!-- بخش تماس در انتهای صفحه ثابت می‌ماند -->
    <h3>Contact Information</h3>
    <p>You can reach me at: <a href="mailto:ashkan.amirnia@polymtl.ca" style="color: #00e6ff;">ashkan.amirnia@polymtl.ca</a></p>
  </div>

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
