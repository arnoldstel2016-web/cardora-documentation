
# CARDORA Deployment

**Status:** Active

---

# Overview

This document describes the deployment process for CARDORA across all supported platforms.

The deployment workflow ensures that every release is tested, documented, and prepared before becoming publicly available.

---

# Supported Platforms

CARDORA is designed for:

* Web
* Android
* iOS

Each platform follows its own deployment process while sharing the same application codebase.

---

# Build Process

Before every release the following steps should be completed:

* Install dependencies
* Verify environment variables
* Run project build
* Verify successful compilation
* Resolve build errors

---

# Android Deployment

Android releases are distributed through Google Play.

Deployment includes:

* Generate Android App Bundle (AAB)
* Upload to Google Play Console
* Internal Testing
* Closed Testing
* Production Release

---

# iOS Deployment

iOS releases are distributed through the Apple App Store.

Deployment includes:

* Build iOS application
* Archive project
* Upload to App Store Connect
* TestFlight Testing
* App Review
* Production Release

---

# Web Deployment

The documentation website is deployed using GitHub Pages.

Documentation updates are published after changes are committed to the repository.

---

# Release Requirements

Before deployment verify:

* Documentation updated
* Privacy Policy published
* Terms of Service published
* Account Deletion page available
* Billing verified
* Membership verification completed
* No critical issues remain

---

# Version Control

CARDORA follows Semantic Versioning.

Format:

MAJOR.MINOR.PATCH

Example:

1.0.0

---

# Rollback Strategy

If a release introduces critical issues:

* Pause deployment
* Investigate the issue
* Fix the problem
* Create a new release
* Publish the corrected version

---

# Release Approval

A production release should only occur after:

* Internal Testing completed
* Closed Testing completed
* Documentation reviewed
* Release checklist completed

---

Last Updated:

Version:

1.0

---

© CARDORA
