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
    width: 1px; /* Narrow sidebar */
    height: 100%; /* Full height */
    background-color: #f8f9fa;
    padding: 10px; /* Reduced padding */
    box-sizing: border-box;
    overflow-y: auto;
  }

  /* Hide any empty <h1> so you don’t get a blank title */
  .sidebar-container h1:empty {
    display: none;
  }

  .sidebar-container h1 {
    margin: 0 0 10px 0;
    font-size: 18px;
    color: #333;
  }

  .sidebar-container p,
  .sidebar-container h2 {
    font-size: 12px;
    color: #555;
    margin: 8px 0;
  }

  /* Iframe container */
  .iframe-container {
    position: absolute;
    top: 0;
    left: 80px; /* Matches the sidebar width */
    right: 0;
    bottom: 0;
    overflow: hidden;
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
    src="https://app.powerbi.com/view?r=eyJrIjoiMzdlMzE0NWYtODUyYS00YTRlLWI0MjEtNDkyZTY5NTRkMDM2IiwidCI6IjRlNDc4YWIwLWFjYWUtNGRiNS1hYjA4LTQ0ZjdlOTliNDc1MiJ9"
    allowfullscreen>
  </iframe>
</div>
