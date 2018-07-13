# Go Step For Windows

## Change directory to go workspace path

```bash
cd <go_workspace_path>

# Example
cd C:\workspace
```

## Set GOPATH

```bash
set GOPATH=%CD%
```

## Check GOPATH via go env

```bash
go env GOPATH
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

## Build main to binary file

```bash
go build -o <output_file>.exe <source_file>

# Example
go build -o bin/main.exe src/main/main.go
```

## Launch binary file

```bash
<output_file>.exe

# Example
bin\main.exe
```
