# Project plan overview

This document summarizes the high-level plan based on Lab 1 estimates.

## Functional requirements

FR1 - FR21 are grouped into feature blocks:

- Catalog and search (FR1, FR2, FR18)
- Authentication and profile (FR3, FR4)
- Product card and checkout (FR5, FR6, FR7, FR8, FR12)
- Delivery and external services (FR9, FR14, FR16, FR17)
- History, bonuses, reviews, notifications (FR10, FR11, FR13, FR15)
- Admin panel (FR19, FR20, FR21)

Each block corresponds to a feature branch and a set of YouTrack issues.

## Branch model

- `main` - production branch for final report
- `develop` - integration branch
- `feature/*` - feature branches per feature block
- `release/*` - release branches for 0.1.0 (MVP) and 1.0.0
