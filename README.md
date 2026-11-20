# Linkz's Gen Studio Beta

This repository is the download for the beta. It does not contain the source code.

## Download

1. Open the [latest release](https://github.com/LinkzVR/Linkzs-Gen-Studio-Beta/releases/latest).
2. Download `LinkzGenStudio.exe`.
3. Double-click it.
4. Enter the 8-digit code you were given. Without a valid code the program does not open. Exit is the only other choice. A valid code lasts 15 days from the moment it is entered. The time left is shown under the title. After 15 days the program asks for a new code.

Microsoft Edge must already be installed. The program opens an Edge window. A display at 1920×1080 or smaller opens maximized. A larger display opens a 1920×1080 window.

No Python install is required. Comfy, Ollama, and model weights are not inside the download. Those stay optional and can be installed from Requirements after you add an API key.

## Your files

Keys, the character library, and logs stay on this PC in:

`%LOCALAPPDATA%\LinkzGenStudio`

Replacing the EXE does not delete that folder.

## Updates

On startup the program reads `latest.json` in this repository. If the published version is newer, it shows the release page. Download the new EXE and run it. Your library stays where it is.

The current beta is **0.6C.4**. Requirements scan the ComfyUI install that is running and name the model files still missing from its models folder. Codes are given out by Linkz. They are not listed in this repository. Generate, Animate, and Prompt Gen stay unavailable until an API key is saved or a local ComfyUI is installed. Get a key explains the API cost before the site opens. The title shows the beta version, and each open checks for a newer download.

## License

Personal testing only. See `LICENSE.txt`. Third-party pieces are listed in `THIRD-PARTY-NOTICES.txt`.
