# Mac Environment

## Installation

=> Setup proxy if any

=> Install `node` and `npm` or `nvm` and `XCode devtools`

=> Setup keys (Git Repos)

=> Download `VSC` and `Hyper.js` and `Docker`

=> install `eslint` into VSC

=> install `homebrew` and get yourself some cool tools `wget`, `graphviz`...

=> `VIM` time

=> dotfiles `https://github.com/jessfraz/.vim`

=> Put `marco.vim` file in your `~/.vim/colors/` directory and add the following line to your `~/.vimrc`:

    syntax enable
    colorscheme marco

# Windows Environment

=> Setup proxy if any

=> Install `node` and `npm` or `nvm`

=> Setup keys (Git service)

=> Download `VSC` and `Hyper.js` and `Docker`

=> Install WSL (latest version)

=> setup Hyper to be used with the ubuntu terminal

    Setup Hyper.js to automatically open Ubuntu on Windows
    Open up Hyper.js configuration again and type Ctrl + ,
    Scroll down to shell and change it to C:\\Windows\\System32\\bash.exe
    
    // the shell to run when spawning a new session (i.e. /usr/local/bin/fish)
    // if left empty, your system's login shell will be used by default
    //
    // Windows
    // - Make sure to use a full path if the binary name doesn't work
    // - Remove `--login` in shellArgs
    //
    // Bash on Windows
    // - Example: `C:\\Windows\\System32\\bash.exe`
    //
    // PowerShell on Windows
    // - Example: `C:\\WINDOWS\\System32\\WindowsPowerShell\\v1.0\\powershell.exe`
    shell: 'C:\\Windows\\System32\\bash.exe'

=> Install colors like above
