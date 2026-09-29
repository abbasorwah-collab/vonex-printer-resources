# Current Deployment Audit — 2026-09-29

A current web check shows vonex.ca already has a Cost Savings Estimator on the Managed Print page, including monthly print volume and estimated annual/monthly savings.

## Decision
Do NOT add a second generic savings calculator to the same page.

Instead:
1. Improve/validate the existing MPS estimator.
2. Add a separate Cost Per Page Calculator if it serves a distinct user need.
3. Add the Copier Lease Payment Estimator on the lease/rental page.
4. Add clear methodology/assumptions to every estimator.
5. Track calculator completion as a conversion event.
6. Add a relevant CTA after results.

## Existing MPS page
https://vonex.ca/managed-print

The current page already includes:
- Assessment & Optimization
- Cost-per-page audit
- Fleet management
- Remote monitoring
- Auto-supply ordering
- Cost-control reporting
- Cost savings estimator
- Lease/rental cross-link
- Print-audit CTA

## Recommended deployment order
### A. Lease/rental page
Deploy the copier lease payment estimator here.

### B. Printer repair page
Do not add a calculator unless it helps the user decide repair vs replacement. A repair-vs-replace tool would be more relevant.

### C. Managed print page
Keep the existing savings estimator and improve transparency rather than duplicating it.

### D. Content clusters
Use the calculators as supporting assets within the relevant articles and service pages, with natural internal links.

## Important
The GitHub project contains deployment-ready HTML/JS prototypes, but no direct deployment to vonex.ca has been performed because the current connected tools do not provide access to the vonex.ca website/CMS or its hosting account.

Never claim an asset is live until it has been deployed and verified on the actual site.
