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
      margin: 10px;
      font-size: 20px;
    }
    .subject a {
      text-decoration: none;
      color: #1a237e;
    }
    .subject a:hover {
      color: #0d47a1;
    }
  </style>
</head>
<body>
  <div class="header">
    <h1>🕌 আসসালামু আলাইকুম</h1>
    <p>এখানে ৭ম থেকে ৯ম-১০ম শ্রেণীর বইয়ের প্রশ্ন ও অনুপ্রশ্নের উত্তর পাওয়া যায়।</p>
  </div>

  <h2>📚 আপনার ক্লাস সিলেক্ট করুন</h2>
  <div class="class-select">
    <button class="button" onclick="showSubjects('class7')">শ্রেণী ৭ম</button>
    <button class="button" onclick="showSubjects('class8')">শ্রেণী ৮ম</button>
    <button class="button" onclick="showSubjects('class9')">শ্রেণী ৯ম-১০ম</button>
  </div>

  <!-- Class 7 Subjects -->
  <div id="class7" class="subject-list">
    <h3>৭ম শ্রেণীর বিষয়সমূহ:</h3>
    <div class="subject"><a href="class7/bangla1.html" target="_blank">📘 বাংলা প্রথম পত্র</a></div>
    <div class="subject"><a href="class7/bangla2.html" target="_blank">📘 বাংলা দ্বিতীয় পত্র</a></div>
    <div class="subject"><a href="class7/english1.html" target="_blank">📘 ইংরেজি প্রথম পত্র</a></div>
    <div class="subject"><a href="class7/english2.html" target="_blank">📘 ইংরেজি দ্বিতীয় পত্র</a></div>
    <div class="subject"><a href="class7/math.html" target="_blank">📘 গণিত</a></div>
    <div class="subject"><a href="class7/science.html" target="_blank">📘 বিজ্ঞান</a></div>
    <div class="subject"><a href="class7/bgs.html" target="_blank">📘 বাংলাদেশ ও বিশ্বপরিচয়</a></div>
    <div class="subject"><a href="class7/agriculture.html" target="_blank">📘 কৃষি শিক্ষা</a></div>
    <div class="subject"><a href="class7/religion.html" target="_blank">📘 ধর্ম</a></div>
    <div class="subject"><a href="class7/ict.html" target="_blank">📘 আইসিটি</a></div>
  </div>

  <!-- Class 8 Subjects -->
  <div id="class8" class="subject-list">
    <h3>৮ম শ্রেণীর বিষয়সমূহ:</h3>
    <div class="subject"><a href="class8/bangla1.html" target="_blank">📘 বাংলা প্রথম পত্র</a></div>
    <div class="subject"><a href="class8/bangla2.html" target="_blank">📘 বাংলা দ্বিতীয় পত্র</a></div>
    <div class="subject"><a href="class8/english1.html" target="_blank">📘 ইংরেজি প্রথম পত্র</a></div>
    <div class="subject"><a href="class8/english2.html" target="_blank">📘 ইংরেজি দ্বিতীয় পত্র</a></div>
    <div class="subject"><a href="class8/math.html" target="_blank">📘 গণিত</a></div>
    <div class="subject"><a href="class8/science.html" target="_blank">📘 বিজ্ঞান</a></div>
    <div class="subject"><a href="class8/bgs.html" target="_blank">📘 বাংলাদেশ ও বিশ্বপরিচয়</a></div>
    <div class="subject"><a href="class8/agriculture.html" target="_blank">📘 কৃষি শিক্ষা</a></div>
    <div class="subject"><a href="class8/religion.html" target="_blank">📘 ধর্ম</a></div>
    <div class="subject"><a href="class8/ict.html" target="_blank">📘 আইসিটি</a></div>
  </div>

  <!-- Class 9 Subjects -->
  <div id="class9" class="subject-list">
    <h3>৯ম-১০ম শ্রেণীর বিষয়সমূহ:</h3>
    <div class="subject"><a href="class9/bangla1.html" target="_blank">📘 বাংলা প্রথম পত্র</a></div>
    <div class="subject"><a href="class9/bangla2.html" target="_blank">📘 বাংলা দ্বিতীয় পত্র</a></div>
    <div class="subject"><a href="class9/english1.html" target="_blank">📘 ইংরেজি প্রথম পত্র</a></div>
    <div class="subject"><a href="class9/english2.html" target="_blank">📘 ইংরেজি দ্বিতীয় পত্র</a></div>
    <div class="subject"><a href="class9/math.html" target="_blank">📘 গণিত</a></div>
    <div class="subject"><a href="class9/science.html" target="_blank">📘 বিজ্ঞান</a></div>
    <div class="subject"><a href="class9/bgs.html" target="_blank">📘 বাংলাদেশ ও বিশ্বপরিচয়</a></div>
    <div class="subject"><a href="class9/agriculture.html" target="_blank">📘 কৃষি শিক্ষা</a></div>
    <div class="subject"><a href="class9/religion.html" target="_blank">📘 ধর্ম</a></div>
    <div class="subject"><a href="class9/ict.html" target="_blank">📘 আইসিটি</a></div>
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
<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>৭ম শ্রেণি - গণিত প্রশ্নোত্তর</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #fff8e1;
      padding: 20px;
      line-height: 1.6;
    }
    h1 {
      text-align: center;
      color: #d84315;
    }
    .question {
      font-weight: bold;
      color: #2e7d32;
    }
    .answer {
      margin-bottom: 20px;
      color: #37474f;
    }
    .back {
      display: block;
      margin-top: 30px;
      text-align: center;
    }
    .back a {
      background-color: #009688;
      color: white;
      padding: 10px 20px;
      border-radius: 6px;
      text-decoration: none;
    }
    .back a:hover {
      background-color: #00796b;
    }
  </style>
</head>
<body>

  <h1>৭ম শ্রেণি - গণিত প্রশ্নোত্তর</h1>

  <div class="question">প্রশ্ন ১: পূর্ণসংখ্যা কী?</div>
  <div class="answer">উত্তর: শূন্য, ধনাত্মক ও ঋণাত্মক সংখ্যাকে পূর্ণসংখ্যা বলে।</div>

  <div class="question">প্রশ্ন ২: বিস্তার রূপে ২.৫৬ কে লিখুন।</div>
  <div class="answer">উত্তর: ২.৫৬ = ২ + ০.৫ + ০.০৬</div>

  <div class="question">প্রশ্ন ৩: গ.সা.গু ও ল.সা.গু কী?</div>
  <div class="answer">উত্তর: গ.সা.গু অর্থ গৃহীত সাধারণ গুণনীয়ক এবং ল.সা.গু অর্থ লঘুতম সাধারণ গুণিতক।</div>

  <!-- আরও প্রশ্ন ও উত্তর এইভাবে যোগ করুন -->

  <div class="back">
    <a href="../index.html">⬅ হোমপেইজে ফিরে যান</a>
  </div>

</body>
</html>
