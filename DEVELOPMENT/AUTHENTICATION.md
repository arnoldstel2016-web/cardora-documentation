
# CARDORA Authentication

**Status:** Active

---

# Overview

This document describes the authentication system used by CARDORA across Web, Android, and iOS.

CARDORA uses Supabase Authentication as the single authentication provider for all supported platforms.

---

# Authentication Methods

The following sign-in methods are supported:

* Email and Password
* Google Sign-In
* Apple Sign-In (iOS when required)

---

# Authentication Flow

The authentication process follows these steps:

1. User signs in.
2. Supabase validates the credentials.
3. A secure session is created.
4. The application loads the authenticated user.
5. React Query synchronizes user data.
6. Protected application routes become available.

---

# Session Management

CARDORA maintains secure user sessions using Supabase Authentication.

The application automatically:

* Restores existing sessions
* Refreshes expired access tokens
* Detects sign-out events
* Updates authentication state

---

# User Profile

After successful authentication, the application loads the user's profile information, including:

* Display Name
* Email Address
* Membership Status
* Founder Number
* Early Supporter Number
* User Preferences

---

# Security

Authentication security includes:

* HTTPS communication
* Secure session storage
* Access token validation
* Protected backend requests
* Row Level Security (RLS)

---

# Supported Platforms

Authentication is available on:

* Web
* Android
* iOS

The same authentication backend is shared across all platforms.

---

# Error Handling

The application handles common authentication scenarios, including:

* Invalid credentials
* Expired sessions
* Network failures
* Account not found
* Email verification (when enabled)

---

# Future Improvements

Future authentication enhancements may include:

* Multi-factor authentication (MFA)
* Additional OAuth providers
* Enhanced account recovery

---

Last Updated:

Version:

1.0

---

© CARDORA
