---
hide:
  - navigation
  - path
  - toc
  - menu
---

# Linux packages

This repository is maintained by [Lawrence Murray](https://indii.org/about). It provides Linux packages for [Mending Wall](https://mendingwall.indii.org), [Doxide](https://doxide.org) and [Birch](https://birch-lang.org). All packages are available for both x86-64 (AMD64) and AArch64 (ARM64) unless otherwise noted.

??? ubuntu "Ubuntu 25.04 Plucky Puffin"
    Add the repository:
    ```
    echo 'deb http://download.indii.org/deb plucky main' | sudo tee /etc/apt/sources.list.d/indii.org.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.org.gpg > /dev/null
    sudo apt update
    ```
    Install desired packages, e.g.:
    ```
    sudo apt install mendingwall doxide birch
    ```

??? ubuntu "Ubuntu 24.04 Noble Numbat"
    Add the repository:
    ```
    echo 'deb http://download.indii.org/deb noble main' | sudo tee /etc/apt/sources.list.d/indii.org.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.org.gpg > /dev/null
    sudo apt update
    ```
    Install desired packages, e.g.:
    ```
    sudo apt install mendingwall doxide birch
    ```

??? debian "Debian 13 Trixie"
    Add the repository:
    ```
    echo 'deb http://download.indii.org/deb bookworm main' | sudo tee /etc/apt/sources.list.d/indii.org.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.org.gpg > /dev/null
    sudo apt update
    ```
    Install desired packages, e.g.:
    ```
    sudo apt install mendingwall doxide birch
    ```

??? debian "Debian 12 Bookworm"
    Add the repository:
    ```
    echo 'deb http://download.indii.org/deb bookworm main' | sudo tee /etc/apt/sources.list.d/indii.org.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.org.gpg > /dev/null
    sudo apt update
    ```
    Install desired packages, e.g.:
    ```
    sudo apt install mendingwall doxide birch
    ```
    Mending Wall is unavailable as a newer version of libadwaita is required. It is available on Debian 13.

??? fedora "Fedora 43"
    Add the repository:
    ```
    sudo dnf config-manager addrepo --from-repofile=https://download.indii.org/rpm/fedora/43/indii.org.repo
    sudo dnf update
    ```
    Install desired packages, e.g.:
    ```
    sudo dnf install mendingwall doxide birch
    ```

??? fedora "Fedora 42"
    Add the repository:
    ```
    sudo dnf config-manager addrepo --from-repofile=https://download.indii.org/rpm/fedora/42/indii.org.repo
    sudo dnf update
    ```
    Install desired packages, e.g.:
    ```
    sudo dnf install mendingwall doxide birch
    ```

??? fedora "Fedora 41"
    Add the repository:
    ```
    sudo dnf config-manager addrepo --from-repofile=https://download.indii.org/rpm/fedora/41/indii.org.repo
    sudo dnf update
    ```
    Install desired packages, e.g.:
    ```
    sudo dnf install mendingwall doxide birch
    ```

??? opensuse "openSUSE Tumbleweed"
    Add the repository:
    ```
    sudo zypper addrepo https://download.indii.org/rpm/opensuse/tumbleweed/indii.org.repo
    sudo zypper refresh
    ```
    Install desired packages, e.g.:
    ```
    sudo zypper install mendingwall doxide birch
    ```

??? opensuse "openSUSE Leap 16"
    Add the repository:
    ```
    sudo zypper addrepo https://download.indii.org/rpm/opensuse/leap/16/indii.org.repo
    sudo zypper refresh
    ```
    Install desired packages, e.g.:
    ```
    sudo zypper install mendingwall doxide birch
    ```
