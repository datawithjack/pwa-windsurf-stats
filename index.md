<style>
  /* General page layout adjustments */
  body, html {
    margin: 0;
    padding: 0;
    height: 100%;
    overflow: hidden; /* Prevents scrolling */
    font-family: Arial, sans-serif;
  }

  .container-lg {
    margin: 0 !important;
    padding: 0 !important;
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
  }

  /* Title moved to the top-left */
  .header {
    position: absolute;
    top: 10px;
    left: 10px;
    background-color: rgba(255, 255, 255, 0.8);
    padding: 10px 20px;
    border-radius: 8px;
    z-index: 10; /* Make sure it stays above the iframe */
  }

  .header h1 {
    margin: 0;
    font-size: 24px;
  }

  .header p {
    margin: 5px 0 0;
    font-size: 14px;
    color: #555;
  }

  iframe {
    border: none;
    width: 100%;
    height: 100%;
  }

  /* Footer for additional details */
  .footer {
    position: absolute;
    bottom: 10px;
    left: 10px;
    background-color: rgba(255, 255, 255, 0.8);
    padding: 10px 20px;
    border-radius: 8px;
    z-index: 10; /* Above iframe */
    max-width: 300px;
  }

  .footer h2 {
    margin: 0;
    font-size: 16px;
  }

  .footer p {
    margin: 5px 0;
    font-size: 14px;
    color: #555;
  }

  .footer h3 {
    margin-top: 15px;
    font-size: 14px;
    color: #333;
  }
</style>

<div class="container-lg">
  <!-- Header -->
  <div class="header">
    <h1>pwa-windsurf-stats</h1>
    <p>The aim of this project was to give rider, event, and results stats from the 2024 PWA Gran Canaria event.</p>
  </div>

  <!-- Power BI Embed -->
  <iframe 
      title="POZO Report Wave & Slalom v5 Wave Only" 
      src="https://app.powerbi.com/view?r=eyJrIjoiM2I4MWJhYjQtMTdmMC00OGE2LTk3MWItMzMyNTg0NTg1MTJlIiwidCI6IjRlNDc4YWIwLWFjYWUtNGRiNS1hYjA4LTQ0ZjdlOTliNDc1MiJ9" 
      allowfullscreen="true">
  </iframe>

  <!-- Footer -->
  <div class="footer">
    <h2>Plans for the Future</h2>
    <p>My plan is to scrape all data for 2025 competitions as they happen and post the results here. I also hope to extend this report to include slalomX, foil slalom, and freestyle competitions.</p>
    
    <h3>Nerd Chat</h3>
    <p>This is a Power BI report embedded into a GitHub Pages site. Everything I'm using here is free and allows for quick iterations and easy updates to designs.</p>
    
    <h3>About</h3>
    <p>I'm Jack Andrew, and I love combining data and sports to create insightful projects like this one.</p>
  </div>
</div>
