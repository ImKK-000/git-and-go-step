# Git Step

## Clone Repository

```bash
git clone <url_repository>

# Example
git clone https://github.com/SCK-SEAL-TEAM-One/datecalculate
```

## Show status git

```bash
git status
```

## Track file to git

```bash
git add <filename>

# Example
git add src/main/main.go
```

## Confirm file from tracking file

```bash
git commit -m "message"

# Example
git commit -m "[Created]: file src/main/main.go"
```

## Integrate code from remote repository to local repository

```bash
git pull <repository_name> <branch_name>

# Example
git pull origin master
```

## When download file from remote repository, **always** run all test

* Unit Test
* Acceptance Test UI Part
* Acceptance Test API Part

## Update code from local repository to remote repository

```bash
git push  <repository_name> <branch_name>

# Example
git push origin master
```
