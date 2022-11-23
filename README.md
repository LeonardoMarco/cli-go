
# CLI-GO

This repository is about a simple GO CLI using the COBRA library.

Commands

#### Help:

command for CLI support

```
go run main.go --help
go run main.go -h
go run main.go help
```

#### inspect:

Command to check number of characters

Command accepts "d" flag to change command line response

```
go run main.go inspect {arg}
go run main.go insp {arg} //alias
go run main.go inspect {arg} --d //using command with flag
```

#### reverse:

Command to return reversed words

```
go run main.go reverse
go run main.go rev //alias
```

---

### Build project

if you build the project, instead of running main.go you can use ./cligo {COMMAND}


```
go build
```
Example
```
./cligo inspect {arg} --d
```


