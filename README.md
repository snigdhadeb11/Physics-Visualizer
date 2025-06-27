<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GamEd: A Gamified 3D Physics Learning Application</title>
    <!-- Tailwind CSS CDN for easy styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #1a1a2e; /* Dark background */
            color: #e0e0e0; /* Light text */
            line-height: 1.6;
        }
        .container {
            max-width: 960px;
            margin: 2rem auto;
            padding: 2rem;
            background-color: #2a2a4a; /* Slightly lighter dark background for content */
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }
        h1, h2 {
            color: #8a8af8; /* A vibrant purple for headings */
            font-weight: 700;
        }
        h1 {
            font-size: 2.5rem;
            margin-bottom: 1.5rem;
            text-align: center;
        }
        h2 {
            font-size: 1.8rem;
            margin-top: 2rem;
            margin-bottom: 1rem;
            border-bottom: 2px solid #5a5a7a; /* A subtle border under headings */
            padding-bottom: 0.5rem;
        }
        ul {
            list-style-type: disc;
            margin-left: 1.5rem;
            margin-bottom: 1rem;
        }
        li {
            margin-bottom: 0.5rem;
        }
        a {
            color: #a0a0ff; /* Lighter purple for links */
            text-decoration: none;
            transition: color 0.3s ease;
        }
        a:hover {
            color: #c0c0ff; /* Even lighter purple on hover */
            text-decoration: underline;
        }
        .section-heading {
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        .emoji {
            font-size: 1.5rem;
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-100 font-sans">
    <div class="container bg-gray-800 rounded-xl shadow-lg p-8 md:p-12">
        <h1 class="text-ind
