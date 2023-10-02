# Setup Instructions for Windows users

Hey Devslopes Student!

Welcome to the first step in the Devslopes Web Academy, where you will set up your computer for this exciting learning journey. Please ensure that you complete each installation in the specified order.

These instructions have been tested on various types of machines, but there may be instances where things don't work exactly as expected. Make sure to carefully read the descriptive terminal messages and, if needed, repeat the previous step. If the issue persists, take a screenshot of the terminal or the software error message and provide it to Devslopes mentors for assistance.

Note: Remember to press "enter" after copying and pasting the command into the terminal to run it.

## Table of contents

Here is a list of software you should have installed and configured before you begin the program to optimize your learning experience with Devslopes:

- [Setup Instructions for Windows users](#setup-instructions-for-windows-users)
  - [Table of contents](#table-of-contents)
  - [Google Chrome Browser](#google-chrome-browser)
    - [Instructions to install Google Chrome Browser](#instructions-to-install-google-chrome-browser)
  - [Discord](#discord)
    - [Instructions to install Discord](#instructions-to-install-discord)
  - [Zoom](#zoom)
    - [Instructions to install Zoom](#instructions-to-install-zoom)
  - [Loom](#loom)
    - [Instructions to install Loom](#instructions-to-install-loom)
  - [VSCode IDE](#vscode-ide)
    - [Instructions to install VSCode IDE](#instructions-to-install-vscode-ide)
    - [Instructions to set the tab default size to 2 spaces](#instructions-to-set-the-tab-default-size-to-2-spaces)
    - [Instructions to install the Prettier extension in VSCode](#instructions-to-install-the-prettier-extension-in-vscode)
    - [Instructions to make Prettier your default code formatting tool](#instructions-to-make-prettier-your-default-code-formatting-tool)
    - [Instructions for automatically formatting code when saving a file](#instructions-for-automatically-formatting-code-when-saving-a-file)
    - [Instructions to install the "Indent-rainbow" extension in VSCode](#instructions-to-install-the-indent-rainbow-extension-in-vscode)
    - [Instructions to install the "Auto close tag" extension in VSCode](#instructions-to-install-the-auto-close-tag-extension-in-vscode)
    - [Instructions to install the "Auto rename tag" extension in VSCode](#instructions-to-install-the-auto-rename-tag-extension-in-vscode)
  - [Windows Subsystem for Linux (WSL)](#windows-subsystem-for-linux-wsl)
    - [Instructions to install Windows Subsystem for Linux](#instructions-to-install-windows-subsystem-for-linux)
    - [WSL2 invalid machine configuration troubleshooting](#wsl2-invalid-machine-configuration-troubleshooting)
    - [Basic navigation and VSCode running Unix terminal Commands List](#basic-navigation-and-vscode-running-unix-terminal-commands-list)
  - [Z Shell (ZSH)](#z-shell-zsh)
    - [Instructions to install Z Shell (ZSH)](#instructions-to-install-z-shell-zsh)
    - [Test your Z Shell (ZSH) installation](#test-your-z-shell-zsh-installation)
    - [Instructions to set Z Shell as the default shell for WSL](#instructions-to-set-z-shell-as-the-default-shell-for-wsl)
  - [Node Version Manager (NVM)](#node-version-manager-nvm)
    - [Instructions to install Node Version Manager (NVM)](#instructions-to-install-node-version-manager-nvm)
    - [Test your Node Version Manager Installation](#test-your-node-version-manager-installation)
  - [NodeJS](#nodejs)
    - [Instructions to install Node.js with NVM](#instructions-to-install-nodejs-with-nvm)
      - [Test your Node.js installation](#test-your-nodejs-installation)
  - [Node Package Manager (NPM)](#node-package-manager-npm)
    - [Test your NPM installation](#test-your-npm-installation)
  - [GIT](#git)
    - [Instructions to configure GIT](#instructions-to-configure-git)
    - [Instructions to update GIT to the latest version](#instructions-to-update-git-to-the-latest-version)
      - [Test your GIT installation](#test-your-git-installation)
    - [Instructions to set the SSH key for GITHUB](#instructions-to-set-the-ssh-key-for-github)
      - [Test your SSH connection to Github](#test-your-ssh-connection-to-github)

## Google Chrome Browser

For beginners, the Google Chrome Browser is the optimal option as it offers the most comprehensive Web Developer experience. While other Webkit engine browsers like Brave or Opera will suffice, we highly recommend starting with Google Chrome to grasp the foundational concepts. Once proficient, you can explore other browsers and determine which suits you best.

### Instructions to install Google Chrome Browser

1. Visit the official [Google Chrome website](https://google.com/chrome).
2. Click on the "Download Chrome" button.
3. The installer will begin downloading automatically.
4. Once the download is complete, locate the installer file in your computer's Downloads folder.
5. Double-click on the installer file to launch the installation process.
6. Follow the on-screen instructions to complete the installation.
7. Once the installation is finished, you can launch Google Chrome by clicking on its icon on the desktop or by searching for it in the Start menu.
8. Upon launching Chrome, you will be prompted to sign in with your Google account. You can choose to skip this step if you prefer.
9. Congratulations! You have successfully installed Google Chrome. Enjoy browsing the web with one of the most popular and feature-rich browsers available.

[Back to TOP](#table-of-contents)

---

## Discord

Discord is a popular communication platform designed for creating communities and fostering real-time interaction among users. It offers features like text chat, voice chat, and video chat, allowing individuals or groups to communicate with each other seamlessly. The Devslopes Web Academy community is using that messenger to communicate, schedule meetups and events, track student progress, and ensure the community stays informed about all the latest updates and changes in the frequently updated curriculum.

### Instructions to install Discord

1. Visit the official [Discord website](https://discord.com).
2. Click on the "Download for Windows" button.
3. The installer will begin downloading automatically.
4. Once the download is complete, locate the installer file in your computer's Downloads folder.
5. Double-click on the installer file to launch the installation process.
6. Follow the on-screen instructions to complete the installation.
7. Once the installation is complete, the Discord application will automatically launch, or you can manually start Discord by searching for it in the Start menu.
8. Complete the sign-in or sign-up process steps.

[Back to TOP](#table-of-contents)

---

## Zoom

Zoom is a widely-used video conferencing platform that enables users to remotely connect and collaborate. With its user-friendly interface and comprehensive set of features, Zoom has become a preferred solution for businesses, schools, and individuals globally. Students are able to attend daily meetings, engage in webinars, and facilitate virtual events using functionalities such as screen sharing, text-based chat, and voice calls with Devslopes Web Academy mentors.

### Instructions to install Zoom

1. Open Windows Terminal as an administrator.
2. Type `wmic os get osarchitecture` to determine the current operating system architecture.
3. Visit the official [Zoom Desktop Client Download page](https://zoom.us/download#client_4meeting).
4. Click on the download button or the lint that matches your architecture (32-bit client, 64-bit client or ARM client).
5. The installer will begin downloading automatically.
6. Once the download is complete, locate the installer file in your computer's Downloads folder.
7. Double-click on the installer file to launch the installation process.
8. Click on the "Sign Up" or "Sign In" button in the popup window that appears after the installation process.
9. Follow the prompts to complete the sign-up process.

[Back to TOP](#table-of-contents)

---

## Loom

Loom is a video messaging and screen recording platform that allows users to easily create and share videos. With Loom, students can quickly capture their screen, record their webcam, or create a combination of both to effectively communicate ideas, share tutorials, provide feedback or demonstrate the issue they struggle on for the Discord all-question posts.

### Instructions to install Loom

1. Visit the official [Loom Desktop App Download page](https://www.loom.com/download).
2. Click on the "Download app" button.
3. The installer will begin downloading automatically.
4. Follow the prompts to complete the sign-in or sign-up process.
5. Once the download is complete, locate the installer file in your computer's Downloads folder.
6. Double-click on the installer file to launch the installation process.
7. Once the installation is complete, the Loom application will automatically launch, or you can manually start Loom by searching for it in the Start menu.

[Back to TOP](#table-of-contents)

---

## VSCode IDE

VSCode, short for Visual Studio Code, is a popular Integrated Development Environment (IDE) developed by Microsoft. It has quickly become one of the top choices among developers and is particularly well-suited for web development using languages such as HTML, CSS, and JavaScript. Moreover, it is available for free, making it an accessible option for programmers.

### Instructions to install VSCode IDE

1. Open Windows Terminal as an administrator.
2. Type `wmic os get osarchitecture` to determine the current operating system architecture.
3. Go to the [VSCode Download page](https://code.visualstudio.com/download).
4. Click on the download button that matches your architecture (32-bit for "x86", 64-bit for "x64", ARM 64-bit for "Arm64").
5. Run the downloaded installer file from your "Downloads" folder.
6. Follow the on-screen instructions to complete the installation process.
7. Once the installation is finished, launch the VSCode app.
8. (Optional) Pin the app to the taskbar for quick access.

### Instructions to set the tab default size to 2 spaces

1. Launch the VSCode application.
2. Press `Shift + Control + P` to open the Command Palette.
3. Enter "Settings" in the search field that appears after the caret symbol (>)
4. Select the option "Preferences: Open Settings (UI)" from the list of suggestions.
5. Enter "tab size" in the search field and set "2" in the "Editor: Tab Size" setting field.

### Instructions to install the Prettier extension in VSCode

1. Launch the VSCode application.
2. Open the "Extensions" sidebar by pressing `Shift + Control + X`.
3. Search for the "Prettier" extension, which should have over 35 million installations.
4. Click on the "Install" button to install the extension.

### Instructions to make Prettier your default code formatting tool

1. Launch the VSCode application.
2. Create a new folder and open it using the "Explorer -> Open Folder" option.
3. Create three files: index.html, styles.css, and scripts.js.
4. For each file (active tab), follow these instructions:
5. Press `Shift + Control + P` to open the Command Palette.
6. Enter "format" in the search field that appears after the caret symbol (>)
7. Select the option "Format Document" from the list of suggestions.
8. Click on "Configure" when prompted.
9. In the dropdown menu, choose "Prettier" for formatting the document.

### Instructions for automatically formatting code when saving a file

1. Launch the VSCode application.
2. Press `Shift + Control + P` to open the Command Palette.
3. Enter "settings" in the search field that appears after the caret symbol (>)
4. Select the option "Preferences: Open Settings (UI)" from the list of suggestions.
5. In the Settings tab, type "format on save" in the search bar.
6. Enable the checkbox for "Editor: Format On Save" to automatically format your code when you save the file.
7. Close the Settings tab.

### Instructions to install the "Indent-rainbow" extension in VSCode

1. Launch the VSCode application.
2. Open the "Extensions" sidebar by pressing `Shift + Ctrl + X`.
3. Search for the "indent-rainbow" extension, which has over 5 million installations.
4. Click on the "Install" button to install the extension.

### Instructions to install the "Auto close tag" extension in VSCode

1. Launch the VSCode application.
2. Open the "Extensions" sidebar (press `shift + ctrl + X`).
3. Search for the "auto close tag" extension, which should have over 10 million installations.
4. Proceed to install the extension by clicking on the "Install" button.

### Instructions to install the "Auto rename tag" extension in VSCode

1. Launch the VSCode application.
2. Open the "Extensions" sidebar (press `shift + ctrl + X`).
3. Search for the "auto rename tag" extension, which should have over 15 million installations.
4. Proceed to install the extension by clicking on the "Install" button.

[Back to TOP](#table-of-contents)

---

## Windows Subsystem for Linux (WSL)

The Windows Subsystem for Linux (WSL) allows developers to run a GNU/Linux environment, which includes command-line tools, utilities, and applications, directly on Windows without the need for a virtual machine or dual-boot setup.

### Instructions to install Windows Subsystem for Linux

1. Open Windows Terminal as an administrator (right-click on the app, select "Run as administrator").
2. Run the command `wsl --install` (You will need to reboot your operating system when the installation is complete).
3. Restart your computer to finish the installation.
4. Open Windows Terminal as an administrator.
5. Type `wsl -l -v` to check the default version of WSL being used. If it is version 2, proceed to step 8.
6. Type `wsl --set-version Ubuntu 2` and wait for the message "Conversion complete" or "This distribution is already the requested version".
7. Type `wsl --status` to ensure the version is 2. If not, follow the [WSL2 invalid machine configuration troubleshooting](#wsl2-invalid-machine-configuration-troubleshooting) steps before continuing to step 8.
8. Run the "Ubuntu" application to complete the installation and set up the UNIX user.
9. Make sure to remember the password you set, as you will need it frequently in the future.
10. Run the command `sudo apt update` to fetch the available software updates from index.
11. Run the command `sudo apt upgrade` to upgrade all the installed packages to their lates versions.
12. Launch VSCode and open the new VSCode terminal.
13. Click the dropdown menu next to the "plus" icon and select "Select default Profile".
14. Choose "Ubuntu (WSL)" from the list.

### WSL2 invalid machine configuration troubleshooting

1. If you encounter the error message "WSL2 is not supported with your current machine configuration," it may be necessary to configure your BIOS settings. Follow the instructions provided in this link to enable virtualization in your BIOS: [BIOS Configuration for WSL2](https://bce.berkeley.edu/enabling-virtualization-in-your-pc-bios.html).
2. Open Windows Terminal as an administrator.
3. Run the command "dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart".
4. Restart your computer to complete the installation.
5. Open Windows Terminal as an administrator.
6. Run the command "wsl --set-version Ubuntu 2" and wait for the message "Conversion complete" or "This distribution is already the requested version".
7. If you still receive the error "WSL2 is not supported with your current machine configuration," continue with WSL1 and go back to step 8 of the [Instructions to install Windows Subsystem for Linux](#instructions-to-install-windows-subsystem-for-linux).

### Basic navigation and VSCode running Unix terminal Commands List

NOTE: By default, the Ubuntu app will open in the UNIX user's folder each time you launch it.

1. Use the command `ls` to view the files and folders in the current directory.
2. Use the command `la` to view all files and folders, including hidden ones, in the current directory.
3. Use the command `touch <file-name>` to create a new file in the current directory.
4. Use the command `mkdir <folder-name>` to create a new folder in the current directory.
5. Use the command `cd <path>` to navigate the terminal to a specific location.
6. Use the command `cd ..` to navigate the terminal to the parent directory.
7. Use the command `cd` or `cd ~` to navigate the terminal to the user's home folder.
8. Use the command `code <folder-name>` to launch VSCode in the specified folder.
9. Use the command `code .` to launch VSCode in the current directory.

[Back to TOP](#table-of-contents)

---

## Z Shell (ZSH)

ZSH, short for Z Shell, is an alternative shell to the widely used Bash shell in Unix-based operating systems. It offers a more powerful and customizable command-line experience with additional features such as advanced tab completion, spelling correction, plugin support, and extensive prompt customization options. ZSH also provides improved performance with optimizations and enhancements over the traditional Bash shell. With its user-friendly interface and extensive configurability, ZSH has become a popular choice among developers and power users for enhancing productivity and efficiency in the command-line environment.

### Instructions to install Z Shell (ZSH)

1. Launch the Ubuntu application.
2. Run the command `sudo apt install zsh` to install the latest Z Shell.
3. Run the command `touch ~/.zshrc` to create Z Shell configuration file.
4. Restart the Ubuntu app.

### Test your Z Shell (ZSH) installation

Run the command `zsh --version` to check the installed version of Z Shell (ZSH).

### Instructions to set Z Shell as the default shell for WSL

1. Lunch the Ubuntu Application.
2. Run the command `chsh -s $(which zsh)` to change the default shell to ZSH
3. Restart Ubuntu app.
4. Run the command `echo $0` to check which shell is used (should say "-zsh").

[Back to TOP](#table-of-contents)

---

## Node Version Manager (NVM)

Node Version Manager (NVM) is a tool that allows developers to easily install, manage, and switch between multiple versions of Node.js on a single machine. It provides a command-line interface to install Node.js versions from the official Node.js distribution, as well as other sources, and enables developers to quickly switch between different versions to ensure compatibility with their projects or to test their code against different Node.js versions. NVM simplifies the process of managing Node.js versions, making it easier for developers to work with different versions of Node.js and ensuring their projects are running on the appropriate runtime environment.

### Instructions to install Node Version Manager (NVM)

1. Launch the Ubuntu app.
2. Run the commands

```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | zsh
```

```sh
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
```

```sh
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
```

3. Restart the Ubuntu app.

### Test your Node Version Manager Installation

1. Run the command `nvm --version` to check the installed version of NVM.
2. Run the command `nvm` to see the available arguments that can be used with nvm.

[Back to TOP](#table-of-contents)

---

## NodeJS

Node.js is an open-source, server-side JavaScript runtime environment that allows developers to build scalable and high-performance applications. It uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, making it particularly well-suited for applications that require real-time communication and data-intensive tasks. Node.js enables developers to write server-side code using JavaScript, which reduces the complexity of having separate client-side and server-side languages. It has a vibrant ecosystem with a wide range of libraries and frameworks, which makes it a popular choice for web and network application development.

### Instructions to install Node.js with NVM

1. Launch the Ubuntu app.
2. Run the command `nvm install v18.17.1` to install the latest long term support version of Node.js.

#### Test your Node.js installation

1. Run the command `nvm list` to check the default version of Node.js is 18.17.1.
2. Run the command `node -v` to check the current version of Node.js is 18.17.1.

[Back to TOP](#table-of-contents)

---

## Node Package Manager (NPM)

Node Package Manager (NPM) is a package manager for the JavaScript programming language. It is bundled with the Node.js runtime and allows developers to easily install, manage, and share reusable JavaScript code packages. NPM provides a vast repository of over a million packages that developers can leverage in their projects, ranging from small utility libraries to full-fledged frameworks and tools. With NPM, developers can easily add new functionality to their applications, handle dependencies, and manage project dependencies efficiently. NPM has become an essential tool in the JavaScript ecosystem, enabling developers to streamline their workflows and build robust and scalable applications.

### Test your NPM installation

1. Make sure Node.js is installed ([Instructions to install Node.js with NVM](#instructions-to-install-nodejs-with-nvm)).
2. Launch the Ubuntu app.
3. Run the command `npm -v` to check the installed version of Node Package Manager (NPM)

[Back to TOP](#table-of-contents)

---

## GIT

GIT is a distributed version control system that allows developers to track changes, collaborate on projects, and manage source code effectively. It provides a way to keep a history of changes made to files, allowing developers to revert to previous versions if needed. GIT's decentralized architecture allows multiple developers to work on the same project simultaneously, independently making changes and merging them seamlessly. It also supports branching, which enables developers to work on separate features or experiments without affecting the main project, and later merge those branches back together. GIT has become an essential tool for software development, enabling teams to work collaboratively, track changes, and ensure code integrity.

GIT is already included in the Windows Subsystem for Linux (WSL), so there is no need for a separate installation. However, you may still need to configure GIT to work properly within the WSL environment and Github remote repos.

### Instructions to configure GIT

1. Create an account on [GitHub](https://github.com/signup).
2. Launch the Ubuntu app.
3. Run the command `git config --global user.name "John Doe"` to set the default user name.
4. Run the command `git config --global user.email name@domain.zone` to set the default email, which should match the email used during GitHub sign-up.
5. Run the command `git config user.name` to verify that the user name is set correctly.
6. Run the command `git config user.email` to verify that the user email is set correctly.

### Instructions to update GIT to the latest version

1. Launch the Ubuntu app.
2. Run the command `sudo add-apt-repository ppa:git-core/ppa` and press enter when prompted.
3. Run the command `sudo apt update` to update the apt package index.
4. Run the command `sudo apt install git` to install Git.

#### Test your GIT installation

1. Run the command `git --version` to check the installed version of Git.
2. Visit [https://git-scm.com](https://git-scm.com) to confirm that your Git version matches the latest available version.

### Instructions to set the SSH key for GITHUB

1. Launch the Ubuntu application.
2. Follow the [Generate new SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=linux) instructions to generate a new SSH key. Be sure to omit the "Generating a new SSH key for a hardware security key" section.
3. Follow the [Add a new SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account?platform=linux&tool=webui) instructions to add a new SSH key to your GitHub account.

#### Test your SSH connection to Github

Run the command `ssh -T git@github.com` to test your connection to GitHub. Wait wor the message "Hi user.name! You've successfully authenticated, but GitHub does not provide shell access."

[Back to TOP](#table-of-contents)

---
