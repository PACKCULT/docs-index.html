<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>PACK CULT</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      min-height: 100vh;
      background:
        radial-gradient(circle at 50% 0%, #333 0%, #111 35%, #050505 75%);
      color: #fff;
      font-family: Arial, Helvetica, sans-serif;
      display: flex;
      justify-content: center;
      padding: 45px 20px;
    }

    .container {
      width: 100%;
      max-width: 430px;
      text-align: center;
    }

    .logo {
      width: 115px;
      height: 115px;
      margin: 0 auto 22px;
      border-radius: 50%;
      background: #fff;
      color: #050505;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 32px;
      font-weight: 900;
      letter-spacing: -2px;
      box-shadow:
        0 0 0 4px #222,
        0 0 35px rgba(255,255,255,0.15);
    }

    .brand {
      font-size: 32px;
      font-weight: 900;
      letter-spacing: 6px;
      margin-bottom: 10px;
    }

    .tagline {
      color: #999;
      font-size: 14px;
      letter-spacing: 2px;
      margin-bottom: 35px;
    }

    .button {
      display: flex;
      align-items: center;
      justify-content: center;
      position: relative;

      width: 100%;
      height: 62px;

      margin: 15px 0;

      border: 1px solid #333;
      border-radius: 16px;

      background: linear-gradient(
        135deg,
        #1c1c1c,
        #090909
      );

      color: #fff;
      text-decoration: none;

      font-size: 16px;
      font-weight: bold;
      letter-spacing: 1px;

      transition: all 0.25s ease;

      box-shadow:
        0 8px 25px rgba(0,0,0,0.45);
    }

    .button:hover {
      transform: translateY(-3px);
      border-color: #777;

      background: linear-gradient(
        135deg,
        #292929,
        #111
      );

      box-shadow:
        0 12px 30px rgba(0,0,0,0.7);
    }

    .button:active {
      transform: scale(0.97);
    }

    .arrow {
      position: absolute;
      right: 20px;
      font-size: 20px;
      color: #777;
    }

    .note {
      margin-top: 30px;
      color: #666;
      font-size: 12px;
      letter-spacing: 1px;
    }

    .footer {
      margin-top: 45px;
      padding-top: 20px;
      border-top: 1px solid #222;
      color: #555;
      font-size: 11px;
      letter-spacing: 2px;
    }

    @media (max-width: 480px) {
      body {
        padding-top: 35px;
      }

      .brand {
        font-size: 27px;
      }

      .button {
        height: 60px;
      }
    }
  </style>
</head>

<body>

  <div class="container">

    <div class="logo">
      PC
    </div>

    <div class="brand">
      PACK CULT
    </div>

    <div class="tagline">
      เท่ได้ • BE YOUR STYLE
    </div>

    <a
      class="button"
      href="https://www.facebook.com/share/1DVBxNLHAD/"
      target="_blank"
      rel="noopener noreferrer"
    >
      FACEBOOK
      <span class="arrow">›</span>
    </a>

    <a
      class="button"
      href="https://www.instagram.com/packcult.shop?igsh=ZDZybXI2cXV6ZGNs"
      target="_blank"
      rel="noopener noreferrer"
    >
      INSTAGRAM
      <span class="arrow">›</span>
    </a>

    <div class="note">
      FOLLOW PACK CULT
    </div>

    <div class="footer">
      PACK CULT © 2026
    </div>

  </div>

</body>
</html>
