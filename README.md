# Clarity Tax Path Check MVP

A static HTML/CSS/JavaScript MVP for the Clarity ITR guidance website.

## What is included

- Homepage with Clarity branding
- Start Filing / Tax Path Check flow
- Step-by-step wizard
- Profile and residency questions
- Income source selection
- Detailed capital gains module
- Interest income field for FD / bank interest
- Detailed deductions section
- Reset and start-over option
- Old regime vs new regime preview
- Tax calculation breakdown on review screen
- Estimated refund / tax payable output
- Document checklist output

## How to run locally

Just open `index.html` in Chrome, Safari, Edge, or Firefox.

No backend, database, npm install, or build step is required for this MVP.

## How to deploy on Vercel using GitHub

1. Create a new GitHub repository.
2. Upload all files from this folder into the repository root.
3. Go to Vercel.
4. Import the GitHub repository.
5. Deploy as a static site.

Vercel should detect this as a static project automatically because the main file is `index.html`.

## Important CA review note

This is a feedback/testing MVP. The tax logic is a preview engine for product validation and should be reviewed by a CA before being used for actual filing decisions.

Areas marked for deeper validation:

- Capital gains classification and special rates
- Debt mutual fund treatment
- Property capital gains and indexation / transition cases
- ESOP / RSU treatment
- Loss set-off and carry-forward logic
- NRI / DTAA handling
- Exact ITR form selection rules
- New regime vs old regime exceptions

## Suggested next product upgrades

- Add login and user data save
- Add document upload
- Add CA review dashboard
- Add backend API for rule engine
- Add PDF summary export
- Add admin-editable tax rules
