---
title: Violations
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
.page-nav .nav-home {
  color: var(--c-muted) !important;
  font-weight: 500;
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

/* --- Notice banner --- */
.notice {
  background: var(--c-notice-bg);
  border-left: 3px solid var(--c-primary);
  border-radius: 0 6px 6px 0;
  padding: 10px 14px;
  font-size: 0.875rem;
  color: var(--c-notice-text);
  margin-bottom: 18px;
  line-height: 1.55;
}

/* --- Legal blockquote --- */
.legal-quote {
  background: var(--c-bg);
  border-left: 3px solid var(--c-border);
  border-radius: 0 6px 6px 0;
  padding: 14px 18px;
  font-size: 0.875rem;
  color: var(--c-muted);
  margin: 16px 0 20px;
  font-style: italic;
  line-height: 1.65;
}
.legal-quote a { color: var(--c-primary) !important; }

/* --- Subsection heading --- */
.subsection-heading {
  font-size: 0.875rem;
  font-weight: 700;
  color: var(--c-text);
  margin: 28px 0 14px;
  padding-bottom: 8px;
  border-bottom: 1px solid var(--c-border);
}
.subsection-heading:first-of-type { margin-top: 8px; }

/* --- Numbered step list --- */
.step-list {
  padding-left: 0;
  list-style: none;
  counter-reset: step;
  margin: 0;
}
.step-list li {
  counter-increment: step;
  display: flex;
  gap: 14px;
  padding: 13px 0;
  border-bottom: 1px solid var(--c-border);
  font-size: 0.9rem;
  line-height: 1.65;
  color: var(--c-text);
}
.step-list li:last-child { border-bottom: none; padding-bottom: 4px; }
.step-list li::before {
  content: counter(step);
  display: flex;
  align-items: center;
  justify-content: center;
  min-width: 26px;
  height: 26px;
  border-radius: 50%;
  background: var(--c-primary);
  color: #fff;
  font-size: 0.72rem;
  font-weight: 700;
  flex-shrink: 0;
  margin-top: 2px;
}

/* --- Example callout --- */
.example-box {
  background: #fefce8;
  border: 1px solid #fde68a;
  border-radius: 6px;
  padding: 16px 18px;
  margin-top: 24px;
  font-size: 0.875rem;
  color: #713f12;
  line-height: 1.65;
}
.example-label {
  font-size: 0.72rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  color: #92400e;
  margin-bottom: 6px;
}

@media (max-width: 620px) {
  .card { padding: 20px; }
}
</style>

<nav class="page-nav">
  <a class="nav-home" href="index">← Home</a>
  <a href="#authority">Legal Authority</a>
  <a href="#parking">Parking Rules</a>
  <a href="#architectural">Architectural</a>
  <a href="#non-architectural">Non-Architectural</a>
</nav>

<div class="card" id="authority">
  <p class="card-title">Legal Authority</p>
  <p><a href="https://drive.google.com/file/d/1sXEQ5biblpdFaENFtViTgPRbcpOQYm-x/view?usp=drive_link">Declarations</a> Article&nbsp;10, Section&nbsp;4(e) states that residents shall maintain adequate off-street parking. Article&nbsp;10, Section&nbsp;3 discusses &ldquo;lot appearance,&rdquo; and Article&nbsp;10, Section&nbsp;5 discusses the authority of the board to publish and enforce reasonable rules.</p>
  <p>Article&nbsp;10, Section&nbsp;5 of the Declarations and Covenants, as amended in 2004, states:</p>
  <blockquote class="legal-quote">Section 5: Rules and Regulations. The Board of Directors of the Association shall have the power to formulate, publish, amend and enforce reasonable rules and regulations concerning the use and enjoyment of the front yard space of each lot and the Common Areas. Such rules and regulations may also provide for imposition, in accordance with <a href="https://www.ncleg.gov/EnactedLegislation/Statutes/PDF/BySection/Chapter_47F/GS_47F-3-107.1.pdf">G.S.&nbsp;47F-3-107.1</a>, of fines or penalties for the violation thereof, or for the violation of any of the covenants and conditions contained in this declaration.</blockquote>
</div>

<div class="card" id="parking">
  <p class="card-title">Permissible Parking</p>
  <div class="notice"><strong>Parking vehicles on grass, gravel, wood chips, or other impermanent surfaces is prohibited.</strong> Please park your vehicles only in your garage, driveway, or other paved location on your property.</div>
  <p>Guests may park on the street only when there is no room in your driveway, and their vehicles should not remain on the street overnight.</p>
  <p style="font-size:0.85rem;color:var(--c-muted);">As promulgated in the <a href="https://drive.google.com/file/d/1_BPEEH8AAY6GXagRj1WZ5ZmLP6PUNcJA/view?usp=drive_link">September 2025 newsletter</a>.</p>
</div>

<div class="card" id="architectural">
  <p class="card-title">Architectural Controls Violations</p>
  <p>Declarations and Covenants Article&nbsp;7, &ldquo;Architectural Controls,&rdquo; requires all owners to submit architectural change plans to the board prior to certain modifications to a property.</p>
  <div class="notice">Payment of violation fines shall be by check or money order to the HOA&rsquo;s published mailing address. Partial payments shall not be accepted without prior consent of the board.</div>
  <ol class="step-list">
    <li>Owners who make modifications without prior approval, or after disapproval, shall be fined <strong>$100</strong> immediately upon the board learning of the modifications. Payment is due within 2&nbsp;weeks or the date stated in the violation notice (whichever is later).</li>
    <li>Every calendar week after the payment due date that payment is not received, an additional <strong>$100</strong> shall be added to the amount due.</li>
    <li>Disapproved modifications (whether approval was sought in advance or not), if any, shall be removed or reverted promptly at the owner&rsquo;s expense.</li>
    <li>If the full amount of the fine is not paid within 6&nbsp;months, the HOA shall levy liens against the property.</li>
  </ol>
</div>

<div class="card" id="non-architectural">
  <p class="card-title">Non-Architectural Violations</p>
  <div class="notice">Payment of violation fines shall be by check or money order to the HOA&rsquo;s published mailing address. Partial payments shall not be accepted without prior consent of the board.</div>
  <ol class="step-list">
    <li>Offending property owners shall receive written notice (by e-mail or postal mail) containing a citation, a photograph of the condition(s) to remedy (when appropriate and available), and a deadline for remediation.</li>
    <li>Violations related to improperly parked vehicles, including trailers, shall have a deadline no longer than 2&nbsp;calendar days after notice is given. For postal mail, the notice date is 5&nbsp;days after the postmark date. For all other violations, the deadline shall be no longer than 2&nbsp;calendar weeks. For e-mail, the notice date is 2&nbsp;days after the message is sent.</li>
    <li>The board will also impose a fine of <strong>$30 per offense</strong> upon the initial notice if the owner has received a violation notice for the same violation within the past 6&nbsp;months. For violations related to improperly parked vehicles, each vehicle is a separate offense. (Each offense does not require a separate violation notice.)</li>
    <li>If the violating condition is not remedied by the deadline, including payment of any fines, the HOA shall send a &ldquo;Final Violation Notice.&rdquo; If a fine was not previously imposed, the final notice shall include a fine. The fine shall be augmented by the original amount each calendar week after the final notice date. If a fine is not paid within 6&nbsp;months of notification of the first fine, the HOA shall levy liens against the property.</li>
    <li>For violation notices issued by postal mail, the remedy shall include the owner providing the HOA with a current e-mail address.</li>
  </ol>
  <div class="example-box">
    <div class="example-label">Example &mdash; Parking Violation</div>
    The HOA documents 2 improperly parked vehicles on January&nbsp;1st. The HOA cites the owner, who is a repeat offender, by mail and imposes a <strong>$60 fine</strong> ($30 per vehicle). The notice is postmarked Monday, January&nbsp;5th, making the notice date Saturday, January&nbsp;10th. The vehicles must be moved no later than <strong>January&nbsp;12th</strong> (2&nbsp;days after the notice date).
  </div>
</div>
