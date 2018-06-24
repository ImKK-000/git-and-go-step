# Go Step

## Set Path ใน Windows
```bash
setx GOPATH %CD%
```

## Set Path ใน Mac/Linux
```bash
export GOPATH=$(pwd)
```

## รัน Unit Test ของ package
```bash
go test <package_name>
```

## Build Go Binary File
```bash
go build -o <output_file>.exe <package_name>
```

## Run Binary File
```bash
<output_file>.exe
```