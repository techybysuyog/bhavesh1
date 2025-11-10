<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Forest Landing Page</title>
  <link rel="stylesheet" href="drone.css" />
  <style>
    /* Navigation buttons */
    div {
      position: absolute;
      top: 20px;
      right: 20px;
    }
    div a {
      background-color: #00cc66;
      color: white;
      padding: 10px 18px;
      margin-left: 10px;
      text-decoration: none;
      border-radius: 6px;
      font-weight: bold;
      transition: 0.3s;
    }
    div a:hover {
      background-color: #00994d;
    }

    /* Center the Welcome box in the middle */
    header {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh; /* Full screen height */
      text-align: center;
    }

    header h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
      color: #006633;
    }

    header p {
      font-size: 1.2em;
      margin-bottom: 20px;
    }

    .btn {
      background-color: #00cc66;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 6px;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      background-color: #00994d;
    }
  </style>
</head>
<body>

  <div>
    <a href="login.html">Login</a>
    <a href="map.html">Map</a>
    <a href="alert.html">Alert</a>
    <a href="Dashboard.html">Dashboard</a>
  </div>
      
  <header>
    <h1>Welcome to GreenGuard AI</h1>
    <p>Smart Forest Monitoring and Reforestation System</p>
    <a href="#explore" class="btn">Explore Now</a>
  </header>

  <section id="explore">
    <h2>About</h2>
    <p>
      Deforestation is one of the biggest challenges facing our planet , leading to climate change , loss of biodiversity , and environmental imbalance. Traditional methods of forest monitoring and reforestation are slow , costly, and often ineffective in preventing large-scale damage. To address this , modern technology can provide smart and sustainable solutions.
      GreenGuard AI is a futuristic system that combines artificial intelligence, drones, and satellite data to protect and restore forests. The system continuously monitors forest areas, detects illegal activities, predicts risks , and supports reforestation using drone-based seed planting. It also offers a simple dashboard where authorities and communities can track forest health in real time.
      This project aims to create a smart, technology-driven approach to safeguard nature while making conservation efforts faster , transparent and more effective..
    </p>
  </section>

  <footer>
    <p>© 2025 Forest Adventures | All Rights Reserved</p>
  </footer>
</body>
</html>
div {
  position: fixed;
  top: 20px;
  right: 20px;
}
html {
  scroll-behavior: smooth;
}
