# MedDrop storefront prototype

Public preview: https://html-preview.github.io/?url=https://github.com/altamashmedtech/hmis-demo/blob/main/index.html

A mobile-responsive Haldwani-first storefront prototype for non-medicinal first-aid supplies and basic healthcare devices.

## Included
- Search and category filters
- Responsive catalogue and interactive cart
- Delivery details form with basic validation
- WhatsApp order-message generation
- No online payment collection

## Important launch blockers
- This is a preview-hosted prototype, not a production deployment on a dedicated MedDrop domain.
- The store WhatsApp number is not configured. WhatsApp opens with the order text and the customer must choose the correct store contact.
- The catalogue and prices are illustrative. Confirm real inventory, prices, and delivery coverage.
- The prototype excludes medicines until each product's legal sale eligibility has been reviewed. It is not a substitute for required licences, prescription controls, privacy terms, customer support, refunds, or local regulatory compliance.
- Cart and orders are not stored in a database. The order draft is handed to WhatsApp and must be reviewed and sent by the customer.

## Local static build
Use the `index.html` from the MedDrop starter ZIP as the source build. It has no build command or external packages. Upload it to a static host's site root for a durable production URL.
