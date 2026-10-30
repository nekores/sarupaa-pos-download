# Sarupaa POS

Point of Sale for the counter: sales, inventory, purchases, customers, and finance. This repository holds the installers. Download the latest release, install it, and open **Sarupaa POS**.

**[Download the latest release](https://github.com/nekores/sarupaa-pos-download/releases/latest)**

Website: [sarupaapos.asiandevs.com](https://sarupaapos.asiandevs.com/)  
Guide: [sarupaapos.asiandevs.com/docs](https://sarupaapos.asiandevs.com/docs/)

## Which file to download

Open the latest release and pick the file for your computer.

| Computer | File | What to do |
| --- | --- | --- |
| Mac with Apple silicon (M1, M2, M3, M4) | `Sarupaa POS-<version>-arm64.dmg` | Open the disk image and drag **Sarupaa POS** into Applications |
| Mac with Intel | `Sarupaa POS-<version>-x64.dmg` | Open the disk image and drag **Sarupaa POS** into Applications |
| Windows | `Sarupaa POS-Setup-<version>.exe` | Run the installer |
| Windows, no install | `Sarupaa POS-<version>-portable.exe` | Run the file. It does not add Start menu shortcuts |
| Linux | `Sarupaa POS-<version>.AppImage` or the `.deb` package | Run the AppImage, or install the `.deb` |

On a Mac, choose **About This Mac** and look at **Chip**. Apple silicon needs the `arm64` file. Intel needs the `x64` file.

The `.zip` files next to the Mac installers are for in-app updates. Install from the `.dmg`.

## Install

**Mac**

1. Download the `.dmg` for your chip.
2. Open it and drag **Sarupaa POS** into **Applications**.
3. Open **Sarupaa POS** from Applications.
4. If macOS says the app cannot be opened, right-click the app in Applications, choose **Open**, then **Open** again.

Keep the app in Applications. Updates install into that copy.

**Windows**

1. Download `Sarupaa POS-Setup-<version>.exe`.
2. Run it and follow the installer.
3. Open **Sarupaa POS** from the Start menu or desktop shortcut.

If Windows SmartScreen appears, choose **More info**, then **Run anyway**.

## First launch

Sarupaa POS stores its data in PostgreSQL. On first launch, the app asks for the database connection. It creates the tables it needs.

A shop that already uses Sarupaa POS should point the new install at the same database. Existing data stays in place.

## Updates

The installed app checks this repository for a newer release and can download it. If macOS will not apply an update automatically, quit Sarupaa POS completely, download the latest `.dmg` from [Releases](https://github.com/nekores/sarupaa-pos-download/releases/latest), and install it over the copy in Applications. Then open the app from Applications.

## Support

Questions about the product: [support@sarupaa.com](mailto:support@sarupaa.com)

This repository is for downloads only. Source code is not published here.
