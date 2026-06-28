
# CARDORA Scanner

**Status:** Active

---

# Overview

The CARDORA Scanner is the primary feature of the application.

It allows users to quickly identify trading cards using their device's camera or an image from their photo library.

The scanner is designed to provide fast, reliable, and accurate card recognition.

---

# Scanner Sources

Users may scan cards using:

* Device Camera
* Photo Library

Both methods use the same recognition workflow.

---

# Recognition Process

The scanner follows these steps:

1. Capture or select an image.
2. Prepare the image for analysis.
3. Perform OCR processing.
4. Detect card information.
5. Search the Pokémon TCG API.
6. Compare possible matches.
7. Display the best result.
8. Allow user confirmation.
9. Save the card to the Vault.

---

# Card Information

When available, the scanner retrieves:

* Card Name
* Set Name
* Card Number
* Rarity
* Card Image
* Market Price
* Language
* Pokémon TCG ID

---

# Collection Integration

After confirmation, the card can be added directly to the user's collection.

Saved information includes:

* Quantity
* Collection status
* Personal notes (when available)
* Scan timestamp

---

# Recognition Quality

Recognition accuracy depends on:

* Image quality
* Lighting conditions
* Card visibility
* Focus
* OCR confidence

The application may request another scan if the confidence level is too low.

---

# Supported Games

Current support:

* Pokémon Trading Card Game

Planned future support:

* Magic: The Gathering
* One Piece Card Game
* Yu-Gi-Oh!

---

# Performance

The scanner is optimized for:

* Fast image processing
* Low memory usage
* Responsive user experience
* Cross-platform compatibility

---

# Error Handling

Common scenarios include:

* Card not recognized
* Low image quality
* API unavailable
* Network failure
* Camera permission denied

Appropriate user feedback is displayed for each situation.

---

# Privacy

Images are processed only for card recognition.

CARDORA does not use scanned images for advertising or marketing purposes.

Users maintain control over their collection and scanned content.

---

Last Updated:

Version:

1.0

---

© CARDORA
