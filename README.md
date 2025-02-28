# GMacQuickActions
A set of custom macOS Quick Actions aimed to simplify the macOS user experience.

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

# Usage
To use a script follow the instructions near the script file.


