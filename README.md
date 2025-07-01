# DAY-2html
# Aim:
Add Downloadable Files to Your Webpage.Use <a href='file.pdf' download'>to add a resume or brochure.
# CODE:
```
<!DOCTYPE html>
<html>
<head>
  <title>Downloadable Files Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f8ff; /* Light blue background */
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #003366; /* Dark blue */
      color: white;
      padding: 20px;
      text-align: center;
    }

    main {
      padding: 40px;
      background-color: #ffffff;
    }

    .download-section {
      background-color: #e6f2ff;
      border: 2px solid #3399ff;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
      width: 50%;
      margin: 0 auto;
    }

    .download-link {
      display: inline-block;
      margin: 10px;
      padding: 12px 20px;
      background-color: #3399ff;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-size: 16px;
    }

    .download-link:hover {
      background-color: #267acc;
    }
  </style>
</head>
<body>

  <header>
    <h1>My Downloadable Files</h1>
  </header>

  <main>
    <div class="download-section">
      <h2>Download Resume & Brochure</h2>
      <a href="resume.pdf" download class="download-link">Download Resume</a>
      <a href="brochure.pdf" download class="download-link">Download Brochure</a>
    </div>
  </main>

</body>
</html>

```
# OUTPUT:
![image](https://github.com/user-attachments/assets/c7db8431-fc08-49df-ad3a-97f0d3cf06a6)

