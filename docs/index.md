---
hide:
  - navigation
  - path
---

# download.indii.org

This software repository provides packages for [Doxide](https://doxide.org) and [Birch](https://birch.sh). Find your operating system below for instructions on adding the repository and installing the software.

## :fontawesome-brands-ubuntu: Ubuntu

??? info "Ubuntu 23.04 Lunar Lobster (amd64)"
    Add the repository:
    ```
    echo 'deb http://download.indii.org/deb lunar main' | sudo tee /etc/apt/sources.list.d/indii.org.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.org.gpg > /dev/null
    sudo apt update
    ```
    Install packages:
    ```
    sudo apt install doxide birch
    ```

??? info "Ubuntu 22.10 Kinetic Kudu (amd64)"
    Add the repository:
    ```
    echo 'deb http://download.indii.org/deb kinetic main' | sudo tee /etc/apt/sources.list.d/indii.org.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.org.gpg > /dev/null
    sudo apt update
    ```
    Install packages:
    ```
    sudo apt install doxide birch
    ```

??? info "Ubuntu 22.04 Jammy Jellyfish (amd64)"
    Add the repository:
    ```
    echo 'deb http://download.indii.org/deb jammy main' | sudo tee /etc/apt/sources.list.d/indii.org.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.org.gpg > /dev/null
    sudo apt update
    ```
    Install packages:
    ```
    sudo apt install doxide birch
    ```

??? info "Ubuntu 20.04 Focal Fossa (amd64)"
    Add the repository:
    ```
    echo 'deb http://download.indii.org/deb focal main' | sudo tee /etc/apt/sources.list.d/indii.org.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.org.gpg > /dev/null
    sudo apt update
    ```
    Install packages:
    ```
    sudo apt install doxide birch
    ```

## :simple-debian: Debian

??? info "Debian 12 Bookworm (amd64)"
    Add the repository:
    ```
    echo 'deb http://download.indii.org/deb bookworm main' | sudo tee /etc/apt/sources.list.d/indii.org.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.org.gpg > /dev/null
    sudo apt update
    ```
    Install packages:
    ```
    sudo apt install doxide birch
    ```

??? info "Debian 11 Bullseye (amd64)"
    Add the repository:
    ```
    echo 'deb http://download.indii.org/deb bullseye main' | sudo tee /etc/apt/sources.list.d/indii.org.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.org.gpg > /dev/null
    sudo apt update
    ```
    Install packages:
    ```
    sudo apt install doxide birch
    ```

??? info "Debian 10 Buster (amd64)"
    Add the repository:
    ```
    echo 'deb http://download.indii.org/deb buster main' | sudo tee /etc/apt/sources.list.d/indii.org.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.org.gpg > /dev/null
    sudo apt update
    ```
    Install packages:
    ```
    sudo apt install doxide birch
    ```

## :fontawesome-brands-fedora: Fedora

??? info "Fedora 38 (x86_64)"
    Add the repository:
    ```
    sudo dnf config-manager --add-repo https://download.indii.org/rpm/fedora/38/indii.org.repo
    sudo dnf update
    ```
    Install packages:
    ```
    sudo dnf install doxide birch
    ```

??? info "Fedora 37 (x86_64)"
    Add the repository:
    ```
    sudo dnf config-manager --add-repo https://download.indii.org/rpm/fedora/37/indii.org.repo
    sudo dnf update
    ```
    Install packages:
    ```
    sudo dnf install doxide birch
    ```

??? info "Fedora 36 (x86_64)"
    Add the repository:
    ```
    sudo dnf config-manager --add-repo https://download.indii.org/rpm/fedora/36/indii.org.repo
    sudo dnf update
    ```
    Install packages:
    ```
    sudo dnf install doxide birch
    ```

??? info "Fedora 35 (x86_64)"
    Add the repository:
    ```
    sudo dnf config-manager --add-repo https://download.indii.org/rpm/fedora/35/indii.org.repo
    sudo dnf update
    ```
    Install packages:
    ```
    sudo dnf install doxide birch
    ```

## :simple-opensuse: openSUSE

??? info "openSUSE Tumbleweed (x86_64)"
    Add the repository:
    ```
    sudo zypper addrepo https://download.indii.org/rpm/opensuse/tumbleweed/indii.org.repo
    sudo zypper refresh
    ```
    Install packages:
    ```
    sudo zypper install doxide birch
    ```

??? info "openSUSE Leap 15.5 (x86_64)"
    Add the repository:
    ```
    sudo zypper addrepo https://download.indii.org/rpm/opensuse/leap/15.5/indii.org.repo
    sudo zypper refresh
    ```
    Install packages:
    ```
    sudo zypper install doxide birch
    ```

??? info "openSUSE Leap 15.4 (x86_64)"
    Add the repository:
    ```
    sudo zypper addrepo https://download.indii.org/rpm/opensuse/leap/15.4/indii.org.repo
    sudo zypper refresh
    ```
    Install packages:
    ```
    sudo zypper install doxide birch
    ```

## :fontawesome-brands-linux: Mageia

??? info "Mageia 8 (x86_64)"
    Add the repository:
    ```
    sudo dnf config-manager --add-repo https://download.indii.org/rpm/mageia/8/indii.org.repo
    sudo dnf update
    ```
    Install packages:
    ```
    sudo dnf install doxide birch
    ```

## :fontawesome-brands-apple: Mac

??? info "Homebrew"
    Install [Homebrew](https://brew.sh) if not already. Add the tap:
    ```sh
    brew tap indii.org/brew https://download.indii.org/brew
    ```
    Install packages:
    ```
    brew install doxide birch
    ```

## :fontawesome-brands-windows: Windows

Native support is not yet provided, but you can install [Windows Subsystem for Linux](https://learn.microsoft.com/en-us/windows/wsl/install) with one of the Linux distributions above and follow the instructions for it.

## :fontawesome-solid-file-zipper: Others: Install from source

If a package is not available for your operating system or you have special requirements, you can install from source. See:

- [Doxide README.md](https://github.com/lawmurray/doxide)
- [Birch README.md](https://github.com/lawmurray/Birch)

## About

This repository is maintained by Lawrence Murray ([:material-github:](https://github.com/lawmurray){target="_blank"} [:material-mastodon:](https://fosstodon.org/@lawmurray){target="_blank"} [:material-twitter:](https://twitter.com/lawmurray){target="_blank"} [:material-web:](https://indii.org){target="_blank"} [:material-email:](mailto:lawrence@indii.org){target="_blank"}). It is rebuilt by an automated pipeline on [CircleCI](https://circleci.com) when new versions of software are released.
