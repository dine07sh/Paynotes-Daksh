# PayNotes Daksh

A mobile-friendly academic storefront for premium study materials.

## Published files

- `index.html` — student storefront with class filters, product search, UPI payment links, QR payment panel, and WhatsApp order confirmation.
- `admin.html` — browser-based product manager. Default password: `daksh2026` (change `ADMIN_PASSWORD` before sharing the admin URL).

## Payment configuration

- Recipient: **RAJKUMAR DINESH SINGH**
- UPI ID: **917005173439@wahdfcbank**
- WhatsApp: **+91 70051 73439**

The order modal creates an amount-specific `upi://pay` link and a QR code using that payment URI. Students should verify the recipient name before paying.

## Deployment

This static site is ready for GitHub Pages or any static hosting service. Enable Pages for the `main` branch and use the published site URL. The admin page is client-side protected for convenience only; do not use it as a security boundary for sensitive data.
