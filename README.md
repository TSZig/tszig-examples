# tszig-examples

Example projects, tutorials, and learning resources for TSZig.

## Overview

This repository contains example code demonstrating TSZig features, from basic syntax to real-world applications.

## Structure

```
tszig-examples/
├── basics/                 # Fundamental concepts
│   ├── hello-world/       # Getting started
│   ├── variables/         # Variable declarations
│   ├── functions/         # Function definitions
│   └── loops/             # Control flow
│
├── es6-features/          # ES6+ syntax support
│   ├── arrow-functions/   # Arrow function syntax
│   ├── template-literals/ # String interpolation
│   ├── destructuring/     # Object/array destructuring
│   ├── default-params/    # Default parameters
│   ├── rest-spread/       # Rest/spread operators
│   └── for-of/            # For...of loops
│
├── memory-safety/         # TSZig memory features
│   ├── auto-defer/        # Automatic cleanup
│   ├── resource-cleanup/  # Resource management
│   └── file-handling/     # Safe file operations
│
├── c-style/               # C-style extensions
│   ├── printf/            # Printf formatting
│   ├── operators/         # Compound operators
│   └── ternary/           # Ternary expressions
│
└── real-world/            # Complete applications
    ├── cli-tool/          # Command-line tool
    ├── file-processor/    # File processing utility
    └── json-parser/       # JSON handling
```

## Quick Start

### Clone and Explore

```bash
git clone https://github.com/TSZig/tszig-examples
cd tszig-examples/basics/hello-world
```

### Run an Example

```bash
# Transpile
tszig transpile main.ts

# Compile
zig build-exe output.zig -o main

# Run
./main
```

## Example Categories

### 🔰 Basics

Learn fundamental TSZig concepts:

- **hello-world**: Your first TSZig program
- **variables**: `const`, `let`, type annotations
- **functions**: Function declarations, parameters, returns
- **loops**: `for`, `while`, `for...of` loops

### 🚀 ES6 Features

Modern JavaScript syntax:

- **arrow-functions**: `const add = (a, b) => a + b`
- **template-literals**: `` `Hello, ${name}!` ``
- **destructuring**: `const { x, y } = point`
- **default-params**: `function greet(name = "World")`
- **rest-spread**: `function sum(...nums)`, `[...arr]`
- **for-of**: `for (const item of array)`

### 🛡️ Memory Safety

TSZig's automatic memory management:

- **auto-defer**: Automatic resource cleanup
- **resource-cleanup**: Managing file handles
- **file-handling**: Safe file operations

### 🔧 C-Style Extensions

C-style programming features:

- **printf**: Format specifiers (`%s`, `%d`, `%f`)
- **operators**: `+=`, `-=`, `++`, `--`
- **ternary**: `condition ? true : false`

### 🌍 Real-World

Complete applications:

- **cli-tool**: Building command-line tools
- **file-processor**: Processing files safely
- **json-parser**: Working with JSON data

## Contributing Examples

We welcome new examples! Please follow these guidelines:

1. Create a new directory under the appropriate category
2. Include a `main.ts` with working code
3. Add a `README.md` explaining the example
4. Ensure the example compiles and runs without errors
5. Follow the [contributing guidelines](https://github.com/TSZig/.github/blob/main/CONTRIBUTING.md)

## License

MIT License - see [LICENSE](LICENSE) for details.
