<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Experience Enabler Deck</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    :root {
      --bg-dark: #1e1e1e;
      --text-light: #f5f5f5;
      --accent-beige: #f5deb3;
      --accent-brown: #c49a6c;
    }
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--bg-dark);
      color: var(--text-light);
      overflow-x: hidden;
    }
    .slide {
      height: 100vh;
      padding: 60px 40px;
      box-sizing: border-box;
      display: flex;
      flex-direction: column;
      justify-content: center;
      scroll-snap-align: start;
      border-bottom: 1px solid #444;
    }
    .title-slide {
      background: linear-gradient(135deg, #2c2c2c, #1e1e1e);
      text-align: center;
    }
    h1, h2 {
      color: var(--accent-beige);
    }
    h1 {
      font-size: 3rem;
    }
    h3 {
      color: var(--accent-brown);
      font-weight: normal;
    }
    ul {
      margin-top: 10px;
      padding-left: 1.2rem;
      line-height: 1.6;
    }
    .icon {
      width: 50px;
      height: 50px;
      vertical-align: middle;
      margin-right: 10px;
    }
    .slide-content {
      display: flex;
      gap: 30px;
      flex-wrap: wrap;
      align-items: center;
    }
    .text-box {
      flex: 1;
      min-width: 300px;
    }
    .image-box img {
      max-width: 300px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.4);
    }
    html {
      scroll-snap-type: y mandatory;
      scroll-behavior: smooth;
    }
  </style>
</head>
<body>

  <!-- Slide 1: Title -->
  <div class="slide title-slide">
    <h1>🔁 Evolving the Role of Experience Enablers</h1>
    <h3>Modern, Empathetic & Data-Led Approaches</h3>
    <p>By: [Your Name]</p>
  </div>

  <!-- Slide 2 -->
  <div class="slide">
    <div class="slide-content">
      <div class="text-box">
        <h2>🗣️ Reverse Feedback Connects</h2>
        <ul>
          <li>Let employees ask Enablers questions.</li>
          <li>Encourages openness and two-way growth.</li>
          <li>Reveals blind spots in culture and policy.</li>
        </ul>
      </div>
      <div class="image-box">
        <img src="https://cdn-icons-png.flaticon.com/512/1250/1250615.png" alt="Reverse Feedback Icon">
      </div>
    </div>
  </div>

  <!-- Slide 3 -->
  <div class="slide">
    <div class="slide-content">
      <div class="text-box">
        <h2>👥 Experience Personas</h2>
        <ul>
          <li>Fictional profiles of employees by role or emotion.</li>
          <li>Helps tailor solutions and communication styles.</li>
          <li>Example: "Aman the New Joiner" – needs onboarding clarity.</li>
        </ul>
      </div>
      <div class="image-box">
        <img src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png" alt="Personas Icon">
      </div>
    </div>
  </div>

  <!-- Slide 4 -->
  <div class="slide">
    <div class="slide-content">
      <div class="text-box">
        <h2>💡 EQ Training for Enablers</h2>
        <ul>
          <li>Monthly mini-sessions on emotional intelligence.</li>
          <li>Topics: body language, active listening, burnout spotting.</li>
          <li>Helps Enablers offer safe and trusted conversations.</li>
        </ul>
      </div>
      <div class="image-box">
        <img src="https://cdn-icons-png.flaticon.com/512/1738/1738696.png" alt="EQ Icon">
      </div>
    </div>
  </div>

  <!-- Slide 5 -->
  <div class="slide">
    <div class="slide-content">
      <div class="text-box">
        <h2>📹 Voice of Employee Snippets</h2>
        <ul>
          <li>Capture real feedback via short videos or quotes.</li>
          <li>Humanizes data and increases empathy with leadership.</li>
          <li>Perfect for leadership reviews or newsletters.</li>
        </ul>
      </div>
      <div class="image-box">
        <img src="https://cdn-icons-png.flaticon.com/512/5023/5023463.png" alt="Video Icon">
      </div>
    </div>
  </div>

  <!-- Slide 6 -->
  <div class="slide">
    <div class="slide-content">
      <div class="text-box">
        <h2>🔍 Vertical-Based Experience Audits</h2>
        <ul>
          <li>Enablers rotate across verticals instead of teams.</li>
          <li>Verticals: Tech, Facilities, Wellbeing, Onboarding.</li>
          <li>Drives cross-learning and real-time improvements.</li>
        </ul>
      </div>
      <div class="image-box">
        <img src="https://cdn-icons-png.flaticon.com/512/4359/4359978.png" alt="Audit Icon">
      </div>
    </div>
  </div>

  <!-- Slide 7 -->
  <div class="slide">
    <div class="slide-content">
      <div class="text-box">
        <h2>🌟 Micro‑Wins Board</h2>
        <ul>
          <li>Track and celebrate daily small actions by Enablers.</li>
          <li>Use a leaderboard, physical board, or digital tracker.</li>
          <li>Boosts visibility and morale for low-effort, high-impact fixes.</li>
        </ul>
      </div>
      <div class="image-box">
        <img src="https://cdn-icons-png.flaticon.com/512/3524/3524634.png" alt="Wins Icon">
      </div>
    </div>
  </div>

  <!-- Slide 8 -->
  <div class="slide">
    <div class="slide-content">
      <div class="text-box">
        <h2>✅ Summary & Next Steps</h2>
        <ul>
          <li>Pick 2–3 ideas and try them in your vertical.</li>
          <li>Assign Enabler leads per initiative.</li>
          <li>Collect learnings & share with wider team.</li>
        </ul>
      </div>
      <div class="image-box">
        <img src="https://cdn-icons-png.flaticon.com/512/2910/2910790.png" alt="Summary Icon">
      </div>
    </div>
  </div>

</body>
</html>