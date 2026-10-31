# ppal-portal

Optional web portal for the broader PantryPal project. The portal is not part of the accepted mobile MVP and is not required for Activity 3 delivery.

## Scope status

- Status: out of the current MVP.
- The required client for the course deliverable is ppal-app, built with Ionic, Angular, and Capacitor.
- Do not add portal-only scope to the mobile release backlog unless an explicit scope decision is approved.

## Repository workflow

This repository uses develop for integration, qa for verification, and main for approved releases. Submit changes through a short-lived feat/, fix/, chore/, or docs/ branch and a pull request. Do not commit directly to protected branches or use force-push.

## Shared project governance

The authoritative project scope, ADRs, API contract, and release guidance live in ppal-docs. Separate repositories organize source code; they do not imply a microservice per repository.

## Security

Do not publish sensitive data or secrets. Any future public portal needs a separate scope decision and security review before deployment.
