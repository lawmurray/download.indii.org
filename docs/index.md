---
hide:
  - navigation
  - path
---

# download.indii.org

This software repository provides packages for [Doxide](https://doxide.org) and [Birch](https://birch-lang.org). Find your operating system below for instructions on adding the repository and installing the software.

## :fontawesome-brands-ubuntu: Ubuntu

??? info "Ubuntu 24.04 Noble Numbat (amd64)"
    Add the repository:
    ```
    echo 'deb http://download.indii.org/deb noble main' | sudo tee /etc/apt/sources.list.d/indii.org.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.org.gpg > /dev/null
    sudo apt update
    ```
    Install packages:
    ```
    sudo apt install doxide birch
    ```

??? info "Ubuntu 23.10 Mantic Minotaur (amd64)"
    Add the repository:
    ```
    echo 'deb http://download.indii.org/deb mantic main' | sudo tee /etc/apt/sources.list.d/indii.org.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.org.gpg > /dev/null
    sudo apt update
    ```
    Install packages:
    ```
    sudo apt install doxide birch
    ```

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

## :fontawesome-brands-fedora: Fedora

??? info "Fedora 40 (x86_64)"
    Add the repository:
    ```
    sudo dnf config-manager --add-repo https://download.indii.org/rpm/fedora/40/indii.org.repo
    sudo dnf update
    ```
    Install packages:
    ```
    sudo dnf install doxide birch
    ```

??? info "Fedora 39 (x86_64)"
    Add the repository:
    ```
    sudo dnf config-manager --add-repo https://download.indii.org/rpm/fedora/39/indii.org.repo
    sudo dnf update
    ```
    Install packages:
    ```
    sudo dnf install doxide birch
    ```

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

## :fontawesome-brands-apple: Mac

Install [Homebrew](https://brew.sh) if not already. Add the tap:
```sh
brew tap lawmurray/all
```
Install packages:
```
brew install doxide birch
```

## :fontawesome-brands-windows: Windows

[:material-download: Doxide installer](https://download.indii.org/win/doxide-installer.exe){ .md-button } [:material-download: Doxide program only](https://download.indii.org/win/doxide.exe){ .md-button }

- [Checksum for Doxide installer](https://download.indii.org/win/doxide-installer.exe.sha256)
- [Checksum for Doxide program only](https://download.indii.org/win/doxide.exe.sha256)

Birch is not available on Windows, at least natively, but you can install [Windows Subsystem for Linux](https://learn.microsoft.com/en-us/windows/wsl/install) with a Linux distribution of your choice from above, and install the package for it.

## :fontawesome-solid-file-zipper: Others: Install from source

If a package is not available for your operating system or you have special requirements, you can install from source. See further instructions:

[:simple-readme: Doxide from source](https://github.com/lawmurray/doxide){ .md-button }
[:simple-readme: Birch from source](https://github.com/lawmurray/Birch){ .md-button }

## About

This repository is maintained by Lawrence Murray ([:material-github:](https://github.com/lawmurray){target="_blank"} [:material-mastodon:](https://fosstodon.org/@lawmurray){target="_blank"} [:material-twitter:](https://twitter.com/lawmurray){target="_blank"} [:material-web:](https://indii.org){target="_blank"} [:material-email:](mailto:lawrence@indii.org){target="_blank"}). It is rebuilt by an automated pipeline on [CircleCI](https://circleci.com) when new versions of software are released.
