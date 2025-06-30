# html-phishing-techniques-educational
A simple educational project demonstrating how HTML and JavaScript can simulate browser-based download triggers, often used in phishing and malware attacks. Includes realistic fake invoice examples for awareness and training.


Overview

This project explores how basic HTML and JavaScript can simulate **download triggers**—both obvious and stealthy—in ways that mimic common phishing and malware tactics. These examples are designed purely for **educational and awareness** purposes.

##  Project Objective

- Demonstrate how front-end code can be used to trigger file downloads
- Highlight legitimate vs. malicious use cases
- Educate developers, students, and cybersecurity enthusiasts on how these tricks work
- Provide realistic “invoice” examples often used in phishing schemes

##  Included Examples

### 1. `Fake_Invoice_With_Redirect.html`
**Concept:** Redirects the user to a hosted file immediately upon page load.

-  **How it works:** Uses `window.location.href` in JavaScript
-  **Legit use:** Redirect after clicking “Download Invoice”
-  **Abuse case:** Directing users to a fake login or disguised malware

### 2. `Fake_Invoice_Background_Download.html`
**Concept:** Invisibly triggers a download behind a seemingly normal invoice page.

-  **How it works:** Simulates a silent dropper using a hidden `<a>` element
   **Legit use:** Auto-downloads tickets or documents
- **Abuse case:** Drops an `.exe` file without user awareness

##  Why These Files Look Real

Both invoice examples include styled content, company names, totals, and email information to resemble genuine business communications—a common phishing tactic.

> These realistic visuals add to the deceptive power when abused by attackers.

##  Security & Browser Notes

Modern browsers:
- Block unauthorized executable downloads
- Warn users of suspicious file types
- Monitor links with tools like Safe Browsing and SmartScreen

Still, **older systems or misconfigured browsers** remain vulnerable.

##  Ethical Disclaimer

This repository is for **learning and ethical cybersecurity testing only**. Never use these techniques on real users or live systems without clear permission.

> Knowing how an attack works is the first step toward stopping it.

##  Learning Outcome

Understanding these behaviors helps you:
- Detect phishing emails and fake invoices
- Educate others about digital hygiene
- Build safer web applications

---
Author: CyberA1eX



