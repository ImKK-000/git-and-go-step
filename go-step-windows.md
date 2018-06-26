# Go Step (Windows)

## Set path
```bash
set GOPATH=%CD%
```

## Set path in Cygwin like Mac and Linux
```bash
export GOPATH=$(pwd)
```

## Install package with package name to pkg
```bash
go install <package_name>
```

## Run unit test with package name
```bash
go test <package_name>
```

## Build go binary file
```bash
go build -o <output_file>.exe <package_name>
```

## Launch binary file
```bash
<output_file>.exe
```
