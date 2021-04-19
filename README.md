# Renaming Files Based on Creation Date

This script renames files in the current directory and subdirectories based on their creation date.

## How it works

1. The script uses the `exiftool` command-line utility to access file metadata.
2. It sets the filename to the creation date, using a specific format.
3. It also updates the file modification date to match the creation date.

## Features

- Renames files with various extensions (heic, mov, mp4, 3gp, jpeg, jpg, png, bmp).
- Supports large files.
- Uses UTC time for QuickTime files.
- Recursively processes files in subdirectories.

## To use the script

1. Save the script as `media-organize`.
2. Make the script executable: `chmod +x media-organize`.
3. Run the script in the directory containing your files: `./media-organize`.

**Note:** Make sure you have `exiftool` installed on your system.
