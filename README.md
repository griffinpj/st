# st - simple terminal
https://img.shields.io/github/last-commit/griffinpj/st

This is a fork of the suckless [st](https://st.suckless.org/) terminal, a simple, lightweight, and highly customizable terminal emulator for X.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The st terminal is designed to be simple, efficient, and reliable. It follows the suckless philosophy of keeping things simple and avoiding unnecessary bloat. This fork aims to provide additional features for my uses and support my local environement for development (macOS).

## Installation

To install st, follow these steps:

### Prerequisites

- Need to install xquartz (for X11 support) and fontconfig
    ```shell
    brew install xquartz
    brew install fontconfig
    ```


1. Clone this repository:

   ```shell
   git clone https://github.com/griffinpj/stA
   cd st
   ```

2. Edit the `config.mk` file as needed.
    - For macOS I had to use the freeBsd `X11/lib` and also change the path for X11 to use the paths for `xquartz`

3. Build and install st
    ```shell
    sudo make clean install
    ```

