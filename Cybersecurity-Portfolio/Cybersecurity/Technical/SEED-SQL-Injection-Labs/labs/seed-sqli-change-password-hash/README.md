# Changing Boby’s Password Hash Through SQL Injection

![Category](https://img.shields.io/badge/Category-SQL%20Injection-blue)
![Environment](https://img.shields.io/badge/Environment-Authorized%20Training-success)
![Documentation](https://img.shields.io/badge/Documentation-Portfolio-informational)

## Overview

A SEED Labs activity combining password hashing with SQL injection to replace another test user’s stored password hash.

## Objective

Generate the SHA-1 hash of the lab password, inject the resulting value into the vulnerable update path, and verify that the new password works while the old one fails.

## Ethical Scope

This repository documents an exercise completed in an authorized training environment. It must not be used against systems, accounts, or people without explicit permission. All credentials, targets, and payloads referenced here are limited to disposable lab resources.

## Skills Demonstrated

- Password-hash generation
- Command-line hashing
- SQL update manipulation
- Authentication verification

## Tools Used

- SEED VM
- Linux terminal
- sha1sum
- Firefox

## Lab Environment

Local SEED SQL Injection training application using the Boby test account.

## Step-by-Step Walkthrough

1. Choose the lab password attacker.
2. Generate its SHA-1 digest in the terminal.
3. Use the resulting hash in the vulnerable SQL update flow to replace Boby’s password value.
4. Attempt login with the old password seedboby and record the failure.
5. Attempt login with attacker and record the successful result.
6. Explain why modern password storage should use salted, slow password-hashing algorithms instead of SHA-1.

## Commands and Test Inputs

```text
echo -n "attacker" | sha1sum
```

## Security Concepts

- Password databases store hashes rather than plaintext, but weak hashing remains dangerous.
- SQL injection can be used to modify credential material and take over accounts.

## Defensive Recommendations

- Use secure coding controls appropriate to the demonstrated weakness.
- Apply least privilege and strong server-side authorization.
- Log and alert on suspicious input, authentication, and data-change patterns.
- Keep testing isolated and limited to explicitly authorized targets.

## MITRE ATT&CK Mapping

MITRE ATT&CK Enterprise: T1098 - Account Manipulation (conceptual mapping in a training application).

## Lessons Learned

- Hash format and application expectations must match for authentication to succeed.
- Modern systems should use Argon2, scrypt, or bcrypt with unique salts.

## Evidence

![Source material - page 3](images/source-page-03.png)

## Source Material

- `SQL Injection KAUST SEED VM.pdf`
- Relevant source pages: 3

## Disclaimer

This project is provided for education, defensive learning, and portfolio documentation. It does not authorize testing of third-party systems.
