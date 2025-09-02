<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My GitHub Account</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #f4f4f4;
    }
    .card {
      width: 350px;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
      overflow: hidden;
      text-align: center;
    }
    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }
    .card h2 {
      margin: 10px 0;
      font-size: 22px;
    }
    .card p {
      padding: 0 15px;
      font-size: 14px;
      color: #555;
    }
    .buttons {
      margin: 15px 0;
      display: flex;
      justify-content: center;
      gap: 10px;
    }
    .btn {
      padding: 10px 15px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 14px;
      transition: 0.3s;
    }
    .visit-btn {
      background: #24292e;
      color: #fff;
    }
    .visit-btn:hover {
      background: #000;
    }
    .copy-btn {
      background: #0366d6;
      color: #fff;
    }
    .copy-btn:hover {
      background: #024a9c;
    }
  </style>
</head>
<body>

  <div class="card">
    <!-- Replace with your uploaded image -->
    <img src="e2702848-3009-4417-877f-3dedb83644ef.png" alt="Thumbnail">

    <h2>My GitHub Account</h2>
    <p>Explore my projects, contributions, and repositories on GitHub. Follow me for updates and new projects!</p>

    <div class="buttons">
      <button class="btn visit-btn" onclick="window.open('https://github.com/your-username', '_blank')">Visit</button>
      <button class="btn copy-btn" onclick="copyLink()">Copy Link</button>
    </div>
  </div>

  <script>
    function copyLink() {
      const link = "https://github.com/your-username"; // change to your GitHub link
      navigator.clipboard.writeText(link).then(() => {
        alert("GitHub link copied!");
      });
    }
  </script>

</body>
</html>
