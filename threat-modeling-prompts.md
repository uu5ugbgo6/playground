# Threat Modeling Prompts

Quick prompts for design reviews and security assessments.

## Architecture
- What are the trust boundaries?
- Where does external input enter the system?
- What are the crown-jewel assets?
- Which components fail open vs fail closed?

## Data
- Is sensitive data encrypted at rest and in transit?
- Can users access resources outside their tenant?
- Are secrets managed outside the repo?

## Dependencies
- Are third-party dependencies pinned and scanned?
- Are known vulnerable versions blocked in CI?

## Operations
- How is access revoked after offboarding?
- Are security events logged and monitored?
- Is there a runbook for incident response?
