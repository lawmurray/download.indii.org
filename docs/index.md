---
hide:
  - navigation
  - path
  - toc
  - menu
---

# Linux package repository for indii.org

This repository is maintained by Lawrence Murray ([:material-github:](https://github.com/lawmurray){target="_blank"} [:material-mastodon:](https://fosstodon.org/@lawmurray){target="_blank"} [:material-web:](https://indii.org){target="_blank"} [:material-email:](mailto:lawrence@indii.org){target="_blank"}). It provides Linux packages of [Mending Wall](https://mendingwall.indii.org), [Doxide](https://doxide.org) and [Birch](https://birch-lang.org). All packages are available for both x86-64 (AMD64) and AArch64 (ARM64) unless otherwise noted.


??? ubuntu "Ubuntu 24.10 Oracular Oriole"
    Add the repository:
    ```
    echo 'deb http://download.indii.org/deb oracular main' | sudo tee /etc/apt/sources.list.d/indii.org.list
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
    Mending Wall is currently unavailable for AArch64 due to a [build error](https://github.com/lawmurray/mendingwall/issues/8).

??? fedora "Fedora 40"
    Add the repository:
    ```
    sudo dnf config-manager --add-repo https://download.indii.org/rpm/fedora/40/indii.org.repo
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
