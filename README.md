<!DOCTYPE html>
<html>
<head>
  <title>Yuvraj's Innovation Lab</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: white;
      text-align: center;
    }

    header {
      padding: 40px;
      background: rgba(0,0,0,0.4);
      animation: fadeIn 1.5s ease;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.1em;
    }

    button {
      margin-top: 20px;
      padding: 12px 20px;
      font-size: 16px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      background: #00ffd5;
      color: black;
    }

    section {
      padding: 30px;
    }

    .card {
      background: rgba(255,255,255,0.1);
      margin: 20px auto;
      padding: 20px;
      border-radius: 12px;
      width: 80%;
      max-width: 400px;

      opacity: 0;
      transform: translateY(30px);
      animation: slideUp 1s ease forwards;

      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .card:nth-child(1) { animation-delay: 0.3s; }
    .card:nth-child(2) { animation-delay: 0.6s; }
    .card:nth-child(3) { animation-delay: 0.9s; }

    .card:hover {
      transform: translateY(-5px) scale(1.02);
      box-shadow: 0 0 20px rgba(0, 255, 213, 0.6);
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes slideUp {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>⚡ Yuvraj's Innovation Lab</h1>
    <p>Exploring devices, systems, and future ideas</p>
    <button onclick="showMessage()">Why this site?</button>
  </header>

  <section>
    <div class="card">
      <h2>🔧 Device Ideas</h2>
      <p>Smart tools and inventions to solve real-world problems.</p>
    </div>

    <div class="card">
      <h2>🧠 Business & System Ideas</h2>
      <p>New ways to organize, communicate, and grow using technology.</p>
    </div>

    <div class="card">
      <h2>📘 Learning Log</h2>
      <p>My journey in electronics, coding, and innovation.</p>
    </div>
  </section>

  <script>
    function showMessage() {
      alert("This website is my digital lab where I experiment, learn, and build future ideas.");
    }
  </script>

</body>
</html>
