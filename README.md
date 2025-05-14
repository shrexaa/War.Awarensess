# War.Awarensess
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ministry of Defence – War Alert</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      background: #fdfdfd;
      color: #212529;
      margin: 0;
    }
    header {
      background: linear-gradient(90deg, #dc3545, #a71d2a);
      color: white;
      padding: 1.5rem 0;
      text-align: center;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }
    .header-title {
      font-size: 2rem;
      font-weight: bold;
      margin: 0.5rem 0;
      text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.3);
    }
    .logo {
      height: 80px;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffc107;
    }
    section {
      margin: 3rem 0;
    }
    .card {
      border: none;
      border-radius: 20px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .card:hover {
      transform: scale(1.01);
    }
    .card h2 {
      font-size: 1.6rem;
      border-left: 6px solid #007bff;
      padding-left: 10px;
    }
    .accordion-button:not(.collapsed) {
      background-color: #007bff;
      color: white;
    }
    iframe, img {
      border-radius: 16px;
      width: 100%;
      margin-top: 1rem;
    }
    footer {
      background: #212529;
      color: white;
      text-align: center;
      padding: 1.5rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/4f/Flag_of_the_Ministry_of_Defence_of_India.svg" alt="Ministry of Defence Logo" class="logo">
    <h1 class="header-title">DEFENCE DEPARTMENT – GOVERNMENT OF INDIA</h1>
    <nav class="container d-flex justify-content-center flex-wrap">
      <a href="#">Home</a>
      <a href="#guidelines">Guidelines</a>
      <a href="#map">Safe Zones</a>
      <a href="#media">Media</a>
      <a href="#contacts">Contact</a>
    </nav>
  </header>

  <main class="container">
    <section class="card p-4">
      <h2>🚨 Emergency Alert</h2>
      <p class="fs-5">Please follow official sources for updates: Doordarshan, AIR News, and the Ministry's verified social media channels. Avoid misinformation and maintain calm.</p>
    </section>

    <section class="accordion mt-5" id="guidelines">
      <div class="accordion-item">
        <h2 class="accordion-header">
          <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#dosCollapse" aria-expanded="true">
            ✅ Do's
          </button>
        </h2>
        <div id="dosCollapse" class="accordion-collapse collapse show">
          <div class="accordion-body">
            <ul class="list-group list-group-flush">
              <li class="list-group-item">Stay indoors during air raid sirens or alerts.</li>
              <li class="list-group-item">Keep emergency supplies ready.</li>
              <li class="list-group-item">Charge your communication devices.</li>
              <li class="list-group-item">Assist elderly, women and children.</li>
              <li class="list-group-item">Keep documents and identity proofs accessible.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="accordion-item">
        <h2 class="accordion-header">
          <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#dontsCollapse">
            🚫 Don'ts
          </button>
        </h2>
        <div id="dontsCollapse" class="accordion-collapse collapse">
          <div class="accordion-body">
            <ul class="list-group list-group-flush">
              <li class="list-group-item">Do not share troop movement info on social media.</li>
              <li class="list-group-item">Avoid spreading panic or unverified news.</li>
              <li class="list-group-item">Do not ignore government advisories.</li>
              <li class="list-group-item">Avoid unnecessary travel.</li>
              <li class="list-group-item">Don’t use drones or RC gadgets.</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <section id="map" class="card p-4 mt-5">
      <h2>📍 Safe Zone Map</h2>
      <p>View red-alert and safe zones below. Follow local instructions in high-risk areas.</p>
      <iframe src="https://www.google.com/maps/d/u/0/embed?mid=1C3ZbfbIO2g9iw0odkM6IvM-nUSgwiEw&ehbc=2E312F" height="450"></iframe>
    </section>

    <section id="media" class="row g-4 mt-5">
      <div class="col-md-6">
        <div class="card p-3">
          <h2>🇮🇳 Armed Forces Highlights</h2>
          <img src="https://upload.wikimedia.org/wikipedia/commons/2/26/INS_Chennai_Missile_Firing.jpg" alt="Missile Launch">
          <p>Visual of recent exercises showcasing defense readiness.</p>
        </div>
      </div>
      <div class="col-md-6">
        <div class="card p-3">
          <h2>🎥 Official Briefing</h2>
          <iframe src="https://www.youtube.com/embed/kd-shpfeSb4" frameborder="0" allowfullscreen></iframe>
        </div>
      </div>
    </section>

    <section id="contacts" class="card p-4 mt-5">
      <h2>📞 Emergency Contacts</h2>
      <ul class="list-group">
        <li class="list-group-item">Police: 100</li>
        <li class="list-group-item">Ambulance: 102</li>
        <li class="list-group-item">Fire Brigade: 101</li>
        <li class="list-group-item">Unified Emergency: 112</li>
        <li class="list-group-item">War Emergency Helpline: 1800-111-999</li>
      </ul>
    </section>

    <section class="card p-4 mt-5">
      <h2>📚 Trusted Resources</h2>
      <ul>
        <li><a href="https://mod.gov.in" target="_blank">Ministry of Defence Official Portal</a></li>
        <li><a href="https://www.ndma.gov.in" target="_blank">National Disaster Management Authority</a></li>
        <li><a href="https://www.youtube.com/@MinistryofDefenceIndia" target="_blank">MoD YouTube</a></li>
        <li><a href="https://twitter.com/DefenceMinIndia" target="_blank">MoD Twitter Updates</a></li>
      </ul>
    </section>
  </main>

  <footer>
    &copy; 2025 Government of India – Ministry of Defence. All rights reserved.
  </footer>
</body>
</html>
