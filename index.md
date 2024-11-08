<style>
  /* General page layout */
  body, html {
    margin: 0;
    padding: 0;
    height: 100%;
    display: flex;
    flex-direction: row; /* Horizontal layout */
    overflow: hidden; /* Prevents scrollbars */
    font-family: Arial, sans-serif;
  }

  /* Sidebar container */
  .sidebar-container {
    width: 300px; /* Fixed width for the sidebar */
    background-color: #f8f9fa; /* Light background for contrast */
    padding: 20px;
    box-sizing: border-box;
    overflow-y: auto; /* Enable scrolling for overflow content */
  }

  .sidebar-container h1 {
    margin: 0 0 10px 0;
    font-size: 24px;
    color: #333;
  }

  .sidebar-container p, .sidebar-container h2 {
    font-size: 14px;
    color: #555;
    margin: 10px 0;
  }

  /* Main iframe container */
  .iframe-container {
    flex-grow: 1; /* Take up the remaining width */
    height: 100%;
    overflow: hidden; /* No scrollbars */
    display: flex;
    justify-content: center;
    align-items: center;
  }

  iframe {
    border: none;
    width: 100%; /* Full width of the iframe container */
    height: 100%; /* Full height of the iframe container */
  }
</style>

<div class="sidebar-container">
  <h1>pwa-windsurf-stats</h1>
  <p>The aim of this project was to provide rider, event, and results stats from the 2024 PWA Gran Canaria event.</p>
  <h2>Plans for the Future</h2>
  <p>
    My plan is to scrape all data for 2025 competitions as they happen and post the results here. I also hope to extend this report to include slalomX, foil slalom, and freestyle competitions.
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

<div class="iframe-container">
  <iframe 
      title="POZO Report Wave & Slalom v5 Wave Only" 
      src="https://app.powerbi.com/view?r=eyJrIjoiM2I4MWJhYjQtMTdmMC00OGE2LTk3MWItMzMyNTg0NTg1MTJlIiwidCI6IjRlNDc4YWIwLWFjYWUtNGRiNS1hYjA4LTQ0ZjdlOTliNDc1MiJ9" 
      allowfullscreen="true">
  </iframe>
</div>
