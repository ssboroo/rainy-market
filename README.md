# RAINY MARKET

Next.js bilingual marketplace demo for Mongolia.

- 12 sample products and six categories
- Product details, category filtering and search
- Persistent browser cart and demo checkout
- QPay, SocialPay and bank transfer options (display only; no live payment processing)
- Seller landing page and multi-vendor-ready sample data model

Run: npm install && npm run dev
Test: npm test

Production note: this is a storefront starter, not yet a live commerce backend. Authentication, database, seller/admin authorization, server-side inventory and price validation, secure order processing, payment callbacks, idempotency, RLS, audit logs and backups must be implemented before accepting real orders. No payment secrets or service-role keys are included.