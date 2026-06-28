# CARDORA Architecture

**Status:** Active

---

# Overview

CARDORA is a cross-platform trading card collection application designed to share a single codebase across Web, Android, and iOS.

The project is built around a unified architecture to reduce maintenance, improve reliability, and ensure feature consistency across all supported platforms.

---

# Core Technologies

## Frontend

* React
* TypeScript
* Vite
* TanStack Router
* TanStack Query

---

## Backend

* Supabase
* PostgreSQL
* Row Level Security (RLS)
* Supabase Authentication
* Supabase Storage

---

## Mobile

* Capacitor
* Android
* iOS

Platform-specific code is only used where required, such as:

* Camera access
* Native authentication
* In-app purchases

---

# Authentication

CARDORA supports:

* Email and Password
* Google Sign-In
* Apple Sign-In (iOS when required)

Authentication is managed through Supabase Authentication.

---

# Scanner

The scanner consists of the following workflow:

1. Capture image
2. OCR processing
3. Card recognition
4. Pokémon TCG API lookup
5. Match confidence evaluation
6. User confirmation
7. Save card to Vault

---

# Collection System

Users can manage:

* Vault
* Favorites
* Wishlist
* Portfolio
* Profile

All collection data is synchronized with Supabase.

---

# Membership System

CARDORA currently supports:

* Free
* Founder
* Early Supporter
* Pro

Membership information is securely stored and synchronized with the backend.

---

# Cloud Infrastructure

Backend services include:

* Authentication
* Database
* Storage
* Server Functions

Communication is encrypted using HTTPS.

---

# Security

Security features include:

* HTTPS
* Row Level Security (RLS)
* Secure Authentication
* Protected API access
* Environment Variables

---

# Design Principles

CARDORA follows these architectural principles:

* Single shared codebase
* Shared business logic
* Platform consistency
* Modular components
* Scalable architecture
* Security by design

---

# Future Expansion

The architecture is designed to support additional trading card games without major structural changes.

Planned future support includes:

* Magic: The Gathering
* One Piece Card Game
* Yu-Gi-Oh!

---

Last Updated:

Version:

1.0

---

© CARDORA
