# SECRET AGENT: TERMINAL ZERO

A self-contained cyberpunk terminal game built as a harmless cybersecurity simulation. Start a mission, run fictional terminal commands, and decode a secret message with a Caesar cipher.

**Student name:** Pari Gothi  
**Student number:** 097

## Project links

- **Live GitHub Pages site:** secret-agent-terminal-zero--parigothi22.replit.app
- **GitHub repository:** https://github.com/Parii22/terminal-zero

Replace the Pages placeholder with the live URL shown in your repository's Pages settings after publishing.

## Features

- Animated Matrix-inspired background and typing introduction.
- Simulated mission launch, progress, and completion feedback.
- Interactive terminal with helpful responses and invalid-command messages.
- Secret cipher challenge using a Caesar cipher.
- Reset controls, keyboard-friendly input, and responsive layout.
- All effects are local and fictional. The app does not connect to computers, networks, or online services.

## How to play

1. Open `index.html` in Chrome, or open the published GitHub Pages link.
2. Select **START MISSION** and follow the on-screen mission.
3. Enter a command in the terminal and press Enter.
4. Try the cipher challenge and decode its secret word.
5. Use **RESET** to start the simulation again.

## Terminal commands

| Command | What it does |
| --- | --- |
| `help` | Lists the available commands. |
| `scan` | Runs a fictional, animated scan simulation. |
| `decrypt` | Starts or advances the simulated decryption/cipher challenge. |
| `status` | Shows the current mission status. |
| `clear` | Clears the terminal output. |

These commands only change what the page displays; they do not perform real cybersecurity actions.

## Secret Features

The cipher challenge is a bonus puzzle: decode the displayed word to complete the secret objective. The mission's simulated progress and completion messages are also part of the game.

## Technologies

- HTML
- CSS
- Vanilla JavaScript

The app is contained in `index.html`; it needs no server, API key, packages, or internet connection.

## GitHub Pages compatibility

The page in the root `index.html` is standalone HTML, CSS, and vanilla JavaScript. It does not load React, Vite, a backend, or external assets at runtime, so it can run from the root of a GitHub Pages repository.

The Replit project also contains React/Vite scaffold files used for the Replit preview. Those files are not needed for GitHub Pages. To publish this version, upload only `index.html`, `README.md`, `DEBUGGING_NOTE.txt`, and `CODE_EXPLANATION.txt` to the root of the existing `Parii22/terminal-zero` repository.

## Assignment activities

- **AI-assisted debugging:** A sample debugging exercise is documented in the source code. Calling `decdoeMessage()` instead of `decodeMessage()` would produce a `ReferenceError` because that misspelled function name is not defined. Correcting the name fixes the call. The submitted app remains working; the deliberate mistake belongs only in a temporary copy.
- **Code analogy:** `decodeMessage(message, shift)` moves letters around a circular alphabet to encode or decode a message.
- **Unit tests:** Three `console.assert()` checks run when the page loads. They cover an ordinary cipher input, an empty string, and a negative shift.

## Preview and test

Open `index.html` directly in Chrome. Try all five commands, launch and reset a mission, and solve the cipher challenge. Open Chrome DevTools → **Console** to see the three cipher assertions; passing assertions do not print an error. No server is required.

## Publish with GitHub Pages

1. Save or download these four files: `index.html`, `README.md`, `DEBUGGING_NOTE.txt`, and `CODE_EXPLANATION.txt`.
2. Open your existing repository: https://github.com/Parii22/terminal-zero
3. Upload the four files to the repository's top level (the root), replacing the older copies if prompted.
4. Open the repository's **Settings** → **Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, then save.
6. After GitHub Pages finishes publishing, open the URL shown in the Pages settings. The expected project URL is `https://Parii22.github.io/terminal-zero/`.
7. Edit `README.md` in the existing repository and replace the Pages placeholder with the live URL GitHub shows.

If GitHub displays a publishing status, wait for it to finish and refresh the Pages settings to find the live link.
