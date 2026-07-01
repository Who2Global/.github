# Contributing to Who2Global Repositories

This guide explains the expected contribution process for repositories owned by the Who2Global GitHub organisation.

## Before making changes

Before starting work, check:

* The issue or request is clearly understood
* The correct repository is being changed
* No secrets, credentials or customer-sensitive information are included
* Any related documentation has been reviewed
* The change fits the purpose of the repository

## Branches

Work should be completed on a branch, not directly on `main`.

Use clear branch names, such as:

* `feature/add-report-export`
* `fix/login-error-handling`
* `docs/update-deployment-notes`
* `security/tighten-permissions`

## Pull requests

Changes should be submitted using a pull request.

A pull request should explain:

* What changed
* Why the change is needed
* How it was tested
* Any security or deployment impact
* Whether AI tools were used to support the work

## AI-assisted development

AI tools may be used to support development, documentation, review and troubleshooting.

AI-generated output must still be reviewed, tested and understood by a responsible human before it is merged.

Do not use AI tools to process secrets, credentials, private customer data or confidential material unless the use has been explicitly approved.

## Security expectations

Never commit:

* Passwords
* Tokens
* API keys
* Certificates
* `.env` files
* Production credentials
* Private customer data

If a secret is accidentally committed, treat it as compromised and raise it immediately.

## Review expectations

Reviewers should check:

* The change is clear and necessary
* The implementation is maintainable
* Tests and checks have been completed
* Security risks have been considered
* Documentation has been updated where needed

## Documentation

Documentation should be updated when a change affects:

* Setup steps
* User behaviour
* Architecture
* Deployment
* Configuration
* Operations
* Security

## Standard of work

Who2Global repositories should stay clean, understandable and safe to maintain.

Small, well-documented changes are preferred over large unclear changes.
