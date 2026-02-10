<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>García & Engstrøm — DJ</title>

  <style>
    * {
      box-sizing: border-box;
    }

    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
                   Roboto, Helvetica, Arial, sans-serif;
      color: #ffffff;
    }

    body {
      background: linear-gradient(
        135deg,
        #2f2f2f 0%,
        #3a332e 40%,
        #5a4634 100%
      );
    }

    .container {
      min-height: 100vh;
      display: flex;
      align-items: center;
      padding: 60px;
    }

    .content {
      max-width: 520px;
    }

    h1 {
      font-size: 3rem;
      font-weight: 600;
      margin: 0 0 20px 0;
    }

    .subtitle {
      font-size: 1.2rem;
      color: rgba(255,255,255,0.75);
      margin-bottom: 30px;
      line-height: 1.6;
    }

    ul {
      list-style: none;
      padding: 0;
      margin: 0 0 40px 0;
    }

    ul li {
      margin-bottom: 10px;
      color: rgba(255,255,255,0.7);
    }

    .social {
      display: flex;
      gap: 20px;
      margin-bottom: 20px;
    }

    .social a {
      color: rgba(255,255,255,0.6);
      text-decoration: none;
      font-size: 0.95rem;
      transition: color 0.2s ease;
    }

    .social a:hover {
      color: #ffffff;
    }

    .contact {
      font-size: 0.95rem;
      color: rgba(255,255,255,0.6);
    }

    .contact a {
      color: rgba(255,255,255,0.8);
      text-decoration: none;
    }

    .contact a:hover {
      text-decoration: underline;
    }

    footer {
      position: fixed;
      bottom: 20px;
      left: 60px;
      font-size: 0.8rem;
      color: rgba(255,255,255,0.4);
    }

    @media (max-width: 700px) {
      .container {
        padding: 40px 25px;
      }

      footer {
        left: 25px;
      }

      h1 {
        font-size: 2.4rem;
      }
    }
  </style>
</head>

<body>
  <div class="container">
    <div class="content">
      <h1>García & Engstrøm</h1>

      <div class="subtitle">
        DJs & selectors<br>
        Available for clubs, festivals & private events
      </div>

      <ul>
        <li>• House / Techno / Electronic</li>
        <li>• Club & festival bookings</li>
        <li>• Private & corporate events</li>
        <li>• International availability</li>
      </ul>

      <div class="social">
        <a href="https://instagram.com/YOURPROFILE" target="_blank">Instagram</a>
        <a href="https://soundcloud.com/YOURPROFILE" target="_blank">SoundCloud</a>
        <a href="https://mixcloud.com/YOURPROFILE" target="_blank">Mixcloud</a>
      </div>

      <div class="contact">
        Booking: <a href="mailto:booking@yourdomain.com">booking@yourdomain.com</a>
      </div>
    </div>
  </div>

  <footer>
    © 2026 García & Engstrøm
  </footer>
</body>
</html>

