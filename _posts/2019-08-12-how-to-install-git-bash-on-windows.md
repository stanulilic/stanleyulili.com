---
header:
  teaser: /assets/images/posts/2019-08-13-install-git-bash/featured-image.jpg
feature_image: /assets/images/posts/2019-08-13-install-git-bash/featured-image.jpg
featured_image_alt: featured-image
excerpt: In this tutorial, we are going to learn how to install Git Bash on Windows. Git Bash for Windows is a package that comprises of `git` and `bash`.

categories:
 - Git
tags:
 - git
 - windows
 - bash
toc: true
---
## Introduction
In this tutorial, we are going to learn how to install Git Bash on Windows.

 Git Bash for Windows is a package that includes `git` and `bash`.

**Git** is an open-source version control system for tracking source code changes when developing software. It keeps a commit history which allows you to revert to a stable state in case you mess up your code. Git also allows multiple developers to collaborate on the same code base.

**Bash** is a Unix command-line shell. The name is an acronym for the 'Bourne-Again Shell'. It comes with useful Unix commands like cat, ssh, SCP, etc., which are not usually found on Windows.

## Download Git Bash
### Step 1: Visit the Official Git Bash Website

Download the latest version of Git Bash from their official website: [https://git-scm.com/](https://git-scm.com/)

![git bash official page](/assets/images/posts/2019-08-13-install-git-bash/official-homepage.jpg)

Click the "Download for windows" button.  

### Step 2: Start Git Bash Download

Next, you will be redirected to a page that lets you know that you are about to start downloading.

![git bash download page](/assets/images/posts/2019-08-13-install-git-bash/download-starting.jpg) 

If all goes well, the download should start automatically.

**Tip:** If the download doesn't start, click on the "click here to download manually" link.
{: .notice--info}

![download bash](/assets/images/posts/2019-08-13-install-git-bash/permission.jpg) 

Click on "Save File" to start downloading the executable.


## Install Git Bash
### Step 3: Run the Installer

Once you have downloaded the Git Bash executable, click it to run the installer.

![accept license](/assets/images/posts/2019-08-13-install-git-bash/accept-license.jpg)

Click "Next" after you have read the license.


### Step 4: Select Destination Location

Next, select the location you want to install Git Bash. I would recommend you just leave the default option as it is, and click "Next".

![choose default](/assets/images/posts/2019-08-13-install-git-bash/installation-directory.jpg)

### Step 5: Select Components

Choose the components you want to install, or you can just proceed with the default options and click "Next". I prefer selecting the "Additional icons" component which creates a Git Bash shortcut on the desktop.

![select components](/assets/images/posts/2019-08-13-install-git-bash/select-components.jpg)

### Step 6: Select Start Menu Folder

You can change the name of start menu folder here if you want, or just leave the default name and click "Next".

![select start menu folder](/assets/images/posts/2019-08-13-install-git-bash/select-start-menu-folder.jpg)

### Step 7: Choose the Default Editor  used by Git

Next, select the default editor for Git to use. Choose the one you like and click "Next". I would recommend you proceed with **Nano** or **Notepad++**. Don't proceed with the default option "Vim" as it has a steep learning curve.

![Choose default editor](/assets/images/posts/2019-08-13-install-git-bash/choose-editor.jpg)
![Choose nano editor](/assets/images/posts/2019-08-13-install-git-bash/choose-nano.jpg)
![editor chosen](/assets/images/posts/2019-08-13-install-git-bash/editor-chosen.jpg)

### Step 8: Adjust your PATH Environment 

Choose the option you want depending on where you want to use Git and click "Next".

Select **"Use Git from Git Bash only"** option if want to run Git and Bash commands from Git Bash only. This means that you won't be able to run Git commands such as `git status` on Windows Command Prompt or Powershell. They will only be found on Git Bash.

Select **"Git from the command line and also from 3rd-party software"** option if you want to run Git commands on Windows Command Prompt or Powershell.

**Notice:**  Bash commands won't work on Command Prompt or Powershell with this option, but only Git commands will work.
{: .notice--warning}  

**Tip:** If you need
run bash commands, you will have to open the Git Bash. So go ahead with this option if that is what you want. 
{: .notice--info}

Select **"Use Git and optional Unix tools from the Command Prompt"** option if you want to use both Git and Bash commands on Windows Command Prompt or Powershell. This option will override some default Windows Command Prompt tools like find and sort. I don't use CMD or Powershell that much to worry about that. So I will go ahead with this option by clicking "Next".

![Adjust Path Environment](/assets/images/posts/2019-08-13-install-git-bash/path-environment.jpg)


### Step 9: Choose HTTPS Transport Backend

Next, select "Use the OpenSSL library" and click "Next".

![choose https transport backend](/assets/images/posts/2019-08-13-install-git-bash/choosing-https-transport.jpg)

### Step 10: Configure the Line Ending Conversions

Select how Git should treat line endings in text files. It's probably safe to go with the default option "Checkout Windows-Style, commit Unix-style line endings". Click "Next" to proceed.

![configure line endings conversions](/assets/images/posts/2019-08-13-install-git-bash/configuring-the-line-endings.jpg)

### Step 11: Configure the Terminal Emulator to use with Git Bsh

Next, select the terminal emulator you want Git Bash to use. I will proceed with the default option "Use MinTTY(the default terminal of MSYS2) and click "Next".

![choose terminal emulator](/assets/images/posts/2019-08-13-install-git-bash/terminal-emulator.jpg)

### Step 12: Configuring Extra Options 

Select the features you want(the default options are fine) and click "Next". 

![enable features](/assets/images/posts/2019-08-13-install-git-bash/extra-options.jpg)

### Step 13: Configuring Extra Options

Enable experimental options if you want. Enabling them allows you to try out newer features that are still in development. I don't enable this, so I will just proceed by clicking "Install" to start the installation process.

![enable experimental options](/assets/images/posts/2019-08-13-install-git-bash/experimental-options.jpg)

### Step 14: Wait for Installation

Now, wait for a few minutes as the Setup Wizard installs Git on your computer.

![Setup wizard](/assets/images/posts/2019-08-13-install-git-bash/installing.jpg)

### Step 15: Complete the Git Setup Wizard

After the installation has finished, check the "Launch Git Bash" and click "Finish" to launch Git Bash.

![finish installation](/assets/images/posts/2019-08-13-install-git-bash/completed-installation.jpg)

The Git Bash terminal will now open and you will be able to enter Git and Bash commands.

![git bash opened](/assets/images/posts/2019-08-13-install-git-bash/git-bash.jpg)

Congratulations on successfully installing Git Bash.

## Launching Git Bash
The following are just some tips on how you can easily launch Git Bash.

**1.** Right-click on any folder, anywhere and it will have the launch Git Bash option on the context menu.

![folder context](/assets/images/posts/2019-08-13-install-git-bash/folder-context.jpg)

**2.** If you enabled the "Additional icons" option on **Step 5**, you can easily launch Git Bash by clicking the Git Bash desktop icon.

![git bash shortcut](/assets/images/posts/2019-08-13-install-git-bash/git-bash-shortcut.jpg)

**3.** If you chose the **third option** "Use Git and optional Unix tools from the Command Prompt" on **Step 8**. You can run both Git and Bash commands by opening Windows Command Prompt or Powershell.

![git bash cmd](/assets/images/posts/2019-08-13-install-git-bash/bash-cmd.jpg)
![git bash cmd](/assets/images/posts/2019-08-13-install-git-bash/powershell-bash.jpg)

`git --version` tells you the Git version currently installed on a system. It is also a confirmation that Git is installed.

`which git` tells you where the Git executable is located. `which` command is part of Unix commands/bash, it is not available on Windows Command Prompt or Powershell by default. 

