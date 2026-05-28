<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sazal Homepage</title>
    <style>
        /* Reset and Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            overflow-x: hidden;
        }

        /* --- 1. INTRO ANIMATION --- */
        .intro-screen {
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            background-color: #111; /* Dark cinematic background */
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 9999;
            /* Slides up and out of the way after 3 seconds */
            animation: slideUpOut 1s ease-in-out 3s forwards;
        }

        .animated-name {
            font-size: 4rem;
            color: #ffffff;
            letter-spacing: 8px;
            text-transform: uppercase;
            opacity: 0;
            /* Fades in and scales up slowly */
            animation: fadeInScale 2s ease-in-out 0.5s forwards;
        }

        /* Keyframes for the Name Animation */
        @keyframes fadeInScale {
            0% { opacity: 0; transform: scale(0.8); }
            50% { opacity: 1; transform: scale(1.05); }
            100% { opacity: 1; transform: scale(1); }
        }

        /* Keyframes for the Screen Sliding Away */
        @keyframes slideUpOut {
            0% { transform: translateY(0); }
            100% { transform: translateY(-100%); visibility: hidden; }
        }

        /* --- 2. NORMAL CONTENT --- */
        .normal-content {
            opacity: 0;
            /* Fades in exactly as the intro screen slides away */
            animation: fadeInContent 1s ease-in-out 3.5s forwards;
        }

        @keyframes fadeInContent {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        /* --- Standard Layout Styling --- */
        header {
            background-color: #fff;
            padding: 20px 50px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo h2 {
            font-size: 1.5rem;
            letter-spacing: 2px;
            text-transform: uppercase;
            color: #111;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 30px;
        }

        nav a {
            text-decoration: none;
            color: #555;
            font-weight: 500;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #000;
        }

        main {
            padding: 100px 20px;
            text-align: center;
            min-height: 80vh;
        }

        main h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            color: #222;
        }

        main p {
            font-size: 1.2rem;
            color: #666;
            max-width: 600px;
            margin: 0 auto;
            line-height: 1.6;
        }
    </style>
</head>
<body>

    <div class="intro-screen">
        <h1 class="animated-name">Sazal</h1>
    </div>

    <div class="normal-content">
        <header>
            <div class="logo">
                <h2>Sazal.</h2>
            </div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </header>

        <main>
            <h1>Welcome to Sazal</h1>
            <p>This is your clean, normal homepage. The cinematic intro animation has finished, and now your visitors can easily navigate and read your content without distractions.</p>
        </main>
    </div>

</body>
</html>
