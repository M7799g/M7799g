### Windows 

Download and run the installer found at http://golang.org/doc/install

### macOS

Download an install the darwin binary from https://golang.org/dl/

You can also install Go using the Homebrew package manager.

### Linux

#### Ubuntu

The Ubuntu repositories carry an old version of Go.

See https://github.com/golang/go/wiki/Ubuntu for more information on how to install an up-to-date version of Go.

#### Other distros

For other distros, please refer to the respective page at https://github.com/golang/go/wiki#platform-specific-information on how to install an up-to-date version of Go.

#### Set GOPATH and PATH

For Go to work properly, you need to set the following two environment variables:

- Setup a go folder `mkdir -p ~/go; echo "export GOPATH=$HOME/go" >> ~/.bashrc` 
- Update your path `echo "export PATH=$PATH:$HOME/go/bin:/usr/local/go/bin" >> ~/.bashrc`
- Read the environment variables into current session: `source ~/.bashrc`