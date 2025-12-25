# NoteTaker – Background Notes Taker (MVP)

A tiny always-on-top text box to jot quick notes into a selected file while you work in other apps.

## Features
- Always on top: window stays above other apps for quick access.
- Quick append: press Ctrl+Enter to append content to your chosen file.
- Dark UI: dark frame and text area for low-glare note taking.
- Safe exit on cancel: if no file is selected no changes happen.

## Requirements
- Python 3.8+ (tkinter is included with standard Python on Windows/macOS).

## Setup & Run via Raw Code
```bash
cd 03_CompletedProjects/NoteTaker
python BackgroundNotesTaker.py
```

On launch, you’ll be prompted to select a file. Notes will be appended to that file.

## Usage
- Select your file using the button on boot. The selection is successful when the title changes to the file name.
- Type your notes in the text box as you would, the window stays on top even if you click off of it.
- Press Ctrl+Enter to append the note to the selected file and clear the box.

## Output Format
- Notes are appended with a blank line after each entry for readability.

## Notes & Tips
- You can close the app by simply cancelling it.
- Use a plain text file (e.g., .txt) for best results.
- Some full-screen exclusive apps may still cover all windows; borderless/windowed modes work best for always-on-top helpers.

## File Reference
- Main script: `BackgroundNotesTaker.py`
