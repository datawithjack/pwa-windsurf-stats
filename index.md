<style>
  /* General page layout adjustments */
  body, html {
    margin: 0;
    padding: 0;
    height: 100%;
    overflow: hidden; /* Prevent scrolling */
    font-family: Arial, sans-serif;
  }

  /* Layout: Split screen */
  .container {
    display: flex;
    height: 100%;
    width: 100%;
  }

  /* Sidebar styling */
  .sidebar {
    width: 20%; /* Adjust width as needed */
    background-color: #f8f9fa; /* Light background for contrast */
    padding: 20px;
    box-sizing: border-box;
    overflow-y: auto; /* Allow scrolling if content overflows */
  }

  .sidebar h1 {
    margin: 0;
    font-size: 24px;
    color: #333;
  }

  .sidebar p {
    font-size: 14px;
    color: #555;
    margin-top: 10px;
  }

  /* Main content (iframe) */
  .main-content {
    flex-grow: 1; /* Take up remaining space */
    display: flex;
    justify-content: center;
    align-items: center;
  }

  iframe {
    border: none;
    width: 100%;
    height: 100%;
  }
</style>

<div class="container">
  <!-- Sidebar -->
  <div class="sidebar">
    <h1>pwa-windsurf-stats</h1>
    <p>
      The aim of this project was to provide rider, event, and results stats from the 2024 PWA Gran Canaria event.
    </p>
    <p>
      My plan is to scrape all data for 2025 competitions as they happen and post the results here. I also aim to extend the report to include slalomX, foil slalom, and freestyle events.
    </p>
    <h2>Nerd Chat</h2>
    <p>
      This project uses a Power BI report embedded into a GitHub Pages site. Everything here is free and simple to set up, allowing for quick iterations and design updates.
    </p>
    <h2>About</h2>
    <p>
      I'm Jack Andrew, and I love combining data and sports to create projects like this one.
    </p>
  </div>

  <!-- Main Content -->
  <div class="main-content">
    <iframe 
        title="POZO Report Wave & Slalom v5 Wave Only" 
        src="https://app.powerbi.com/view?r=eyJrIjoiM2I4MWJhYjQtMTdmMC00OGE2LTk3MWItMzMyNTg0NTg1MTJlIiwidCI6IjRlNDc4YWIwLWFjYWUtNGRiNS1hYjA4LTQ0ZjdlOTliNDc1MiJ9" 
        allowfullscreen="true">
    </iframe>
  </div>
</div>
