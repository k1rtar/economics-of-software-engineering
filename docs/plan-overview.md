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

## Feature: Catalog and search (FR1, FR2, FR18)

Scope:
- FR1 – basic catalog of digital goods with categories and pagination.
- FR2 – search by product name and description.
- FR18 – advanced filters (price range, platform, region).

YouTrack:
- Epics: KUP-1 (Catalog), KUP-2 (Search).
- Tasks: KUP-10..KUP-19 – backend API, UI, filters.

Sprint: 1  
Planned release: 0.1.0 (MVP)  
Git branch: `feature/catalog-search`

## Feature: Authentication and profile (FR3, FR4)

Scope:
- FR3 – login via VK and Telegram (social auth).
- FR4 – user profile page with personal data and quick access to purchase history.

YouTrack:
- Epics: KUP-3 (Social login), KUP-4 (Profile).
- Tasks: KUP-20..KUP-29 – OAuth integration, sessions, profile UI.

Sprint: 1  
Planned release: 0.1.0 (MVP)  
Git branch: `feature/auth-profile`

## Feature: Product card and checkout (FR5, FR6, FR7, FR8, FR12)

Scope:
- FR5 – product card with description, images, price, platform and region.
- FR6 – purchase flow for a single product.
- FR7 – applying and validating promo codes.
- FR8 – checkout page (contact data, payment method).
- FR12 – delivery method selection inside checkout.

YouTrack:
- Epics: KUP-5 (Product card), KUP-6 (Checkout).
- Tasks: KUP-30..KUP-49 – payment integration, promo codes, delivery options.

Sprint: 2  
Planned release: 0.1.0 (MVP)  
Git branch: `feature/product-checkout`

## Feature: Delivery and external services (FR9, FR14, FR16, FR17)

Scope:
- FR9 – instant delivery / account top-up after payment.
- FR14 – Steam wallet top-up.
- FR16 – gift cards for digital goods.
- FR17 – payments for international services and subscriptions.

YouTrack:
- Epics: KUP-7 (Instant delivery), KUP-8 (External services).
- Tasks: KUP-50..KUP-69 – integration with external providers, error handling.

Sprint: 3  
Planned release: 0.2.0 (External services)  
Git branch: `feature/delivery-external`

## Feature: History, bonuses, reviews, notifications (FR10, FR11, FR13, FR15)

Scope:
- FR10 – order history page.
- FR11 – bonuses / cashback accumulation and spending.
- FR13 – product reviews and ratings.
- FR15 – notifications about order status and promotions.

YouTrack:
- Epics: KUP-9 (Loyalty program), KUP-10 (Reviews and notifications).
- Tasks: KUP-70..KUP-89 – loyalty logic, review moderation, notification templates.

Sprint: 4  
Planned release: 0.3.0 (Loyalty and reviews)  
Git branch: `feature/history-bonuses-reviews`
