# bf2rs

An interpreter that converts Brainfuck code to Rust.

## Usage

- Go to the [releases](https://github.com/vs-123/bf2rs/releases) of this repository and download one based on your OS.
- Unpack the downloaded file.
- Add the executable called `bf2rs` to your PATH variable.
- Write a Brainfuck file.
- Open terminal at the place where you wrote the Brainfuck file.
- Then use the command `bf2rs <file>` where `<file>` should be replaced with your Brainfuck file.
- After that, it should generate a `.rs` (Rust) file, which you can compile, modify, do whatever you wish.

Example usage:

```
$ # In the folder after unpacking the file downloaded from `releases`
$ # Created a file called `my_file.bf`
$ ls
bf2rs my_file.bf
$ cat my_file.bf
++++++++++[>+++++++>++++++++++>+++>+<<<<-]>++.>+.+++++++..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.>.
$ bf2rs my_file.bf
Success!
Output file: my_file.rs
$ ls
bf2rs my_file.bf my_file.rs
```
