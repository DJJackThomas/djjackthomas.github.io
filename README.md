<!DOCTYPE html>
<html lang="da">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>DJ Jack Thomas — Booking</title>

  <style>
    * { box-sizing: border-box; }

    html, body {
      margin: 0;
      padding: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
                   Roboto, Helvetica, Arial, sans-serif;
      color: #ffffff;
      scroll-behavior: smooth;
      background:
        radial-gradient(1200px 700px at 20% 25%, rgba(168,0,255,0.18), transparent 55%),
        radial-gradient(900px 600px at 80% 75%, rgba(0,255,204,0.10), transparent 55%),
        linear-gradient(135deg, #0a0a0a 0%, #111111 40%, #000000 100%);
      min-height: 100vh;
    }

    .container {
      padding: 80px 60px;
      max-width: 800px;
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 14px;
    }

    .subtitle {
      font-size: 1.2rem;
      opacity: 0.8;
      margin-bottom: 24px;
    }

    .cta {
      display: inline-block;
      margin-bottom: 40px;
      padding: 14px 26px;
      background: #ffffff;
      color: #000;
      font-weight: 700;
      border-radius: 999px;
      text-decoration: none;
      transition: 0.2s ease;
    }

    .cta:hover { opacity: 0.9; }

    ul {
      list-style: none;
      padding: 0;
      margin: 20px 0 30px 0;
      opacity: 0.75;
    }

    ul li { margin-bottom: 8px; }

    .social a {
      margin-right: 16px;
      color: rgba(255,255,255,0.7);
      text-decoration: none;
    }

    .social a:hover {
      color: #ffffff;
    }

    .contact {
      margin: 20px 0 50px 0;
      opacity: 0.75;
    }

    .card {
      padding: 24px;
      border-radius: 20px;
      border: 1px solid rgba(255,255,255,0.15);
      background: rgba(255,255,255,0.05);
      backdrop-filter: blur(10px);
      max-width: 700px;
    }

    footer {
      margin-top: 80px;
      opacity: 0.4;
      font-size: 0.85rem;
    }

    @media (max-width: 768px) {
      .container { padding: 60px 25px; }
      h1 { font-size: 2.3rem; }
    }
  </style>
</head>

<body>

  <div class="container">

    <h1>DJ Jack Thomas</h1>
    <p class="subtitle">Baseret i København, kører ud til hele Sjælland.
    <p Klubber, festivaler & private events</p>

    <a href="#booking" class="cta">Book nu</a>

    <ul>
      <li>• Private events</li>
      <li>• Firmaarrangementer</li>
      <li>• Klub- & festivalbookinger</li>
      <li>• International tilgængelighed</li>
    </ul>

    <div class="social">
      <a href="https://www.instagram.com/jackreimannjensen" target="_blank">Instagram</a>
      <a href="https://soundcloud.com/YOURPROFILE" target="_blank">SoundCloud</a>
      <a href="https://mixcloud.com/YOURPROFILE" target="_blank">Mixcloud</a>
    </div>

    <div class="contact">
      Booking: <a href="mailto:jrj87@live.com" style="color:white;">jrj87@live.com</a>
    </div>

    <div id="booking" class="card">
      <h2>Send en bookingforespørgsel</h2>

      <iframe
        id="JotFormIFrame-260403565752052"
        title="DJ Booking Inquiry Form"
        onload="window.parent.scrollTo(0,0)"
        allowtransparency="true"
        allow="geolocation; microphone; camera; fullscreen; payment"
        src="https://form.jotform.com/260403565752052"
        frameborder="0"
        style="min-width:100%;max-width:100%;height:539px;border:none;"
        scrolling="no">
      </iframe>

      <script src="https://cdn.jotfor.ms/s/umd/latest/for-form-embed-handler.js"></script>
      <script>
        window.jotformEmbedHandler(
          "iframe[id='JotFormIFrame-260403565752052']",
          "https://form.jotform.com/"
        );
      </script>

    </div>

    <footer>© 2026 DJ Jack Thomas</footer>

  </div>

</body>
</html>
