
# CARDORA Google AdMob

**Status:** Planned

---

# Overview

This document describes how Google AdMob is implemented in CARDORA.

Advertising is used to support the free version of the application while providing an ad-free experience for eligible premium members.

---

# Advertising Strategy

CARDORA uses Google AdMob to display advertisements to users of the free version of the application.

Advertisements are displayed in accordance with Google Play policies and applicable privacy regulations.

---

# Supported Ad Types

## Banner Ads

Displayed in selected areas of the application without interrupting the user experience.

Status:

Planned

---

## Interstitial Ads

Displayed only at appropriate transition points.

Status:

Planned

---

## Rewarded Ads

Rewarded advertisements may be introduced in future versions.

Status:

Future Feature

---

## App Open Ads

Currently not planned.

Status:

Not Implemented

---

# Membership Rules

## Free Users

* Advertisements enabled
* Banner advertisements may be displayed
* Interstitial advertisements may be displayed

---

## Pro Members

* Advertisements disabled
* Full ad-free experience

---

## Founder Members

* Advertisements disabled
* Permanent ad-free experience

---

## Early Supporter Members

Advertisement behavior follows the currently active membership benefits.

---

# Privacy

Google AdMob may collect and process data according to Google's Privacy Policy.

CARDORA itself does not sell personal data.

Users may manage advertising preferences where supported by their device and applicable regulations.

---

# GDPR Compliance

CARDORA will use Google's User Messaging Platform (UMP) where required.

The application will request user consent before serving personalized advertisements in supported regions.

---

# Google Play Data Safety

All AdMob-related data collection is documented in the Google Play Data Safety section.

The Data Safety form will always reflect the actual implementation of the application.

---

# Testing

Before public release, the following must be verified:

* Test advertisements display correctly
* Production advertisements display correctly
* Advertisements are hidden for Pro members
* Advertisements are hidden for Founder members
* GDPR consent flow functions correctly
* No policy violations are present

---

# Release Checklist

* [ ] AdMob account created
* [ ] Application linked
* [ ] Ad Unit IDs configured
* [ ] Test ads verified
* [ ] Production ads enabled
* [ ] GDPR consent implemented
* [ ] Data Safety updated
* [ ] Google Play policy review completed

---

Last Updated:

Version:

1.0

---

© CARDORA
