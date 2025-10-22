<!-- <!DOCTYPE html> -->
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Evolve Technology</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif;
            background: #8b5cf6;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #ffffff;
            padding: 20px;
        }

        .container {
            text-align: center;
            max-width: 800px;
            animation: fadeIn 1s ease-in;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        h1 {
            font-size: 3.5rem;
            font-weight: 700;
            letter-spacing: 2px;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }

        h2 {
            font-size: 1.8rem;
            font-weight: 400;
            margin-bottom: 2rem;
            opacity: 0.9;
        }

        p {
            font-size: 1.2rem;
            line-height: 1.6;
            opacity: 0.85;
            font-weight: 300;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }

            h2 {
                font-size: 1.4rem;
            }

            p {
                font-size: 1rem;
            }
        }

        @media (max-width: 480px) {
            h1 {
                font-size: 2rem;
                letter-spacing: 1px;
            }

            h2 {
                font-size: 1.2rem;
            }

            p {
                font-size: 0.95rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>EVOLVE TECHNOLOGY</h1>
        <h2>Avijit Jaiswal</h2>
        <p>Technology transformation running in auto-pilot</p>
    </div>
</body>
</html>
