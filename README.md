# devfile-registry-arm

A repository of devfiles that use arm32v7 arch docker images

## regenerate index.json

```
cd tools
go run cmd/index/index.go -devfiles-dir ../devfiles -index ../devfiles/index.json
```
