
# CARDORA Testing

**Status:** Active

---

# Overview

Testing is an essential part of the CARDORA development process.

Every new feature, bug fix, and release candidate should be verified before being published.

The objective is to provide users with a stable, reliable, and consistent experience across all supported platforms.

---

# Testing Strategy

CARDORA uses multiple testing stages:

* Development Testing
* Feature Testing
* Integration Testing
* Internal Testing
* Closed Testing
* Production Verification

Each stage focuses on different aspects of the application before public release.

---

# Functional Testing

The following features must be tested:

## Authentication

* Email Sign In
* Google Sign-In
* Session Restore
* Sign Out
* Password Reset

---

## Scanner

Verify:

* Camera Scanning
* Gallery Image Scanning
* OCR Recognition
* Card Identification
* Save to Vault

---

## Collection

Verify:

* Vault
* Favorites
* Wishlist
* Portfolio
* Profile

---

## Membership

Verify:

* Founder Purchase
* Founder Badge
* Founder Certificate
* Early Supporter Purchase
* Pro Subscription
* Restore Purchases

---

## Billing

Verify:

* Product Loading
* Purchase Flow
* Purchase Verification
* Restore Purchases
* Membership Synchronization

---

## Advertising

Verify:

* Test Ads
* Production Ads
* Ad Removal for Pro Members
* Ad Removal for Founder Members

---

# Performance Testing

Confirm:

* Fast application startup
* Smooth navigation
* Fast scanner response
* Image loading performance
* Database synchronization
* API response times

---

# Security Testing

Verify:

* HTTPS communication
* Authentication security
* Row Level Security (RLS)
* Purchase verification
* Account deletion
* Permission handling

---

# Compatibility Testing

Supported platforms:

* Web
* Android
* iOS

Supported devices should include:

* Samsung Galaxy devices
* Google Pixel devices
* Android Emulator
* iPhone
* iPad (when supported)

---

# Bug Classification

## Critical

Application cannot be released.

---

## Major

Core functionality affected.

---

## Minor

Non-critical issue with limited impact.

---

## Release Approval

A production release should only proceed when:

* All critical issues are resolved.
* Major issues are reviewed and resolved.
* Core functionality is verified.
* Documentation is up to date.
* Release checklist is completed.

---

# Continuous Improvement

Testing documentation should be updated whenever:

* New features are introduced.
* New platforms are supported.
* Release procedures change.
* New testing requirements are identified.

---

Last Updated:

Version:

1.0

---

© CARDORA
