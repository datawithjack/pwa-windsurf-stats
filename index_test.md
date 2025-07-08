<style>
  /* General page layout */
  body, html {
    margin: 0;
    padding: 0;
    height: 100%;
    width: 100%;
    overflow: hidden; /* Prevents scrollbars */
    font-family: Arial, sans-serif;
  }

  /* Sidebar styling */
  .sidebar-container {
    position: absolute;
    top: 0;
    left: 0;
    width: 300px; /* Fixed width for the sidebar */
    height: 100%; /* Full height of the viewport */
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

  /* Iframe container */
  .iframe-container {
    position: absolute;
    top: 0;
    left: 300px; /* Position next to the sidebar */
    right: 0;
    bottom: 0;
    overflow: hidden; /* No scrollbars */
  }

  iframe {
    width: 100%;
    height: 100%;
    border: none;
  }
</style>

<div class="sidebar-container">
  <h1>Gran Canaria PWA Event Insights</h1>
<p>
  This dashboard highlights rider performance, event stats, and results from the *2025* PWA Gran Canaria 'Pozo' Windsurf Event. Dive into the data behind one of the tour's most exciting competitions!
</p>
<br>
<h2>Future Plans</h2>
<p>
  I’ll be adding data for all 2025 PWA competitions, including SlalomX, Foil Slalom, and Freestyle events. Check back for fresh insights as the season unfolds.
</p>
<br>
<h2>Nerd Chat</h2>
<p>
  I scraped data from the PWA website using Python, loaded it into Power BI, and embedded the dashboard via GitHub Pages. This lightweight approach is cost-effective, simple, and ideal for quick updates.
</p>
<br>
<h2>About Me</h2>
<p>
  I'm Jack Andrew, a keen windsurfer and data analyst based in Doha, Qatar. I combine my passion for sports and data to create tools like this that bring performance insights to life.
</p>

</div>

<div class="iframe-container">
  <iframe 
      title="Pozo 2025 Report (Wave)" 
    src="https://app.powerbi.com/view?r=eyJrIjoiNGViODIwZmYtNGVlNy00ZTdjLWEzNmUtOTkxNjRjYzIwY2U0IiwidCI6IjRlNDc4YWIwLWFjYWUtNGRiNS1hYjA4LTQ0ZjdlOTliNDc1MiJ9" 
     
      allowfullscreen="true">
  </iframe>
</div>
