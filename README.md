<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Specular Technologies Ltd</title>
    <meta name="description" content="Specular Technologies Ltd — a geometric framework for information processing.">
    <style>
        :root {
            --specular-dark: #2E1A6B;
            --specular-light: #5B3FA8;
            --text-dark: #1A1A1A;
            --text-gray: #4A4A4A;
            --bg-light: #F5F3FA;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Inter', 'Helvetica Neue', Arial, sans-serif;
            background: #FFFFFF;
            color: var(--text-dark);
            line-height: 1.65;
            font-size: 16px;
            -webkit-font-smoothing: antialiased;
        }

        .container {
            max-width: 720px;
            margin: 0 auto;
            padding: 4rem 2rem;
        }

        header {
            margin-bottom: 3rem;
        }

        .logo {
            width: 60px;
            height: auto;
            margin-bottom: 1.5rem;
        }

        h1 {
            color: var(--specular-dark);
            font-size: 2rem;
            font-weight: 700;
            letter-spacing: -0.02em;
            margin-bottom: 0.5rem;
        }

        .tagline {
            color: var(--specular-light);
            font-size: 1.1rem;
            font-weight: 500;
            margin-bottom: 2rem;
        }

        h2 {
            color: var(--specular-dark);
            font-size: 1.1rem;
            font-weight: 600;
            margin-top: 2.5rem;
            margin-bottom: 0.8rem;
            letter-spacing: -0.01em;
        }

        p {
            color: var(--text-dark);
            margin-bottom: 1rem;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            color: var(--text-dark);
            padding: 0.3rem 0;
            padding-left: 1.2rem;
            position: relative;
        }

        ul li::before {
            content: "—";
            position: absolute;
            left: 0;
            color: var(--specular-light);
        }

        a {
            color: var(--specular-dark);
            text-decoration: none;
            border-bottom: 1px solid var(--specular-light);
            transition: all 0.2s ease;
        }

        a:hover {
            color: var(--specular-light);
            border-bottom-color: var(--specular-dark);
        }

        .button {
            display: inline-block;
            background: var(--specular-dark);
            color: #FFFFFF;
            padding: 0.8rem 1.5rem;
            border-radius: 4px;
            font-weight: 500;
            border: none;
            margin-top: 1rem;
            transition: background 0.2s ease;
        }

        .button:hover {
            background: var(--specular-light);
            color: #FFFFFF;
            border-bottom: none;
        }

        footer {
            margin-top: 4rem;
            padding-top: 2rem;
            border-top: 1px solid #E0DCE8;
            font-size: 0.9rem;
            color: var(--text-gray);
        }

        footer p {
            margin-bottom: 0.4rem;
        }

        @media (max-width: 600px) {
            .container {
                padding: 2.5rem 1.5rem;
            }
            h1 {
                font-size: 1.6rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <!-- Se vuoi, sostituisci con il logo: -->
            <!-- <img src="logo.png" alt="Specular Technologies" class="logo"> -->
            <h1>Specular Technologies Ltd</h1>
            <p class="tagline">A geometric framework for information processing.</p>
        </header>

        <main>
            <section>
                <h2>About</h2>
                <p>
                    Specular Technologies Ltd develops the <strong>Specular Field Theory (SFT)</strong>, 
                    a geometric framework for information processing with applications in AI, 
                    quantum information, and secure computation. The framework models learning 
                    and informational dynamics through a curvature-like parameter intrinsic to the 
                    system, enabling the detection of stable versus critical regimes.
                </p>
            </section>

            <section>
                <h2>Research Areas</h2>
                <ul>
                    <li>Information Geometry</li>
                    <li>Quantum Systems and Error Correction</li>
                    <li>AI and Computational Optimization</li>
                    <li>Secure Computation and Quantum Networks</li>
                </ul>
            </section>

            <section>
                <h2>Preprint</h2>
                <p>
                    The conceptual foundation of the framework is available as a preprint on Zenodo:
                </p>
                <p>
                    <a href="https://doi.org/10.5281/zenodo.22258180" class="button" target="_blank" rel="noopener">
                        Read the preprint on Zenodo
                    </a>
                </p>
            </section>
        </main>

        <footer>
            <p><strong>Specular Technologies Ltd</strong></p>
            <p>London, United Kingdom</p>
            <p>
                Email: <a href="mailto:valentina@speculartech.uk">valentina@speculartech.uk</a><br>
                ORCID: <a href="https://orcid.org/0009-0009-5931-1106" target="_blank" rel="noopener">0009-0009-5931-1106</a>
            </p>
        </footer>
    </div>
</body>
</html>
