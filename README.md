# `try-until-cli`

A simple Bash script to retry the execution of a command if it fails. Written with the help of AI.

## Features
- Automatically retries a command if it exits with a non-zero status.
- Allows you to specify a custom number of retry attempts.
- Defaults to 5 retry attempts if no value is provided.

## Usage

### Basic Usage

Run a command with up to 5 retry attempts by default:

```bash
$ try-until echo "Hello World"
```

### Custom Number of Retries

Specify the number of retry attempts as the first parameter before the command:

```bash
$ try-until 3 echo "Hello World"
```
