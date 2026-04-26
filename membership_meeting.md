---
title: Membership Meeting — Beachwood HOA
---

<style>
:root {
  --c-primary:      #157878;
  --c-primary-dark: #0f5c5c;
  --c-surface:      #ffffff;
  --c-bg:           #f3f6f6;
  --c-text:         #1a1a1a;
  --c-muted:        #6b7280;
  --c-border:       #dde5e5;
  --c-badge-bg:     #e6f4f4;
  --c-badge-border: #a3cfcf;
  --c-notice-bg:    #eaf6f4;
  --c-notice-text:  #0d4f4f;
  --radius:         10px;
  --shadow:         0 1px 4px rgba(0,0,0,0.08), 0 0 0 1px var(--c-border);
}

body { background: var(--c-bg); }

.hoa-logo {
  text-align: center;
  padding: 16px 0 24px;
}
.hoa-logo img {
  max-width: 240px;
  height: auto;
  border-radius: 50%;
  box-shadow: 0 4px 20px rgba(0,0,0,0.15);
}

.page-nav {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  background: var(--c-surface);
  border-radius: var(--radius);
  box-shadow: var(--shadow);
  padding: 14px 18px;
  margin-bottom: 24px;
  align-items: center;
}
.page-nav a {
  display: inline-block;
  padding: 5px 16px;
  border-radius: 999px;
  background: var(--c-bg);
  color: var(--c-primary) !important;
  font-size: 0.85rem;
  font-weight: 600;
  text-decoration: none !important;
  border: 1px solid var(--c-border);
  transition: background 0.15s, color 0.15s, border-color 0.15s;
}
.page-nav a:hover {
  background: var(--c-primary);
  color: #fff !important;
  border-color: var(--c-primary);
}

.card {
  background: var(--c-surface);
  border-radius: var(--radius);
  box-shadow: var(--shadow);
  padding: 28px 32px;
  margin-bottom: 20px;
}
.card-title {
  display: flex;
  align-items: center;
  gap: 10px;
  font-size: 0.75rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  color: var(--c-muted);
  margin: 0 0 20px;
  padding-bottom: 14px;
  border-bottom: 1px solid var(--c-border);
}
.card-title::before {
  content: '';
  display: inline-block;
  width: 4px;
  height: 16px;
  background: var(--c-primary);
  border-radius: 2px;
  flex-shrink: 0;
}

.notice {
  background: var(--c-notice-bg);
  border-left: 3px solid var(--c-primary);
  border-radius: 0 6px 6px 0;
  padding: 10px 14px;
  font-size: 0.85rem;
  color: var(--c-notice-text);
  margin-bottom: 18px;
  line-height: 1.5;
}

.intro-banner {
  background: linear-gradient(135deg, var(--c-primary) 0%, var(--c-primary-dark) 100%);
  border-radius: var(--radius);
  box-shadow: 0 2px 8px rgba(21,120,120,0.25);
  padding: 22px 32px;
  margin-bottom: 20px;
  color: #fff;
  font-size: 0.95rem;
  line-height: 1.6;
}
.intro-banner strong {
  display: block;
  font-size: 1.05rem;
  font-weight: 700;
  margin-bottom: 4px;
  letter-spacing: 0.01em;
}

.data-table {
  width: 100%;
  border-collapse: collapse;
  font-size: 0.9rem;
  margin: 16px 0 4px;
}
.data-table thead th {
  text-align: left;
  padding: 8px 12px;
  font-size: 0.72rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.07em;
  color: var(--c-muted);
  border-bottom: 2px solid var(--c-border);
  background: none;
}
.data-table tbody td {
  padding: 12px;
  border-bottom: 1px solid var(--c-border);
  color: var(--c-text);
  vertical-align: top;
  line-height: 1.5;
}
.data-table tbody tr:last-child td { border-bottom: none; }
.data-table tbody tr:hover td { background: var(--c-bg); }
.data-table td.amount {
  text-align: right;
  font-variant-numeric: tabular-nums;
  white-space: nowrap;
}
.data-table td.row-label {
  font-weight: 700;
  font-size: 0.8rem;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  color: var(--c-muted);
}

.footnotes {
  margin-top: 14px;
  padding-top: 12px;
  border-top: 1px solid var(--c-border);
  font-size: 0.825rem;
  color: var(--c-muted);
  line-height: 1.6;
}
.footnotes p { margin: 4px 0; }

@media (max-width: 620px) {
  .intro-banner { padding: 18px 20px; }
  .card { padding: 20px; }
}
</style>

<div class="hoa-logo">
  <img src="Beachwood_logo.jpg" alt="Beachwood duck logo">
</div>

<div class="intro-banner">
  <strong>Annual Membership Meeting</strong>
  Details, agenda, proxy voting, and budget for the Beachwood HOA membership meeting.
</div>

<nav class="page-nav">
  <a href="index">&larr; Home</a>
  <a href="#meeting">Meeting Info</a>
  <a href="#agenda">Agenda</a>
  <a href="#proxy">Proxy Voting</a>
  <a href="#budget">Budget</a>
</nav>

<div class="card" id="meeting">
  <p class="card-title">Meeting Details</p>
  <p>Our next membership meeting will occur on <strong>10 November 2025</strong>, <strong>6:30&ndash;8:30&nbsp;pm</strong>, in the Box Car room of the <a href="https://maps.app.goo.gl/TuAAZmJCYW42ibkL9">Knightdale Recreation Center</a>.</p>
  <p>We conduct membership meetings in accordance with our <a href="https://drive.google.com/file/d/14MBkpzJXBb8arIgo56G_cxWHbkrlR2sa/view?usp=drive_link">bylaws</a> and <a href="https://www.boardeffect.com/blog/roberts-rules-of-order-cheat-sheet/">Robert&rsquo;s Rules of Order</a>. Please familiarize yourself with Robert&rsquo;s Rules if you plan to attend.</p>
  <p>We will elect 5 board members.</p>
</div>

<div class="card" id="agenda">
  <p class="card-title">Agenda</p>
  <div class="notice">We have hard start and stop times dictated by the venue. Please expect the moderator to keep things moving.</div>
  <table class="data-table">
    <thead>
      <tr>
        <th style="width:110px">Time (pm)</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>6:30</td><td>Doors open for board members to set up</td></tr>
      <tr><td>6:45</td><td>Doors open for everybody else</td></tr>
      <tr><td>6:50</td><td>Call to order. President&rsquo;s presentation. Q&amp;A, time permitting.</td></tr>
      <tr><td>7:20</td><td>Treasurer presents the budget. Budget Q&amp;A.</td></tr>
      <tr><td>7:30</td><td>Vote for amendments, if any, and board members. Candidates will get a short time to make their pitch.</td></tr>
      <tr><td>8:00</td><td>Election results, general Q&amp;A, and new business, if any.</td></tr>
    </tbody>
  </table>
  <p style="margin-top:20px;font-size:0.9rem">Topics in the President&rsquo;s presentation:</p>
  <ul style="font-size:0.9rem;line-height:1.7;margin:0">
    <li>Housekeeping from the last membership meeting
      <ul>
        <li>Should the treasurer be bonded? (Spoiler: The HOA&rsquo;s insurance policy covers malfeasance.)</li>
        <li>&ldquo;More community&rdquo;</li>
      </ul>
    </li>
    <li><a href="https://drive.google.com/file/d/1ArkkR1PGWGoYf3hp-uUHc3hhWEJncKj-/view?usp=drive_link">Proposed bylaws amendments</a> (subject to quorum)</li>
    <li>Enforcement of the covenants and restrictions
      <ul>
        <li>Grey areas</li>
        <li><a href="violations">Published procedures</a></li>
      </ul>
    </li>
  </ul>
</div>

<div class="card" id="proxy">
  <p class="card-title">Proxy Voting</p>
  <p>If you would like to delegate your voting power, please complete the <a href="https://drive.google.com/file/d/1A3-qK6Uwx0RRLl87cNTKFIwmqmo58lAB/view?usp=drive_link">proxy form</a> and mail it to the board post-marked no later than <strong>3 November 2025</strong>. Proxies mailed after that date will be discarded.</p>
</div>

<div class="card" id="budget">
  <p class="card-title">Budget</p>
  <table class="data-table">
    <thead>
      <tr>
        <th>Asset</th>
        <th>Liability</th>
        <th>Income</th>
        <th>Expense</th>
        <th class="amount">10 Nov 2025 &ndash; ~1 Nov 2026 ($)</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>Checking</td><td></td><td></td><td></td><td class="amount">35,338</td></tr>
      <tr><td colspan="4" class="row-label">Members&rsquo; Equity Beginning</td><td class="amount">35,338</td></tr>
      <tr><td></td><td></td><td>2026 dues AR</td><td></td><td class="amount">0</td></tr>
      <tr><td></td><td></td><td></td><td>Landscaping</td><td class="amount">(12,000)</td></tr>
      <tr><td></td><td></td><td></td><td>Fig buttercup</td><td class="amount">(1,000)</td></tr>
      <tr><td></td><td></td><td></td><td>Duke Energy (1)</td><td class="amount">(1,000)</td></tr>
      <tr><td></td><td></td><td></td><td>Insurance</td><td class="amount">(1,500)</td></tr>
      <tr><td></td><td></td><td></td><td>Tree removal</td><td class="amount">(5,000)</td></tr>
      <tr><td></td><td></td><td></td><td>Admin (2)</td><td class="amount">(300)</td></tr>
      <tr><td colspan="4" class="row-label">Members&rsquo; Equity Ending</td><td class="amount">14,538</td></tr>
    </tbody>
  </table>
  <div class="footnotes">
    <p>AR = accounts receivable</p>
    <p>(1) The HOA pays Duke Energy for the lights around the sign at the neighborhood entrance.</p>
    <p>(2) &ldquo;Admin&rdquo; includes mailing expenses and filing fees, such as updating the HOA entity&rsquo;s registered agent.</p>
  </div>
</div>
