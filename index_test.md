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


<div class="iframe-container">
  <iframe 
      title="Pozo 2025 Report (Wave)" 
      src= "https://app.powerbi.com/view?r=eyJrIjoiMzdlMzE0NWYtODUyYS00YTRlLWI0MjEtNDkyZTY5NTRkMDM2IiwidCI6IjRlNDc4YWIwLWFjYWUtNGRiNS1hYjA4LTQ0ZjdlOTliNDc1MiJ9"
      allowfullscreen="true">
  </iframe>
</div>

