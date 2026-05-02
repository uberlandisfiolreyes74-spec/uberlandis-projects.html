<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>README — Uberlandis Fiol Reyes</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@300;400;500&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet" />
  <style>
    :root {
      --bg: #0d1117;
      --surface: #161b22;
      --border: #30363d;
      --text: #e6edf3;
      --muted: #7d8590;
      --accent: #58a6ff;
      --green: #3fb950;
      --amber: #d29922;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: 'DM Sans', sans-serif;
      font-weight: 300;
      line-height: 1.7;
      padding: 2rem 1rem;
    }

    .container {
      max-width: 800px;
      margin: 0 auto;
    }

    h1 {
      font-size: 1.6rem;
      font-weight: 500;
      margin-bottom: 0.5rem;
      padding-bottom: 0.75rem;
      border-bottom: 1px solid var(--border);
    }

    h2 {
      font-size: 1.15rem;
      font-weight: 500;
      margin: 2rem 0 0.75rem;
      padding-bottom: 0.4rem;
      border-bottom: 1px solid var(--border);
    }

    p { margin-bottom: 0.75rem; color: var(--text); font-size: 0.95rem; }

    a { color: var(--accent); text-decoration: none; }
    a:hover { text-decoration: underline; }

    .portfolio-link {
      display: inline-block;
      margin: 0.75rem 0 1.25rem;
      font-family: 'IBM Plex Mono', monospace;
      font-size: 0.8rem;
      background: rgba(88,166,255,0.1);
      border: 1px solid rgba(88,166,255,0.3);
      color: var(--accent);
      padding: 0.4rem 0.9rem;
      border-radius: 4px;
    }

    hr {
      border: none;
      border-top: 1px solid var(--border);
      margin: 1.5rem 0;
    }

    .framework {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 6px;
      padding: 1rem 1.25rem;
      margin-bottom: 0.75rem;
    }

    .fw-name {
      font-family: 'IBM Plex Mono', monospace;
      font-size: 0.8rem;
      color: var(--accent);
      margin-bottom: 0.3rem;
      font-weight: 500;
    }

    .fw-desc { font-size: 0.88rem; color: var(--muted); }

    code {
      font-family: 'IBM Plex Mono', monospace;
      font-size: 0.78rem;
      background: rgba(255,255,255,0.07);
      padding: 0.1rem 0.4rem;
      border-radius: 3px;
      color: var(--text);
    }

    .metrics {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
      margin: 0.75rem 0;
    }

    .metric {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 4px;
      padding: 0.6rem 1rem;
      font-family: 'IBM Plex Mono', monospace;
      font-size: 0.72rem;
      color: var(--muted);
    }

    .metric span {
      display: block;
      font-size: 1.3rem;
      font-weight: 500;
      color: var(--green);
      line-height: 1.2;
    }

    .metric span.amber { color: var(--amber); }

    table {
      width: 100%;
      border-collapse: collapse;
      font-size: 0.85rem;
      margin: 0.75rem 0;
    }

    th {
      font-family: 'IBM Plex Mono', monospace;
      font-size: 0.65rem;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      color: var(--muted);
      text-align: left;
      padding: 0.5rem 0.75rem;
      border-bottom: 1px solid var(--border);
    }

    td {
      padding: 0.6rem 0.75rem;
      border-bottom: 1px solid rgba(48,54,61,0.5);
      color: var(--text);
      font-size: 0.83rem;
    }

    tr:last-child td { border-bottom: none; }

    .badge {
      font-family: 'IBM Plex Mono', monospace;
      font-size: 0.6rem;
      padding: 0.15rem 0.45rem;
      border-radius: 2px;
      letter-spacing: 0.05em;
      white-space: nowrap;
    }

    .b-blue { background: rgba(88,166,255,0.15); color: var(--accent); }
    .b-amber { background: rgba(210,153,34,0.15); color: var(--amber); }
    .b-gray { background: rgba(125,133,144,0.15); color: var(--muted); }

    .license-box {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 6px;
      padding: 1rem 1.25rem;
      font-family: 'IBM Plex Mono', monospace;
      font-size: 0.75rem;
      color: var(--muted);
      line-height: 1.6;
    }
  </style>
</head>
<body>
  <div class="container">

    <h1>Uberlandis Fiol Reyes — Decision Science &amp; AI Research</h1>

    <p>Independent researcher specializing in decision science, quantitative modeling, and organizational systems. This repository hosts my research portfolio website.</p>

    <a class="portfolio-link" href="https://uberlandisfiolreyes74-spec.github.io/uberlandis.github.io/" target="_blank">🌐 View Portfolio →</a>

    <hr />

    <h2>Research Frameworks</h2>

    <div class="framework">
      <div class="fw-name">SMA-03 v3 — Irreversibility Index</div>
      <div class="fw-desc">Quantifies organizational lock-in risk through the II-Score (0–1 range), validated on 120 decisions at 87.5% accuracy. Core equation: <code>E[V]_adjusted = E[V] / (1 + II²)</code></div>
    </div>

    <div class="framework">
      <div class="fw-name">MSCA v6 — Monte Carlo Scenario Analysis</div>
      <div class="fw-desc">Probabilistic option evaluation via Monte Carlo simulation and adjusted expected value computation. v7 roadmap includes causal inference and Extreme Value Theory.</div>
    </div>

    <div class="framework">
      <div class="fw-name">EGDS — Execution-Gated Decision System</div>
      <div class="fw-desc">Temporal governance framework with checkpoints at Days 7, 30, 60, and 90, gating execution based on reversibility windows.</div>
    </div>

    <hr />

    <h2>LockGuard AI</h2>

    <p>Enterprise decision intelligence platform built on the SMA-03 / MSCA / EGDS stack. Identifies irreversible commitments before they crystallize and quantifies lock-in risk in real time.</p>

    <div class="metrics">
      <div class="metric"><span>87.5%</span>Validation Accuracy · N=120</div>
      <div class="metric"><span class="amber">79%</span>II-score Variance (FD)</div>
      <div class="metric"><span>4</span>Gov. Checkpoints</div>
    </div>

    <hr />

    <h2>Academic Output</h2>

    <table>
      <thead>
        <tr>
          <th>#</th>
          <th>Paper</th>
          <th>Target</th>
          <th>Status</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>01</td>
          <td>Irreversibility Measurement in Organizational Decision-Making: SMA-03</td>
          <td>SSRN / JBR</td>
          <td><span class="badge b-gray">In Preparation</span></td>
        </tr>
        <tr>
          <td>02</td>
          <td>Execution-Gated Decision Systems: A Temporal Governance Framework</td>
          <td>Org Science / AMR / ASQ</td>
          <td><span class="badge b-gray">In Preparation</span></td>
        </tr>
        <tr>
          <td>03</td>
          <td>Monte Carlo Scenario Analysis for Strategic Option Evaluation: MSCA v6</td>
          <td>Journal of Business Research</td>
          <td><span class="badge b-gray">In Preparation</span></td>
        </tr>
        <tr>
          <td>04</td>
          <td>SMA-03: An Epistemological Perspective on Organizational Lock-In</td>
          <td>SSRN · ArXiv</td>
          <td><span class="badge b-amber">Preprint</span></td>
        </tr>
      </tbody>
    </table>

    <hr />

    <h2>License</h2>
    <div class="license-box">
      Copyright (c) 2025 Uberlandis Fiol Reyes — All rights reserved.<br/>
      See LICENSE file for full terms.
    </div>

  </div>
</body>
</html>
