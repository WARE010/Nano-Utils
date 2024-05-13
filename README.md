# Nano Utils

Nano Utils is a lightweight Java utility library designed to simplify everyday development tasks. It provides a set of static methods, organized by category, for working with strings, dates, collections, files, and other common operations.

## Features

- Compact: Nano Utils is designed as a lightweight library with minimal dependencies, allowing for fast integration and low overhead.
- Ease of Use: With static methods organized by category, using Nano Utils is intuitive and does not require creating class instances.
- Extensibility: The modular structure of the library makes it easy to add new utility classes and methods as needed.

## Installation

To use Nano Utils in your project, simply download the new version of the library in the .jar extension, then place the library in the libs folder of your project, and specify the necessary dependencies in pom.xml or build.gradle

Or, if you're using Maven or Gradle, add the following dependency to your build file:

<!-- Maven -->
<dependency>
    <groupId>com.npstudio</groupId>
    <artifactId>nano-utils</artifactId>
    <version>1.0.0</version>
</dependency>

// Gradle
implementation 'com.npstudio:nano-utils:1.0.0'

## Usage

After installing the library, you can import the necessary utility classes and start using their methods. For example:

import com.npstudio.nanoutils.StringUtils;

public class Example {
    public static void main(String[] args) {
        String input = "   Hello, World!   ";
        String trimmed = StringUtils.trim(input); // "Hello, World!"
        System.out.println(trimmed);
    }
}

## Documentation

Detailed documentation for all available classes and methods in Nano Utils is under development. For now, check out the library's source code for information on current functionality.

## Contribution

We welcome any contributions to the development of Nano Utils. If you have ideas for improvement or find a bug, please create an appropriate issue or send a pull request.

## License

Nano Utils is licensed under the MIT License. Details can be found in the [LICENSE](LICENSE) file.
