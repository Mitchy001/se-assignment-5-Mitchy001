[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15271961&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5

Installation and Navigation of Visual Studio Code (VS Code) Instructions: Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.
Questions:
Installation of VS Code:



1.Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
Installation of VS Code
Steps to Download and Install Visual Studio Code on Windows 11:
1.	Download:
o	Go to the Visual Studio Code website.
o	Click on the "Download for Windows" button.
2.	Install:
o	Run the downloaded setup file (VSCodeSetup.exe).
o	Follow the installation wizard:
	Accept the license agreement.
	Choose the installation location.
	Select additional tasks such as creating a desktop icon, adding "Open with Code" action to Windows Explorer file context menu, and registering the code as an editor for supported file types.
	Click "Install".



2.First-time Setup:
•	After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

First-time Setup
Initial Configurations and Settings:
1.	Theme:
o	Open VS Code.
o	Go to File > Preferences > Color Theme (or use Ctrl+K Ctrl+T).
o	Choose a preferred theme.
2.	Extensions:
o	Open the Extensions view by clicking the Extensions icon on the Activity Bar or using Ctrl+Shift+X.
o	Recommended extensions:
	Prettier: Code formatter.
	ESLint: JavaScript linter.
	Live Server: Launch a development local Server with live reload.
	Bracket Pair Colorizer: Colorize matching brackets.
	Debugger for Chrome: Debug JavaScript code in the Google Chrome browser.
3.	Settings Sync:
o	Go to File > Preferences > Settings Sync.
o	Sign in with your GitHub or Microsoft account to sync settings across devices.
4.	Other Settings:
o	Go to File > Preferences > Settings (or use Ctrl+,).
o	Adjust settings such as Font Size, Tab Size, Auto Save, etc.
 
![image](https://github.com/Mitchy001/se-assignment-5-Mitchy001/assets/140062227/6108b9c7-d89b-4603-97d5-a9b5a7ce3b12)

3. User Interface Overview:
Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
User Interface Overview
Main Components of the VS Code User Interface:
1.	Activity Bar:
o	Located on the left side.
o	Provides access to views such as Explorer, Search, Source Control, Run and Debug, and Extensions.
2.	Side Bar:
o	Displays different views like the Explorer view, Source Control view, etc.
o	Helps in navigating and managing files and folders.
3.	Editor Group:
o	The main area where you edit your files.
o	Supports multiple editors side by side.
4.	Status Bar:
o	Located at the bottom.
o	Provides information about the current project, such as the current Git branch, line, and column numbers, and language mode.
 ![image](https://github.com/Mitchy001/se-assignment-5-Mitchy001/assets/140062227/e088a64a-3a31-4117-8ded-526657ee8dbe)

4.Command Palette:

What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
Command Palette
Command Palette:
•	Accessed via Ctrl+Shift+P or F1.
•	Provides a quick way to execute commands.
•	Examples of common tasks:
o	Open a file: Ctrl+P.
o	Open settings: Preferences: Open Settings.
o	Install extensions: Extensions: Install Extensions.
 ![image](https://github.com/Mitchy001/se-assignment-5-Mitchy001/assets/140062227/b83c7141-b650-4902-88e1-d7d3210edf1b)



5.Extensions in VS Code:
Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
Extensions in VS Code
Role of Extensions:
•	Extend the functionality of VS Code.
•	Users can find, install, and manage extensions via the Extensions view (Ctrl+Shift+X).
•	Examples of essential extensions for web development:
o	Prettier: For code formatting.
o	ESLint: For identifying and fixing JavaScript issues.
o	Live Server: For real-time feedback on changes in the browser.
o	Debugger for Chrome: For debugging JavaScript code in Chrome.
 ![image](https://github.com/Mitchy001/se-assignment-5-Mitchy001/assets/140062227/55e298de-2304-4588-bfa9-a08dad491c5c)



6.Integrated Terminal:
Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
Integrated Terminal
Opening and Using the Integrated Terminal:
•	Open via View > Terminal or using `Ctrl+``.
•	Advantages:
o	Directly execute commands without leaving the editor.
o	Supports multiple terminals.
o	Integrates with tasks and debugging.
7.File and Folder Management:
Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
File and Folder Management
Managing Files and Folders:
1.	Creating:
o	Right-click in the Explorer view and select "New File" or "New Folder".
o	Use Ctrl+N for a new file.
2.	Opening:
o	Use File > Open Folder or Ctrl+K Ctrl+O.
3.	Navigating:
o	Quick Open: Ctrl+P to quickly open files.
o	Use breadcrumbs for easy navigation at the top of the editor.
 ![image](https://github.com/Mitchy001/se-assignment-5-Mitchy001/assets/140062227/b13d1215-bca4-4c3c-9590-2dcc6967f2a4)



8.Settings and Preferences:
Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
Settings and Preferences
Customizing Settings:
•	Go to File > Preferences > Settings (or Ctrl+,).
•	Examples:
o	Change Theme: Type "color theme" in the settings search bar and select your desired theme.
o	Change Font Size: Adjust "Editor: Font Size".
o	Change Keybindings: Go to File > Preferences > Keyboard Shortcuts or Ctrl+K Ctrl+S.
9.Debugging in VS Code:
Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
Debugging in VS Code
Setting up and Starting Debugging:
1.	Open a project and ensure you have a launch configuration file (launch.json).
2.	Go to Run > Start Debugging or use F5.
3.	Set breakpoints by clicking on the margin next to the line numbers.
4.	Key features:
o	Watch: Monitor variable values.
o	Call Stack: View the call stack of your program.
o	Variables: Inspect variables in the current scope.
 ![image](https://github.com/Mitchy001/se-assignment-5-Mitchy001/assets/140062227/2533ab6e-8da8-41c4-b32f-8a4f6f084d5c)

10.Using Source Control:
How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
Using Source Control
Integrating Git with VS Code:
1.	Initialize a repository:
o	Open a folder in VS Code.
o	Open the Source Control view by clicking the Source Control icon in the Activity Bar.
o	Click "Initialize Repository".
2.	Making Commits:
o	Stage changes by clicking the + icon next to files.
o	Enter a commit message and click the checkmark icon to commit.
3.	Pushing Changes to GitHub:
o	Open the Source Control view.
o	Click the "..." menu and select "Push".
 
![image](https://github.com/Mitchy001/se-assignment-5-Mitchy001/assets/140062227/e90636c8-e61d-43aa-85ec-cc88ef496615)


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

