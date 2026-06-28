
# CARDORA Google Play Billing

**Status:** Planned

---

# Overview

This document describes the Google Play Billing implementation used by CARDORA.

Google Play Billing is used to process all in-app purchases and subscriptions on Android devices.

---

# Supported Products

## Founder Membership

Type:

One-time Purchase

Status:

Planned

Description:

Provides permanent Founder status, Founder number assignment, Founder badge, and Founder Certificate.

---

## Early Supporter Membership

Type:

One-time Purchase

Status:

Planned

Description:

Provides permanent Early Supporter status and Early Supporter badge.

---

## Pro Membership

Type:

Auto-Renewing Subscription

Billing Cycle:

Monthly

Status:

Planned

Description:

Unlocks premium features including an ad-free experience and future Pro functionality.

---

# Purchase Flow

The purchase process follows the official Google Play Billing guidelines.

1. User selects a product.
2. Available products are loaded from Google Play.
3. Google Play Billing launches the purchase screen.
4. User completes the purchase.
5. Purchase is verified.
6. Membership is activated.
7. Purchase acknowledgement is completed.
8. User profile is updated.

---

# Purchase Verification

All purchases are verified before membership benefits are granted.

Verification includes:

* Product ID validation
* Purchase token validation
* Purchase acknowledgement
* Duplicate purchase protection

---

# Restore Purchases

Users can restore previously purchased products using Google Play.

Supported:

* Founder Membership
* Early Supporter Membership
* Active Pro Subscription

---

# Failed Purchases

If a purchase fails:

* No membership is activated.
* No payment information is stored by CARDORA.
* The user may retry the purchase.

---

# Subscription Management

Google Play manages:

* Subscription renewal
* Subscription cancellation
* Payment methods
* Billing history

CARDORA synchronizes the active subscription status with the user's account.

---

# Security

Google Play Billing is used exclusively for Android purchases.

CARDORA does not process or store credit card information.

All purchase validation is performed using secure backend verification.

---

# Testing

Before public release the following scenarios must be verified:

* Successful purchase
* Failed purchase
* Cancelled purchase
* Restore purchases
* Subscription renewal
* Subscription expiration
* Membership activation
* Membership synchronization

---

# Release Checklist

* [ ] Google Play Billing integrated
* [ ] Products created
* [ ] Purchase verification completed
* [ ] Restore purchases tested
* [ ] Subscription validation tested
* [ ] Production release approved

---

Last Updated:

Version:

1.0

---

© CARDORA
