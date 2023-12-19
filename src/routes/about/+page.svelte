<!-- routes/about/About.svelte -->
<script>
    // About-specific logic
  </script>
  
  <style>
    body, h1, p {
      margin: 0;
      padding: 0;
    }
  
    * {
      box-sizing: border-box;
    }
  
    .page {
      text-align: center;
      font-size: 20px;
      padding: 50px;
      background-color: #bbbbbb;
    }
  
    #about,
    #contact {
      margin-bottom: 0;
      padding: 80px 50px;
    }
  
    .cta-button {
      display: inline-block;
      padding: 12px 24px;
      background-color: #ffffff;
      color: #000000;
      text-decoration: none;
      border-radius: 6px;
      font-weight: bold;
      font-size: 20px;
      transition: background-color 0.3s ease;
    }
  
    .cta-button:hover {
      background-color: #fcfcfc;
    }
  
    .alternate-section {
      display: flex;
      flex-direction: column;
      background-color: #ffffff;
      color: #ffffff;
      padding: 20px;
    }
  
    .alternate-block {
      display: flex;
      flex-direction: row;
      justify-content: space-between;
      align-items: center;
      width: 100%;
    }
  
    .alternate-block:nth-child(even) {
      flex-direction: row-reverse;
    }
  
    .alternate-image {
      flex: 1;
      padding: 10px;
    }
  
    .alternate-image img {
      max-width: 100%;
      height: auto;
    }
  
    .alternate-content {
      flex: 1;
      padding: 10px;
    }
  
    .alternate-h2 {
      font-size: 24px;
    }
  
    .alternate-p {
      font-size: 16px;
    }
  </style>
  
  <div>
    <section class="page" id="about">
      <h2>About Us</h2>
      <p>Welcome to KADAM, your ultimate online destination for quality footwear. With a diverse collection sourced from different countries and brands...</p>
    </section>
  
    <footer id="site-footer">
      <p>&copy; 2023 KADAM All rights reserved.</p>
      <div class="social-icons">
        <a href="https://facebook.com/yourpage" target="_blank"><img src="https://q-media.ru/images/2021/10/27/1576058917-facebooklogo.jpg" alt="Facebook" style="width: 30px; height: 30px;"></a>
        <a href="https://instagram.com/yourusername" target="_blank"><img src="https://avatars.mds.yandex.net/i?id=ff3558841d54e3766cb612b3b84644e1274ab13f-11386386-images-thumbs&n=13" alt="Instagram" style="width: 30px; height: 30px;"></a>
      </div>
    </footer>
  </div>
  
  