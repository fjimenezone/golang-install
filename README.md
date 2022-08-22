# golang-install
Download version 1.19 for Linux

`curl -LO https://go.dev/dl/go1.19.linux-amd64.tar.gz`

Run as root

`sudo rm -rf /usr/local/go`

`sudo tar xzf go1.19.linux-amd64.tar.gz -C /usr/local`

Run as the user to use the tools

`export PATH=$PATH:/usr/local/go/bin`

Test

`which go`

`go version`

Make the golang location permanent

`echo 'export PATH=$PATH:/usr/local/go/bin' > ~/.bash_profile`

