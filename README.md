# Nemo_Scripts
Scripts for nemo file manager.

# Execution
- When executed from a local folder, scripts will be passed the selected file names. When executed from a remote folder (e.g. a folder showing web or ftp content), scripts will be passed no parameters.

# Environment Variables Set By Nemo
- In all cases, the following environment variables will be set by Nemo, which the scripts may use:

- NEMO_SCRIPT_SELECTED_FILE_PATHS: newline-delimited paths for selected files (only if local)
- NEMO_SCRIPT_SELECTED_URIS: newline-delimited URIs for selected files
- NEMO_SCRIPT_CURRENT_URI: URI for current location
- NEMO_SCRIPT_WINDOW_GEOMETRY: position and size of current window
- NEMO_SCRIPT_NEXT_PANE_SELECTED_FILE_PATHS: newline-delimited paths for selected files in the inactive pane of a split-view window (only if local)
- NEMO_SCRIPT_NEXT_PANE_SELECTED_URIS: newline-delimited URIs for selected files in the inactive pane of a split-view window
- NEMO_SCRIPT_NEXT_PANE_CURRENT_URI: URI for current location in the inactive pane of a split-view window


# Installation
- Place these scripts within your NEMO_HOME directory, which is often found at ~/.local/share/nemo/scripts.
- Make them executable
  - `cd ~/.local/share/nemo/scripts`
  - `git clone https://github.com/mr-phil1/nemo_scripts`
  - `chmod a+x -R ~/.local/share/nemo/scripts/*`
- All executable files in this folder will appear in the Nemo Scripts menu. 
- Choosing a script from the menu will run that script.

# To-Do
 - [ ] Write functional for Ubuntu Budgie
