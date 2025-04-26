# Blog Duds Dev

Hello! I’m Eduardo. To open the project on your machine and use it, follow the steps below. :smiley:

If you already have GIT installed, go directly to the **Second Step**. If you don’t, follow this tutorial from here.

## First Step: How to Install GIT

1. **Download and install Git** from the official website (64-bit): [https://www.git-scm.com/downloads](https://www.git-scm.com/downloads)

2. **Command to check if Git is installed and its version**:
   Open the CMD terminal and type:
   git --version
Configuration
Configure GitHub username and email in Git:

`git config --global user.name "your-github-username"`
`git config --global user.email your-email@type.com`

3. Initialize a folder with Git (creates a hidden folder with Git configuration commands). Note: Place this folder inside the project folder.


`cd path-to-your-folder-on-computer`
`git init`

4. How to clone a GitHub repository to your computer: Right-click inside the folder (Git Bash) and type in the terminal:

`git clone (GitHub-repository-link)`

5. Check for new files or changes to existing files:

`git status`

6. How to Make a Commit (Package for Sending): Add files to be included in the commit:

`git add ./path.extension` (specific file)
`git add .` (to prepare all repository files for committing/sending)

NOTE:
For every code change, you need to add the file again to prepare for sending (commit). Always remember to use -m after the commit command to leave a message and better identify that commit.

7. Command to Send the Files:

`git push origin main`

The origin main specifies which branch the files will be sent to on the remote GitHub server. In this case, it’s the main branch. If you haven’t created any other branches, this will be the only one, and all pushes will go to it.

## Second Step: Opening the Project on Your Computer :sunglasses:

### For Windows:

1. Open the Windows PowerShell by right-clicking and selecting "Run as administrator".

2. Create a folder in a desired location to house the project, then click the folder's path at the top of the screen to copy it.

3. Return to PowerShell, type the cd command, and right-click to paste the folder path. The prompt will look like this:

`cd path-to-your-project\project-folder`
Press Enter.

You’re now in the desired folder via PowerShell. Let’s clone the project using Git.

4. Go to the project repository on GitHub, click the green "<> Code" button, and in the window that opens, click the copy button next to the link or select and copy the entire link.

5. Return to PowerShell and type:

`git clone copied-repository-link.git`
Press Enter.

6. At this point, you can open the project files with your preferred code editor. To start the Hugo server and view the site in your browser, you’ll need to type these Hugo commands in PowerShell.

7. In PowerShell, navigate to the project’s root folder and type:

`hugo server -D`
Press Enter. A list of items in the project will appear, indicating that the Hugo server is now active.

8. Open your preferred browser and enter in the search bar: localhost:1313, then press Enter. Done! You’ve successfully opened and run the project in your browser.

### For Mac

1. Open the Terminal:

On macOS, you generally don’t need admin permissions for basic Terminal commands.

2. Use Spotlight Search (Cmd + Space), type "Terminal," and press Enter.

3. Create a folder in Finder: Navigate to the desired location in Finder, right-click in an empty space, and select New Folder. Name the folder, for example, my-project.

4. Copy the folder path:

5. Right-click the folder, select Get Info, and copy the full path under Where.
Alternatively, drag and drop the folder into the Terminal to paste its path automatically.

6. Access the folder in Terminal: Open the Terminal and type:

`cd /path-to-your-project/project-folder`
Press Enter.

7. Clone the GitHub repository: Go to the project repository on GitHub, click the green "<> Code" button, and copy the repository link.

8. Return to the Terminal and type:

`git clone copied-repository-link.git`
Press Enter.

9. Open the project files in your preferred code editor. To start the Hugo server and view the site in your browser, run the following commands in the Terminal.

10. Start the Hugo server: In the project’s root folder, type:

`hugo server -D`
Press Enter. A list of project items will appear, indicating that the Hugo server is now active.

11. Open the site in your browser: Open your preferred browser and enter: localhost:1313, then press Enter. Done! You’ve successfully opened and run the project in your browser.

If you have any questions, feel free to contact me: :mailbox:

**contato.eduardo96@gmail.com**

See you soon! :hand:

