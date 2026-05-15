<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Blog | James Hedvall</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #fcfcfc;
            color: #333;
        }

        /* Consistent Top Banner */
        .status-banner {
            width: 100%;
            background-color: #415681;
            color: #ffffff;
            padding: 15px 0;
            text-align: left;
            text-indent: 60px; /* Aligns with content padding */
            font-size: 1rem;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        /* Main Layout Container */
        .blog-container {
            max-width: 900px;
            margin: 0 auto;
            padding: 60px 20px;
        }

        header {
            margin-bottom: 50px;
            border-bottom: 2px solid #eee;
            padding-bottom: 20px;
        }

        h1 {
            font-size: 3rem;
            color: #415681;
            margin: 0;
        }

        .subtitle {
            font-size: 1.2rem;
            color: #666;
            margin-top: 10px;
        }

        /* Article Card Styles */
        .article-card {
            margin-bottom: 60px;
            display: flex;
            flex-direction: column;
        }

        .article-date {
            font-size: 0.9rem;
            color: #415681;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 10px;
        }

        .article-title {
            font-size: 2rem;
            color: #333;
            text-decoration: none;
            margin-bottom: 15px;
            transition: color 0.3s ease;
        }

        .article-title:hover {
            color: #415681;
        }

        .article-excerpt {
            font-size: 1.1rem;
            line-height: 1.7;
            color: #555;
            margin-bottom: 20px;
        }

        .read-more {
            color: #415681;
            text-decoration: none;
            font-weight: bold;
            font-size: 1rem;
        }

        .read-more:hover {
            text-decoration: underline;
        }

        .nav-back {
            margin-bottom: 40px;
            display: inline-block;
            color: #415681;
            text-decoration: none;
            font-weight: bold;
        }

        /* Mobile Adjustments */
        @media (max-width: 768px) {
            .blog-container { padding: 40px 20px; }
            h1 { font-size: 2.2rem; }
            .article-title { font-size: 1.6rem; }
            .status-banner { text-indent: 20px; }
        }
    </style>
</head>
<body>

    <div class="status-banner">
        James Hedvall's Professional Blog
    </div>

    <div class="blog-container">
        <a href="index.html" class="nav-back">← Back to Home</a>
        
        <header>
            <h1>Mortgage Banking Insights</h1>
            <p class="subtitle">Weekly commentary on secondary marketing, industry trends, and finance.</p>
        </header>

        <!-- Article 1 -->
        <article class="article-card">
            <span class="article-date">April 30, 2026</span>
            <a href="#" class="article-title">Secondary Marketing Strategies in a Volatile Environment</a>
            <p class="article-excerpt">
                As market conditions continue to shift, understanding the nuances of pipeline hedging and execution becomes more critical than ever...
            </p>
            <a href="#" class="read-more">Read Full Article →</a>
        </article>

        <!-- Article 2 -->
        <article class="article-card">
            <span class="article-date">April 27, 2026</span>
            <a href="#" class="article-title">The Future of Mortgage Servicing Rights</a>
            <p class="article-excerpt">
                Evaluating the long-term value of MSRs requires a deep dive into prepayment speeds and the current interest rate trajectory...
            </p>
            <a href="#" class="read-more">Read Full Article →</a>
        </article>

    </div>

</body>
</html>