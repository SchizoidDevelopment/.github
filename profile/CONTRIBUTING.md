# Contributing to Schizoid

Thank you for considering contributing to our projects! Your contributions will help to make
it even better.

### Setting up a Workspace

1. Clone our repository using your preferred IDE or the command line.
2. Open the project in your IDE and ensure that the Gradle project is imported.
3. Run the `:downloadAssets` Gradle task to download the necessary assets.
4. Run the `:genSources` Gradle task to generate the necessary sources.
5. Run the client to ensure that everything is working correctly.
   Use your preferred method:
    - Run the `:runClient` Gradle task to start the client.
    - Run the `Minecraft Client` run configuration in your IDE. (Add the `:fixRunResources` Gradle task before launch.)  
      Add the CI environment variable `CI=true` if necessary.
6. Make your changes and submit a pull request.
7. Ensure that your code is formatted according to the project's code style.

## How to Contribute

There are many ways to contribute to this project, from writing tutorials and implement new features, to fixing bugs
and improving the code.

### Reporting Bugs

If you find a bug, please report it by creating a new issue on the project's GitHub repository. Be sure to include a
clear and concise description of the issue, as well as steps to reproduce it.

### Suggesting Features

If you have a great idea for a new feature, please let us know by creating a new issue on the project's GitHub
repository. Be sure to include a clear and concise description of the feature, and explain why you think it would be
valuable to the project.

### Writing Code

If you are interested in contributing code to the project, here are a few things to keep in mind:

- The code should be well-documented and easy to understand.
- All code should be written in Kotlin (except mixins and shaders), and should be compatible with
  both the Fabric API and Minecraft.
- Before submitting a pull request, make sure that your code has been tested thoroughly and does not cause any issues
  with the existing code.

## Style Guide

When contributing code, please follow the project's coding style and conventions. This includes:

- JetBrains' coding conventions for [Kotlin](https://kotlinlang.org/docs/coding-conventions.html).
- IntelliJ IDEA's default code style for [Java](https://www.jetbrains.com/help/idea/code-style-java.html).
- Oracles's naming conventions for [Java](https://www.oracle.com/java/technologies/javase/codeconventions-namingconventions.html).
- Sight's naming conventions for [GLSL](https://sight.pages.ircad.fr/sight-doc/CodingStyle/src/07-glsl-style.html).

## Code of Conduct

By participating in this project, you agree to follow the project's code of conduct. This includes treating all
contributors with respect and refraining from any form of harassment or discrimination.

## Get in Touch

If you have any questions or need help getting started, please feel free to reach out by creating an issue on the
project's GitHub repository. We would be happy to help!