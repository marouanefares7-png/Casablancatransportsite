<html>
<head>
  <title>Marouane Luxury Tour</title>
  <style>
    body {
      font-family: 'Montserrat', sans-serif;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #000;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    section {
      padding: 20px;
      text-align: center;
    }
    form {
      max-width: 400px;
      margin: 0 auto;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
      text-align: left;
    }
    input, select {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      margin-top: 20px;
      padding: 10px;
      width: 100%;
      background-color: #000;
      color: #fff;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    button:hover {
      background-color: #333;
    }
    img {
      max-width: 600px;
      width: 100%;
      margin: 10px auto;
      display: block;
      border-radius: 8px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Marouane Luxury Tour</h1>
    <p>Book your private ride from Casablanca to any major city in Morocco</p>
    <p>📧 marouanefares7@gmail.com | 📞 +212621617643</p>
  </header>

  <section>
    <h2>Our Vehicles</h2>
    <img src="https://www.platinumautohaus.com/imagetag/14754/7/l/Used-2022-Mercedes-Benz-E-Class-E-350.jpg" alt="Mercedes E-Class Black">
    <img src="https://www.morocco-transport.com/wp-content/uploads/2020/11/vito-mercedes-.png" alt="Mercedes Vito Black">
  </section>

  <section>
    <h2>Discover Morocco</h2>
    <img src="https://trekbible.com/wp-content/uploads/2018/04/casablanca-2807439_1920.jpg" alt="Casablanca">
    <img src="https://wallpaperaccess.com/full/2172018.jpg" alt="Marrakech">
  </section>

  <section>
    <h2>Book Your Transfer</h2>
    <form action="mailto:marouanefares7@gmail.com" method="POST" enctype="text/plain">
      <label for="pickup">Pickup Address (Casablanca)</label>
      <input type="text" id="pickup" name="Pickup Address" placeholder="e.g. 12 Rue de Paris, Casablanca" required>

      <label for="destination">Destination</label>
      <select id="destination" name="Destination" required>
        <option value="Rabat">Rabat</option>
        <option value="Marrakech">Marrakech</option>
        <option value="Agadir">Agadir</option>
        <option value="Tangier">Tangier</option>
        <option value="Fes">Fes</option>
        <option value="Ouarzazate">Ouarzazate</option>
        <option value="Essaouira">Essaouira</option>
        <option value="Chefchaouen">Chefchaouen</option>
      </select>

      <label for="date">Transfer Date</label>
      <input type="date" id="date" name="Transfer Date" required>

      <label for="name">Your Name</label>
      <input type="text" id="name" name="Name" required>

      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" name="Phone" required>

      <button type="submit">Book Now</button>
    </form>
  </section>
</body>
</html>
`
