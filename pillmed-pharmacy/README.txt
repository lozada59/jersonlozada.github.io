PILLMED PHARMACY - RESPONSIVE ALL-PHONE VERSION

Optimized for:
- Small phones (320-380px)
- Standard Android and iPhone widths
- Large phones and foldable cover screens
- Tablets and desktop

Features:
- Responsive one-line logo
- Three responsive rotating orbit rings
- Touch-friendly NFC card and buttons
- Hamburger menu
- Fixed Call, Save, Review, and Message bar on mobile
- Safe-area support for phones with home indicators
- Direct Google review and Messenger links
- Save Contact VCF function

UNIVERSAL MOBILE V2
Reworked the iPhone and Android layout using fluid clamp() sizing, aspect-ratio cards, safe-area insets, narrow-phone rules, large-phone rules, and phone-landscape rules. The NFC card, logo, buttons, address, typography, three rings, menu, and bottom action bar now resize independently without horizontal overflow.

REFERENCE FORMAT UPDATE
All portrait phones now use the same composition as the provided reference: compact header, full-width NFC card with three rings, centered headline directly below the card, two equal action buttons, address, and a fixed four-button tray. Fluid dimensions keep the same proportions on 320px to 900px screens.

FINAL OVERFLOW FIX
- Horizontal page scrolling is disabled.
- Orbit rings are clipped inside the card area.
- Every layout container uses min-width: 0 and max-width: 100%.
- The fixed mobile action tray uses four minmax(0,1fr) columns so Call, Save, Review, and Message remain visible on every phone width.
- Safe-area insets are supported for iPhones.
