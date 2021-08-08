# bf2c
An interpreter that converts brainfuck to C

## Usage
**Note: You need to have a Go compiler**

Clone or download this repository
```
$ git clone https://github.com/vs-123/bf2c.git
```
(Unzip if you have downloaded)

Go to the directory
```
$ cd bf2c
```
Compile it and run it
```
$ go build -o bf2c main.go
$ ls
bf2c examples/ main.go README.md
$ cat examples/hello_world.bf
++++++++++[>+++++++>++++++++++>+++>+<<<<-]>++.>+.+++++++..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.>.
$ ./bf2c -f examples/hello_world.bf
$ ls
bf2c examples/ main.go README.md output.c
```
