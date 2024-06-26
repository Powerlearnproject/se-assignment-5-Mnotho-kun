# Visual Studio Code (VS Code) Installation and Navigation Guide

## Installation of VS Code

### Steps to Download and Install Visual Studio Code on Windows 11

1. **Download VS Code:**
   - Visit the [official Visual Studio Code website](https://code.visualstudio.com/).
   - Click on the "Download for Windows" button.
   - The site will automatically detect your OS and provide the appropriate download link.
   - ![1--Official-Page](https://github.com/Mnotho-kun/Assigment-5/assets/168840740/616d0887-a9ac-4ec9-bb2f-43f83ffe5e59)

2. **Install VS Code:**
   - Run the downloaded installer (usually `VSCodeUserSetup-x64-<version>.exe`).
   - ![3--Open-File](https://github.com/Mnotho-kun/Assigment-5/assets/168840740/de9f04f7-7a79-4b4a-9a72-6f03cfdb6634)
   - Follow the installation wizard steps:
     - Accept the license agreement.
     - Choose the installation location.
     - Select additional tasks (e.g., create a desktop icon, add to PATH, register code as an editor for supported file types).
   - Click “Install” and wait for the process to complete.
   - Once installed, you can choose to launch Visual Studio Code immediately.
   - ![4--Accept-License](https://github.com/Mnotho-kun/Assigment-5/assets/168840740/214abd28-5a20-47cd-b76f-b85770de22d5)
   - ![5--Click-Next](https://github.com/Mnotho-kun/Assigment-5/assets/168840740/f0751356-47de-4053-8c03-f245730d6fab)
   - ![6--Click-Install](https://github.com/Mnotho-kun/Assigment-5/assets/168840740/0900e50f-7706-4bad-82b8-b9f1af90944f)
   - ![8--Finish](https://github.com/Mnotho-kun/Assigment-5/assets/168840740/3ddaff5f-932d-47b2-9d25-76d8e80b021f)


### Prerequisites
- Windows 11 operating system.
- Administrator privileges to install software.
- Optionally, a Git client installed if you plan to use source control features.

## First-time Setup

### Initial Configurations and Settings

1. **Settings Sync:**
   - Go to `File > Preferences > Settings` or press `Ctrl+,`.
   - Search for "Settings Sync" and sign in with your Microsoft or GitHub account to sync settings across devices.
   - ![turn-on-sync](https://github.com/Mnotho-kun/Assigment-5/assets/168840740/985fcf5c-7f90-4462-b5b3-05b64f27dd2f)

2. **Theme and Appearance:**
   - Open the Command Palette (`Ctrl+Shift+P`) and type `Color Theme`.
   - Choose a preferred theme from the available options.
   - ![themes_hero](https://github.com/Mnotho-kun/Assigment-5/assets/168840740/86b9bd45-2972-4a8c-922b-bee72332b65c)

3. **Extensions:**
   - Install essential extensions:
     - **Python:** For Python development.
     - **ESLint:** For JavaScript linting.
     - **Prettier - Code Formatter:** For code formatting.
     - **Live Server:** To launch a development local server with live reload.
     - **GitLens:** Supercharges the Git capabilities built into Visual Studio Code.
     - ![extensions-view-icon](https://github.com/Mnotho-kun/Assigment-5/assets/168840740/27cab81c-1526-463d-bace-a4dfb4b897e4)
     - ![extensions-popular](https://github.com/Mnotho-kun/Assigment-5/assets/168840740/fd7e02cf-6330-46bc-943f-56d975b5865b)


4. **Editor Settings:**
   - Configure settings for a better coding experience:
     - Auto-save files: `File > Auto Save`.
     - Adjust font size: `Ctrl+,` then search for "Font Size".
     - Enable format on save: Search for "Format On Save" in settings.

## User Interface Overview

### Main Components of the VS Code User Interface

1. **Activity Bar:**
   - Located on the far left.
   - Provides access to different views such as Explorer, Search, Source Control, Run and Debug, and Extensions.

2. **Side Bar:**
   - Located next to the Activity Bar.
   - Displays the content of the selected activity, such as a list of files in the Explorer or search results.

3. **Editor Group:**
   - Central area where files are opened and edited.
   - Supports multiple tabs and split views for side-by-side file editing.

4. **Status Bar:**
   - Located at the bottom of the window.
   - Displays information about the open file, such as encoding, line ending, language mode, and git branch.
  
   - ![Editor bar](https://github.com/Mnotho-kun/Assigment-5/assets/168840740/f5ab9e09-e7b7-4669-8e12-f5652fe11d0e)

## Command Palette

### Command Palette in VS Code

- Accessed by pressing `Ctrl+Shift+P` or `F1`.
- Provides a quick way to execute commands.
- Examples of common tasks:
  - **Opening Settings:** Type `Preferences: Open Settings`.
  - **Changing Theme:** Type `Color Theme` and select a theme.
  - **Running a Build Task:** Type `Tasks: Run Build Task`.

## Extensions in VS Code

### Role of Extensions

- Extend the functionality of VS Code.
- Provide language support, themes, debuggers, and tools.
  
### Finding, Installing, and Managing Extensions

1. **Finding and Installing:**
   - Go to the Extensions view by clicking the Extensions icon in the Activity Bar or press `Ctrl+Shift+X`.
   - Search for extensions using keywords.
   - Click "Install" on the desired extension.

2. **Managing Extensions:**
   - View installed extensions in the Extensions view.
   - Disable or uninstall extensions by clicking the gear icon next to the extension.

### Essential Extensions for Web Development

- **HTML CSS Support:** Provides CSS class name completion for the HTML class attribute.
- **JavaScript (ES6) code snippets:** Adds snippets for JavaScript development.
- **Path Intellisense:** Autocompletes filenames.

## Integrated Terminal

### Opening and Using the Integrated Terminal

1. **Open Terminal:**
   - Use `Ctrl+` (backtick) or go to `View > Terminal`.

2. **Using Terminal:**
   - Supports multiple terminal instances.
   - Execute commands directly within the editor.

### Advantages
- No need to switch between editor and terminal.
- Directly navigate and operate within the project directory.

## File and Folder Management

### Creating, Opening, and Managing Files and Folders

1. **Creating Files/Folders:**
   - Right-click in the Explorer view and select "New File" or "New Folder".
   - Use the `Ctrl+N` shortcut to create a new file.

2. **Opening Files/Folders:**
   - Drag and drop files/folders into the editor.
   - Use `File > Open File` or `File > Open Folder`.

3. **Managing Files/Folders:**
   - Use the Explorer to move, rename, and delete files/folders.
   - Use the breadcrumbs navigation at the top of the editor for easy navigation.

## Settings and Preferences

### Customizing Settings in VS Code

1. **Accessing Settings:**
   - Go to `File > Preferences > Settings` or press `Ctrl+,`.

2. **Changing Theme:**
   - Search for `Color Theme` in settings and select a theme.

3. **Adjusting Font Size:**
   - Search for `Font Size` and set the desired size.

4. **Customizing Keybindings:**
   - Go to `File > Preferences > Keyboard Shortcuts` or press `Ctrl+K Ctrl+S`.
   - Modify existing shortcuts or add new ones.

## Debugging in VS Code

### Setting Up and Starting Debugging

1. **Open Debug View:**
   - Click on the Debug icon in the Activity Bar or press `Ctrl+Shift+D`.

2. **Configure Debugger:**
   - Create a launch configuration by clicking on the gear icon and selecting the appropriate environment.

3. **Set Breakpoints:**
   - Click in the gutter next to the line numbers in the editor.

4. **Start Debugging:**
   - Press `F5` to start debugging.

### Key Debugging Features
- Breakpoints, step through code, watch variables, and view call stack.

- ![debugging_hero](https://github.com/Mnotho-kun/Assigment-5/assets/168840740/1a150851-e046-449c-9b01-3eaa39184047)

## Using Source Control

### Integrating Git with VS Code

1. **Initialize Repository:**
   - Open the Source Control view by clicking the Source Control icon in the Activity Bar.
   - Click "Initialize Repository".
  
   - Watch a demo on YouTube: [Link to Demo](https://youtu.be/i_23KUAEtUM)

2. **Making Commits:**
   - Stage changes by clicking the `+` icon next to files.
   - Enter a commit message and click the checkmark to commit.
  
   - Watch a demo on YouTube: [Link to Demo](https://youtu.be/E6ADS2k8oNQ)

3. **Pushing to GitHub:**
   - Use the Command Palette (`Ctrl+Shift+P`) and type `Push` to push commits to the remote repository.

By following these instructions, users can efficiently install, set up, and navigate Visual Studio Code, enhancing their coding environment and productivity.

## References

1. **Settings Sync:**
   - [Visual Studio Code Documentation](https://code.visualstudio.com/docs/editor/settings-sync)

2. **Theme and Appearance:**
   - [Visual Studio Code Documentation](https://code.visualstudio.com/docs/getstarted/themes)

3. **Extensions:**
   - [Visual Studio Code Marketplace](https://marketplace.visualstudio.com)

4. **Editor Settings:**
   - [Visual Studio Code Documentation](https://code.visualstudio.com/docs/getstarted/settings)

5. **Activity Bar:**
   - [Visual Studio Code Documentation](https://code.visualstudio.com/docs/getstarted/userinterface#_activity-bar)

6. **Side Bar:**
   - [Visual Studio Code Documentation](https://code.visualstudio.com/docs/getstarted/userinterface#_side-bar)

7. **Editor Group:**
   - [Visual Studio Code Documentation](https://code.visualstudio.com/docs/getstarted/userinterface#_editor-group)

8. **Status Bar:**
   - [Visual Studio Code Documentation](https://code.visualstudio.com/docs/getstarted/userinterface#_status-bar)
  

7. **Initialize Repository:**
    - [Visual Studio Code Documentation](https://code.visualstudio.com/docs/editor/versioncontrol)

8. **Make Commits:**
    - [Visual Studio Code Documentation](https://code.visualstudio.com/docs/editor/versioncontrol)

