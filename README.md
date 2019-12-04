[![pipeline status](https://api.travis-ci.org/33cn/plugin.svg?branch=master)](https://travis-ci.org/33cn/plugin/)
[![Go Report Card](https://goreportcard.com/badge/github.com/33cn/plugin?branch=master)](https://goreportcard.com/report/github.com/33cn/plugin)


# BitNasdaq chain system based on chain33 blockchain development framework


### 编译

```
git clone https://github.com/bitnasdaqtop/bnchain $GOPATH/src/github.com/bitnasdaqtop/bnchain
cd $GOPATH/src/github.com/bitnasdaqtop/bnchain
go build -i -o bnchain
go build -i -o bnchain-cli github.com/bitnasdaqtop/bnchain/cli
```

### 运行
拷贝编译好的bnchain, bnchain-cli, bn.toml这三个文件置于同一个文件夹下，执行：
```
./bnchain -f bn.toml
```
