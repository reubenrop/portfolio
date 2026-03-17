<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reuben Rop | Portfolio</title>
    <style>
        body {
            background: #0b0e14;
            color: white;
            font-family: sans-serif;
            display: flex;
            justify-content: center;
            padding: 20px;
        }
        .container {
            display: grid;
            grid-template-columns: 300px 600px;
            gap: 20px;
            max-width: 1000px;
        }
        .card {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 20px;
        }
        .hero { grid-column: span 2; display: flex; align-items: center; gap: 20px; }
        .profile-img { width: 100px; height: 100px; border-radius: 50%; object-fit: cover; }
        h1 { margin: 0; font-size: 1.5rem; }
    </style>
</head>
<body>

    <div class="container">
        <div class="card hero">
            <img src="YOUR_IMAGE_FILENAME.jpg" class="profile-img" alt="Reuben Rop">
            <div>
                <h1>Reuben Rop</h1>
                <p>AWS Certified Technical Trainer & Software Developer</p>
            </div>
        </div>

        <div class="card">
            <h2>Core Competencies</h2>
            <ul>
                <li>AWS re/Start Curriculum</li>
                <li>Cloud Infrastructure</li>
                <li>Mobile App Development</li>
            </ul>
        </div>

        <div class="card">
            <h2>Experience</h2>
            <p>AWS Alumni Community Lead</p>
            <p>B.Sc. Computer Science, University of Kabianga</p>
        </div>
    </div>

</body>
</html>
