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
    </style>
</head>
<body>

    <header>
        <h1>Kennedy Maina | Data Analyst Portfolio</h1>
    </header>

    <div class="pdf-container" id="pdf-viewer"></div>

    <script>
        // Embed PDF using PDFObject
        PDFObject.embed("https://yourwebsite.com/pdfs/Kennedy_Ithagu_Maina_report.pdf", "#pdf-viewer");
    </script>

</body>
</html>
