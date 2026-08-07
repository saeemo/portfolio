# Seed Sql Injection Labs

> A structured collection of SQL injection exercises completed in the SEED security lab environment, covering authentication bypass and unauthorized data modification.

![Category](https://img.shields.io/badge/Category-Cybersecurity%20Labs-blue) ![Documentation](https://img.shields.io/badge/Documentation-English-success) ![Use](https://img.shields.io/badge/Use-Authorized%20Labs%20Only-critical)

## Overview

This repository consolidates related hands-on exercises into one organized portfolio project. Each lab remains in its own folder with a dedicated walkthrough, screenshots, source notes, objectives, commands or inputs, security concepts, and lessons learned.

## Ethical Use

All activities documented here were performed in intentionally vulnerable or controlled training environments. The material is provided for education, defensive understanding, and authorized security testing only.

## Repository Structure

```text
seed-sql-injection-labs/
├── README.md
└── labs/
    ├── seed-sqli-admin-login/
    ├── seed-sqli-update-own-salary/
    ├── seed-sqli-modify-other-user-salary/
    └── seed-sqli-change-password-hash/
```

## Labs Included

| # | Lab |
|---:|---|
| 1 | [SQL Injection Authentication Bypass](labs/seed-sqli-admin-login/) |
| 2 | [Updating Alice’s Salary Through SQL Injection](labs/seed-sqli-update-own-salary/) |
| 3 | [Modifying Another User’s Salary Through SQL Injection](labs/seed-sqli-modify-other-user-salary/) |
| 4 | [Changing Boby’s Password Hash Through SQL Injection](labs/seed-sqli-change-password-hash/) |

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
