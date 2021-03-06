# Visual Studio Code Updater
This is a simple script to automate downloading, installing and restarting vscode.

## Usage
```bash
    git clone https://github.com/moeenz/vscode-updater
    cd vscode-updater
    ./update.sh
```

For easier future usages simply put this in your .bashrc or .bash_profile file:
```
    alias update-vscode="bash /path/to/vscode-updater/update.sh"
```
Now you can run ```update-vscode``` easily from anywhere in terminal.

## Update the script
```bash
    cd vscode-updater
    git pull
```

# Note
This script will kill all vscode processes before installing latest version, so you're responsible for saving your work before running this script.


# License
The MIT License (MIT)

Copyright (c) 2018 vscode-updater Project.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
