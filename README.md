# PayGuard: Zero-PII Autonomous Fraud Risk Engine

PayGuard is a privacy-first risk validation assistant built natively within the **IBM watsonx Orchestrate UI Console**. The system dynamically intercepts, aggregates, and scores non-identifiable payment metadata (transaction timestamps, velocity surges, and hardware configuration flags) in real-time. By decoupling systemic telemetry analysis from consumer identity profiles, it validates transactions with an advanced financial risk framework while maintaining compliance with strict banking privacy mandates.

---

## 🏗️ Core System Blueprint

The orchestrator combines precise system routing with an internal database loop to evaluate transaction threats over a multi-layered verification cycle:

### 1. Sequential 3-Skill Prompt Architecture
The core system script explicitly forces the orchestration engine to handle client data through a linear engineering execution loop:
* **[Skill 1: Risk Identification & Anomaly Check]** Maps localized request indicators against strict structural definitions (Time-Threat and Volume Multipliers).
* **[Skill 2: Quantitative Risk Scoring]** Evaluates the combined telemetry matrix by fetching exact, predetermined compliance severity values from ingested operational manuals.
* **[Skill 3: Enforcement & Strategic Mitigation Profile]** Translates the calculated risk index into strict, actionable security playbooks (Ledger Release, MFA Challenges, or Biometric Overrides).

### 2. Retrieval-Augmented Generation (RAG) Layer
A unified document reference framework is bound directly to the assistant's runtime layer. When a payment scenario is provided, the engine queries the ingested corporate security guidelines to pull risk-weight multipliers (+30, +35, +22) and clear enforcement parameters, completely eliminating data hallucinations.

### 3. Absolute PII Filtering Blueprint
The prompt workflow acts as an administrative data filter. It strictly prohibits the extraction, retention, or processing of primary account identifiers, phone metadata, consumer names, or credit card PAN lines, prioritizing total operational privacy.

---

## 🛠️ Local Build & Activation Steps

To set up a local mirror of this engineering environment on your machine:

1. Clone this repository structure:
   ```bash
   git clone https://github.com
   cd payguard-orchestrate-ui
   ```
2. Open `index.html` in a standard text editor.
3. Locate the script placement block at the bottom of the code, inject your custom asset credentials fetched from the watsonx Orchestrate chat integration UI workspace, and save the document.
4. Run the file directly in any modern browser to verify local initialization.

---

## 🔗 Live Interactive Deployment & Production Test Scenarios

The live cloud agent is integrated directly into this repository's web interface. 

👉 **To test the implementation:** Locate the floating chat application launcher in the bottom-right corner of this landing page, trigger the interface panel, and submit any of the following real-world payment crises to see the engine execute its live risk calculation:

* **The Typo/Fat-Finger Crisis:**  
  `"I accidentally type-faulted and authorized a UPI payment of ₹45,000 instead of ₹450 to a local vendor. Is there a way to recall or freeze this transaction before it completely settles?"`
  
* **The Late-Night Suspicious Account Drain:**  
  `"It is 2:30 AM and my phone just flashed an alert showing a ₹32,000 debit toward a rapid settlement crypto wallet. I did not initiate this. What immediate emergency security steps should I take?"`

* **The Transit Terminal QR Code Trap:**  
  `"I scanned a dynamic merchant QR code at a high-transit terminal and it immediately redirected my phone to process an automated wallet-draining authorization. Can you run a metadata risk check on this session?"`

* **The Suspicious Device/Hardware Hijack:**  
  `"I just set up a brand new smartphone and tried to link my primary digital wallet, but the app generated a critical warning flag. Check if it is safe to process a pending transaction from this unverified device profile."`
