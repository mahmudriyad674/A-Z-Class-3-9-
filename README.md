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
your-website-folder/
├── index.html
└── class7/
    ├── bangla1.html
    ├── bangla2.html
    ├── english1.html
    ├── english2.html
    ├── math.html
    ├── science.html
    ├── bgs.html
    ├── agriculture.html
    ├── religion.html
    └── ict.html
<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>গণিত - ৭ম শ্রেণী</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 30px;
      background-color: #f9f9f9;
    }
    h1 {
      color: #2196f3;
      text-align: center;
    }
    ol {
      margin-top: 20px;
    }
    li {
      margin-bottom: 15px;
      background: #fff;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    .question {
      font-weight: bold;
      color: #333;
    }
  </style>
</head>
<body>
  <h1>৭ম শ্রেণী - গণিত</h1>
  <ol>
    <li><span class="question">প্রশ্ন: সংখ্যা কাকে বলে?</span><br>উত্তর: যেগুলোর দ্বারা গণনা করা যায় তাকে সংখ্যা বলে।</li>
    <li><span class="question">প্রশ্ন: ভগ্নাংশ কাকে বলে?</span><br>উত্তর: পূর্ণসংখ্যার অংশকে ভগ্নাংশ বলে।</li>
    <li><span class="question">প্রশ্ন: গ.সা.গু. নির্ণয় কীভাবে করা হয়?</span><br>উত্তর: একটি সংখ্যা যেটি একাধিক সংখ্যাকে নিঃশেষে ভাগ দেয় তাকেই গ.সা.গু. বলে।</li>
    <li><span class="question">প্রশ্ন: ল.সা.গু. নির্ণয় কীভাবে করা হয়?</span><br>উত্তর: একটি সংখ্যা যেটি একাধিক সংখ্যার গুণিতক এবং সর্বনিম্ন সংখ্যা, তাকেই ল.সা.গু. বলে।</li>
  </ol>
</body>
</html>
<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>বিজ্ঞান - ৭ম শ্রেণী</title>
  <style>
    body { font-family: Arial, sans-serif; padding: 30px; background-color: #fffde7; }
    h1 { color: #4caf50; text-align: center; }
    ol { margin-top: 20px; }
    li {
      margin-bottom: 15px;
      background: #f1f8e9;
      padding: 15px;
      border-radius: 10px;
    }
    .question {
      font-weight: bold;
      color: #2e7d32;
    }
  </style>
</head>
<body>
  <h1>৭ম শ্রেণী - বিজ্ঞান</h1>
  <ol>
    <li><span class="question">প্রশ্ন: কোষ কাকে বলে?</span><br>উত্তর: জীবদেহের গঠন ও কার্যগত একক হলো কোষ।</li>
    <li><span class="question">প্রশ্ন: জারণ ও অপচয় কাকে বলে?</span><br>উত্তর: জারণ হচ্ছে অক্সিজেনের সংযোজন, অপচয় হচ্ছে অক্সিজেনের অপসারণ।</li>
    <li><span class="question">প্রশ্ন: শক্তির উৎস কী?</span><br>উত্তর: সূর্য হলো পৃথিবীর প্রধান শক্তির উৎস।</li>
    <li><span class="question">প্রশ্ন: পদার্থ কাকে বলে?</span><br>উত্তর: যে সব কিছুর ভর এবং আয়তন আছে তাকে পদার্থ বলে।</li>
  </ol>
</body>
</html>
<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>আইসিটি - ৭ম শ্রেণী</title>
  <style>
    body { font-family: Arial, sans-serif; padding: 30px; background-color: #e3f2fd; }
    h1 { color: #0288d1; text-align: center; }
    ol { margin-top: 20px; }
    li {
      margin-bottom: 15px;
      background: #ffffff;
      padding: 15px;
      border-radius: 10px;
    }
    .question {
      font-weight: bold;
      color: #01579b;
    }
  </style>
</head>
<body>
  <h1>৭ম শ্রেণী - তথ্য ও যোগাযোগ প্রযুক্তি</h1>
  <ol>
    <li><span class="question">প্রশ্ন: কম্পিউটার কাকে বলে?</span><br>উত্তর: কম্পিউটার একটি ইলেকট্রনিক যন্ত্র যা ডেটা প্রক্রিয়াকরণ করে।</li>
    <li><span class="question">প্রশ্ন: ইনপুট ও আউটপুট ডিভাইস কী?</span><br>উত্তর: ইনপুট ডিভাইস দ্বারা তথ্য প্রবেশ করানো হয়, আউটপুট ডিভাইস দ্বারা ফলাফল পাওয়া যায়।</li>
    <li><span class="question">প্রশ্ন: সফটওয়্যার ও হার্ডওয়্যার কী?</span><br>উত্তর: হার্ডওয়্যার হলো দৃশ্যমান অংশ এবং সফটওয়্যার হলো প্রোগ্রাম।</li>
  </ol>
</body>
</html>

A-Z-Class-3-9-/
├── index.html
└── class7/
    ├── math.html
    ├── science.html
    ├── ict.html
    └── ...
      
