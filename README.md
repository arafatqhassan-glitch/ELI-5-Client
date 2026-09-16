<div align="center">

  <img src="android/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png" alt="ELI 5 Client Logo" width="128" height="128">

  # ELI 5 Client

  **A custom, optimized Android client built on the Luanti / Minetest engine.**

  [![GitHub Release](https://img.shields.io/github/v/release/arafatqhassan-glitch/ELI-5-Client?include_prereleases&style=flat-square&color=blue)](https://github.com/arafatqhassan-glitch/ELI-5-Client/releases)
  [![Build Android APK](https://github.com/arafatqhassan-glitch/ELI-5-Client/actions/workflows/build-apk.yml/badge.svg)](https://github.com/arafatqhassan-glitch/ELI-5-Client/actions)
  [![License](https://img.shields.io/badge/License-LGPL%20v2.1-orange.svg)](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)

</div>

---

## 🌟 Features

* **Universal Compatibility:** Single binary bundle compiled for both 32-bit (`armeabi-v7a`) and 64-bit (`arm64-v8a`) Android hardware.
* **Standalone Installation:** Custom package ID (`client.eli5.game`) allows seamless side-by-side installation alongside official Luanti or Minetest builds.
* **Custom Branding:** Specialized interface assets, launcher icons, and resource configs.
* **Automated CI/CD:** Fully automated build pipeline powered by GitHub Actions.

---

## 📲 Installation

1. Go to the [Releases](https://github.com/arafatqhassan-glitch/ELI-5-Client/releases) page.
2. Download **`ELI-5-Client Debug.apk`** under **v5.0.0**.
3. Open the downloaded file on your Android device and install it.
   > **Note:** Ensure **Install from Unknown Sources** is enabled in your file manager or browser settings.

---

## 🛠️ Building from Source

This project uses Gradle and GitHub Actions for continuous integration.

### Prerequisites

* Java Development Kit (JDK) 17
* CMake & Ninja Build
* GNU Gettext (`msgfmt`)
* Android NDK & SDK

### Local Build Steps

```bash
# Clone the repository
git clone [https://github.com/arafatqhassan-glitch/ELI-5-Client.git](https://github.com/arafatqhassan-glitch/ELI-5-Client.git)
cd ELI-5-Client

# Build the universal APK
./gradlew assembleDebug
