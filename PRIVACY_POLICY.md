# Privacy Policy for PokéRogue to Showdown

**Last Updated:** October 2026

## Overview
**PokéRogue to Showdown** is a browser extension developed to convert Pokémon teams from [PokéRogue](https://pokerogue.net) into standard Pokémon Showdown export format.

We are firmly committed to user privacy. **This extension does not collect, track, store, or transmit any personal data or browsing activity.**

---

## Data Collection and Usage

1. **No Personal Data Collected**:
   - The extension does not collect your name, email, IP address, browsing history, login credentials, or account identifiers.
2. **Local Processing Only**:
   - All save decryption, parsing, and formatting logic runs **100% locally** in your browser's memory using bundled, client-side code.
   - The extension makes **no external network requests** to any remote servers, analytics services, or third-party tracking platforms.
3. **Save Game Data**:
   - Save file data (active party, IVs, vitamin counts, and held items) is accessed strictly when you click one of the scanning buttons or import a file manually.
   - This data is used solely to generate the Pokémon Showdown text output on your screen. It is never uploaded or shared.
4. **Local Storage**:
   - The extension uses the `chrome.storage` API exclusively to remember your preferred UI settings (e.g. EV cap toggle, items breakdown toggle) locally on your device.

---

## Permissions Justification

- **`activeTab` & `*://pokerogue.net/*`**: Used solely to read active save states or run history from the PokéRogue web application when you actively click the extension icon.
- **`scripting`**: Used to safely access the live in-memory game state (`window.globalScene`) and browser storage on `pokerogue.net` to retrieve your team members and items.
- **`storage`**: Used solely to save your local UI preferences (such as EV capping and held items breakdown settings).

---

## Third-Party Disclosure
We do not sell, trade, or transfer any user information to third parties.

---

## Contact
If you have any questions or feedback regarding this Privacy Policy, please open an issue on the official project repository or contact the extension developer.
