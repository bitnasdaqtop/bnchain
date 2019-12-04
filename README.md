[![pipeline status](https://api.travis-ci.org/33cn/plugin.svg?branch=master)](https://travis-ci.org/33cn/plugin/)
[![Go Report Card](https://goreportcard.com/badge/github.com/33cn/plugin?branch=master)](https://goreportcard.com/report/github.com/33cn/plugin)


# BitNasdaq chain system based on chain33 blockchain development framework


### Compile

```
git clone https://github.com/bitnasdaqtop/bnchain $GOPATH/src/github.com/bitnasdaqtop/bnchain
cd $GOPATH/src/github.com/bitnasdaqtop/bnchain
go build -i -o bnchain
go build -i -o bnchain-cli github.com/bitnasdaqtop/bnchain/cli
```

### Function
Copy the three compiled files bnchain, bnchain-cli, bn.toml and put them in the same folder. Execute:
```
./bnchain -f bn.toml
```
