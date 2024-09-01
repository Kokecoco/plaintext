# plaintext - A Minimalistic and Humorous Programming Language

**plaintext** is a minimalistic and humorous programming language designed to do nothing more than output the contents of a `.txt` file. If you're looking for a programming language that takes simplicity to the extreme, you've come to the right place!

## Features

- Just one command: `cat`
- Supports `.txt` files as the primary (and only) source file format
- Lightweight and easy to use
- Perfect for beginners, trolls, and everyone in between!

## Installation

### Ubuntu

1. Clone the repository and navigate to the project directory:

   ```bash
   git clone https://github.com/your-username/plaintext.git
   cd plaintext
   ```

2. Run the installation script:

   ```bash
   sudo ./scripts/install.sh
   ```

3. Verify the installation:
   ```bash
   plaintext --version
   ```

## Usage

To run a `plaintext` program, simply pass a `.txt` file as an argument:

```bash
plaintext my_program.txt
```

Example:

```bash
plaintext examples/hello_world.txt
```

This will output the contents of the `hello_world.txt` file.

## Example Code

### Hello World

Create a file called `hello_world.txt` with the following content:

```plaintext
Hello, World!
```

Then, run it using `plaintext`:

```bash
plaintext hello_world.txt
```

### FizzBuzz (in plaintext style)

Create a file called `fizzbuzz.txt` with some humorous take on FizzBuzz:

```plaintext
Fizz
Buzz
FizzBuzz
```

Run it:

```bash
plaintext fizzbuzz.txt
```

## Standard Library

plaintext comes with a minimal standard library (`stdlib.txt`) that provides some simple functionality. However, keep in mind that this is a humorous and minimalist language, so don't expect too much!

## Contributing

Feel free to fork this project, submit issues, or even contribute your own humorous additions! All contributions are welcome, no matter how absurd.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Version

Current version: 1.0.0 (Released: 2024-09-01)