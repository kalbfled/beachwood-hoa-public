---
title: Beachwood Homeowners Association, Inc.
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

/* --- Page background --- */
body { background: var(--c-bg); }

/* --- Logo --- */
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

/* --- Pill navigation --- */
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

/* --- Cards --- */
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

/* --- Two-column grid --- */
.grid-2 {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
  margin-bottom: 20px;
}
@media (max-width: 620px) {
  .grid-2 { grid-template-columns: 1fr; }
  .card { padding: 20px; }
}

/* --- News empty state --- */
.no-news {
  text-align: center;
  padding: 20px 0 8px;
  color: var(--c-muted);
  font-size: 0.95rem;
  font-style: italic;
}

/* --- Notice banner --- */
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

/* --- Contact channels --- */
.contact-row {
  display: flex;
  gap: 14px;
  padding: 11px 0;
  border-bottom: 1px solid var(--c-border);
  font-size: 0.9rem;
}
.contact-row:last-child { border-bottom: none; }
.contact-label {
  min-width: 52px;
  font-size: 0.72rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.07em;
  color: var(--c-muted);
  padding-top: 2px;
}
.contact-value a {
  color: var(--c-primary) !important;
  font-weight: 500;
}

/* --- Dues display --- */
.dues-amount {
  font-size: 3rem;
  font-weight: 800;
  color: var(--c-primary);
  line-height: 1;
  margin: 4px 0 2px;
}
.dues-label {
  font-size: 0.8rem;
  color: var(--c-muted);
  margin-bottom: 14px;
}
.dues-instructions {
  font-size: 0.875rem;
  color: var(--c-text);
  line-height: 1.55;
}

/* --- Call-to-action button --- */
.btn {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  padding: 10px 22px;
  background: var(--c-primary);
  color: #fff !important;
  border-radius: 6px;
  text-decoration: none !important;
  font-weight: 600;
  font-size: 0.875rem;
  margin-top: 12px;
  transition: background 0.15s;
}
.btn:hover { background: var(--c-primary-dark); }
.btn-arrow { font-size: 1rem; }

/* --- Board table --- */
.board-table {
  width: 100%;
  border-collapse: collapse;
  font-size: 0.9rem;
}
.board-table thead th {
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
.board-table tbody td {
  padding: 12px;
  border-bottom: 1px solid var(--c-border);
  color: var(--c-text);
}
.board-table tbody tr:last-child td { border-bottom: none; }
.board-table tbody tr:hover td { background: var(--c-bg); }
.badge {
  display: inline-block;
  padding: 2px 11px;
  border-radius: 999px;
  background: var(--c-badge-bg);
  color: var(--c-primary);
  font-size: 0.78rem;
  font-weight: 600;
  border: 1px solid var(--c-badge-border);
}

/* --- Intro banner --- */
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
@media (max-width: 620px) {
  .intro-banner { padding: 18px 20px; }
}

/* --- Board links disclosure --- */
.board-links {
  margin-top: 18px;
  padding-top: 16px;
  border-top: 1px solid var(--c-border);
}
.board-links summary {
  cursor: pointer;
  font-size: 0.82rem;
  color: var(--c-muted);
  font-weight: 600;
  list-style: none;
  user-select: none;
}
.board-links summary::-webkit-details-marker { display: none; }
.board-links summary::before { content: '▶\00a0'; font-size: 0.65rem; }
.board-links[open] summary::before { content: '▼\00a0'; }
.board-links ul {
  margin: 12px 0 4px;
  padding-left: 16px;
}
.board-links li { padding: 3px 0; }
.board-links a { font-size: 0.875rem; color: var(--c-primary) !important; }
</style>

<div class="hoa-logo">
  <img src="Beachwood_logo.jpg" alt="Beachwood duck logo">
</div>

<div class="intro-banner">
  <strong>Beachwood Homeowners Association, Inc.</strong>
  This is the website for the Beachwood subdivision of Wake County, NC.
</div>

<nav class="page-nav">
  <a href="#news">News</a>
  <a href="#contact">Contact</a>
  <a href="#dues">Dues</a>
  <a href="#violations">Violations</a>
  <a href="#documents">Documents</a>
  <a href="membership_meeting">Meetings</a>
  <a href="#board">Board</a>
</nav>

<div class="card" id="news">
  <p class="card-title">News</p>
  <p class="no-news">No current announcements.</p>
</div>

<div class="grid-2">

  <div class="card" id="contact">
    <p class="card-title">Contact</p>
    <p class="notice">This website, occasional mailings, and the email address below are the <strong>only official channels</strong>. We do not use social media or distribute newsletters.</p>
    <div class="contact-row">
      <span class="contact-label">Email</span>
      <span class="contact-value"><a href="mailto:beachwood.hoa.inc@gmail.com">beachwood.hoa.inc@gmail.com</a></span>
    </div>
    <div class="contact-row">
      <span class="contact-label">Mail</span>
      <span class="contact-value">Beachwood Homeowners Association, Inc.<br>P.O. Box 1198<br>Knightdale, NC 27545</span>
    </div>
  </div>

  <div class="card" id="dues">
    <p class="card-title">HOA Dues</p>
    <div class="dues-amount">$243</div>
    <div class="dues-label">Annual assessment &mdash; 2026</div>
    <p class="dues-instructions">Send a check or money order payable to &ldquo;Beachwood Homeowners Association, Inc.&rdquo; to the mailing address. Please include your <strong>property address</strong> in the memo line.</p>
  </div>

</div>

<div class="card" id="violations">
  <p class="card-title">Violations</p>
  <p>All homeowners are bound by the <a href="https://drive.google.com/file/d/1sXEQ5biblpdFaENFtViTgPRbcpOQYm-x/view?usp=drive_link">Covenants and Restrictions</a>, including amendments. Violations are handled in accordance with the HOA&rsquo;s <a href="violations">published procedures</a>.</p>
</div>

<div class="card" id="documents">
  <p class="card-title">Documents &amp; Records</p>
  <p>Public documents &mdash; board meeting minutes, governing documents, architectural forms, notices, and more &mdash; are available on Google Drive. Membership meeting details, including agendas, proxy voting, and budget summaries, are on the <a href="membership_meeting">Meetings page</a>.</p>
  <a class="btn" href="https://drive.google.com/drive/folders/1_-tm8V_nUE70x1_UTEimFcTi776MbLtS?usp=drive_link">
    View public documents <span class="btn-arrow">&rarr;</span>
  </a>
</div>

<div class="card" id="board">
  <p class="card-title">Board Members</p>
  <p>The HOA is a NC not-for-profit entity. Board members serve 2-year terms. All current seats were elected in November&nbsp;2025; the next election is <strong>November&nbsp;2027</strong>.</p>
  <table class="board-table">
    <thead>
      <tr>
        <th>Name</th>
        <th>Position</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>Clyde Thompson</td><td><span class="badge">President</span></td></tr>
      <tr><td>Justin Murphy</td><td><span class="badge">Vice President</span></td></tr>
      <tr><td>Sal LaRocca</td><td><span class="badge">Treasurer</span></td></tr>
      <tr><td>Rob Jones</td><td><span class="badge">Secretary</span></td></tr>
      <tr><td>Perri Davenport</td><td><span class="badge">Member</span></td></tr>
    </tbody>
  </table>
  <details class="board-links" open>
    <summary>Board member links</summary>
    <ul>
      <li><a href="https://github.com/users/saljinlr/projects/1">Project board</a></li>
      <li><a href="https://github.com/saljinlr/beachwood-hoa">Knowledge repository</a></li>
      <li><a href="https://drive.google.com/drive/folders/1FTfRWxEOffus-xh-Zg0sHXluXewCWweB?usp=drive_link">Beachwood HOA private Google Drive</a></li>
    </ul>
  </details>
</div>
