
## Install

```shell script
go get -u github.com/pefish/go-build-tool/cmd/...@v0.0.8
```

## Example

```shell script
go-build-tool -p ./example/... -os all -pack
```

上面命令将生成如下build目录

```shell script
build/
├── bin
│   ├── darwin
│   │   ├── test
│   │   └── test1
│   ├── linux
│   │   ├── test
│   │   └── test1
│   └── windows
│       ├── test.exe
│       └── test1.exe
└── pack
    └── release_all.tar.gz
```
