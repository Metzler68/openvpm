# Summerfields PIMS — AI Development Instructions

## Project Objective
Develop a customized veterinary practice management system based on OpenVPM for Summerfields Animal Hospital.

DaySmart Vet remains the live production PIMS throughout development. This repository is for development and testing only.

## Development Principles
1. Inspect existing code, documentation, and tests before proposing changes.
2. Reuse existing OpenVPM functionality wherever possible.
3. Make small, reversible changes on the summerfields-development branch.
4. Do not modify the main branch or deploy to production without explicit authorization.
5. Do not access or use real client, patient, employee, or financial records during development. Use fictional test data.
6. Never commit passwords, API keys, tokens, or other secrets.
7. Preserve existing license notices and follow AGPLv3 obligations.
8. Do not assume external integrations, including DaySmart Vet and Zoetis, are available without verifying their access and terms.
9. Require human clinical review of AI-generated records, medication calculations, prescriptions, and treatment recommendations.
10. Protect data integrity, security, audit trails, permissions, and backup procedures.
11. Add or update tests for every functional change.
12. Do not claim success without verifying the changed functionality and reporting what was actually tested.

## AI Credit Protection
- Diagnose problems before modifying code.
- Avoid unnecessary rewrites and speculative attempts.
- Prefer non-credit-consuming verification methods where possible.
- Label repairs to existing work as FIX or CORRECTION.
- Stop and request approval before corrective work that will consume additional AI credits due to a platform rule.
- Explain proposed changes and estimated effort before major development work.

## Initial Priorities
1. Audit OpenVPM's existing capabilities and architecture.
2. Establish a reproducible development and testing environment.
3. Document Summerfields-specific clinical workflows.
4. Develop and validate one small customization at a time.
5. Keep all development isolated from DaySmart Vet and hospital production systems.
