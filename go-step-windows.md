# Go Step (Windows)

## Go to go workspace path
```bash
cd <go_workspace_path>

# Example
cd C:\workspace
```

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

# Example
go install datecalculate
```

## Run unit test with package name
```bash
go test <package_name>

# Example
go test datecalculate
```

## Build go binary file
```bash
go build -o <output_file>.exe <package_name>

# Example
go build -o bin/app.exe main
```

## Launch binary file
```bash
<output_file>.exe

# Example
bin/app.exe
```
