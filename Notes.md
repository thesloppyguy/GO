# **GO Lang**

## **How To Install GO**

## **Commands with Go CLI**

Creates a **go.mod** file for the project

```Shell
    go mod init <name>
```

Runs the go file

```Shell
    go run <name>
```

## **Variables**

1. **Syntax**

```Go
    var <name> <type> =<value>
    Eg:-
        var user string = "sahil"
```

2. **Types**

- String (default empty)
- Bool (default false)
- Int (default 0)

  - unint8
  - unint64
  - int8
  - int64
  - uintptr

- Float (default 0.0)
  - float32
  - float64
- Complex

3. **Advanced Types**

- Array
- Slices
- Maps
- Structs
- Pointers

**Notes**

1. Every data type has a default value.
2. Type can be implicitly defined i.e no need to mention data type.
3. Also there is no need to mention **var** while declarataion.
4. Point 2 and 3 are only applicable inside a method.
