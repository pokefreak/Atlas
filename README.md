# Atlas (WotLK 3.3.5 Edition)

**Atlas** is a core map navigation framework for World of Warcraft, providing highly detailed, hand-drawn maps for instances, dungeons, battlegrounds, and flight paths. This specific repository is optimized and maintained for compatibility with the **Wrath of the Lich King (Patch 3.3.5a)** game client.

---

## 🗺️ Core Features

*   **Instance & Raid Maps:** Detailed sub-maps showcasing boss locations, entry points, zone transitions, and point-of-interest markers.
*   **WotLK Content Ready:** Built-in maps covering all major Northrend instances (including Icecrown Citadel, Ulduar, Naxxramas, and Trial of the Crusader).
*   **Modular Design:** Serves as the base framework required to power data modules like `AtlasLoot`.
*   **Interactive UI:** Seamless positioning, opacity adjustments, and integrated search functionality to locate specific instance layouts instantly.

---

## 🛠️ Installation

1.  **Download** the repository source archive or clone it directly.
2.  Extract the archive and move the directory folder to your client's AddOn path:
    ```text
    C:\YourWoWDirectory\Interface\AddOns\
    ```
    *(Ensure the main folder is named exactly `Atlas`. If you download a zipped branch, remove trailing prefixes like `-master` or `-3.3.5` from the folder name.)*
3.  Launch your game client and verify that **Atlas** is enabled in the AddOns menu at the character selection screen.

---

## ⌨️ Slash Commands

Interact with the addon frame or toggle settings via chat using the following slash options:

*   `/atlas` — Toggles the main Atlas map window visibility.
*   `/atlas options` — Directly opens the addon's configuration menu.

---

## 🤝 Contribution & Feedback

If you run into missing map coordinates, broken instances, or want to contribute baseline localization fixes:

1. Fork this repository.
2. Create your module or bugfix branch (`git checkout -b feature/MapFix`).
3. Commit your layout updates (`git commit -m 'Fixed entry coordinates for Gundrak'`).
4. Push your changes (`git push origin feature/MapFix`).
5. Open a Pull Request for review.

---

## 📝 License

This project is open-source software distributed under standard community modifications frameworks. See the accompanying `LICENSE` file for additional details.
