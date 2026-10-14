# Clad Privacy

**Hosts the privacy policy, terms of use, and support page for Clad, an iOS app that scores outfit photos with on-device machine learning.**

Live: **https://keshavkrishnan08.github.io/CladPrivacy/privacy-policy.html**

## Pages

- `privacy-policy.html`: the privacy policy, last updated March 22, 2026
- `terms-of-use.html`: terms of use, including subscription and renewal terms
- `support.html`: FAQ, subscription plans, and the support contact

## What the policy says

Clad analyzes outfit photos on the iPhone with Core ML models and Apple's Vision framework, and the policy states that photos are never uploaded and that Clad runs no backend servers. The style profile, scan history, scores, and photos are stored locally with SwiftData and can sync through the user's own iCloud account via CloudKit. Clad collects anonymous, aggregated feature-usage analytics and subscription status from StoreKit. It does not collect real names, email addresses, phone numbers, location, or advertising identifiers, uses no third-party analytics or advertising SDKs, and does not sell or share personal data. Users can erase everything in the app under Profile, Delete My Data.

## Update and deploy

GitHub Pages serves the `main` branch from the repository root. Edit the HTML files and push to `main`. There is no `index.html`, so link to the page files directly; the bare site root returns 404.

Contact: keshav-krishnan@outlook.com
