# AirBnB Clone [The Console]

![AirBnB Logo](link_to_airbnb_logo) ![Holberton Logo](link_to_holberton_logo)

This project serves as the foundation for building a full web application: the AirBnB clone. It's crucial as it forms the backend for other projects, including HTML/CSS templating, database storage, API, and front-end integration.

## Synopsis

**The Console**

This software functions as a command interpreter akin to a Linux shell, tailored for managing objects within the AirBnB Clone:

- Creating new objects (e.g., a new User or a new Place)
- Retrieving an object from a file, a database, etc.
- Performing operations on objects (count, compute stats, etc.)
- Updating attributes of an object
- Destroying an object

It operates in two modes:

- **Interactive:** The console displays a prompt (hbnb) allowing users to write and execute commands iteratively.
- **Non-interactive:** Commands are piped into the shell's execution, allowing immediate command execution without a prompt.

## Format of Command Input

- **Interactive Mode:** Commands are entered via the keyboard at the prompt, recognized upon pressing the enter key (new line).
- **Non-interactive Mode:** Commands are piped through an echo command.

## Arguments

Most commands accept several options or arguments, separated by spaces.

## Commands

The commands recognized by the interpreter are as follows:

| Command | Description |
| ------- | ----------- |
| quit or EOF | Exits the program |
| help | Provides guidance on using a command |
| create | Creates a new instance of a valid Class, saves it, and prints the ID |
| show | Prints the string representation of an instance based on the class name and ID |
| destroy | Deletes an instance based on the class name and ID |
| all | Prints string representations of all instances based on the class name |
| update | Updates an instance based on the class name and ID by adding or updating attributes |
| count | Retrieves the number of instances of a class |


### Testing

The program runs on Python3, requiring no compilation. To execute the console:

- **Interactive Mode:**
  ```bash
  ./console
  ```
- **Non-interactive Mode:**
  ```bash
  echo "command" | ./console
  ```

## General Use Examples

### Interactive Mode

```bash
./console.py
(hbnb) create BaseModel
49faff9a-6318-451f-87b6-910505c55907
(hbnb) all BaseModel
...
```

### Non-Interactive Mode

```bash
echo "create BaseModel" | ./console.py
(hbnb)
49faff9a-6318-451f-87b6-910505c55907
```

## Built with

- Ubuntu 14.04
- Emacs
- Python3 language

## Authors

- Mariam Ahmed | [Github: mariamsamu ](https://github.com/mariamsamu)
