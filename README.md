<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Regenesis – Eco Reproduction Dashboard</title>
  <style>
    :root {
      --primary-bg: #D3E5E4;
      --primary-dark: #2E635C;
      --card-bg: #ffffff;
      --text-dark: #2C2C2C;
      --accent: #6BA99C;
      --radius: 16px;
    }

    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background-color: var(--primary-bg);
      color: var(--text-dark);
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
      background-color: #B6D2CD;
    }

    header h1 {
      font-size: 1.5rem;
      margin: 0;
    }

    nav button, select {
      background-color: var(--primary-dark);
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: var(--radius);
      cursor: pointer;
      font-size: 0.9rem;
    }

    .container {
      padding: 2rem;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 2rem;
    }

    .card {
      background: var(--card-bg);
      border-radius: var(--radius);
      padding: 1.5rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.06);
    }

    .card h2 {
      margin-top: 0;
      font-size: 1.2rem;
      color: var(--primary-dark);
    }

    .score {
      font-size: 3rem;
      color: var(--primary-dark);
      font-weight: bold;
    }

    .footer {
      text-align: center;
      padding: 1rem;
      font-size: 0.8rem;
      color: #666;
    }
  </style>
</head>
<body>
  <header>
    <h1>🌿 Regenesis</h1>
    <nav>
      <select>
        <option>United States</option>
        <option>China</option>
        <option>India</option>
      </select>
      <button>Log In</button>
    </nav>
  </header>

  <div class="container">
    <div class="card">
      <h2>Ecological Overview</h2>
      <p>🌎 Current Overshoot Status: <strong style="color:#A43131">Deficit</strong></p>
      <img src="https://via.placeholder.com/300x150" alt="Bar Chart" />
    </div>

    <div class="card">
      <h2>Your Eco Score</h2>
      <p class="score">85</p>
      <img src="https://via.placeholder.com/200x200" alt="Radar Chart" />
    </div>

    <div class="card">
      <h2>Reproductive Quota</h2>
      <p>🟢 Quota Granted</p>
      <p>🔗 Matched with: Eco ID #20491</p>
    </div>

    <div class="card">
      <h2>Suggestions for Improvement</h2>
      <ul>
        <li>Reduce meat consumption by 30%</li>
        <li>Use shared transport 3x/week</li>
        <li>Adopt a renewable energy plan</li>
      </ul>
    </div>
  </div>

  <div class="footer">
    Data powered by Global Footprint Network · Regenesis 2025
  </div>
</body>
</html>
