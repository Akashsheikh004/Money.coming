<!DOCTYPE html><html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>RefEarn - ইনকাম সাইট</title>
  <link rel="stylesheet" href="style.css">
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #e9f0f4;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 400px;
      margin: 60px auto;
      background-color: white;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
      text-align: center;
    }
    h1 {
      color: #2196f3;
      margin-bottom: 10px;
    }
    p.tagline {
      color: #555;
      font-size: 15px;
      margin-bottom: 25px;
    }
    input, button {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border-radius: 6px;
      border: 1px solid #ccc;
    }
    button {
      background-color: #2196f3;
      color: white;
      border: none;
      font-weight: bold;
    }
    button:hover {
      background-color: #1976d2;
    }
    a {
      color: #2196f3;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    footer {
      text-align: center;
      margin-top: 40px;
      color: #999;
      font-size: 13px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>RefEarn</h1>
    <p class="tagline">রেফার করো, ইনকাম করো 💸</p>
    <form action="/register" method="POST">
      <input type="text" name="username" placeholder="ইউজারনেম" required>
      <input type="password" name="password" placeholder="পাসওয়ার্ড" required>
      <input type="text" name="invite_code" placeholder="ইনভাইট কোড (ঐচ্ছিক)">
      <button type="submit">একাউন্ট তৈরি করুন</button>
    </form>
    <p>ইতোমধ্যে অ্যাকাউন্ট আছে? <a href="/login.html">লগইন করুন</a></p>
  </div>
  <footer>
    &copy; 2025 RefEarn | ডিজাইন করেছেন ChatGPT
  </footer>
</body>
</html>
