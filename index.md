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
  This project provides detailed insights into rider performance, event highlights, and results from the 2024 PWA Gran Canaria 'Pozo' Windsurf Event. Explore the trends and stats behind one of the most exciting stops on the tour!
</p>
<br> 
<h2>Future Plans</h2>
<p>
  I plan to scrape and analyze data from all 2025 PWA competitions as they happen, expanding this dashboard to include pages for SlalomX, Foil Slalom, and Freestyle events. Stay tuned for even more detailed insights and interactive reports.
</p>
<br> 
<h2>Nerd Chat</h2>
<p>
  This project was built using Python to scrape data from the PWA website, which I then imported into Power BI. The dashboard is embedded on a GitHub Page, offering a simple, cost-effective, and flexible solution for iterative design and updates. While it's not the most sophisticated tech stack, it gets the job done efficiently.
</p>
<br> 
<h2>About Me</h2>
<p>
  I'm Jack Andrew, a passionate windsurfer and data analyst currently based in Doha, Qatar. My work at a leading sports academy combines my love for sports and data, creating tools like this to bring performance insights to life. I'm always looking for ways to blend technology and sports to enhance understanding and engagement.
</p>

</div>

<div class="iframe-container">
  <iframe 
      title="POZO Report Wave & Slalom v5 Wave Only" 
      src="https://app.powerbi.com/view?r=eyJrIjoiM2I4MWJhYjQtMTdmMC00OGE2LTk3MWItMzMyNTg0NTg1MTJlIiwidCI6IjRlNDc4YWIwLWFjYWUtNGRiNS1hYjA4LTQ0ZjdlOTliNDc1MiJ9" 
      allowfullscreen="true">
  </iframe>
</div>
