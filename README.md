# Part 1 - Installing VS Code with GitHub Integration

## Installing and Setting Up Visual Studio Code with GitHub on Windows

This guide provides step-by-step instructions on how to install Visual Studio Code (VS Code), integrate it with GitHub, and optionally generate an SSH key for Windows. This setup is ideal for web development and other programming tasks.

### Step 1: Install Visual Studio Code

1. Visit the VS Code download page: [Visual Studio Code Download](https://code.visualstudio.com/download)
2. Click on the Windows download link to download the installer.
3. Run the downloaded `.exe` file and follow the installation prompts to install VS Code on your Windows machine.

### Step 2: Install Git for Windows

To integrate VS Code with GitHub, you need Git installed on your machine.

1. Download Git for Windows from [Git - Download](https://git-scm.com/download/win)
2. Run the downloaded `.exe` file and follow the installation instructions. Make sure to select the option that adds Git to your PATH.

### Step 3: Configure VS Code with Git

1. Open VS Code.
2. Open the Command Palette by pressing `Ctrl+Shift+P`.
3. Type `Git: Clone` and press Enter, then follow the prompts to clone a repository. This step is to ensure Git is integrated correctly with VS Code.

# Part 2 - GitHub Terminology

- **Branch**: A separate line of development. It allows you to diverge from the main line of development and continue to work independently without affecting the main line.

- **Clone**: Making a copy of the repository on your local machine. 

- **Commit**: The process of saving your changes to the local repository. A commit is like a snapshot of your project's current state, which you can return to at any time.

- **Fetch**: A command that downloads content from a remote repository to your local repository. It updates your remote-tracking branches but does not merge the changes into your current working files.

- **GIT**: Git is a distributed version control system used to track changes in source code during software development. It enables multiple developers to work together on a project and tracks every change made to the files.

- **GitHub**: GitHub is a web-based interface that uses Git for version control. It allows users to host and review code, manage projects, and build software alongside millions of developers.

- **Merge**: A way to bring the diverged development history back together. It combines the changes from one branch into another, typically into the main branch.

- **Merge Conflict**: Occurs when Git is unable to automatically resolve differences in code between two commits. It requires manual intervention to resolve the differences.

- **Push**: The act of sending your committed changes to a remote repository, such as GitHub. 

- **Pull**: The process of fetching and downloading content from a remote repository and immediately updating the local repository to match that content. 

- **Remote**: A version of your project that is hosted on the internet or network somewhere. You can have several of them, which can be read-only or read/write for you.

- **Repository**: A directory where Git has been initialized to start tracking and recording changes to the files. It can be local (on your machine) or remote (e.g., on GitHub).