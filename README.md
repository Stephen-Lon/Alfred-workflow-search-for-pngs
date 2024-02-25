# Alfred-workflow-search-for-pngs
Search for PNGs (using Alfred 5.5 and later)

# Introduction

The workflow searches for PNG files in a folder within Alfred's default search scope. You select the folder and the workflow displays the PNG files from that folder in a grid. You can then view within Alfred's Image View a selected PNG file.

# Usage

Type the workflow keyword (the default is `fpg`—for "Find PNG"—but you can change it in the configuration). You will be prompted to choose a folder in which to search. Press <kbd><space></kbd> and start typing the name of the folder in which you wish to search. Press <kbd>⏎</kbd> when the relevant folder name is displayed (or select the relevant folder if more than one is displayed) and you will see a grid of the PNG files in that folder with the full name of and path to the selected image displayed at the bottom.

In that view you can do a number of things:
- Move through the thumnails using the arrow keys.
- Search for images in the grid by typing in the search box at the top of the window.
- Click on an image, or press <kbd>⏎</kbd> on a highlighted image, to view only that image in Alfred's Image View. If you wish you can then press <kbd>esc</kbd> in Image View to return to the grid view.
- Press <kbd>⌘</kbd><kbd>O</kbd> (“O” for “open”) to open a highlighted image in your default PNG viewer or editor.
- Use commands common to both Grid View and Image View (see below).
- Press <kbd>esc</kbd> to end the workflow.

# Image View

Image View displays a single selected image from the grid view when you press <kbd>⏎</kbd> or click on an image in the grid view.

In Image View you can do the following:
- Press <kbd>esc</kbd> to take you back to grid view.
- Press <kbd>⏎</kbd> or <kbd>⌘</kbd><kbd>O</kbd> (“O” for “open”) to open the image in your default PNG viewer or editor.
- Use commands common to both Grid View and Image View (see below).
- Press <kbd>⌘</kbd><kbd>esc</kbd> to end the workflow.

# Commands common to both Grid View and Image View
- Press <kbd>⌘</kbd><kbd>0</kbd> (command zero) to toggle the size of the window.
- With a selected image hold down either <kbd>⌘</kbd> or <kbd>⌥</kbd> and press <kbd>⏎</kbd>—the former to allow you to action the selected image in Alfred and the latter to reveal the selected image in Finder.
