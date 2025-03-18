# Helix

[Helix](https://helix-editor.com/) is a post-modern modal editor, cross-platform, built in Rust with minimal configuration needed to start using as a complete code editor.

## Installation

Helix config files for themes are placed in `$XDG_CONFIG_HOME/helix/themes` (which typically expands to `~/.config/helix/themes` on Linux and macOS, or `%AppData%\helix\themes` on Windows).

To install the OneHalf themes for Helix:

1. Create the themes directory if it doesn't exist:
   ```bash
   mkdir -p ~/.config/helix/themes
   ```

2. Copy the theme files to the Helix themes directory:
   ```bash
   cp onehalf_dark.toml onehalf_light.toml ~/.config/helix/themes/
   ```

3. Open Helix editor and issue the `:theme` command
   
4. Search for "onehalf" and select either "onehalf_dark" or "onehalf_light"

## Features

- Complete syntax highlighting for many languages
- Carefully selected colors matching the official OneHalf color scheme
- Special styles for diagnostics, UI elements, and more
- Proper styling for markup (Markdown, etc.)
- Optimized for readability and reduced eye strain

## Screenshots

See the main repository README for screenshots of the OneHalf themes.