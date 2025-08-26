# Risk Assessment Report

## Overview
I reviewed a fictional healthcare environment against NIST 800-53 and captured common issues with practical recommendations.

## Findings I Noted
- Remote access missing MFA
- Password policies too weak (length & lockout)
- No recurring vulnerability scans
- Endpoints not patched consistently

## Recommendations
- Enforce MFA across remote access (AC-2)
- Strengthen password policy + lockouts (IA-5)
- Run quarterly vulnerability scans and track remediation (RA-5)
- Establish monthly patch windows and SLAs (SI-2)

## Outcome
I built a risk register (Excel) with likelihood, impact, and status to track remediation to closure.
