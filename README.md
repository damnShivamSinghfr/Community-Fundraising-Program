# Community Fundraising Transparency Portal

**Course:** CSE326 | **Section:** [Your section] | **Team Roll No.:** [Your team roll no.]

## Team

| Name | Reg. No. | Contribution |
|------|----------|--------------|
| Lalit Kumar (Leader) | [Reg No] | [e.g. campaign pages, admin panel] |
| Shivam Singh | [Reg No] | [e.g. charts, CSV export, testing] |
| [Member 3, if any] | [Reg No] | [Contribution] |

## Problem

Community fundraising often suffers from unclear collection targets, contributions, and spending updates. People give money without knowing how much was collected or how it was spent.

## Objective

A transparent, frontend-only platform where communities can run fundraising campaigns and publish their progress, donations, and expenses in public, with admin verification and a full audit trail.

## Features

- **Campaign creation** with title, organizer, purpose, target amount, and deadline
- **Campaign list** with search, status filter, progress bars, and summary totals
- **Donations** with an anonymous option and a public donor history
- **Updates feed** on each campaign
- **Expense reporting** (expenses cannot exceed the money raised)
- **Admin panel** to verify or reject campaigns and expenses
- **Audit trail** that logs every action with a timestamp
- **Charts page** showing progress towards targets, donations per day, how much is spent, and anonymous vs named donations
- **CSV export** of all donations or of a single campaign

## Technology

Plain **HTML, CSS and JavaScript** in a single file (`index.html`). No frameworks, libraries, or backend. Data is stored in the browser using `localStorage`. Charts are drawn with inline SVG and CSS.

## How to run

1. Download or clone this repository.
2. Open `index.html` in Chrome, Edge, or Firefox.

Nothing needs to be installed.

## Admin login

Go to the **Admin** page. Demo password: `admin123`

## Suggested walkthrough

1. Open the home page and look at the campaigns and totals.
2. Open a verified campaign and make a donation.
3. Add an update and an expense.
4. Start a new campaign (it shows as "Awaiting verification").
5. Log in as admin, verify the campaign and the expense.
6. Open the Charts page.
7. Export the donations as CSV.
8. Check the audit trail in the admin panel.

## Limitations

- No real payments are processed; donations are a demo only.
- Data is saved only in the user's own browser, so it is not shared between users or devices.
- The admin password is stored in the code, which is not secure for real use.
- A production version would need a backend, a database, real authentication, and a payment gateway.

## Future work

Backend with a database, secure login for organizers and admins, online payment integration, email receipts, and document upload for expense bills.
