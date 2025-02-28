# GMacQuickActions
A set of custom macOS Quick Actions aimed to simplify the macOS user experience.

# Installation
1. Double-click on the desired Quick Action `.workflow` file.
2. Click on `Install`.
3. macOS might open Setting window. There you can find the new Quick Action and assign a shortcut to it. After that you can safely close the window.

# Usage

## New File
1. Open a folder where you want to create a file.
2. Click on `Finder -> Services -> New File`.

# Build
Choose a Quick Action from `scripts` folder of the repo. Each Quick Action comes with an 
`.applescript` file containing the script itself. If you want to see more details about the 
chosen Quick Action, refer to the `README.md` file nearby.

Once you're ready to build the script, follow the instructions below.

1. Open `Automator` app on macOS.
2. If the app doesn't ask for a type of a new document, click on `File -> New`. Otherwise
go directly to step 3.
3. Select `Quick Action` as a type of the document.
4. Click on `Choose`.
5. Search for `Run AppleScript` item on the left side of the app's main window.
6. Drag `Run AppleScript` item to the workflow window.
7. Delete the code generated automatically.
8. Paste the new code from the chosen `.applescript` file.
9. Click on the build button. This will validate the script. You'll see an error in case of
any issues with the script.
10. Click on `File -> Save`.
11. Enter a name of the new Quick Action. 
12. Click on `Save`.
13. (Optional)
If you want to create an installation `.workflow` file, click on `File -> Export...` and save the file.
