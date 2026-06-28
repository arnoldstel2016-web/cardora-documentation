
# CARDORA Google Play Internal Testing

**Status:** Planned

---

# Overview

This document defines the internal testing process for CARDORA before public release on Google Play.

Internal testing is used to verify application stability, functionality, purchases, and overall user experience before progressing to Closed Testing and Production.

---

# Objectives

The Internal Testing phase ensures that:

* Core features operate correctly.
* Purchases function as expected.
* User accounts synchronize properly.
* No critical issues remain before wider testing.

---

# Test Environment

Platform:

Android

Distribution:

Google Play Internal Testing Track

Application Format:

Android App Bundle (AAB)

---

# Functional Testing

## Authentication

* Email Sign In
* Google Sign In
* Session Restore
* Sign Out
* Password Reset

---

## Scanner

* Camera Scanning
* Gallery Image Scanning
* OCR Recognition
* Pokémon Card Identification
* Save to Vault

---

## Collection

* Vault
* Favorites
* Wishlist
* Portfolio
* Profile

---

## Membership

* Founder Purchase
* Founder Number Assignment
* Founder Badge
* Founder Certificate

---

## Early Supporter

* Purchase
* Number Assignment
* Badge

---

## Pro Membership

* Subscription Purchase
* Subscription Validation
* Restore Purchases

---

## Advertising

* Free User Ads
* Pro Ad Removal
* Founder Ad Removal
* AdMob Test Ads

---

# Performance Testing

Verify:

* Application startup
* Navigation speed
* Scanner performance
* Image loading
* Database synchronization
* API response times

---

# Security Testing

Verify:

* HTTPS communication
* Authentication security
* Row Level Security (RLS)
* Secure purchase verification
* Account deletion

---

# Compatibility Testing

Devices should include:

* Samsung Galaxy devices
* Google Pixel devices
* Android Emulator

Android Versions:

* Android 12+
* Android 13+
* Android 14+
* Android 15+

---

# Bug Tracking

## Critical Issues

Record blocking issues that prevent testing or release.

---

## Major Issues

Record significant issues affecting functionality.

---

## Minor Issues

Record cosmetic or low-impact issues.

---

# Exit Criteria

Internal Testing is considered complete when:

* All critical issues are resolved.
* All major features function correctly.
* Billing is verified.
* Data Safety information is confirmed.
* No release blockers remain.

---

# Next Phase

After successful Internal Testing, CARDORA proceeds to:

**Google Play Closed Testing**

---

Last Updated:

Version:

1.0

---

© CARDORA
