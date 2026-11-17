# Facilitator Guide

## Before the session

Complete these steps before distributing the training:

1. Replace the placeholders in `TRAINING.md` with your organization's actual reporting and escalation contacts.
2. Test the reporting process from the mail clients employees use.
3. Confirm who monitors reports, when they are available, and what employees should do if the primary contact is unavailable.
4. Confirm how employees should independently verify vendor payment changes.
5. Read the scenarios and adapt details to match normal company workflows.

Do not use real passwords, MFA codes, payment details, or sensitive customer information in training.

## Session plan

### Minutes 0–5: Explain the reporting path

Walk through the three actions in `TRAINING.md`: pause, verify, report.

Demonstrate the approved reporting method using a harmless example. Explain the fallback and urgent contact. Make clear that employees should report mistakes promptly and will receive help.

### Minutes 5–13: Discuss the scenarios

Ask employees what they would do. Focus on the decision and reporting process, not on tricking someone into the “wrong” answer.

#### Scenario 1: Account alert

**Expected response:** Do not use the message's link. Open the service using a known bookmark or address, check the account directly, and report the message.

**Discussion point:** An urgent deadline and a familiar service name do not establish that the request is legitimate.

#### Scenario 2: Vendor payment change

**Expected response:** Verify the requested change using a vendor contact from an established directory or other independently verified source. Follow the organization's payment-change approval process and report suspicious requests.

**Discussion point:** A familiar sender address alone may not be enough; a vendor's account could be compromised.

#### Scenario 3: Shared document

**Expected response:** Ask the coworker through an established channel whether they intended to share the document. Do not enter credentials through the unexpected link while the request remains unverified. Report suspicious messages.

**Discussion point:** A displayed sender name can be misleading.

#### Follow-up: Someone already interacted

**Expected response:** Contact the urgent IT contact immediately and explain what happened: for example, whether a link was opened, credentials or a code were entered, an MFA prompt was approved, a file was opened, or money was sent.

**Discussion point:** Fast reporting gives IT a chance to assess and respond. Avoid blame.

### Minutes 13–15: Reinforce the local process

Repeat:

- The primary reporting method.
- The fallback.
- The urgent contact.
- The independent verification process for payment changes.

Ask whether anyone sees a practical obstacle to following the process.

## After the session

- Record completion in your approved system.
- Note process questions or obstacles without recording unnecessary personal details.
- Fix unclear instructions and update the training.
- Include the training in onboarding and revisit it periodically.

Completion demonstrates participation. It does not prove that someone will recognize every phishing attempt.

## Relationship to simulations

This kit can be used without a phishing simulation. If your organization also runs one, obtain written authorization and follow the boundaries and reporting procedures described in **The Minimum Viable Phishing Program**.

The companion `minimum-viable-phishing-campaign` project demonstrates campaign planning and metrics using synthetic data; it does not send emails or run live simulations.

Do not commit actual training records or simulation results to a public repository.
