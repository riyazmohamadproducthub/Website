index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Professional Website</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Single file production-ready website">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
    }

    body {
      color: #111;
      background: #fff;
      line-height: 1.6;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 18px 40px;
      background: #000;
      color: #fff;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    header nav a {
      color: #fff;
      text-decoration: none;
      margin-left: 24px;
      font-weight: 500;
    }

    .hero {
      min-height: 85vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 40px;
      background: linear-gradient(135deg, #000, #222);
      color: white;
    }

    .hero h1 {
      font-size: 3rem;
      max-width: 800px;
    }

    .hero p {
      margin-top: 16px;
      font-size: 1.2rem;
      max-width: 600px;
    }

    .hero button {
      margin-top: 28px;
      padding: 14px 32px;
      border: none;
      background: white;
      color: black;
      font-size: 1rem;
      cursor: pointer;
      border-radius: 6px;
    }

    section {
      padding: 70px 40px;
      max-width: 1200px;
      margin: auto;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 24px;
      margin-top: 40px;
    }

    .card {
      padding: 30px;
      border-radius: 10px;
      background: #f7f7f7;
      text-align: center;
      font-weight: 500;
    }

    .about {
      background: #fafafa;
      border-radius: 12px;
      padding: 50px;
    }

    form {
      max-width: 420px;
      margin: auto;
      display: flex;
      flex-direction: column;
    }

    form input, form textarea {
      padding: 12px;
      margin-bottom: 16px;
      border-radius: 6px;
      border: 1px solid #ccc;
    }

    form button {
      padding: 12px;
      background: black;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }

    footer {
      background: #000;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 60px;
    }

    @media (max-width: 768px) {
      .hero h1 {
        font-size: 2.2rem;
      }
    }
  </style>
</head>

<body>

<header>
  <strong>YourBrand</strong>
  <nav>
    <a href="#features">Features</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <h1>Build Once. Deploy Instantly. Scale Anytime.</h1>
  <p>A clean, professional website in a single file
