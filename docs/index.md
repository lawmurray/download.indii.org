---
hide:
  - navigation
  - path
  - toc
  - menu
---

# Indii.org Software Repository

## :fontawesome-brands-linux: Linux

This software repository provides packages for [Doxide](https://doxide.org) and [Birch](https://birch-lang.org). Find your operating system below for instructions on adding the repository and installing the software.

??? warning "Ubuntu 24.10 Oracular Oriole (amd64)"
    Add the repository:
    ```
    echo 'deb http://download.indii.org/deb oracular main' | sudo tee /etc/apt/sources.list.d/indii.org.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.org.gpg > /dev/null
    sudo apt update
    ```
    Install packages:
    ```
    sudo apt install doxide birch
    ```

??? warning "Ubuntu 24.04 Noble Numbat (amd64)"
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

??? bug "Debian 12 Bookworm (amd64)"
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

??? abstract "Fedora 40 (x86_64)"
    Add the repository:
    ```
    sudo dnf config-manager --add-repo https://download.indii.org/rpm/fedora/40/indii.org.repo
    sudo dnf update
    ```
    Install packages:
    ```
    sudo dnf install doxide birch
    ```

??? abstract "Fedora 39 (x86_64)"
    Add the repository:
    ```
    sudo dnf config-manager --add-repo https://download.indii.org/rpm/fedora/39/indii.org.repo
    sudo dnf update
    ```
    Install packages:
    ```
    sudo dnf install doxide birch
    ```

??? question "openSUSE Tumbleweed (x86_64)"
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
