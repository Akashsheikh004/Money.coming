# Money.coming  <!DOCTYPE html><html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>money coming</title>
  <link rel="stylesheet" href="style.css">
  <style>
    body {
      font-family: sans-serif;
      background: #f3f3f3;
      margin: 0;
      padding: 20px;
    }
    .container {
      max-width: 400px;
      margin: auto;
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    input, button {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      background-color: #4CAF50;
      color: white;
      cursor: pointer;
    }
    button:hover {
      background-color: #45a049;
    }
    a {
      color: #007BFF;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>রেজিস্ট্রেশন করুন</h2>
    <form action="/register" method="POST">
      <input type="text" name="username" placeholder="ইউজারনেম" required>
      <input type="password" name="password" placeholder="পাসওয়ার্ড" required>
      <input type="text" name="invite_code" placeholder="ইনভাইট কোড (ঐচ্ছিক)">
      <button type="submit">রেজিস্টার</button>
    </form>
    <p>ইতোমধ্যে অ্যাকাউন্ট আছে? <a href="/login.html">লগইন করুন</a></p>
  </div>
</body>
</html>
