
# CARDORA Database

**Status:** Active

---

# Overview

CARDORA uses Supabase PostgreSQL as its primary database.

The database stores user accounts, collections, memberships, application settings, and other data required by the platform.

All database operations are secured using Row Level Security (RLS).

---

# Database Platform

Database Provider:

Supabase

Database Engine:

PostgreSQL

Authentication:

Supabase Authentication

Storage:

Supabase Storage

---

# Main Tables

## profiles

Stores user profile information.

Typical data includes:

* User ID
* Display Name
* Email
* Avatar
* Membership Status
* Founder Number
* Early Supporter Number
* Preferences

---

## user_cards

Stores cards owned by each user.

Typical information includes:

* Pokémon Card ID
* Quantity
* Language
* Condition
* Personal Notes
* Collection Status

---

## founder_config

Stores Founder program configuration.

Includes:

* Total Founder Spots
* Claimed Founder Spots
* Founder Price
* Early Supporter Configuration

---

## Additional Tables

Additional tables may include:

* User Settings
* Notifications
* Feature Flags
* Purchase Records
* Application Configuration

---

# Relationships

Database relationships are designed around the authenticated user.

Each user's collection is isolated using Row Level Security (RLS).

This ensures users can only access their own data.

---

# Security

Database security includes:

* Row Level Security (RLS)
* Secure authentication
* Protected server functions
* Parameterized queries
* HTTPS communication

---

# Data Synchronization

Application data is synchronized using:

* Supabase
* React Query
* Secure API requests

This minimizes unnecessary requests while keeping the application responsive.

---

# Backups

Database backups are managed by Supabase according to the configured project settings.

Regular backups are recommended before major releases.

---

# Future Expansion

The database is designed to support:

* Additional trading card games
* Marketplace features
* Trading features
* Community features
* Expanded membership functionality

---

Last Updated:

Version:

1.0

---

© CARDORA
