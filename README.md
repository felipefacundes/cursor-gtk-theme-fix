# Cursor and GTK Theme Fix Script

This script is designed to fix mouse cursor and GTK themes for various window managers, including sway, openbox, i3, awesome, and more. It ensures a consistent and visually appealing desktop environment. The script provides two main functionalities: a loop for xrdb fixes and a loop for cursor and GTK theme fixes.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Options](#options)
- [License](#license)
- [Credits](#credits)

## Features

- Continuous loop for updating xrdb settings.
- Periodic check and adjustment of cursor and GTK themes.
- Compatibility with various window managers.
- Easy to integrate into your desktop environment.

## Prerequisites

- Linux-based operating system.
- Bash shell.
- wget for downloading the default .Xresources file.

## Installation

1. Clone the repository or download the script directly:

    ```bash
    git clone https://github.com/felipefacundes/cursor-gtk-theme-fix.git
    ```

2. Make the script executable:

    ```bash
    chmod +x cursor-gtk-theme-fix.sh
    ```

## Usage

Run the script with the desired options to fix cursor and GTK themes. The script provides two main options:

1. **xrdb Fix Loop Only:**
    ```bash
    ./cursor-gtk-theme-fix.sh -o
    ```

2. **Cursor and GTK Theme Fix Loop:**
    ```bash
    ./cursor-gtk-theme-fix.sh -t
    ```

## Options

- **-o:** Run only the xrdb fix loop.
- **-t:** Run the cursor and GTK theme fix loop.

## License

This script is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for details.

## Credits

- **Author:** Felipe Facundes
- **GitHub Repository:** [felipefacundes/cursor-gtk-theme-fix](https://github.com/felipefacundes/cursor-gtk-theme-fix)

Feel free to contribute, report issues, or suggest improvements!
