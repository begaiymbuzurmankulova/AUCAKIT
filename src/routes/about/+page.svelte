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
  
    <section class="alternate-section">
      <div class="alternate-block">
        <div class="alternate-image">
          <img src="https://example.com/image1.jpg" alt="Image 1">
        </div>
        <div class="alternate-content">
          <h2 class="alternate-h2">Heading 1</h2>
          <p class="alternate-p">Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
        </div>
      </div>
  
      <div class="alternate-block reverse">
        <div class="alternate-image">
          <img src="https://example.com/image2.jpg" alt="Image 2">
        </div>
        <div class="alternate-content">
          <h2 class="alternate-h2">Heading 2</h2>
          <p class="alternate-p">Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua...</p>
        </div>
      </div>
    </section>
  
    <footer>
      <p>&copy; 2023 KADAM All rights reserved.</p>
      <div class="social-icons">
        <a href="https://facebook.com/yourpage" target="_blank">Facebook</a>
        <a href="https://instagram.com/yourusername" target="_blank">Instagram</a>
      </div>
    </footer>
  </div>
  
  