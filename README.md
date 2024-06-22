# SE-Assignment-5

# Installation and Navigation of Visual Studio Code (VS Code)

## Instructions:

## Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

## Questions:

### 1. Installation of VS Code:

#### - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

**Step 1:** Visit the [Official Website](https://code.visualstudio.com/docs/?dv=win) of the Visual Studio Code using any web browser like Google Chrome, Microsoft Edge, etc.

**Step 2:** Press the “Download for Windows” button on the website to start the download of the Visual Studio Code Application.

**Step 3:** When the download finishes, then the Visual Studio Code Icon appears in the downloads folder.

**Step 4:** Click on the Installer icon to start the installation process of the Visual Studio Code.

**Step 5:** After the Installer opens, it will ask you to accept the terms and conditions of the Visual Studio Code. Click on I accept the agreement and then click the Next button.

**Step 6:** Choose the location data for running the Visual Studio Code. It will then ask you to browse the location. Then click on the Next button.

**Step 7:** Then it will ask to begin the installation setup. Click on the Install button.

**Step 8:** After clicking on Install, it will take about 1 minute to install the Visual Studio Code on your device.

**Step 9:** After the Installation setup for Visual Studio Code is finished, it will show a window like this below. Tick the “Launch Visual Studio Code” checkbox and then click Next.

**Step 10:** After the previous step, the Visual Studio Code window opens successfully. Now you can create a new file in the Visual Studio Code window and choose a language of yours to begin your programming journey!

### 2. First-time Setup:

#### - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

After the installation of VS code, select an appropriate theme that suits your taste. Search for the extension bar and install languages such as - C++, C#, Go, Java, Python, then install git. Others will be installed as the project proceeds.

### 3. User Interface Overview:

#### - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

VS Code adopts a common user interface and layout of an explorer on the left, showing all of the files and folders you have access to, and an editor on the right, showing the content of the files you have opened.

1. Editor - The main area to edit your files. You can open as many editors as you like side by side vertically and horizontally.

2. Side Bar - Contains different views like the Explorer to assist you while working on your project.

3. Status Bar - Information about the opened project and the files you edit.

4. Activity Bar - Located on the far left-hand side. Lets you switch between views and gives you additional context-specific indicators, like the number of outgoing changes when Git is enabled. You can change the position of the Activity Bar.

### 4. Command Palette:

#### - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

The Command Palette is where all Commands are found. It's important that your command names are labeled appropriately so users can easily find them. The VS Code Command Palette can be accessed in windows using Ctrl+Shift+P

**Here are some examples of common tasks you can perform using the Command Palette:**

- File management:

  - Create new files and folders
  - Open existing files and folders
  - Rename files and folders
  - Save files

- Code editing:

  - Find and replace text
  - Go to specific lines or symbols
  - Toggle features like word wrap or indentation

- Code execution and debugging:

  - Run code snippets or entire programs
  - Set breakpoints and step through code line by line
  - Debug errors and exceptions

- Refactoring:

  - Rename variables and functions throughout your code
  - Extract code into functions or classes
  - Organize code using features like indent or comment

- Version control:

  - Commit changes to your code repository
  - View the history of changes
  - Checkout different versions of your code

* Extensions:

  - Install and manage extensions that add new features to your development environment
  - Run commands specific to extensions you've installed

### 5. Extensions in VS Code:

#### - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

VS Code extensions let you add languages, debuggers, and tools to your installation to support your development workflow. VS Code's rich extensibility model lets extension authors plug directly into the VS Code UI and contribute functionality through the same APIs used by VS Code.

**How to find, install, and manage extensions**

You can browse and install extensions from within VS Code. Bring up the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of VS Code or the View: Extensions command (Ctrl+Shift+X). This will show you a list of the most popular VS Code extensions on the VS Code Marketplace.

**Examples of essential extensions for web development.**

- Formatting and Linting:

  - Prettier: This extension automatically formats your code according to a consistent style guide, improving readability and collaboration.
  - ESLint: ESLint helps catch errors and potential issues in your JavaScript code as you write, ensuring better code quality.

- Development Workflow:

  - Live Server: Live Server lets you launch a local development server right from VS Code, allowing you to see your changes reflected in a web browser instantly.
  - GitLens: GitLens supercharges Git functionality within VS Code, providing rich visualizations and easier navigation through your code history.

- Language Support:

  - HTML CSS Support: This extension enhances HTML and CSS editing with features like code completion, linting, and emmet support for faster code writing.
  - JavaScript (ES6) code snippets: Get quick access to commonly used JavaScript code snippets to save time and effort.

- Bonus Extensions:

  - Web Dev: This extension combines several popular web development extensions like Live Server, ESLint, and code snippets into a single package for a convenient setup.
  - Debugger for Chrome: Debug your JavaScript code directly within Chrome from VS Code, making it easier to identify and fix bugs.

### 6. Integrated Terminal:

#### - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

There are several ways to open the integrated terminal:

- Keyboard Shortcut: The most common way is using the keyboard shortcut. Press Ctrl + (backtick key) on Windows and Linux. For macOS, use Cmd + instead.
- Menu: Go to the Terminal menu and select New Terminal. Alternatively, you can use the View > Terminal menu option.
- Command Palette: Open the Command Palette (Ctrl + Shift + P) and type "View: Toggle Integrated Terminal" and press Enter.

**Advantages of using the integrated terminal compared to an external terminal**

- Convenience: The biggest advantage is convenience. With an integrated terminal, you can switch between your code and the terminal output instantly without having to minimize or maximize windows. This can be a huge time saver, especially if you're constantly running commands and checking their output.

- Integration with the editor: Many integrated terminals offer features that tie directly into the editor. For example, you might be able to click on a path in the editor and have it automatically opened in the terminal, or you might see errors from your code reflected directly in the terminal output.

- Context awareness: Some integrated terminals can be aware of the current working directory or project you're working on in the editor. This can be helpful because it means you won't have to manually navigate to the correct directory every time you want to run a command.

- Simplified workflow: Especially for beginners, having everything in one window can streamline the workflow and reduce the feeling of being overwhelmed by multiple windows.

### 7. File and Folder Management:

#### - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

**Creating and Opening Files and Folders in VS Code**

VS Code offers several ways to create, open, and manage files and folders within your project. Here's a breakdown of the methods:

- Opening a Folder (Workspace):

  - File Explorer: Navigate to your desired folder in your operating system's file explorer. Drag and drop the folder onto the VS Code window.
  - Menu Bar: Go to the "File" menu and select "Open Folder" (or "Open Workspace" on some versions). Choose the folder you want to open in the file selection dialog.

- Creating a New File:

  - Explorer View: In the left-hand sidebar (Explorer view), right-click on the folder where you want the new file. Select "New File" from the context menu. Enter a name for your file and press Enter.
  - Menu Bar: Go to the "File" menu and select "New File." A new untitled file will open in the editor window. Give it a name when saving.
  - Keyboard Shortcut: Use the keyboard shortcut for "New File" (Cmd + N on macOS, Ctrl + N on Windows/Linux). This is a quick way to create a new file within the current folder.

- Opening an Existing File:

  - Explorer View: In the Explorer view, double-click on the file you want to open. It will load in the editor window.
  - Keyboard Shortcut: Use the "Go to File" function (Cmd + P on macOS, Ctrl + P on Windows/Linux). Start typing the filename, and VS Code will suggest matching files as you type. Select the desired file and press Enter to open it.

- Managing Files and Folders
  VS Code's Explorer view lets you manage your project's files and folders:

  - Renaming: Right-click on a file or folder and select "Rename" from the context menu. Edit the name and press Enter.
  - Deleting: Right-click on a file or folder and select "Delete." VS Code will prompt you for confirmation before deleting.
  - Moving and Copying: Use drag-and-drop functionality to move or copy files and folders within the Explorer view. Hold Ctrl (Windows/Linux) or Cmd (macOS) while dragging to copy.
  - Context Menu: Right-clicking on a file or folder provides various options depending on the file type. You can cut, copy, paste, or perform other actions specific to the file.

### 8. Settings and Preferences:

#### - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

There are two main ways to find and customize settings in VS Code:

- Using the Settings Editor: This is the recommended way for most users. You can access the Settings editor by going to File > Preferences > Settings (or use the keyboard shortcut Ctrl+,). The Settings editor provides a user-friendly interface to search, browse, and modify various VS Code settings.

- Editing the settings.json file: The settings are also stored in JSON files. These files can be useful for more advanced configuration or managing settings with version control. The location of the settings.json file depends on the type of settings:

- User settings: These affect all workspaces and are located at the following paths depending on your operating system:

Windows: %APPDATA%\Code\User\settings.json
macOS: $HOME/Library/Application Support/Code/User/settings.json
Linux: $HOME/.config/Code/User/settings.json

Workspace settings: These apply only to the current workspace and are located in a .vscode folder within your workspace root directory. The file name is also settings.json.

**Changing Themes**

Windows 10/11:

- Click Start and go to Settings.
- Select "Personalization".
- Under "Themes", choose a pre-installed theme or click "Get more themes in the Microsoft Store" to download new ones.

Mac:

- Open System Preferences.
- Click "General".
- Select the desired theme under "Appearance".

**Changing Font Size:**

Windows 10/11:

- Open Settings and navigate to "Ease of Access".
- Click "Display".
- Use the slider under "Make text bigger" to adjust font size.

Mac:

- Open System Preferences.
- Click "Displays".
- Adjust the "Resolution" slider to indirectly change font size (higher resolution leads to smaller text).

Alternatively, some applications allow internal font size adjustments within their settings.

**Changing Keybindings:**

Windows 10/11:

Unfortunately, Windows doesn't offer a built-in way to change system-wide keybindings. However, some applications allow customization within their settings. Additionally, third-party software can be used to manage keyboard shortcuts.

Mac:

- Open System Preferences.
- Click "Keyboard".
- Select the tab related to the functionality you want to change shortcuts for (e.g., "Shortcuts", "Mission Control").
- Click the desired action and press the new key combination you want to use.

### 9. Debugging in VS Code:

#### - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

**Here's a breakdown of setting up and debugging a simple program in VS Code:**

- Create your program:

  - Open VS Code and create a new file with the appropriate extension for your programming language (e.g., .py for Python, .js for Javascript).
  - Write your simple program code in this file.

- (Optional) Configure Launch Settings:

  - While not always necessary for basic debugging, launch configurations allow you to customize how VS Code runs and debugs your program. You can find the launch settings by clicking the gear icon in the Run and Debug view (left sidebar).
  - Explore creating a launch configuration for your specific programming language if you want more control over the debugging process.

- Set Breakpoints:

  - Breakpoints are lines of code where you want the program to pause during execution. Click next to the line of code where you want to pause in the editor. A red dot will appear indicating a breakpoint.

- Start Debugging:

* There are two ways to initiate debugging:

  - Press F5 on your keyboard.
  - Click the green "Run and Debug" button in the top left corner of VS Code.

* Debug your Program:

Once the program hits a breakpoint, it will pause execution.
The Run and Debug view will show various debugging options:

- Step Over (F10): Executes the current line and moves to the next line.
- Step Into (F11): Steps into function calls, pausing at the beginning of the called function.
- Step Out (Shift+F11): Steps out of the current function, continuing execution until the function finishes.
- Continue (F5): Resumes program execution until the next breakpoint or program termination.

* Inspect Variables:

  - The Variables pane in the Run and Debug view allows you to inspect the values of variables at any point during debugging. This helps you understand the program's state and identify potential issues.

### 10. Using Source Control:

#### - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

VS Code already has built-in support for Git, so you don't need any additional downloads to integrate them. Here's a quick guide on how to get started:

1. Check for Git installation:

   - VS Code will prompt you to install Git if it's not already on your system. You can also check by running git --version in the terminal.

2. Initialize a new repository (or open an existing one):

   - For a new project, open the folder in VS Code and use the "Source Control" tab (View > Source Control or Ctrl+Shift+G) to find the "Initialize Repository" button. This creates a new Git repository in your folder.
   - To open an existing Git repository, just open the folder containing the .git folder in VS Code. VS Code will automatically recognize it as a Git repository.

3. Managing your code:

   - VS Code's Source Control view will show you the status of your files (modified, staged, etc.).
   - You can use the buttons or right-click menus to stage changes, commit them with a message, and view the history of commits.
   - VS Code also offers features like branching, merging, and conflict resolution within the IDE.

**Initializing a Repository, Making Commits, and Pushing to GitHub**

Here's a breakdown of the process:

1. Initialize a Local Repository:

   - Open your terminal or command prompt and navigate to your project directory using the cd command.
   - Run the command git init in the terminal. This creates a hidden folder called .git and initializes the version control system for your project.

2. Create a Remote Repository on GitHub (optional):

   - Log in to your GitHub account and go to the "New repository" section.
   - Give your repository a name and description (optional) and choose Public or Private visibility.
   - This creates an empty repository on GitHub that will hold your code.

3. Making Commits:

   - Make changes to your project files (code, documents, etc.).
   - Run the command git add <filename> to stage specific files for your commit, or git add . to stage all changes in the current directory.
   - Run the command git commit -m "Your commit message". This creates a snapshot of the staged changes with your descriptive message.

4. Pushing Changes to GitHub:

(Assuming you created a remote repository in step 2)

- Run the command git remote add origin <remote repository URL>. This creates a connection (remote) between your local repository and the one on GitHub. You can find the URL on your GitHub repository homepage under "Clone or download".
- Run the command git push -u origin <branch name>. This pushes your local commits to the specified branch (usually main) on the remote repository. You'll be prompted to enter your GitHub credentials for authentication (only the first time).

## REFERENCES

https://www.geeksforgeeks.org/how-to-install-visual-studio-code-on-windows/

https://code.visualstudio.com/docs/getstarted/userinterface#:~:text=At%20its%20heart%2C%20Visual%20Studio,the%20files%20you%20have%20opened.

https://code.visualstudio.com/api/ux-guidelines/command-palette#:~:text=The%20Command%20Palette%20is%20where,Use%20clear%20names%20for%20commands

https://code.visualstudio.com/docs/editor/extension-marketplace#:~:text=VS%20Code%20extensions%20let%20you,APIs%20used%20by%20VS%20Code.

https://code.visualstudio.com/docs/editor/extension-marketplace#:~:text=You%20can%20browse%20and%20install,on%20the%20VS%20Code%20Marketplace.

https://code.visualstudio.com/docs/getstarted/settings

https://www.atlassian.com/git/tutorials
