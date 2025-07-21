# otp_auth

# OTP Auth Backend

A Node.js + Express.js backend for user signup, login, OTP verification, refresh token logic, and route protection using JWT.

## Features
- Signup with email/mobile, name, and password
- OTP generation and expiry logic (in file-based storage)
- Login and token issuance
- Refresh token logic using HTTP-only cookies
- Middleware-protected routes

## How to Run
```bash
npm install
node app.js
