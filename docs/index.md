---
hide:
  - navigation
  - path
---

# download.indii.org

This repository provides packages for Linux and Mac for software including [Doxide](https://doxide.org) and [Birch](https://birch.sh). Follow the instructions below for your platform to set up the repository and install.

## :fontawesome-brands-ubuntu: Ubuntu

??? example "Ubuntu 22.10 Kinetic Kudu (amd64)"
    Set up the repository:
    ```
    echo 'deb http://download.indii.org/deb kinetic main' | sudo tee /etc/apt/sources.list.d/indii.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.gpg > /dev/null
    sudo apt update
    ```
    Install packages:
    ```
    sudo apt install doxide birch
    ```
    To enable Nvidia GPU support with Birch, [install CUDA][cuda] separately and then the NumBirch CUDA backend:
    ```
    sudo apt install numbirch-cuda-dev
    ```

??? example "Ubuntu 22.04 Jammy Jellyfish (amd64)"
    Set up the repository:
    ```
    echo 'deb http://download.indii.org/deb jammy main' | sudo tee /etc/apt/sources.list.d/indii.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.gpg > /dev/null
    sudo apt update
    ```
    Install packages:
    ```
    sudo apt install doxide birch
    ```
    To enable Nvidia GPU support with Birch, [install CUDA][cuda] separately and then the NumBirch CUDA backend:
    ```
    sudo apt install numbirch-cuda-dev
    ```

??? example "Ubuntu 20.04 Focal Fossa (amd64)"
    Set up the repository:
    ```
    echo 'deb http://download.indii.org/deb focal main' | sudo tee /etc/apt/sources.list.d/indii.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.gpg > /dev/null
    sudo apt update
    ```
    Install packages:
    ```
    sudo apt install doxide birch
    ```
    To enable Nvidia GPU support with Birch, [install CUDA][cuda] separately and then the NumBirch CUDA backend:
    ```
    sudo apt install numbirch-cuda-dev
    ```

## :simple-debian: Debian

??? example "Debian 11 Bullseye (amd64)"
    Set up the repository:
    ```
    echo 'deb http://download.indii.org/deb bullseye main' | sudo tee /etc/apt/sources.list.d/indii.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.gpg > /dev/null
    sudo apt update
    ```
    Install packages:
    ```
    sudo apt install doxide birch
    ```
    To enable Nvidia GPU support with Birch, [install CUDA][cuda] separately and then the NumBirch CUDA backend:
    ```
    sudo apt install numbirch-cuda-dev
    ```

??? example "Debian 10 Buster (amd64)"
    Set up the repository:
    ```
    echo 'deb http://download.indii.org/deb buster main' | sudo tee /etc/apt/sources.list.d/indii.list
    curl -fsSL https://download.indii.org/deb/Release.key | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/indii.gpg > /dev/null
    sudo apt update
    ```
    Install packages:
    ```
    sudo apt install doxide birch
    ```
    To enable Nvidia GPU support with Birch, [install CUDA][cuda] separately and then the NumBirch CUDA backend:
    ```
    sudo apt install numbirch-cuda-dev
    ```

## :fontawesome-brands-fedora: Fedora

??? example "Fedora 37 (x86_64)"
    Set up the repository:
    ```
    sudo dnf config-manager --add-repo https://download.indii.org/rpm/fedora/37/indii.repo
    sudo dnf update
    ```
    Install packages:
    ```
    sudo dnf install doxide birch
    ```
    To enable Nvidia GPU support with Birch, [install CUDA][cuda] separately and then the NumBirch CUDA backend:
    ```
    sudo dnf install numbirch-cuda-devel
    ```

??? example "Fedora 36 (x86_64)"
    Set up the repository:
    ```
    sudo dnf config-manager --add-repo https://download.indii.org/rpm/fedora/36/indii.repo
    sudo dnf update
    ```
    Install packages:
    ```
    sudo dnf install doxide birch
    ```
    To enable Nvidia GPU support with Birch, [install CUDA][cuda] separately and then the NumBirch CUDA backend:
    ```
    sudo dnf install numbirch-cuda-devel
    ```

??? example "Fedora 35 (x86_64)"
    Set up the repository:
    ```
    sudo dnf config-manager --add-repo https://download.indii.org/rpm/fedora/35/indii.repo
    sudo dnf update
    ```
    Install packages:
    ```
    sudo dnf install doxide birch
    ```
    To enable Nvidia GPU support with Birch, [install CUDA][cuda] separately and then the NumBirch CUDA backend:
    ```
    sudo dnf install numbirch-cuda-devel
    ```

## :simple-opensuse: openSUSE

??? example "openSUSE Tumbleweed (x86_64)"
    Set up the repository:
    ```
    sudo zypper addrepo https://download.indii.org/rpm/opensuse/tumbleweed/indii.repo
    sudo zypper refresh
    ```
    Install packages:
    ```
    sudo zypper install doxide birch
    ```
    To enable Nvidia GPU support with Birch, [install CUDA][cuda] separately and then the NumBirch CUDA backend:
    ```
    sudo zypper install numbirch-cuda-devel
    ```

??? example "openSUSE Leap 15.4 (x86_64)"
    Set up the repository:
    ```
    sudo zypper addrepo https://download.indii.org/rpm/opensuse/leap/15.4/indii.repo
    sudo zypper refresh
    ```
    Install packages:
    ```
    sudo zypper install doxide birch
    ```
    To enable Nvidia GPU support with Birch, [install CUDA][cuda] separately and then the NumBirch CUDA backend:
    ```
    sudo zypper install numbirch-cuda-devel
    ```

## :fontawesome-brands-linux: Mageia

??? example "Mageia 8 (x86_64)"
    Set up the repository:
    ```
    sudo dnf config-manager --add-repo https://download.indii.org/rpm/mageia/8/indii.repo
    sudo dnf update
    ```
    Install packages:
    ```
    sudo dnf install doxide birch
    ```
    To enable Nvidia GPU support with Birch, [install CUDA][cuda] separately and then the NumBirch CUDA backend:
    ```
    sudo dnf install numbirch-cuda-devel
    ```

## :fontawesome-brands-apple: Mac

??? example "Homebrew"
    Install [Homebrew](https://brew.sh) if not already, add the tap with:
    ```sh
    brew tap indii/all https://download.indii.org/brew
    ```
    then install the packages that you need with e.g.
    ```
    brew install indii/all/doxide indii/all/birch
    ```

## :fontawesome-brands-windows: Windows

Native support is not yet provided, but you can install [Windows Subsystem for Linux](https://learn.microsoft.com/en-us/windows/wsl/install) with one of the Linux distributions above and follow the instructions for it.

!!! tip
    If you are particularly interested in Windows support for Doxide, see [this ticket](https://github.com/lawmurray/doxide/issues/3) for ways to help.

## :fontawesome-solid-file-zipper: Others: Install from source

If a package is not available for your operating system or you have special requirements, you can install from source. See:

- [Doxide README.md](https://github.com/lawmurray/doxide)
- [Birch README.md](https://github.com/lawmurray/Birch)

[cuda]: https://developer.nvidia.com/cuda-downloads

## About

This repository is maintained by Lawrence Murray ([:material-github:](https://github.com/lawmurray){target="_blank"} [:material-mastodon:](https://fosstodon.org/@lawmurray){target="_blank"} [:material-twitter:](https://twitter.com/lawmurray){target="_blank"} [:material-web:](https://indii.org){target="_blank"} [:material-email:](mailto:lawrence@indii.org){target="_blank"}). It is rebuilt by an automated pipeline on [CircleCI](https://circleci.com) when new versions of software are tagged.
