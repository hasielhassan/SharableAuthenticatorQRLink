# ShareableAuthenticatorQRLink

A tool for generating shareable Time-based One-Time Password (TOTP) authenticator links with QR codes, making it easy to set up two-factor authentication.

Check it out here: https://www.hasielhassan.com/ShareableAuthenticatorQRLink

## Features

- Generate TOTP QR codes for easy setup with authenticator apps.
- Share TOTP links via URL.
- Customizable options: secret key, label, and issuer.
- Hash URL parameters for optional obfuscation.

## How to Use

1. **Generate QR Code:**
   - Open the application.
   - Click on the `+` button at the buttom right corner
   - Input the **Secret**, **Label**, and optional **Issuer**.
   - Optionally you can check the "Hash" checkbox so the url will contain all data in a single hashed string, for obfuscation.
   - Click **Generate** to create the TOTP URL and corresponding QR code.
   
2. **Scan with Authenticator App:**
   - Use your preferred TOTP authenticator app (e.g., Google Authenticator, Authy).
   - Scan the QR code displayed on the page to add the account.

3. **Share the Link:**
   - Once the QR code is generated, you can copy the page url and share it with others.
