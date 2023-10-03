# Setup Instructions for Windows users

Hey Devslopes Student!

Welcome to the first step in the Devslopes Web Academy, where you will set up your computer for this exciting learning journey 😃. Please ensure that you complete each installation in the specified order.

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
  - [Windows Subsystem for Linux (WSL)](#windows-subsystem-for-linux-wsl)
    - [Instructions to install Windows Subsystem for Linux](#instructions-to-install-windows-subsystem-for-linux)
  - [Install some WSL Packages](#install-some-wsl-packages)
  - [Setup VSCode to Work With WSL](#setup-vscode-to-work-with-wsl)
  - [Install zgen](#install-zgen)
  - [NodeJS](#nodejs)
    - [Instructions to install Node.js with NVM](#instructions-to-install-nodejs-with-nvm)
      - [Test your Node.js installation](#test-your-nodejs-installation)
  - [Test your NPM installation](#test-your-npm-installation)
    - [WSL2 invalid machine configuration troubleshooting](#wsl2-invalid-machine-configuration-troubleshooting)
  - [GIT](#git)
    - [Instructions to configure GIT](#instructions-to-configure-git)
    - [Instructions to set the SSH key for GITHUB](#instructions-to-set-the-ssh-key-for-github)
      - [Test your SSH connection to Github](#test-your-ssh-connection-to-github)
  - [Setup VSCode (Optional)](#setup-vscode-optional)
    - [Instructions to set the tab default size to 2 spaces](#instructions-to-set-the-tab-default-size-to-2-spaces)
    - [Instructions to install the Prettier extension in VSCode](#instructions-to-install-the-prettier-extension-in-vscode)
    - [Instructions to make Prettier your default code formatting tool](#instructions-to-make-prettier-your-default-code-formatting-tool)
    - [Instructions for automatically formatting code when saving a file](#instructions-for-automatically-formatting-code-when-saving-a-file)
    - [Instructions to install the "Indent-rainbow" extension in VSCode](#instructions-to-install-the-indent-rainbow-extension-in-vscode)
    - [Instructions to install the "Auto close tag" extension in VSCode](#instructions-to-install-the-auto-close-tag-extension-in-vscode)
    - [Instructions to install the "Auto rename tag" extension in VSCode](#instructions-to-install-the-auto-rename-tag-extension-in-vscode)

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

---

## Windows Subsystem for Linux (WSL)

The Windows Subsystem for Linux (WSL) allows developers to run a GNU/Linux environment, which includes command-line tools, utilities, and applications, directly on Windows without the need for a virtual machine or dual-boot setup.

### Instructions to install Windows Subsystem for Linux

1. Download Ubuntu from the Microsoft Store
2. When you go to open it you will likely encounter this error

```txt
WslRegisterDistribution failed with error: 0x8007019e
Error: 0x8007019e The Windows Subsystem for Linux has not been enabled.
```

3.Open Windows Terminal as an administrator (right-click on the app, select "Run as administrator").

Run the following commands line by line. Please make sure to check each step along the way that no errors occurred. If you do get errors you can either try good ol' google or reaching out in #all-questions on discord.

```powershell
# Line 1
wsl --install

# Line 2
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart


# Line 3
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart

# Line 4
wsl --set-default-version 2
```

4.Restart your computer to finish the installation.

5.Open up another powershell instance as an admin and type in `wsl --status` to check if you are on version 2, if not follow the [WSL2 invalid machine configuration troubleshooting](#wsl2-invalid-machine-configuration-troubleshooting) steps before continuing to step 6

6.Run the "Ubuntu" application to complete the installation and set up the UNIX user.

7.Make sure to remember the password you set, as you will need it frequently in the future.

8.Right click the top of your ubuntu window and go to `properties`

a. Make sure to click the box that says `use Ctr + Shift + C/V as Copy/Paste`
b. This will make it easier to copy stuff over to your ubuntu terminal both now and in the future

## Install some WSL Packages

1.Run the command `sudo apt update` to fetch the available software updates from index.

2.Run the command `sudo apt upgrade` to upgrade all the installed packages to their lates versions.

3.Install some useful packages using this command

This will install some packages that you will need later on in this course.

`sudo apt install zsh unzip git`

4.Change default shell to zsh

This will make your terminal look nicer, and give you some free cool shit when you are using github later on in this course.

`chsh -s $(which zsh)`

5.Restart Ubuntu

6.Install Bun

Bun is a Javascript Runtime that will be helpful for debugging once you start learning Javascript.

Run the following in your terminal

```zsh
curl -fsSL https://bun.sh/install | bash
```

7.Install Node

To install nvm please run the following command in your terminal
`curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | zsh`

## Setup VSCode to Work With WSL

1.In VSCode Install WSL Plugin

Go to the extension store in VSCode and download the WSL extension. It should be produced by microsoft and have over 20M downloads

This is extremely important, and will let you use VSCode with your WSL for Linux

That's it for this one 😃

To test to see if it worked, go into your Ubuntu terminal and type in `which code`

As long as it doesn't say `command not found "code"` or something like that, then you are good to go ✅

## Install zgen

Run this command to clone down the files for zgen

```zsh
git clone https://github.com/tarjoilija/zgen.git "${HOME}/.zgen"
```

ZGen will make your terminal much nicer looking. Watch what happens after running a few commands.

To finish this installation, let's open our `zsh` configuration file by typing the following in Ubuntu

```zsh
code ~/.zshrc
```

Then you will copy and paste the following contents into the `.zshrc` configuration file and hit save

```zsh
source "${HOME}/.zgen/zgen.zsh"

zgen prezto
prompt steeef

# bun completions
[ -s "/root/.bun/_bun" ] && source "/root/.bun/_bun"

# bun
export BUN_INSTALL="$HOME/.bun"
export PATH="$BUN_INSTALL/bin:$PATH"

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"
# This loads nvm bash_completion
```

1. Launch VSCode and open the new VSCode terminal.
2. Click the dropdown menu next to the "plus" icon and select "Select default Profile". 14. Choose "Ubuntu (WSL)" from the list.

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

## Test your NPM installation

1. Make sure Node.js is installed ([Instructions to install Node.js with NVM](#instructions-to-install-nodejs-with-nvm)).
2. Launch the Ubuntu app.
3. Run the command `npm -v` to check the installed version of Node Package Manager (NPM)

[Back to TOP](#table-of-contents)

---

### WSL2 invalid machine configuration troubleshooting

1. If you encounter the error message "WSL2 is not supported with your current machine configuration," it may be necessary to configure your BIOS settings. Follow the instructions provided in this link to enable virtualization in your BIOS: [BIOS Configuration for WSL2](https://bce.berkeley.edu/enabling-virtualization-in-your-pc-bios.html).
2. Open Windows Terminal as an administrator.
3. Run the command "dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart".
4. Restart your computer to complete the installation.
5. Open Windows Terminal as an administrator.
6. Run the command "wsl --set-version Ubuntu 2" and wait for the message "Conversion complete" or "This distribution is already the requested version".
7. If you still receive the error "WSL2 is not supported with your current machine configuration," continue with WSL1 and go back to step 8 of the [Instructions to install Windows Subsystem for Linux](#instructions-to-install-windows-subsystem-for-linux).

---

## GIT

GIT is a distributed version control system that allows developers to track changes, collaborate on projects, and manage source code effectively. It provides a way to keep a history of changes made to files, allowing developers to revert to previous versions if needed. GIT's decentralized architecture allows multiple developers to work on the same project simultaneously, independently making changes and merging them seamlessly. It also supports branching, which enables developers to work on separate features or experiments without affecting the main project, and later merge those branches back together. GIT has become an essential tool for software development, enabling teams to work collaboratively, track changes, and ensure code integrity.

GIT is already included in the Windows Subsystem for Linux (WSL), so there is no need for a separate installation. However, you may still need to configure GIT to work properly within the WSL environment and Github remote repos.

### Instructions to configure GIT

We've already installed Git earlier when we ran `sudo apt install xxx xxx git`. Git was one of the pieces of software that our package manager `apt` was installing.

Please verify that it is there by typing in.

`which git`

As long as it doesn't say 'Command Not Found' we're good to go

1. Create an account on [GitHub](https://github.com/signup).
2. Open an Ubuntu Terminal (May be easier to copy / paste inside of VSCode)
3. Run the command `git config --global user.name "John Doe"` to set the default user name. **Make sure that you change this text to match your username that you used for github.**
4. Run the command `git config --global user.email name@domain.zone` to set the default email, which should match the email used during GitHub sign-up.**Make sure that you change this text to match your email that you used for github.**

5. Run the command `git config user.name` to verify that the user name is set correctly.
6. Run the command `git config user.email` to verify that the user email is set correctly.

### Instructions to set the SSH key for GITHUB

1. Launch the Ubuntu application.
2. Follow the [Generate new SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=linux) instructions to generate a new SSH key. Be sure to omit the "Generating a new SSH key for a hardware security key" section.
3. Follow the [Add a new SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account?platform=linux&tool=webui) instructions to add a new SSH key to your GitHub account.

#### Test your SSH connection to Github

Run the command `ssh -T git@github.com` to test your connection to GitHub. Wait wor the message "Hi user.name! You've successfully authenticated, but GitHub does not provide shell access."

[Back to TOP](#table-of-contents)

---

## Setup VSCode (Optional)

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
