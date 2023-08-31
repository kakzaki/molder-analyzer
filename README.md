# Molder Analyzer README

Welcome to the README for the "Molder Analyzer" extension. This extension provides syntax highlighting and analysis support for `.mold` files, which use a syntax similar to Mustache templates.

## Features

The "Molder Analyzer" extension offers the following features:

- Syntax highlighting for `.mold` files: Your `.mold` files will be visually enhanced with syntax highlighting, making it easier to read and work with Mustache-like templates.

- Syntax Analysis: The extension understands Molder's syntax and can help identify syntax errors in real-time as you type.

## How to Use

1. Install the "Molder Analyzer" extension from the Visual Studio Code Marketplace.
2. Create or open a `.mold` file in your workspace.
3. Enjoy automatic syntax highlighting and real-time syntax analysis as you work with Molder templates.

## Example

Consider the following example of a `.mold` file:

```mold
class Person {
  {{#fields}}
  final {{type}} {{name}};
  {{/fields}}

  Person({{#fields}}this.{{name}}, {{/fields}});
}
```

In this example, the extension would provide syntax highlighting for variables, keywords, and other Molder syntax elements.

## Requirements

There are no specific requirements to use the "Molder Analyzer" extension. Simply install it and start using it with your `.mold` files.

## Extension Settings

The extension currently does not contribute additional settings to Visual Studio Code.

## Known Issues

If you encounter any issues or have feedback, please feel free to report them on the extension's [GitHub repository](https://github.com/kakzaki/molder-analyzer/issues).


**Enjoy enhancing your `.mold` files with Molder Analyzer!**
