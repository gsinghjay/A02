# Part 1 - Installing VS Code with GitHub Integration

This guide assumes you have pre-created all repositories for the assignments on GitHub to clone over to your machine whether they are empty or not.

## Installing and Setting Up Visual Studio Code with GitHub on Windows

This guide provides step-by-step instructions on how to install Visual Studio Code (VS Code), integrate it with GitHub, and optionally generate an SSH key for Windows. This setup is ideal for web development and other programming tasks.

### Step 1: Install Visual Studio Code

1. Visit the VS Code download page: [Visual Studio Code Download](https://code.visualstudio.com/download)
2. Click on the Windows download link to download the installer.
3. Run the downloaded `.exe` file and follow the installation prompts to install VS Code on your Windows machine.

### Step 2: Install Git for Windows

1. Download Git for Windows from [Git - Download](https://git-scm.com/download/win).
2. Execute the downloaded `.exe` file and follow the installation instructions. Ensure you choose the option to add Git to your PATH to integrate seamlessly with VS Code.

### Step 3: Access the Source Control Panel

1. Press `Ctrl + Shift + G` to open the Source Control panel.

### Step 4: Clone the Repository

1. At the top of the Source Control panel, find and click the "Clone Repository" button.
2. VS Code will prompt you to enter the URL of the repository you want to clone.
3. Skip entering a URL and select Clone from GitHub.
4. VS Code will prompt you that "The extension 'GitHub' wants to sign in using GitHub." Click allow.
5. Link your GitHub account with VS Code.
6. Now you are able to clone and commit to your repositories.

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