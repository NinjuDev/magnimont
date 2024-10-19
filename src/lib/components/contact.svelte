<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f7f7f7;
    }

    .contact-section {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 50px;
      background-color: #fff;
    }

    .contact-left {
      flex: 1;
    }

    .contact-left h2 {
      color: #ffc107;
      font-size: 36px;
      font-weight: bold;
    }

    .contact-left p {
      margin: 10px 0 30px;
      font-size: 16px;
      color: #333;
    }

    .contact-form {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .contact-form input,
    .contact-form textarea {
      width: calc(50% - 10px);
      padding: 15px;
      border: 1px solid #ddd;
      border-radius: 5px;
      font-size: 16px;
    }

    .contact-form textarea {
      width: 100%;
      resize: none;
      height: 150px;
    }

    .contact-form input[type="submit"] {
      background-color: #ffc107;
      color: #fff;
      border: none;
      cursor: pointer;
      width: auto;
      padding: 10px 20px;
    }

    .contact-form input[type="submit"]:hover {
      background-color: #e0a800;
    }

    .contact-right {
      flex: 1;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .contact-right img {
      max-width: 300px;
      border-radius: 50%;
    }

    .disclaimer {
      font-size: 12px;
      color: #888;
      margin-top: 15px;
    }

    .disclaimer a {
      color: #ffc107;
      text-decoration: none;
    }

    .disclaimer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <div class="contact-section">
    <div class="contact-left">
      <h2>Contact Us & We Can Work Together</h2>
      <p>Ready to collaborate with a team of skilled developers? Drop us a line and let's discuss your project.</p>

      <form class="contact-form">
        <input type="text" name="name" placeholder="Name" required>
        <input type="text" name="phone" placeholder="Phone Number" required>
        <input type="email" name="email" placeholder="Email" required>
        <textarea name="message" placeholder="Message" required></textarea>
        
        <label>
          <input type="checkbox" required> I agree to be contacted by BearSecure org. via call, email, and text. To opt out, you can reply "stop" at any time or click the unsubscribe link in the emails. Message and data rates may apply. Messages frequency varies. <a href="#">Privacy Policy</a>.
        </label>
        
        <input type="submit" value="Submit Message">
      </form>

      <p class="disclaimer">
        <a href="#">Privacy Policy</a>
      </p>
    </div>

    <div class="contact-right">
      <img src="https://images-ext-1.discordapp.net/external/Fck1ccubcCLfJ_sL7BuIG3Q6c5uU_MFZ3XbEAme0jBQ/%3Fsize%3D512/https/cdn.discordapp.com/icons/876113814314164256/0e0f35f8cd793beefafbdec39382f1db.png" alt="Company Logo">
    </div>
  </div>

</body>
</html>
