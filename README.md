# INDLIA-REFRIGATIONS
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>INDLIA REFRIGERATORS</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: 
        linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)),
        url('https://images.unsplash.com/photo-1619020227349-b8f47e1b13b7?auto=format&fit=crop&w=1600&q=80') no-repeat center center fixed;
      background-size: cover;
      color: white;
    }
    header {
      background: linear-gradient(to bottom right, #8e0000, #ff0000);
      padding: 20px;
      text-align: center;
      border: 5px solid gold;
    }
    header h1 {
      margin: 0;
      font-size: 2em;
      color: gold;
    }
    .logo {
      width: 100px;
      height: auto;
    }
    .container {
      padding: 20px;
      background-color: rgba(0, 0, 0, 0.6);
      margin: 20px;
      border: 3px solid gold;
      border-radius: 10px;
    }
    .section-title {
      font-size: 1.5em;
      color: gold;
      margin-bottom: 10px;
    }
    .options label,
    .locations label {
      display: block;
      margin: 8px 0;
    }
    .whatsapp-button {
      display: inline-block;
      background-color: #25D366;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }
    footer {
      background-color: rgba(0, 0, 0, 0.8);
      text-align: center;
      padding: 20px;
      border-top: 5px solid gold;
      margin-top: 40px;
    }
    .footer-text {
      font-style: italic;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://upload.wikimedia.org/wikipedia/commons/e/e0/BabaRamdev_Patanjali.png" alt="Baba Ramdev Logo" class="logo" />
    <h1>INDLIA REFRIGERATORS</h1>
  </header>

  <div class="container">
    <div class="section-title">Repairment Options</div>
    <div class="options">
      <label><input type="checkbox" /> AC</label>
      <label><input type="checkbox" /> Fridge</label>
      <label><input type="checkbox" /> Water Cooler</label>
      <label><input type="checkbox" /> Washing Machine</label>
      <label><input type="checkbox" /> Service</label>
    </div>

    <div class="section-title">Choose Service Type</div>
    <div class="options">
      <label><input type="radio" name="serviceType" /> Repair</label>
      <label><input type="radio" name="serviceType" /> Service</label>
    </div>

    <div class="section-title">Available at</div>
    <div class="locations">
      <label><input type="checkbox" /> Rajgarh</label>
      <label><input type="checkbox" /> Jaipur</label>
    </div>

    <br />
    <a href="https://wa.me/919828417496" class="whatsapp-button">Contact on WhatsApp</a>
  </div>

  <footer>
    <div class="footer-text">SHOP ADDRESS ⚠️:- J D A COLONY SANGANER JAIPUR</div>
    <div class="footer-text">HOME ADDRESS ⚠️:- INDIRA COLONY NEAR RS MEMORIAL SCHOOL</div>
    <div class="footer-text">WARNING ⚠️:- INSTANT PAYMENT NEEDED</div>
  </footer>
</body>
</html>
