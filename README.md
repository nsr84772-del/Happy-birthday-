<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy Birthday - Avengers Initiative</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700;900&family=Rajdhani:wght@500;600;700&display=swap" rel="stylesheet">
  <style>
    /* MARVEL / STARK INDUSTRIES THEME ENGINE */
    :root {
      --stark-red: #8B0000;
      --stark-gold: #FFD700;
      --arc-blue: #00f3ff;
      --dark-bg: #0a0c10;
      --card-bg: rgba(20, 25, 35, 0.85);
      --glass-border: rgba(255, 215, 0, 0.3);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background-color: var(--dark-bg);
      background-image: 
        radial-gradient(circle at 50% 20%, rgba(139, 0, 0, 0.3) 0%, transparent 60%),
        radial-gradient(circle at 80% 80%, rgba(0, 243, 255, 0.15) 0%, transparent 50%);
      color: #ffffff;
      font-family: 'Rajdhani', sans-serif;
      min-height: 100vh;
      overflow-x: hidden;
      padding-bottom: 50px;
    }

    /* Comic Book Pattern Overlay */
    .comic-overlay {
      position: fixed;
      top: 0; left: 0; width: 100%; height: 100%;
      background-image: radial-gradient(rgba(255, 255, 255, 0.05) 1px, transparent 0);
      background-size: 12px 12px;
      pointer-events: none;
      z-index: 1;
    }

    .container {
      max-width: 600px;
      margin: 0 auto;
      padding: 20px;
      position: relative;
      z-index: 2;
    }

    /* TOP LOGO BANNER */
    .marvel-header {
      text-align: center;
      margin-top: 10px;
      margin-bottom: 25px;
    }

    .marvel-logo {
      background-color: #E23636;
      color: #FFF;
      font-family: 'Orbitron', sans-serif;
      font-weight: 900;
      font-size: 2.2rem;
      letter-spacing: -1px;
      padding: 4px 18px;
      display: inline-block;
      text-transform: uppercase;
      box-shadow: 0 0 15px rgba(226, 54, 54, 0.6);
      border: 2px solid #fff;
    }

    .jarvis-badge {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      background: rgba(0, 243, 255, 0.1);
      border: 1px solid var(--arc-blue);
      color: var(--arc-blue);
      padding: 6px 14px;
      border-radius: 20px;
      font-size: 0.85rem;
      font-family: 'Orbitron', sans-serif;
      margin-top: 15px;
      letter-spacing: 1px;
    }

    /* HERO SECTION */
    .hero-card {
      background: var(--card-bg);
      border: 1px solid var(--glass-border);
      border-radius: 20px;
      padding: 30px 20px;
      text-align: center;
      position: relative;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
      backdrop-filter: blur(10px);
      margin-bottom: 30px;
    }

    .arc-reactor {
      
# Happy-birthday-
