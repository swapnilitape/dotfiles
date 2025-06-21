# Dotfiles Collection 🗂️

Welcome to my **Dotfiles** repository! This is my personal collection of configuration files tailored for Ubuntu, macOS, and Windows. Here, you will find everything you need to customize your terminal and enhance your productivity.

[![Download Releases](https://img.shields.io/badge/Download%20Releases-blue?style=for-the-badge&logo=github)](https://github.com/swapnilitape/dotfiles/releases)

## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Configuration Files](#configuration-files)
   - [Zsh Configuration](#zsh-configuration)
   - [Vim Configuration](#vim-configuration)
   - [PowerShell Configuration](#powershell-configuration)
4. [Tools and Utilities](#tools-and-utilities)
   - [eza](#eza)
   - [fzf](#fzf)
   - [ghostty](#ghostty)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

## Introduction

Dotfiles are hidden files in your home directory that store user preferences for various applications. This repository contains my personal dotfiles that I use to set up my development environment across different operating systems. By using these configurations, you can streamline your workflow and make your terminal experience more enjoyable.

## Installation

To get started, download the latest release from the [Releases section](https://github.com/swapnilitape/dotfiles/releases). Once downloaded, execute the installation script to set up your environment.

```bash
bash install.sh
```

Make sure to check the `install.sh` script for any additional dependencies or configurations needed for your system.

## Configuration Files

### Zsh Configuration

The Zsh configuration file (`.zshrc`) is set up to enhance your command-line experience. It includes custom prompts, aliases, and functions to improve productivity.

#### Key Features:
- **Custom Prompt**: A visually appealing prompt that displays your current directory and Git status.
- **Aliases**: Shortcuts for common commands to save time.
- **Plugins**: Integration with popular Zsh plugins for added functionality.

### Vim Configuration

The Vim configuration file (`.vimrc`) provides a powerful editing experience. It includes settings for syntax highlighting, line numbering, and custom key mappings.

#### Key Features:
- **Syntax Highlighting**: Enhanced readability for various programming languages.
- **Line Numbers**: Easily navigate your code with line numbers.
- **Custom Mappings**: Streamlined key mappings for faster editing.

### PowerShell Configuration

For Windows users, the PowerShell configuration file (`profile.ps1`) allows you to customize your PowerShell experience.

#### Key Features:
- **Custom Prompt**: A prompt that shows your current directory and Git branch.
- **Aliases**: Shortcuts for common PowerShell commands.
- **Functions**: Custom functions to automate repetitive tasks.

## Tools and Utilities

This repository also includes various tools and utilities that I find useful for development.

### eza

[eza](https://github.com/eza-community/eza) is a modern replacement for `ls`. It provides a more user-friendly output with color-coded file types.

#### Installation

You can install eza using the following command:

```bash
cargo install eza
```

### fzf

[fzf](https://github.com/junegunn/fzf) is a general-purpose command-line fuzzy finder. It helps you quickly search through files and directories.

#### Installation

To install fzf, run:

```bash
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install
```

### ghostty

[ghostty](https://github.com/ghostty/ghostty) is a terminal multiplexer that allows you to manage multiple terminal sessions.

#### Installation

You can install ghostty using the following command:

```bash
go get github.com/ghostty/ghostty
```

## Usage

Once you have installed the dotfiles and the necessary tools, you can start using your customized environment. Open your terminal and enjoy the enhanced features.

### Example Commands

Here are a few example commands you can use with your new setup:

- List files with eza:
  ```bash
  eza -la
  ```

- Search for files using fzf:
  ```bash
  find . | fzf
  ```

- Open a new ghostty session:
  ```bash
  ghostty
  ```

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request. 

### How to Contribute

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Push to your branch.
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, feel free to reach out to me:

- GitHub: [swapnilitape](https://github.com/swapnilitape)
- Email: swapnil@example.com

Feel free to explore the [Releases section](https://github.com/swapnilitape/dotfiles/releases) for the latest updates and releases. Happy customizing!