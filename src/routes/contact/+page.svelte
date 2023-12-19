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
      <p>If you have any ideas or want collaboration with our company, contact us via email</p>
      <p>kadamshoes@gmail.com</p>
    </section>
  
    <footer id="site-footer">
      <p>&copy; 2023 KADAM All rights reserved.</p>
      <div class="social-icons">
        <a href="https://facebook.com/yourpage" target="_blank"><img src="https://q-media.ru/images/2021/10/27/1576058917-facebooklogo.jpg" alt="Facebook" style="width: 30px; height: 30px;"></a>
        <a href="https://instagram.com/yourusername" target="_blank"><img src="https://avatars.mds.yandex.net/i?id=ff3558841d54e3766cb612b3b84644e1274ab13f-11386386-images-thumbs&n=13" alt="Instagram" style="width: 30px; height: 30px;"></a>
      </div>
    </footer>
  </div>
  