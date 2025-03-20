# digiSIKHO-POSTER
Learning platform for everyone 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DigiSikho Poster</title>
  <!-- Google Fonts for a modern look -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    /* Reset & Global Styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      font-family: 'Poppins', sans-serif;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      overflow: hidden;
      color: #fff;
    }
    /* Poster Container */
    .poster {
      background: rgba(255, 255, 255, 0.15);
      backdrop-filter: blur(10px);
      border-radius: 15px;
      padding: 40px 50px;
      max-width: 600px;
      width: 90%;
      text-align: center;
      position: relative;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .poster:hover {
      transform: translateY(-10px);
      box-shadow: 0 15px 40px rgba(0, 0, 0, 0.5);
    }
    /* Header Section */
    .header {
      margin-bottom: 25px;
    }
    .header h1 {
      font-size: 3rem;
      letter-spacing: 3px;
      color: #f0a500;
      margin-bottom: 10px;
    }
    .header p {
      font-size: 1.3rem;
      font-style: italic;
      color: #d1e8e2;
    }
    /* Content Section */
    .content h2 {
      font-size: 1.8rem;
      margin-bottom: 15px;
      padding-bottom: 5px;
      border-bottom: 2px solid rgba(240, 165, 0, 0.7);
    }
    .content ul {
      list-style: none;
      text-align: left;
      margin: 20px 0;
      padding-left: 20px;
    }
    .content ul li {
      margin: 12px 0;
      padding-left: 30px;
      position: relative;
      line-height: 1.6;
      transition: transform 0.2s ease, color 0.2s ease;
      cursor: pointer;
    }
    .content ul li::before {
      content: "✔";
      position: absolute;
      left: 0;
      color: #f0a500;
      font-size: 1.2rem;
      transition: transform 0.2s ease;
    }
    .content ul li:hover {
      transform: translateX(5px);
      color: #ffc107;
    }
    .content ul li:hover::before {
      transform: scale(1.2);
    }
    /* Call-to-Action */
    .cta {
      margin-top: 25px;
    }
    .cta a {
      display: inline-block;
      background: #f0a500;
      color: #203a43;
      padding: 15px 30px;
      border-radius: 50px;
      font-size: 1.2rem;
      text-decoration: none;
      transition: background 0.3s ease, transform 0.3s ease;
    }
    .cta a:hover {
      background: #ffc107;
      transform: scale(1.05);
    }
    /* Footer Section */
    .footer {
      margin-top: 30px;
      font-size: 1rem;
      color: #d1e8e2;
    }
    /* Decorative Elements */
    .floating {
      position: absolute;
      opacity: 0.2;
      animation: float 6s ease-in-out infinite;
    }
    .floating.circle {
      width: 100px;
      height: 100px;
      background: #f0a500;
      border-radius: 50%;
      top: -50px;
      right: -50px;
    }
    .floating.square {
      width: 60px;
      height: 60px;
      background: #ffc107;
      top: 80%;
      left: -30px;
      transform: rotate(45deg);
      animation-duration: 8s;
    }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(15px); }
    }
  </style>
</head>
<body>
  <div class="poster">
    <!-- Decorative Floating Elements -->
    <div class="floating circle"></div>
    <div class="floating square"></div>
    
    <!-- Header -->
    <div class="header">
      <h1>DigiSikho</h1>
      <p>"Learn With Us"</p>
    </div>
    
    <!-- Content -->
    <div class="content">
      <h2>Master Computer Skills Online</h2>
      <ul>
        <li>Beginner-Friendly Courses</li>
        <li>Advanced Modules in Coding &amp; Web Development</li>
        <li>Hands-On Learning with Live Projects</li>
        <li>Free Demo Class to Experience Our Teaching</li>
        <li>Study from the Comfort of Your Home</li>
      </ul>
    </div>
    
    <!-- Call-to-Action -->
    <div class="cta">
      <a href="tel:9773821899">Call/WhatsApp: 9773821899</a>
    </div>
    
    <!-- Footer -->
    <div class="footer">
      DigiSikho – Learn, Grow, and Succeed!
    </div>
  </div>
</body>
</html>
