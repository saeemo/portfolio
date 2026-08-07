# Portswigger Xss Labs

> A practical portfolio of reflected, stored, and DOM-based cross-site scripting labs completed in controlled PortSwigger training environments.

![Category](https://img.shields.io/badge/Category-Cybersecurity%20Labs-blue) ![Documentation](https://img.shields.io/badge/Documentation-English-success) ![Use](https://img.shields.io/badge/Use-Authorized%20Labs%20Only-critical)

## Overview

This repository consolidates related hands-on exercises into one organized portfolio project. Each lab remains in its own folder with a dedicated walkthrough, screenshots, source notes, objectives, commands or inputs, security concepts, and lessons learned.

## Ethical Use

All activities documented here were performed in intentionally vulnerable or controlled training environments. The material is provided for education, defensive understanding, and authorized security testing only.

## Repository Structure

```text
portswigger-xss-labs/
├── README.md
└── labs/
    ├── reflected-xss-portswigger/
    ├── stored-xss-portswigger/
    ├── dom-xss-document-write/
    └── dom-xss-innerhtml-activity/
```

## Labs Included

| # | Lab |
|---:|---|
| 1 | [Reflected XSS in an HTML Context](labs/reflected-xss-portswigger/) |
| 2 | [Stored XSS Through Blog Comments](labs/stored-xss-portswigger/) |
| 3 | [DOM XSS in a document.write Sink](labs/dom-xss-document-write/) |
| 4 | [DOM XSS in an innerHTML Sink](labs/dom-xss-innerhtml-activity/) |

## Skills Demonstrated

- Structured security testing in authorized lab environments
- Technical documentation and evidence organization
- Vulnerability identification and impact analysis
- Clear explanation of objectives, methodology, and lessons learned
- Security-focused GitHub repository design

## How to Review

Open any folder under `labs/` and read its `README.md`. Supporting screenshots are stored in the lab's `images/` directory, while source-traceability notes are retained under `resources/`.

## Disclaimer

Do not apply the documented techniques against systems without explicit authorization.
