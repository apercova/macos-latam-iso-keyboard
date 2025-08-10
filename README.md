# macos-latam-iso-keyboard
Latam ISO Keyboard Layouts
# macOS Latin American ISO Keyboard Layouts

A custom keyboard layout bundle for macOS that provides comprehensive support for Latin American ISO keyboards. This project is designed for Spanish-typers who require accurate mapping of Latin American special characters, accents, and symbols, on an ISO-layout keyboard.

## Overview

Many users in Latin America experience issues with default macOS keyboard layouts, such as incorrect placement of Spanish characters, accents, and programming symbols. This project addresses these challenges by offering:

- Accurate mapping of Spanish characters and diacritics
- Proper placement of commonly used symbols
- Two layout variants: standard and programming-friendly
- Native macOS integration with custom icons and localization

### Layouts
Two layout variants (A and B) are included to suit different preferences.

#### Layout A (Standard)
Closely matches the traditional Latin American ISO keyboard layout.
Designed for users who want their macOS keyboard to behave like standard Latin American keyboards found on most PCs.
All Spanish characters, accents, and common symbols are mapped to their expected physical keys.

#### Layout B (Programming-Friendly)
Optimized for users who frequently write code or use special symbols.
Provides easier access to programming-related characters (such as `@`, `#`, `|`, `~`, etc.).
Reduces the use of dead keys and places frequently used symbols in more accessible positions.

## Installation

1. **Download or clone this repository.**
```bash
git clone https://github.com/apercova/macos-latam-iso-keyboard.git
```
2. **Install the `Latin-American-ISO.bundle`**
Locate the `Latin-American-ISO.bundle` directory inside the `src` folder.
```bash
cd macos-latam-iso-keyboard/src
```
- For your user only: `~/Library/Keyboard Layouts/`
```bash
cp -R Latin-American-ISO.bundle ~/Library/Keyboard\ Layouts/
```
- For all users: `/Library/Keyboard Layouts/`
```bash
sudo cp -R Latin-American-ISO.bundle /Library/Keyboard\ Layouts/
```
3. **Refresh keyboard layouts:**  
Log out and log back in, or restart your Mac to ensure the new layouts are recognized.

4. **Add the new layout in System Settings:**
- Open **System Settings** > **Keyboard** > **Input Sources**.  
- Click the **"+"** button and add "Latin American ISO" (A or B) from the list.  

5. **(Optional) Remove the layout:**  
To uninstall, simply delete the bundle:

- For the current user:
```bash
rm -rf ~/Library/Keyboard\ Layouts/Latin-American-ISO.bundle
```
- or, if installed system-wide:
```bash
sudo rm -rf /Library/Keyboard\ Layouts/Latin-American-ISO.bundle
```

## Usage

Choose the layout that best fits your typing habits by selecting either "Latin American ISO A" or "Latin American ISO B" in your macOS input sources.

You can switch between keyboard layouts using the input menu in the menu bar or the default shortcut (Control + Space).

## Contributing

Contributions are welcome! If you have suggestions, improvements, or find issues, feel free to open an issue or submit a pull request. All feedback and collaboration are appreciated to help improve support for Latin American ISO keyboards on macOS.
