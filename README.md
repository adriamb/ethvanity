# genaddress
Generate an ethereum address that starts with some prefix

### installation

You need to install golang 1.8, first, check https://golang.org/

Just drop into the command line:

`go get github.com/adriamb/genaddres`

### execution

`~/go/bin/genaddress <maxparallel> <prefix>`

It will find an account that starts with a prefix (hexdecimal lowercase),
using the specified threads (gorutines), e.g.

`~/go/bin/genaddress 5 ab1a`

Will output a private key with an account that starts with 0xab1a
