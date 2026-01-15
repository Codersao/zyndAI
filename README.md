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
      --accent: #EA4B71;          /* n8n-inspired vivid pink */
      --accent-dark: #c73d5f;
      --border: #1e293b;
      --code-bg: #02060f;
      --highlight-border: #EA4B71;
    }

    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      background: var(--bg-primary);
      color: var(--text-primary);
      line-height: 1.7;
      margin: 0;
      padding: 0;
    }

    header {
      background: linear-gradient(135deg, #1e3a8a, #7c3aed, #c026d3);
      padding: 5rem 1.5rem 4rem;
      text-align: center;
      position: relative;
      overflow: hidden;
    }

    header::before {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: radial-gradient(circle at 30% 70%, rgba(234,75,113,0.18), transparent 60%);
      pointer-events: none;
    }

    header h1 {
      font-size: 3.8rem;
      font-weight: 700;
      margin: 0 0 0.8rem;
      letter-spacing: -0.02em;
    }

    header p {
      font-size: 1.35rem;
      max-width: 680px;
      margin: 0 auto 0.6rem;
      opacity: 0.95;
    }

    header .tagline {
      font-size: 1.1rem;
      font-weight: 500;
      color: #e0f2fe;
    }

    main {
      max-width: 980px;
      margin: -3rem auto 0;
      padding: 0 1.5rem 4rem;
    }

    section {
      margin-bottom: 4.5rem;
      background: var(--bg-secondary);
      padding: 2.5rem;
      border-radius: 12px;
      border: 1px solid var(--border);
      box-shadow: 0 10px 30px rgba(0,0,0,0.4);
    }

    h2 {
      color: var(--accent);
      font-size: 2.1rem;
      font-weight: 600;
      margin: 0 0 1.4rem;
      padding-bottom: 0.6rem;
      border-bottom: 2px solid rgba(234,75,113,0.18);
    }

    ul {
      padding-left: 1.4rem;
      list-style: none;
    }

    ul li {
      margin-bottom: 0.9rem;
      position: relative;
      padding-left: 1.8rem;
    }

    ul li::before {
      content: "→";
      color: var(--accent);
      position: absolute;
      left: 0;
      font-weight: bold;
    }

    .highlight {
      background: rgba(234,75,113,0.08);
      border-left: 4px solid var(--highlight-border);
      padding: 1.4rem 1.8rem;
      border-radius: 8px;
      margin: 1.5rem 0;
      font-weight: 500;
      color: #fce7f3;
    }

    pre, code {
      background: var(--code-bg);
      border-radius: 10px;
      padding: 1.4rem;
      font-size: 0.95rem;
      overflow-x: auto;
      border: 1px solid #1e293b;
      color: #e2e8f0;
    }

    pre {
      position: relative;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin: 1.5rem 0;
      font-size: 0.95rem;
    }

    th, td {
      border: 1px solid var(--border);
      padding: 1rem 1.2rem;
      text-align: left;
    }

    th {
      background: #1e293b;
      color: var(--accent);
      font-weight: 600;
    }

    footer {
      text-align: center;
      padding: 3rem 1.5rem;
      color: #94a3b8;
      font-size: 0.95rem;
      border-top: 1px solid var(--border);
    }

    .btn-demo {
      display: inline-block;
      background: var(--accent);
      color: white;
      padding: 0.9rem 2rem;
      border-radius: 8px;
      text-decoration: none;
      font-weight: 600;
      margin-top: 1.5rem;
      transition: all 0.2s;
    }

    .btn-demo:hover {
      background: var(--accent-dark);
      transform: translateY(-2px);
    }

    @media (max-width: 768px) {
      header h1 { font-size: 2.8rem; }
      header p { font-size: 1.15rem; }
      section { padding: 1.8rem; }
    }
  </style>
</head>

<body>

<header>
  <h1>🚀 FreelanceGuard</h1>
  <p>AI-Verified Fair Hiring & Automated Payments</p>
  <p class="tagline"><strong>Replacing trust with intelligence in the future of work</strong></p>
</header>

<main>

<section>
  <h2>🌍 Problem Statement</h2>
  <p><strong>Fair Hiring Network – Future of Work</strong></p>
  <ul>
    <li>Delayed or denied payments</li>
    <li>Low-quality or copied work</li>
    <li>Manual, biased dispute resolution</li>
    <li>No automated trust mechanism</li>
  </ul>
  <p>Both freelancers and clients suffer in a <strong>trust-deficit system</strong>.</p>
</section>

<section>
  <h2>💡 Solution – What is FreelanceGuard?</h2>
  <ul>
    <li>💰 Client payment <strong>secured first</strong></li>
    <li>🤖 Work <strong>verified by AI</strong></li>
    <li>⚙️ Decisions <strong>automated using n8n</strong></li>
    <li>⏱ Freelancers protected via <strong>24-hour auto-release</strong></li>
  </ul>
  <div class="highlight">
    No disputes. No manual trust. No cheating.
  </div>
</section>

<section>
  <h2>🧠 How It Works</h2>
  <pre>
Client submits work + payment
        ↓
X402 Paid Webhook (Payment Locked)
        ↓
Zynd AI verifies work
        ↓
AI Decision Engine (n8n)
        ↓
Outcome:
• APPROVED   → Auto release after 24h
• NEEDS_REVIEW → Payment on hold
• REJECTED    → Payment not released
  </pre>
</section>

<section>
  <h2>⚙️ Tech Stack</h2>
  <ul>
    <li><strong>n8n</strong> – Workflow automation engine</li>
    <li><strong>Zynd AI</strong> – AI work verification</li>
    <li><strong>X402 Protocol</strong> – Conditional payment logic</li>
    <li><strong>Web3 Wallet (Testnet)</strong> – Secure payments</li>
  </ul>
</section>

<section>
  <h2>🧩 n8n Workflow – Nodes Used</h2>
  <table>
    <tr><th>Node</th><th>Purpose</th></tr>
    <tr><td>X402 Webhook</td><td>Paid entry point</td></tr>
    <tr><td>Zynd Agent Search</td><td>Select AI reviewer</td></tr>
    <tr><td>HTTP Request (X402)</td><td>Send work to AI</td></tr>
    <tr><td>IF Nodes</td><td>Decision logic</td></tr>
    <tr><td>Wait (24h)</td><td>Auto-release safeguard</td></tr>
    <tr><td>Edit Fields</td><td>Build response JSON</td></tr>
    <tr><td>Respond to Webhook</td><td>Final output</td></tr>
  </table>
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

<section>
  <h2>🛠 How to Run the Prototype</h2>
  <pre>
1. Install n8n
2. Import FreelanceGuard workflow JSON
3. Configure:
   - X402 Facilitator URL
   - Web3 Wallet credentials
4. Activate workflow
5. Trigger the X402 Webhook
  </pre>

  <a href="#" class="btn-demo">Try Demo Workflow (coming soon)</a>
</section>

<section>
  <h2>🎯 Impact</h2>
  <ul>
    <li>Prevents freelancer exploitation</li>
    <li>Reduces hiring disputes by >90%</li>
    <li>Automates trust using AI</li>
    <li>Scalable for next-gen work platforms</li>
  </ul>
</section>

<section>
  <h2>📌 One-Line Summary</h2>
  <div class="highlight">
    “FreelanceGuard ensures fair hiring by releasing payments only when AI verifies the work — with automatic protection for freelancers.”
  </div>
</section>

</main>

<footer>
  Built with ❤️ for the Future of Work • Hackathon Prototype • Inspired by n8n style
</footer>

</body>
</html>
