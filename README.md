# Audit Reports

This repository contains my smart contract security audit reports.

I use this repository to document my security research work, including vulnerability findings, proofs of concept, impact analysis, and recommended mitigations.

## What Each Report Includes

Each audit report may include:

* Protocol summary
* Audit scope
* Roles and trust assumptions
* Risk classification
* Executive summary
* Findings by severity
* Proofs of concept
* Recommended mitigations
* Gas and informational observations

## Severity Classification

Findings are generally classified as:

| Severity      | Description                                                                                                    |
| ------------- | -------------------------------------------------------------------------------------------------------------- |
| High          | Issues that may cause major loss of funds, broken core functionality, or severe protocol manipulation          |
| Medium        | Issues that may cause limited loss of funds, denial of service, incorrect accounting, or meaningful disruption |
| Low           | Minor issues with limited impact                                                                               |
| Gas           | Gas optimization opportunities                                                                                 |
| Informational | Code quality, maintainability, documentation, or best-practice improvements                                    |

## Methodology

My review process may include:

* Manual smart contract review
* Foundry-based testing
* Proof-of-concept exploit development
* Access control review
* Reentrancy and external call analysis
* Accounting and precision review
* Denial-of-service and edge-case testing
* Randomness and oracle-related risk review

## Repository Structure

```text
audit-reports/
├── PuppyRaffle/
│   └── PuppyRaffle_Audit_Report.pdf
├── PasswordStore/
│   └── PasswordStore_Audit_Report.pdf
└── README.md
```

## Disclaimer

These reports are created for educational, research, and portfolio purposes. A security review is time-boxed and does not guarantee that all vulnerabilities were found.

The reports do not represent an endorsement of any protocol, project, or business model.

## Author

**Abdullah Amr**
Smart Contract Security Researcher
