<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>FreelanceGuard – AI-Verified Fair Hiring</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --bg-primary: #0a0f1a;
      --bg-secondary: #111827;
      --text-primary: #f1f5f9;
      --text-secondary: #cbd5e1;
      --accent: #EA4B71;
      --accent-dark: #c73d5f;
      --border: #1e293b;
      --code-bg: #02060f;
    }

    * { box-sizing: border-box; }

    body {
      font-family: 'Inter', sans-serif;
      background: var(--bg-primary);
      color: var(--text-primary);
      margin: 0;
      line-height: 1.7;
    }

    header {
      background: linear-gradient(135deg, #1e3a8a, #7c3aed, #c026d3);
      padding: 5rem 1.5rem 4rem;
      text-align: center;
    }

    header h1 {
      font-size: 3.5rem;
      margin: 0;
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.95;
    }

    main {
      max-width: 980px;
      margin: -3rem auto 0;
      padding: 0 1.5rem 4rem;
    }

    section {
      background: var(--bg-secondary);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 2.5rem;
      margin-bottom: 3rem;
    }

    h2 {
      color: var(--accent);
      border-bottom: 2px solid rgba(234,75,113,0.2);
      padding-bottom: 0.5rem;
    }

    ul { list-style: none; padding-left: 0; }

    ul li {
      padding-left: 1.5rem;
      margin-bottom: 0.7rem;
      position: relative;
    }

    ul li::before {
      content: "→";
      color: var(--accent);
      position: absolute;
      left: 0;
    }

    pre {
      background: var(--code-bg);
      padding: 1.4rem;
      border-radius: 10px;
      overflow-x: auto;
      border: 1px solid var(--border);
    }

    footer {
      text-align: center;
      padding: 2.5rem;
      color: #94a3b8;
      border-top: 1px solid var(--border);
    }
  </style>
</head>

<body>

<header>
  <h1>🚀 FreelanceGuard</h1>
  <p>AI-Verified Fair Hiring & Automated Payments</p>
  <p><strong>Replacing trust with intelligence in the future of work</strong></p>
</header>

<main>

<section>
  <h2>🌍 Problem Statement</h2>
  <ul>
    <li>Delayed or denied payments</li>
    <li>Low-quality or copied work</li>
    <li>Manual, biased dispute resolution</li>
    <li>No automated trust mechanism</li>
  </ul>
</section>

<section>
  <h2>💡 Solution</h2>
  <ul>
    <li>Client payment secured first</li>
    <li>AI verifies submitted work</li>
    <li>n8n automates decisions</li>
    <li>24-hour auto-release protection</li>
  </ul>
</section>

<section>
  <h2>🧠 Workflow</h2>
  <pre>
Client submits work + payment
↓
X402 Webhook (escrow)
↓
Zynd AI verification
↓
n8n Decision Engine
↓
APPROVED / HOLD / REJECTED
  </pre>
</section>

<section>
  <h2>🧪 Sample API Response</h2>
  <pre>
{
  "paymentStatus": "AUTO_RELEASED",
  "decision": "APPROVED",
  "reason": "AI approved, auto released after 24h",
  "releaseType": "AUTO"
}
  </pre>
</section>

</main>

<footer>
  Built with ❤️ for the Future of Work • Hackathon Prototype
</footer>

</body>
</html>
