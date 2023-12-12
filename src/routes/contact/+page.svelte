<!-- routes/contacts/Contacts.svelte -->
<script>
    // Contacts-specific logic
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
  
    .options {
      display: flex;
      flex-direction: column;
      align-items: stretch;
      margin-top: 50px;
      background-color: #ffffff;
      padding: 20px;
    }
  
    .options h2 {
      align-self: center;
      font-size: 60px;
      text-align: center;
    }
  
    .options h3 {
      align-self: center;
      font-size: 30px;
    }
  
    .option {
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 50px;
      gap: 50px;
    }
  
    .option.reverse {
      flex-direction: row-reverse;
      background-color: rgb(255, 255, 255);
    }
  
    .options .option p {
      font-size: 23px;
    }
  
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 10px;
      width: 100%;
    }
  
    .social-icons {
      margin-top: 10px;
    }
  
    .social-icons a {
      margin: 0 10px;
      color: white;
      text-decoration: none;
    }
  </style>
  
  <div>
    <section class="page" id="contact">
      <h2>Contact Us</h2>
      <p>For further details on your orders or any inquiries, feel free to get in touch with us...</p>
      <p>Call us anytime at: +996 123 456 789</p>
    </section>
  
    <section class="options">
      <h2>Choose the Perfect Shoes for You and Your Family!</h2>
  
      <div class="option">
        <img src="https://example.com/mens-shoes.jpg" alt="Men's Shoes">
        <h3>Men's Shoes</h3>
        <p>$145</p>
        <p>Explore our collection of men's shoes and pick the perfect size and color for your order.</p>
      </div>
  
      <div class="option reverse">
        <img src="https://example.com/womens-shoes.jpg" alt="Women's Shoes">
        <div>
          <h3>Women's Shoes</h3>
          <p>$150</p>
          <p>Discover elegant and comfortable women's shoes for various occasions and different models.</p>
        </div>
      </div>
  
      <div class="option">
        <img src="https://example.com/kids-shoes.jpg" alt="Kid's Shoes">
        <div>
          <h3>Kid's Shoes</h3>
          <p>$145</p>
          <p>Give your little ones the joy of taking their first steps with our adorable collection of kid's shoes.</p>
        </div>
      </div>
    </section>
  
    <footer>
      <p>&copy; 2023 KADAM reserved.</p>
      <div class="social-icons">
        <a href="https://facebook.com/yourpage" target="_blank">Facebook</a>
        <a href="https://instagram.com/yourusername" target="_blank">Instagram</a>
      </div>
    </footer>
  </div>
  