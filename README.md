### vps2parch

vps2parch is a shell script designed to transform any Linux-based VPS into a ParchLinux system. This script handles the complete process of downloading, extracting, and configuring the ParchLinux environment on your VPS.

## Features

- Converts any Linux-based VPS to ParchLinux.
- Automates the download and installation process.
- Easy to use and minimal user interaction required.

## Prerequisites

Before running the script, ensure your VPS has the following tools installed:

- `curl`
- `tar`
- `wget`
- `aria2`

You can install these tools using your distribution's package manager. For example:

### Debian/Ubuntu
```sh
sudo apt update
sudo apt install curl tar wget aria2 -y
```

### CentOS/RHEL
```sh
sudo yum install curl tar wget aria2 -y
```

### Fedora
```sh
sudo dnf install curl tar wget aria2 -y
```

### Arch Linux
```sh
sudo pacman -Syu curl tar wget aria2
```

## Installation

1. Clone the repository or download the script directly:

    ```sh
    git clone https://github.com/yourusername/vps2parch.git
    ```

    or

    ```sh
    wget https://github.com/parchlinux/vps2parch/raw/main/vps2parch.sh
    ```

2. Navigate to the directory containing the script:

    ```sh
    cd vps2parch
    ```

3. Make the script executable:

    ```sh
    chmod +x vps2parch.sh
    ```

## Usage

Run the script with root privileges to begin the conversion process:

```sh
sudo ./vps2parch.sh
```

The script will guide you through the necessary steps to complete the installation. It will download the required ParchLinux files, extract them, and set up the system on your VPS.

## Note

- This script will overwrite existing system files and configurations. Ensure you have backups of important data before proceeding.
- The conversion process may take some time depending on your network speed and VPS performance.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please submit pull requests or open issues to help improve this project.

Enjoy your new ParchLinux system!
