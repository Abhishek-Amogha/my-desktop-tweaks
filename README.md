# my-tweaks

This repository contains my personal configuration tweaks for Vim, Bash, Firefox, etc. It includes custom `.vimrc` and `.inputrc` files that enhance my workflow and provide a more efficient editing experience.

## `.vimrc`

The `.vimrc` file contains my Vim editor customizations. It includes a number of settings related to line numbering, tab spaces, search behavior, key mappings, and other editor tweaks to improve productivity.

### Key Features

- **Line Numbers**: Line numbers are enabled for easy navigation and reference.
- **Cursorline and Cursorcolumn**: Highlights the line and column under the cursor to easily locate your position.
- **Indentation**: Set to use 4 spaces for indentation and automatically expands tabs to spaces.
- **Clipboard**: The ability to copy to the system clipboard using the `Ctrl+C` key.
- **Python Integration**: Bind the F5 key to save, clear the screen, and run Python scripts from within Vim.
- **Window Switching**: Easily switch between split windows in vimdiff using `Alt+Right-Arrow`.
- **Mouse Support**: Configured to disable mouse selection for line numbers.

### How to Use
3. **Install `.vimrc`**:
    Copy the `.vimrc` file from this repository to your home directory:
    ```bash
    cp my-desktop-tweaks/.vimrc ~/.vimrc
    ```

3. **Install `.inputrc`**:
    Copy the `.inputrc` file to your home directory:
    ```bash
    cp my-desktop-tweaks/.inputrc ~/.inputrc
    ```

4. **Reload the configuration**:
    For Vim:
    ```bash
    vim
    ```
    For Bash:
    ```bash
    source ~/.bashrc
    ```

## `.inputrc`

The `.inputrc` file contains key bindings to improve the command line experience. These settings specifically target the behavior of the **Bash shell** to improve text editing and navigation.

### Key Features

- **Ctrl+Delete**: Delete the next word.
- **Ctrl+Backspace**: Delete the previous word.

---

Feel free to fork or make your own adjustments based on these configurations!
