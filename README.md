# CubeSAT-GRC

## macOS 
### Install Homebrew
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
### Install Python3
`brew install python`
### Install Pip
Homebrew installs `pip` pointing to the Homebrew’d Python 3 for you
### Install GNURadio
`brew install gnuradio`
### Running GNURadio for the first time
In terminal `open .zshrc`

Append this line `alias grc="gnuradio-companion"`

Save and close file

Restart terminal `grc`
### Run Volk_Profile
`volk_profile`
