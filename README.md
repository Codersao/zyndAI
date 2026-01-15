<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>FreelanceGuard – AI-Verified Fair Hiring</title>

  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen;
      background: #0f172a;
      color: #e5e7eb;
      line-height: 1.7;
      margin: 0;
      padding: 0;
    }

    header {
      background: #0f172a;          /* Removed blue gradient → now same as body */
      padding: 3rem 1.5rem;
      text-align: center;
      color: white;
      border-bottom: 1px solid #1e293b; /* optional subtle separator */
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.95;
    }

    main {
      max-width: 900px;
      margin: auto;
      padding: 2rem 1.5rem;
    }

    section {
      margin-bottom: 3rem;
    }

    h2 {
      color: #93c5fd;
      border-bottom: 2px solid #1e293b;
      padding-bottom: 0.3rem;
      margin-bottom: 1rem;
    }

    ul {
      padding-left: 1.2rem;
    }

    li {
      margin-bottom: 0.5rem;
    }

    code, pre {
      background: #020617;
      border-radius: 8px;
      padding: 1rem;
      display: block;
      overflow-x: auto;
      color: #e5e7eb;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 1rem;
    }

    th, td {
      border: 1px solid #1e293b;
      padding: 0.8rem;
      text-align: left;
    }

    th {
      background: #1e293b;
      color: #93c5fd;
    }

    footer {
      text-align: center;
      padding: 2rem;
      background: #020617;
      color: #94a3b8;
      font-size: 0.9rem;
    }

    .highlight {
      background: #020617;
      padding: 1rem;
      border-left: 4px solid #22c55e;
      border-radius: 6px;
      margin-top: 1rem;
    }
  </style>
</head>

<body>



<main>

<section>
  <h2>🌍 Problem Statement</h2>
  <p><strong>Fair Hiring Network – Future of Work</strong></p>
  <ul>
    <li>❌ Delayed or denied payments</li>
    <li>❌ Low-quality or copied work</li>
    <li>❌ Manual, biased dispute resolution</li>
    <li>❌ No automated trust mechanism</li>
  </ul>
  <p>Both freelancers and clients operate in a <strong>trust-deficit system</strong>.</p>
</section>

<section>
  <h2>💡 Solution – What is FreelanceGuard?</h2>
  <ul>
    <li>💰 Client payment is <strong>secured first</strong></li>
    <li>🤖 Work is <strong>verified by AI</strong></li>
    <li>⚙️ Decisions are <strong>automated using n8n</strong></li>
    <li>⏱ Freelancers are protected via <strong>24-hour auto-release</strong></li>
  </ul>
  <div class="highlight">
    No disputes. No manual trust. No cheating.
  </div>
</section>

<!-- Rest of your sections remain unchanged -->

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
• APPROVED → Auto release after 24h
• NEEDS_REVIEW → Payment on hold
• REJECTED → Payment not released
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
</section>

<section>
  <h2>🎯 Impact</h2>
  <ul>
    <li>✅ Prevents freelancer exploitation</li>
    <li>✅ Reduces hiring disputes</li>
    <li>✅ Automates trust using AI</li>
    <li>✅ Scalable for future work platforms</li>
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
  Built with ❤️ for the Future of Work • Hackathon Prototype
</footer>

</body>
</html>
