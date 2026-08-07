# Webgoat Sql Injection Labs

> A progressive set of WebGoat SQL exercises covering query construction, injection discovery, authorization abuse, query chaining, and destructive impact.

![Category](https://img.shields.io/badge/Category-Cybersecurity%20Labs-blue) ![Documentation](https://img.shields.io/badge/Documentation-English-success) ![Use](https://img.shields.io/badge/Use-Authorized%20Labs%20Only-critical)

## Overview

This repository consolidates related hands-on exercises into one organized portfolio project. Each lab remains in its own folder with a dedicated walkthrough, screenshots, source notes, objectives, commands or inputs, security concepts, and lessons learned.

## Ethical Use

All activities documented here were performed in intentionally vulnerable or controlled training environments. The material is provided for education, defensive understanding, and authorized security testing only.

## Repository Structure

```text
webgoat-sql-injection-labs/
├── README.md
└── labs/
    ├── webgoat-select-query/
    ├── webgoat-update-query/
    ├── webgoat-alter-table/
    ├── webgoat-grant-rights/
    ├── webgoat-boolean-injection/
    ├── webgoat-identify-injectable-field/
    ├── webgoat-authentication-tan-bypass/
    ├── webgoat-query-chaining-salary/
    └── webgoat-drop-table/
```

## Labs Included

| # | Lab |
|---:|---|
| 1 | [WebGoat Injection Intro - Lesson 2: SELECT Query](labs/webgoat-select-query/) |
| 2 | [WebGoat Injection Intro - Lesson 3: UPDATE Query](labs/webgoat-update-query/) |
| 3 | [WebGoat Injection Intro - Lesson 4: ALTER TABLE](labs/webgoat-alter-table/) |
| 4 | [WebGoat Injection Intro - Lesson 5: GRANT Rights](labs/webgoat-grant-rights/) |
| 5 | [WebGoat Injection Intro - Lesson 9: Boolean Injection](labs/webgoat-boolean-injection/) |
| 6 | [WebGoat Injection Intro - Lesson 10: Injectable Field Identification](labs/webgoat-identify-injectable-field/) |
| 7 | [WebGoat Injection Intro - Lesson 11: TAN Bypass](labs/webgoat-authentication-tan-bypass/) |
| 8 | [WebGoat Injection Intro - Lesson 12: Query Chaining](labs/webgoat-query-chaining-salary/) |
| 9 | [WebGoat Injection Intro - Lesson 13: DROP TABLE](labs/webgoat-drop-table/) |

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
