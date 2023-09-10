# bare-server-brainfuck
[Bare server implementation](https://github.com/TompHTTP/specifications) written in brainfuck using the [systemf interpreter](https://github.com/ajyoon/systemf).

With systemf, you're able to make linux syscalls with the `%` operator, making a bare server implementation possible. I have provided a pre-compiled systemf binary so you do not have to build it yourself.

# Starting
1. Clone this repo
2. Run `./systemf bare_server.bf` in the cloned repo directory
3. The bare server should be started

# Building
If you want to build the systemf interpreter, you need to have NASM and make installed. 

[Clone this repo](https://github.com/ajyoon/systemf) and run `make build`.
