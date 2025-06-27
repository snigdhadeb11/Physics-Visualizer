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
        <h1 class="text-indigo-400 text-4xl md:text-5xl font-extrabold text-center mb-8">GamEd: A Gamified 3D Physics Learning Application</h1>

        <div class="mb-10">
            <h2 class="text-indigo-300 text-2xl md:text-3xl font-bold border-b-2 border-indigo-500 pb-3 mb-6">Project Overview</h2>
            <p class="text-lg leading-relaxed">
                GamEd is an interactive educational platform designed to revolutionize the way physics concepts are taught and understood. By combining the power of real-time simulations with gamified learning, GamEd offers users the ability to visualize, interact with, and manipulate fundamental physics principles in an engaging and intuitive manner.
            </p>
            <p class="text-lg leading-relaxed mt-4">
                The platform leverages Unity Engine for high-quality visualization and dynamic physics simulations, enabling users to explore topics such as projectiles, collisions (1D), magnetism, logic gates, incline motion, and uniform circular motion (pendulums). With features like customizable parameters, real-time feedback, and hands-on experimentation, GamEd bridges the gap between theoretical knowledge and practical understanding.
            </p>
            <p class="text-lg leading-relaxed mt-4">
                Its modular design supports tailored learning experiences, catering to a wide range of learners, from students and educators to lifelong enthusiasts. By transforming complex physics topics into interactive challenges and simulations, GamEd aims to make physics education both accessible and enjoyable.
            </p>
        </div>

        <div class="mb-10">
            <h2 class="text-indigo-300 text-2xl md:text-3xl font-bold border-b-2 border-indigo-500 pb-3 mb-6 flex items-center"><span class="emoji mr-2">✨</span> Features & Functionality</h2>
            <ul class="list-disc ml-6 space-y-3 text-lg">
                <li><strong>Interactive 3D Physics Simulations:</strong> Explore core physics concepts (Projectile Motion, 1D Collisions, Magnetism, Logic Gates, Incline Motion, Pendulum/UCM) in a visually engaging 3D environment powered by Unity Engine.</li>
                <li><strong>Customizable Parameters:</strong> Manipulate key variables like mass, velocity, angles, gravity, and environmental factors to observe real-time impacts on simulations.</li>
                <li><strong>Real-Time Feedback:</strong> Receive instant visual and numerical feedback on simulations, including trajectories, calculated values (range, height, time of flight), and force visualizations.</li>
                <li><strong>Gamified Learning:</strong> Designed to encourage experimentation and problem-solving through hands-on interaction, fostering deeper understanding beyond theoretical concepts.</li>
                <li><strong>Modular Architecture:</strong> Built for scalability, allowing for seamless addition of new physics models, gameplay mechanics, and customization options.</li>
                <li><strong>Intuitive User Interface:</strong> An easy-to-use interface makes the platform accessible for students and educators of all technical backgrounds.</li>
            </ul>
        </div>

        <div class="mb-10 text-center">
            <h2 class="text-indigo-300 text-2xl md:text-3xl font-bold border-b-2 border-indigo-500 pb-3 mb-6 flex items-center justify-center"><span class="emoji mr-2">🚀</span> Live Demo</h2>
            <p class="text-lg mb-4">Experience the web-based prototype of GamEd here:</p>
            <a href="https://physvis.lovable.app/" class="inline-block bg-indigo-600 hover:bg-indigo-700 text-white font-bold py-3 px-6 rounded-full transition-colors duration-300 text-xl shadow-lg">Go to Live Demo: PhysVis</a>
        </div>

        <div class="mb-10">
            <h2 class="text-indigo-300 text-2xl md:text-3xl font-bold border-b-2 border-indigo-500 pb-3 mb-6 flex items-center"><span class="emoji mr-2">🛠️</span> Technologies Used</h2>
            <ul class="list-disc ml-6 space-y-3 text-lg">
                <li><strong>Unity Engine:</strong> For 3D physics simulations and interactive scenes (C# scripting).</li>
                <li><strong>HTML, CSS:</strong> For the website structure and stylization.</li>
                <li><strong>TypeScript & React:</strong> For building modular and maintainable web components, ensuring a responsive and intuitive user interface.</li>
                <li><strong>Tailwind CSS:</strong> For streamlined and efficient styling of the web frontend.</li>
            </ul>
        </div>

        <div class="mb-10">
            <h2 class="text-indigo-300 text-2xl md:text-3xl font-bold border-b-2 border-indigo-500 pb-3 mb-6 flex items-center"><span class="emoji mr-2">🎯</span> Future Scope</h2>
            <p class="text-lg leading-relaxed mb-4">GamEd is built with expandability in mind. Potential future enhancements include:</p>
            <ul class="list-disc ml-6 space-y-3 text-lg">
                <li><strong>Advanced Simulation Features:</strong> Incorporating more complex physics phenomena (e.g., fluid dynamics, thermodynamics).</li>
                <li><strong>User-Created Content:</strong> Enabling users to save, share, and export their custom simulations.</li>
                <li><strong>Enhanced Gamification:</strong> Adding more challenges, scenarios, leaderboards, and achievement systems to boost engagement.</li>
                <li><strong>3D Environments and Multiplayer:</strong> Expanding to full 3D interactive environments and introducing collaborative multiplayer features.</li>
            </ul>
        </div>

        <div>
            <h2 class="text-indigo-300 text-2xl md:text-3xl font-bold border-b-2 border-indigo-500 pb-3 mb-6 flex items-center"><span class="emoji mr-2">📄</span> License</h2>
            <p class="text-lg leading-relaxed">
                (Consider adding a license, e.g., MIT, if you want to explicitly allow others to use your work.)
            </p>
        </div>
    </div>
</body>
</html>
