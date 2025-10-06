# Arch Linux Gaming Dependencies Installer

This script automates the installation of a list of gaming-related dependencies on Arch Linux using `yay`.

## Prerequisites

- An Arch-based Linux distribution.
- `yay` AUR helper installed.

## Files

- `install_gaming_dependencies.sh`: The main installation script.
- `list.txt`: A list of packages to be installed. You can edit this file to add or remove packages.

## How to Use

1.  **Review the package list:** Open `list.txt` and make sure you agree with the packages that will be installed. You can add or remove packages from this list.

2.  **Make the script executable:**
    ```bash
    chmod +x install_gaming_dependencies.sh
    ```

3.  **Run the script:**
    ```bash
    ./install_gaming_dependencies.sh
    ```

The script will then use `yay` to install all the packages listed in `list.txt`.

## Disclaimer

Review the contents of `list.txt` and `install_gaming_dependencies.sh` before running the script to ensure you understand what it does and what packages will be installed on your system.
