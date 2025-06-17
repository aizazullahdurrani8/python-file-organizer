# Python File Organizer

A simple Python script that organizes files in a specified directory into folders based on their file extensions.

## Features
- Automatically creates folders for each file extension (e.g., `pdf_files`, `jpg_files`).
- Moves files into their respective folders for better organization.
- Easy to use with a simple command-line interface.

## Requirements
- Python 3 installed on your system.

## Usage
1. Clone or download this repository.
2. Run the script using Python:

```bash
python file_organizer.py
```
3. When prompted, enter the full path of the directory you want to organize.
4. The script will create folders and move files accordingly.

## Example
If your folder contains files:

```
report.pdf
photo.jpg
notes.txt
```
After running the script, the folder structure will be:
```
pdf_files/report.pdf
jpg_files/photo.jpg
txt_files/notes.txt
```

## Notes
* Make sure to back up your files or test on a sample folder before running on important data.
* This script only organizes files in the specified directory, not subdirectories.