# Heroic Games Launcher

ROCKNIX supports Heroic Games Launcher (arm64), allowing you to run games from GOG, Epic Games Store, and Amazon Prime Gaming. It allows native Linux games as well as Windows games using FEX + Proton (x86) and Proton (arm64), and Wine.

## Step 1: Install Heroic in ROCKNIX
Heroic needs to be installed first from Tools by selecting "Install Heroic". After the installation is complete, Heroic will appear in the main EmulationStation menu.

!!! tip "Installing ROCKNIX to internal memory significantly decreases Heroic startup time, as well as game installation and launch times. Therefore, using ROCKNIX from internal memory is recommended for the best performance."

## Step 2: Configure Heroic in ROCKNIX
Heroic offers three launch options, each suited for a different use case:

- **Heroic Games Launcher (Authenticate)** — Launches Heroic with keyboard input enabled. Use this the first time to log in to your GOG, Epic, or Amazon accounts.
- **Heroic Games Launcher** — Launches Heroic without Gamescope. Use this for general browsing and game management.
- **Heroic Games Launcher (Gamescope)** — Launches Heroic with Gamescope enabled for enhanced display management and better integration with your device's screen.

After logging in, Heroic will scan your installed games and add them to the EmulationStation launcher.

## Step 3: Play
Install your games through Heroic, then launch them from EmulationStation as usual.

Any game installed by Heroic will also appear in the EmulationStation menu under Heroic.

## Build Note
The version of Heroic included in ROCKNIX is a temporary ARM-compiled build, as the official Heroic Games Launcher does not yet have an official ARM release. Once an official ARM build is available, ROCKNIX will transition to it.

## Compatibility Notes
* I've personally had most success with using **wine-GE-latest** as the Wine version in Heroic's settings. But results vary per game of course.
