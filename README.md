# [ARCHIVE] Stardew Valley Custom NPC Project: Remi & Oarfish (2023)

> **ARCHIVAL NOTICE:** This repository is a preserved historical archive of a personal custom NPC expansion developed in 2023 for **Stardew Valley 1.5.6**. It is hosted here untouched for portfolio, data preservation, and demonstration purposes only. It is **unmaintained**, not updated for Stardew Valley 1.6+, and provided strictly as-is.

---

### Project Overview
Created entirely by hand in 2023 prior to the adoption of modern LLM tooling, this project was developed as a personal expansion introducing two original characters: **Remi (Cluster Residue)** and **Oarfish Pearl**. 

This project was engineered as a modular, event-driven systems expansion running on **Content Patcher** and **SMAPI**, featuring custom map geometry, multi-part investigative questlines, and cross-mod integrations.

---

### Key Technical & Creative Contents

#### 1. Custom Pixel Art Assets
* **Custom Portrait Sets:** 64x64 emotional portrait sheets for both Remi and Oarfish (ranging across neutral, happy, blushing, crying, dazed, and unique narrative states).
* **Complete Overworld Sprite Sheets:** Custom 4-directional walk cycles, sitting frames, sleeping poses, fishing rod casting/reeling animations for Oarfish, and custom drowning sprite frames for Remi.

#### 2. Event Scripting & Chained Cutscenes
* **18+ Chained Heart Events:** Scripted across 0, 2, 3, 4, 5, 6, 7, 8, 10, and 14-heart tiers.
* **The 7-Map Dream Warp (`Remi_06Hearts`):** A continuous cutscene teleporting the player across seven distinct game locations (`Mine`, `Tunnel`, `Forest`, `MermaidHouse`, `ElliottSea`, `Beach`, and `Railroad`).
* **The 7-Part Detective Mystery (`Oarfish_06Hearts`):** A multi-chapter narrative arc spanning Town, Mountain, Railroad, Mine, and Beach, culminating in a subterranean confrontation against a shapeshifting doppelganger.

#### 3. Map Geometry & Late-Game Integration
* **Custom Map Injection (`Custom_grotovu_LostGarden.tmx`):** Injects a permanent cosmic greenhouse platform into `Maps/Backwoods` upon completing Remi's 8-heart event.
* **Multi-Stage Patio Upgrades:** A three-tier progression system across the 14-heart questline that dynamically updates the spouse patio (`spousepatiosRemiUpgrade.tmx`, `spousepatiosRemiUpgrade2.tmx`) and rewrites warp properties to link directly to Ginger Island.
* **Spouse Room:** Complete custom spouse room mapping assigned to Slot 13.

#### 4. Cross-Mod Compatibility
* **Stardew Valley Expanded (SVE) Patches:** Custom conditional coordinate overrides that resolve pathing conflicts with SVE's third saloon arcade machine and reroute mine cutscenes to SVE's `Custom_AdventurerSummit`.
* **NPC Adventures Integration:** Custom combat, mining, and travel companion dialogue trees covering over 35 distinct map environments, complete with unique battle cries.
* **Restauranteer Integration:** Custom culinary dialogue reactions when working shifts at the Stardrop Saloon.

#### 5. Dialogue & Behavioral Systems
* **Complete Calendar Dialogue:** Four full seasons, seven days a week, scaling across all friendship tiers.
* **Full Marriage & Roommate Framework:** Custom platonic wedding vows, morning chores, adoption dialogue, and divorce memory-wipe handling.
* **Comprehensive Movie Reactions:** Individual before, during, and after-movie reactions for all in-game films across all four seasons, paired with custom concession snack tastes.
