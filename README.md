<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Kennedy Maina's Data Analyst Portfolio">
    <title>Kennedy Maina | Data Analyst</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/pdfobject/2.2.7/pdfobject.min.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            text-align: center;
            padding: 1rem;
            background-color: #007BFF;
            color: white;
        }

        .pdf-container {
            width: 100%;
            height: 600px;
            margin: 2rem auto;
            background-color: #fff;
            border: 1px solid #ddd;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .download-link {
            text-align: center;
            margin-top: 10px;
        }

        .download-link a {
            background-color: #007BFF;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }

        .download-link a:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

    <header>
        <h1>Kennedy Maina | Data Analyst Portfolio</h1>
    </header>

    <!-- Embed the first PDF -->
    <h2>Kennedy Ithagu Maina Report</h2>
    <div class="pdf-container" id="pdf-viewer1"></div>
    <script>
        // Embed PDF from GitHub Pages URL
        PDFObject.embed("https://moonwiing.github.io/report.1/assets/pdfs/Kennedy%20Ithagu%20Maina_report.pdf", "#pdf-viewer1");
    </script>
    <!-- Download Link for the first PDF -->
    <div class="download-link">
        <a href="https://moonwiing.github.io/report.1/assets/pdfs/Kennedy%20Ithagu%20Maina_report.pdf" target="_blank" download>Download Report</a>
    </div>

    <!-- Embed the second PDF -->
    <h2>Kennedy Ithagu Maina Visual</h2>
    <div class="pdf-container" id="pdf-viewer2"></div>
    <script>
        // Embed PDF from GitHub Pages URL
        PDFObject.embed("https://moonwiing.github.io/report.1/assets/pdfs/Kennedy%20Ithagu%20Maina_Visual.pdf", "#pdf-viewer2");
    </script>
    <!-- Download Link for the second PDF -->
    <div class="download-link">
        <a href="https://moonwiing.github.io/report.1/assets/pdfs/Kennedy%20Ithagu%20Maina_Visual.pdf" target="_blank" download>Download Visual</a>
    </div>

</body>
</html>
