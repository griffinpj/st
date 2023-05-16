# st

This is my fork of st used to track my own changes to the project.

# st - simple terminal

This is a fork of the suckless [st](https://st.suckless.org/) terminal, a simple, lightweight, and highly customizable terminal emulator for X.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The st terminal is designed to be simple, efficient, and reliable. It follows the suckless philosophy of keeping things simple and avoiding unnecessary bloat. This fork aims to provide additional features and improvements while maintaining the core principles of st.

## Installation

To install st, follow these steps:

## Prerequisites

### macOS
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

