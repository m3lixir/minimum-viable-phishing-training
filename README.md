# Minimum Viable Phishing Training

A short, practical phishing-awareness training kit for small organizations and solo IT administrators.

The training focuses on three actions:

1. **Pause** when a request creates pressure or changes a normal process.
2. **Verify** through a trusted, independent channel.
3. **Report** suspicious messages and possible mistakes quickly.

This kit is part of **The Minimum Viable Phishing Program**. Its companion project, [Minimum Viable Phishing Campaign](https://github.com/m3lixir/minimum-viable-phishing-campaign), demonstrates campaign planning and reporting metrics using synthetic data.

## Contents

| File | Purpose |
|---|---|
| [TRAINING.md](TRAINING.md) | Employee-facing training and quick-reference guide |
| [EXERCISES.md](EXERCISES.md) | Three discussion scenarios |
| [FACILITATOR.md](FACILITATOR.md) | Setup, suggested answers, and delivery guidance |
| [examples/completion-log.csv](examples/completion-log.csv) | Synthetic training completion records |

## Who this is for

- Organizations with approximately 5–50 employees.
- Solo IT administrators and small operations teams.
- New-hire orientation, a team meeting, or a short refresher.

No software, accounts, paid services, or external infrastructure are required.

## Run the training

1. Open [FACILITATOR.md](FACILITATOR.md) and fill in your organization's reporting and escalation details.
2. Share [TRAINING.md](TRAINING.md) with employees.
3. Hold a 15-minute session using [EXERCISES.md](EXERCISES.md).
4. Use the facilitator guide to discuss responses and clarify local procedures.
5. Record completion using your organization's approved system.

| Activity | Time |
|---|---:|
| Reporting and verification basics | 5 minutes |
| Three scenario discussions | 8 minutes |
| Questions and local contacts | 2 minutes |

## Customize before use

Replace these placeholders in the materials:

- `[REPORTING METHOD]`
- `[SECURITY CONTACT]`
- `[URGENT CONTACT]`
- `[KNOWN VENDOR PHONE DIRECTORY]`

Test the reporting method before asking employees to use it. If forwarding messages as attachments is part of your process, confirm that employees can do so with the mail clients they use.

## Privacy and scope

The included completion log contains fictional identifiers only. Do not commit real employee names, training records, incident reports, or message content to a public repository.

The completion log records participation, not security proficiency. It is not a substitute for testing reporting procedures or maintaining technical controls such as multifactor authentication.

This kit does not send email, run phishing simulations, collect credentials, or track employee behavior.

## Sources

- [CISA and FBI: Protecting against account phishing](https://www.cisa.gov/sites/default/files/2024-10/cisa-fbi-protecting-against-irgc-phishing-508c.pdf)
- [Google: Avoid and report phishing emails](https://support.google.com/mail/answer/8253)
- [NIST: Phish Scale user guide](https://doi.org/10.6028/NIST.TN.2276)

## License

MIT. See [LICENSE](LICENSE).
