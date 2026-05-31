# Privacy Policy

**Last updated:** May 31, 2025

## Overview

Tools Hub ("the App") is a free, open-source web application available at [https://andrewrayr.github.io/tools-hub/](https://andrewrayr.github.io/tools-hub/) and hosted on GitHub Pages. This Privacy Policy explains what data is collected when you use the App and how it is handled.

---

## Who This Policy Applies To

This policy applies to all visitors and users of Tools Hub, whether or not they create an account.

---

## Data We Collect

### Without an Account (Guest Users)

If you use Tools Hub without signing in, no personal data is collected or stored by the App. All tool operations (unit conversion, QR generation, color picking, etc.) run entirely in your browser.

Your browser's **localStorage** may be used to save local preferences. This data never leaves your device and is not accessible to us or any third party.

### With an Account (Registered Users)

If you choose to create an account, the following data is collected and stored:

- **Email address** — used to identify your account
- **Display name** — derived from your Google account or email, shown in the UI
- **Dashboard preferences** — your tool order and hidden tools, stored in Firestore under your user ID

Account creation is entirely optional. It is only required to use the dashboard customization feature (reordering tools, hiding tools).

---

## Third-Party Services

### Firebase (Google)

Tools Hub uses **Firebase**, a platform by Google, for:

- **Firebase Authentication** — handles sign-in via Google OAuth or email/password
- **Cloud Firestore** — stores your dashboard preferences (tool order, hidden tools) tied to your user ID

By creating an account, you agree to [Google's Privacy Policy](https://policies.google.com/privacy) and [Firebase's Terms of Service](https://firebase.google.com/terms). Google may collect additional data as part of providing these services, including usage logs and authentication metadata.

### GitHub Pages

The App is hosted on **GitHub Pages** (by GitHub, Inc.). When you visit the site, GitHub may automatically log technical information including your IP address, browser type, and referring URL. See [GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) for details.

### QR Code Library

The App loads a QR code generation library (`qrcodejs`) from `cdnjs.cloudflare.com`. Cloudflare may collect standard CDN request logs when this resource is fetched. No user content is sent to Cloudflare — QR code generation happens locally in your browser.

---

## How We Use Your Data

Data collected is used solely to:

- Authenticate your identity when you sign in
- Save and restore your personal dashboard preferences across sessions

We do not sell, share, or use your data for advertising or analytics purposes.

---

## Data Retention and Deletion

Your account data (email, display name, dashboard preferences) is stored in Firebase for as long as your account exists. To delete your data:

1. Open an issue at [https://github.com/AndrewRayR/tools-hub/issues](https://github.com/AndrewRayR/tools-hub/issues) requesting account deletion, including the email address associated with your account.

We will delete your Firestore data and Firebase Auth record upon request.

---

## Children's Privacy

Tools Hub is a general-purpose utility application and is not directed at children under the age of 13. We do not knowingly collect personal information from children under 13.

---

## Changes to This Policy

This Privacy Policy may be updated from time to time. The "Last updated" date at the top of this page reflects the most recent revision. Continued use of the App after any changes constitutes acceptance of the updated policy.

---

## Contact

For privacy-related questions or data deletion requests, please open an issue in the GitHub repository:

[https://github.com/AndrewRayR/tools-hub/issues](https://github.com/AndrewRayR/tools-hub/issues)
