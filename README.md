# bf2c
An interpreter that converts brainfuck to C

## Installation

**Note: You need to have a Go compiler**

### From Source

Clone this repository
```
$ git clone https://github.com/vs-123/bf2c.git
```
or [download the source](https://codeload.github.com/vs-123/bf2c/zip/refs/heads/main) and unzip it

Go to the directory
```
$ cd bf2c
```
Compile it
```
$ go build
```

### With go

For go version 1.16 or lower:
```
$ go get -u github.com/vs-123/bf2c
```

For go version 1.17 or higher:
```
$ go install github.com/vs-123/bf2c@latest
```

## Usage
```
$ ls
bf2c examples/ main.go README.md
$ cat examples/hello_world.bf
++++++++++[>+++++++>++++++++++>+++>+<<<<-]>++.>+.+++++++..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.>.
$ ./bf2c -f examples/hello_world.bf
$ ls
bf2c examples/ main.go README.md output.c
```
