# 🔐 OpenSSH Installation in Arch Linux

This guide walks you through installing and enabling OpenSSH on Arch Linux.

## 📦 Installation

1. Install the `openssh` package.

    ```bash
    sudo pacman -S openssh
    ```

2. Enable the `sshd` service to start at boot.

    ```bash
    sudo systemctl enable sshd.service
    ```

3. Start the `sshd` service.

    ```bash
    sudo systemctl start sshd.service
    ```

You are now ready to use OpenSSH on your Arch Linux system! 🔐
