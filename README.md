# Stalker – Shadow Fight 2 Save Viewer & Modifier

# This repository has been archived, please follow [this](https://github.com/onerdna/stalker) repository instead

**Stalker** is a android utility application designed to **view and optionally modify save files** for the mobile game **Shadow Fight 2**.

> ⚠️ **Disclaimer:** Shadow Fight 2 is a trademark of **Nekki Limited**. This application is not affiliated with, endorsed by, or associated with Nekki in any way. Use of this application is at your own risk. You are solely responsible for ensuring your use complies with Nekki’s terms of service and any applicable laws.

## 🔍 What It Does

Stalker allows users to inspect and optionally tweak various aspects of their Shadow Fight 2 game progress by interacting with local save files.

### 🔧 Features

- **View and modify**:
  - Coins
  - Gems
  - Forge materials
- **Enable**:
  - Unlimited energy
  - Dojo disciple
- **Inventory Management**:
  - Add or remove weapons, armor, helmets, and ranged gear
  - Apply enchantments to equipment (Simple, Medium, Mythical)
- **Save records (slots)**:
  - A feature that allows you to manage your progress with separate records - load and save them at any time and access them later whenever you want

> Modifying save files can impact gameplay and may violate the game’s terms of use. Use modification features responsibly.

## ❗ How to install
- Download and install the APK file from [releases](https://github.com/onerdna/stalker_release/releases) page
- Install [Shizuku](https://shizuku.rikka.app/)
- Start Shizuku service if it's not already running. There are great tutorials on the internet of doing so.
- Launch the app, grant Shizuku permissions
- Proceed to the additional setup step. Before that, ensure that the game is fully closed. Minimize the app (do not fully close it!), open the game and wait until it fully loads. Then, close the game, go back to the app and press "Reinitialize" button.

### ❗ Before using...
- Fully close the game and only then open the app
- If you make any tweaks to the save, then press "Save" button after doing any modifications

## ❓ FaQ
- **Will there be an IOS version?**
  - No.
- **Why the app uses Shizuku?**
  - Shizuku is required to access save files (because it's not accessible for regular apps) and it's used to launch setup service binary.
- **Can you add verified gems/raid consumables or damage hack?**
  - No.
- **What setup service actually does? I'm concerned about running high-privelleged compiled binaries.**
  - The only purpose of setup service is to tamper your user id from the game's process. After doing so, it will automatically close itself (or after two minutes of inactivity). User ID is different for each device and it's just a random string that does not contain any information about your device. I won't share the process of acquiring the ID here because it's the only possible way of doing that, so it can be patched easily by the developers if they know. 

## 📦 About This Repository

This repository contains **compiled release files only**. The source code is **not included**. Please refer to the [LICENSE](./LICENSE.md) file for usage terms.

### ❤ Special thanks to:
- [**Shizuku**](https://shizuku.rikka.app/)
- **ShadowFight2dojo community**
  - [Reddit](https://www.reddit.com/r/ShadowFight2dojo/)
  - [Discord](https://discord.gg/ThDBZztuJu)
## 📄 License

By downloading or using this software, you agree to the terms outlined in the [LICENSE](./LICENSE.md) and [EULA](./EULA.txt).

---
