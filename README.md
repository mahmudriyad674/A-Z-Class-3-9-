# A-Z-Class-3-9-
<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>শ্রেণীভিত্তিক প্রশ্নোত্তর</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f0f8ff;
      text-align: center;
      padding: 30px;
    }
    .header {
      background-color: #009688;
      color: white;
      padding: 40px 20px;
      border-radius: 10px;
      margin-bottom: 20px;
    }
    .class-select {
      margin-top: 30px;
    }
    .button {
      display: inline-block;
      margin: 10px;
      padding: 15px 30px;
      font-size: 18px;
      background-color: #4caf50;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .button:hover {
      background-color: #388e3c;
    }
    .subject-list {
      display: none;
      margin-top: 30px;
    }
    .subject {
      margin: 5px;
      font-size: 20px;
    }
  </style>
</head>
<body>
  <div class="header">
    <h1>🕌 আসসালামু আলাইকুম</h1>
    <p>এখানে সপ্তম থেকে নবম-দশম শ্রেণীর বইয়ের প্রশ্ন ও অনুপ্রশ্নের উত্তর পাওয়া যায়।</p>
  </div>

  <h2>📚 আপনার ক্লাস সিলেক্ট করুন</h2>
  <div class="class-select">
    <button class="button" onclick="showSubjects('class7')">শ্রেণী ৭ম</button>
    <button class="button" onclick="showSubjects('class8')">শ্রেণী ৮ম</button>
    <button class="button" onclick="showSubjects('class9')">শ্রেণী ৯ম-১০ম</button>
  </div>

  <div id="class7" class="subject-list">
    <h3>৭ম শ্রেণীর বিষয়সমূহ:</h3>
    <div class="subject">📘 বাংলা প্রথম পত্র</div>
    <div class="subject">📘 বাংলা দ্বিতীয় পত্র</div>
    <div class="subject">📘 ইংরেজি প্রথম পত্র</div>
    <div class="subject">📘 ইংরেজি দ্বিতীয় পত্র</div>
    <div class="subject">📘 গণিত</div>
    <div class="subject">📘 বিজ্ঞান</div>
    <div class="subject">📘 বাংলাদেশ ও বিশ্বপরিচয় (বাওবি)</div>
    <div class="subject">📘 কৃষি শিক্ষা</div>
    <div class="subject">📘 ধর্ম</div>
    <div class="subject">📘 আইসিটি</div>
  </div>

  <div id="class8" class="subject-list">
    <h3>৮ম শ্রেণীর বিষয়সমূহ:</h3>
    <div class="subject">📘 বাংলা প্রথম পত্র</div>
    <div class="subject">📘 বাংলা দ্বিতীয় পত্র</div>
    <div class="subject">📘 ইংরেজি প্রথম পত্র</div>
    <div class="subject">📘 ইংরেজি দ্বিতীয় পত্র</div>
    <div class="subject">📘 গণিত</div>
    <div class="subject">📘 বিজ্ঞান</div>
    <div class="subject">📘 বাংলাদেশ ও বিশ্বপরিচয়</div>
    <div class="subject">📘 কৃষি শিক্ষা</div>
    <div class="subject">📘 ধর্ম</div>
    <div class="subject">📘 আইসিটি</div>
  </div>

  <div id="class9" class="subject-list">
    <h3>৯ম-১০ম শ্রেণীর বিষয়সমূহ:</h3>
    <div class="subject">📘 বাংলা প্রথম পত্র</div>
    <div class="subject">📘 বাংলা দ্বিতীয় পত্র</div>
    <div class="subject">📘 ইংরেজি প্রথম পত্র</div>
    <div class="subject">📘 ইংরেজি দ্বিতীয় পত্র</div>
    <div class="subject">📘 গণিত</div>
    <div class="subject">📘 বিজ্ঞান</div>
    <div class="subject">📘 বাংলাদেশ ও বিশ্বপরিচয়</div>
    <div class="subject">📘 কৃষি শিক্ষা</div>
    <div class="subject">📘 ধর্ম</div>
    <div class="subject">📘 আইসিটি</div>
  </div>

  <script>
    function showSubjects(classId) {
      const subjectLists = document.querySelectorAll('.subject-list');
      subjectLists.forEach(list => list.style.display = 'none');
      document.getElementById(classId).style.display = 'block';
    }
  </script>
</body>
</html>
