---
hide:
  - navigation
  - path
  - toc
  - menu
---

# Indii.org Software Repository

This repository provides packages of [Doxide](https://doxide.org) and [Birch](https://birch-lang.org) for various Linux distributions. Select a distribution below for instructions to use.

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

??? abstract "Fedora 41 (x86_64)"
    Add the repository:
    ```
    sudo dnf config-manager addrepo --from-repofile=https://download.indii.org/rpm/fedora/41/indii.org.repo
    sudo dnf update
    ```
    Install packages:
    ```
    sudo dnf install doxide birch
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

## About

This repository is maintained by Lawrence Murray ([:material-github:](https://github.com/lawmurray){target="_blank"} [:material-mastodon:](https://fosstodon.org/@lawmurray){target="_blank"} [:material-web:](https://indii.org){target="_blank"} [:material-email:](mailto:lawrence@indii.org){target="_blank"}) for software that he develops. It is rebuilt by an automated pipeline on [CircleCI](https://circleci.com) when new versions are released.

