# Xyz Bulk Rename

An extension for Visual Studio Code to quickly bulk-rename files and folders.

## Installation

1. Open Visual Studio Code
2. Press `Ctrl+Shift+X` (Windows/Linux) or `Cmd+Shift+X` (macOS) to open the Extensions view
3. Search for `Xyz Bulk Rename`
4. Click Install

## Disclaimer

Bulk-renaming files can break your project if you're not careful. Be sure to try this extension with a dummy project before you use it with an important project. Always save your project before bulk-renaming files or folders in case you break something or th extension behaves in an unexpected way.

## Usage

1. Open a a workspace in Visual Studio Code
2. Save your project.
3. Right-click in the Explorer view
4. Select "[Xyz Bulk Rename] Start" from the context menu
5. A file named ".BULK_RENAME.txt" will be created in the root of the workspace
6. Open ".BULK_RENAME.txt", and rename the files or folders as needed (Tip: Press `Ctrl+F` (Windows/Linux) or `Cmd+F` (macOS) to search for the files or folders if there are too many)
7. Save the file (Tip: Enable auto-save in Visual Studio Code)
8. The files and folders will be renamed accordingly and ".BULK_RENAME.txt" will update
9. Files or folders staring with a dot "." will be ignored

## Known Issues

- Currently no folders or files are ignored, except files of folders starting with a dot ".". So if you have a "node_modules" folder for example, all those files and folders will appear in "BULK_RENAME.txt". For now, press `Ctrl+F` (Windows/Linux) or `Cmd+F` (macOS) to search for the files or folders if there are too many.
- There is currently no way to stop the process once started, unless you close and reopen Visual Studio Code. Luckily it's not really disruptive.

## Author

Robert Mollentze
## GitHub

https://github.com/robmllze/xyz_bulk_rename

## License

This extension is licensed under the [MIT License](LICENSE).
