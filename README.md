# UPX Updater

This small program automates the process of downloading and updating the UPX executable (`upx.exe`) to the latest version from the official UPX website (https://upx.github.io/).

## Purpose

The purpose of this script is to ensure that the `upx.exe` file is up-to-date by checking the official UPX website for the latest version, downloading it if necessary, and replacing the existing `upx.exe` file with the updated version.

## Features

- Retrieves the latest version of `upx.exe` from the official UPX website without downloading the file.
- Downloads the latest version of `upx.exe` from the official UPX website.
- Checks if the existing `upx.exe` file is up-to-date.
- Extracts the `upx.exe` file from the downloaded ZIP archive and updates it.
- Deletes the extracted folder and the downloaded ZIP archive after the update is complete.

## Usage

1. Run the script to check if `upx.exe` is up-to-date.
2. If an update is required, the script will download the latest version of `upx.exe` and replace the existing file.
3. The script will automatically extract the downloaded ZIP archive and update the `upx.exe` file.
4. After the update is complete, the script will clean up by deleting the extracted folder and the ZIP archive.

## Requirements

- Python 3.x
- Requests library (`pip install requests`)
- tqdm library (`pip install tqdm`)

## Note

- The script assumes that `upx.exe` is located in the same directory as the script.
- Make sure you have an active internet connection to download the latest version of `upx.exe`.
- The script uses the regular expression module (`re`) to extract information from the official UPX website.

Feel free to customize and modify the script according to your needs.

