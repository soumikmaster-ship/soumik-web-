
<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>সৌমিক দাশ | Personal Website</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  background: #090909;
  color: white;
  font-family: Arial, sans-serif;
  line-height: 1.8;
}

header {
  background: #111;
  padding: 18px;
  text-align: center;
  border-bottom: 2px solid #d9b45d;
  position: sticky;
  top: 0;
}

header h2 {
  color: #e4c16e;
}

nav {
  margin-top: 10px;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 8px;
  font-size: 14px;
}

nav a:hover {
  color: #e4c16e;
}

.hero {
  text-align: center;
  padding: 80px 20px;
  background: linear-gradient(#201a0c, #090909);
}

.hero h1 {
  color: #e4c16e;
  font-size: 42px;
}

.hero p {
  color: #ccc;
  margin-top: 15px;
}

.hero img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  border: 3px solid #d9b45d;
  margin-top: 25px;
}

.welcome {
  color: #e4c16e;
  border: 1px solid #d9b45d;
  padding: 8px 20px;
  border-radius: 30px;
}

section {
  padding: 65px 20px;
  border-bottom: 1px solid #40351e;
}

.section-title {
  text-align: center;
  color: #e4c16e;
  font-size: 30px;
  margin-bottom: 25px;
}

.card {
  max-width: 850px;
  margin: auto;
  background: #171717;
  border: 1px solid #80652d;
  border-radius: 18px;
  overflow: hidden;
}

.card img {
  width: 100%;
  max-height: 600px;
  object-fit: cover;
  display: block;
}

.content {
  padding: 30px;
}

.content h3 {
  color: #e4c16e;
  font-size: 24px;
  margin-bottom: 12px;
}

.content p,
.content li {
  color: #ccc;
  margin-bottom: 12px;
}

.content ul {
  padding-left: 25px;
}

.quote {
  color: #e4c16e;
  background: #252014;
  padding: 15px;
  border-left: 4px solid #d9b45d;
  margin-top: 20px;
}

.school {
  text-align: center;
  background: #171717;
  border: 1px solid #80652d;
  border-radius: 18px;
  max-width: 850px;
  margin: auto;
  padding: 25px;
}

.school img {
  width: 100%;
  border-radius: 12px;
  margin-bottom: 20px;
}

.school h3 {
  color: #e4c16e;
}

.school p {
  color: #ccc;
}

.follow {
  display: inline-block;
  background: #d9b45d;
  color: #111;
  padding: 13px 30px;
  border-radius: 40px;
  text-decoration: none;
  font-weight: bold;
  font-size: 18px;
  margin-top: 20px;
  box-shadow: 0 5px 20px #d9b45d44;
}

.follow:hover {
  background: #f4dda0;
  transform: scale(1.04);
}

footer {
  text-align: center;
  padding: 30px;
  color: #ccc;
  background: #111;
}

footer span {
  color: #e4c16e;
}

@media(max-width:600px) {
  .hero h1 {
    font-size: 32px;
  }

  nav a {
    margin: 5px;
  }

  .content {
    padding: 20px;
  }
}
</style>
</head>

<body>

<header>
  <h2>সৌমিক দাশ</h2>
  <nav>
    <a href="#home">হোম</a>
    <a href="#scout">স্কাউটিং</a>
    <a href="#student">শিক্ষার্থী</a>
    <a href="#football">ফুটবল</a>
    <a href="#school">বিদ্যালয়</a>
    <a href="#contact">যোগাযোগ</a>
  </nav>
</header>

<!-- HOME -->
<section class="hero" id="home">
  <span class="welcome">
    আমার ব্যক্তিগত ওয়েবসাইটে স্বাগতম
  </span>

  <h1>হ্যালো! আমি<br>সৌমিক দাশ</h1>

  <p>
    আমি মাদারীপুরের একজন শিক্ষার্থী।
    স্কাউটিং, পড়াশোনা এবং ফুটবল
    আমার জীবনের তিনটি পরিচয়।
  </p>

  <img src="scout.jpg" alt="সৌমিক দাশ">
</section>

<!-- SCOUT -->
<section id="scout">
  <h2 class="section-title">আমার স্কাউটিং জীবন</h2>

  <div class="card">
    <img src="scout.jpg" alt="স্কাউটিং ছবি">

    <div class="content">
      <h3>একজন স্কাউট হিসেবে আমার পরিচয়</h3>

      <p>
        স্কাউটিং হলো সেবা, শৃঙ্খলা,
        দায়িত্ববোধ ও নেতৃত্ব শেখার
        একটি সুন্দর মাধ্যম।
      </p>

      <p>
        আমি স্কাউটিংয়ের মাধ্যমে নিজেকে
        আত্মবিশ্বাসী, সহযোগিতাপরায়ণ
        এবং দায়িত্বশীল মানুষ হিসেবে
        গড়ে তুলতে চাই।
      </p>

      <ul>
        <li>মানুষের উপকার করা</li>
        <li>শৃঙ্খলা মেনে চলা</li>
        <li>দলবদ্ধভাবে কাজ করা</li>
        <li>নেতৃত্বের গুণ অর্জন করা</li>
        <li>পরিবেশের যত্ন নেওয়া</li>
      </ul>

      <div class="quote">
        সদা প্রস্তুত — নিজের ও অন্যের উপকারে।
      </div>
    </div>
  </div>
</section>

<!-- STUDENT -->
<section id="student">
  <h2 class="section-title">আমার শিক্ষাজীবন</h2>

  <div class="card">
    <img src="student.jpg" alt="স্কুলের ছবি">

    <div class="content">
      <h3>আমি একজন শিক্ষার্থী</h3>

      <p>
        আমার নাম সৌমিক দাশ।
        আমি বর্তমানে সপ্তম শ্রেণিতে পড়াশোনা করি।
        আমার বিদ্যালয় ইউনাইটেড ইসলামিয়া
        সরকারি উচ্চ বিদ্যালয়।
      </p>

      <p>
        আমার শাখার নাম পদ্মা।
        আমি প্রতিদিন নতুন কিছু শিখতে
        এবং নিজের জ্ঞান বৃদ্ধি করতে ভালোবাসি।
      </p>

      <ul>
        <li>নিয়মিত পড়াশোনা করা</li>
        <li>শিক্ষকদের সম্মান করা</li>
        <li>নতুন বিষয় শেখা</li>
        <li>ভালো মানুষ হওয়ার চেষ্টা করা</li>
      </ul>

      <div class="quote">
        আজকের শেখাই আগামী দিনের ভবিষ্যৎ।
      </div>
    </div>
  </div>
</section>

<!-- FOOTBALL -->
<section id="football">
  <h2 class="section-title">আমার ফুটবল জীবন</h2>

  <div class="card">
    <img src="football.jpg" alt="ফুটবল খেলার ছবি">

    <div class="content">
      <h3>একজন ফুটবলপ্রেমী</h3>

      <p>
        ফুটবল আমার কাছে আনন্দ,
        উদ্যম এবং দলগত প্রচেষ্টার
        একটি সুন্দর অভিজ্ঞতা।
      </p>

      <p>
        ফুটবল আমাদের ধৈর্য,
        পরিশ্রম, আত্মবিশ্বাস এবং
        একসঙ্গে কাজ করতে শেখায়।
      </p>

      <ul>
        <li>দলগতভাবে কাজ করা</li>
        <li>নিয়ম মেনে খেলা</li>
        <li>প্রতিপক্ষকে সম্মান করা</li>
        <li>অনুশীলন ও পরিশ্রম করা</li>
      </ul>

      <div class="quote">
        একসঙ্গে খেলি, একসঙ্গে এগিয়ে যাই।
      </div>
    </div>
  </div>
</section>

<!-- SCHOOL -->
<section id="school">
  <h2 class="section-title">আমার বিদ্যালয়</h2>

  <div class="school">
    <img src="school.jpg" alt="আমার বিদ্যালয়">

    <h3>
      ইউনাইটেড ইসলামিয়া সরকারি উচ্চ বিদ্যালয়
    </h3>

    <p>মাদারীপুর হাই স্কুল</p>
    <p>শ্রেণি: সপ্তম</p>
    <p>শাখা: পদ্মা</p>
  </div>
</section>

<!-- PERSONAL INFORMATION -->
<section id="profile">
  <h2 class="section-title">আমার ব্যক্তিগত পরিচয়</h2>

  <div class="school">
    <h3>আমার তথ্য</h3>
    <p>নাম: সৌমিক দাশ</p>
    <p>শ্রেণি: সপ্তম</p>
    <p>শাখা: পদ্মা</p>
    <p>স্কুল: ইউনাইটেড ইসলামিয়া সরকারি উচ্চ বিদ্যালয়</p>
    <p>ঠিকানা: আমিরাবাদ, মাদারীপুর, ঢাকা, বাংলাদেশ</p>
    <p>স্কাউটিং: হ্যাঁ</p>
    <p>ফুটবল: হ্যাঁ</p>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <h2 class="section-title">যোগাযোগ</h2>

  <div class="school">
    <h3>সৌমিক দাশ</h3>

    <p>
      ফেসবুকে আমাকে ফলো করতে
      নিচের বোতামে ক্লিক করুন।
    </p>

    <a
      class="follow"
      href="https://www.facebook.com/share/1ACfH4wkPb/"
      target="_blank"
      rel="noopener noreferrer">

      f &nbsp; ফেসবুকে ফলো করুন ↗

    </a>
  </div>
</section>

<footer>
  © 2026 <span>সৌমিক দাশ</span>
  <p>আমার ব্যক্তিগত ওয়েবসাইট</p>
</footer>

</body>
</html>
