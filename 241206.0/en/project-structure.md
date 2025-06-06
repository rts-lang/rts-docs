## Project Structure

The structure of any project consists of:

* package.json file: Stores metadata about your project, as well as the libraries used as dependencies;
* package-lock.json file: Stores the exact versions of libraries in use in your project's working state;
* .rt project files: Contains the core files for your project written in RTS;
* Other project files.

To create a new project, you can use the built-in RTS Package Manager with the following commands:

* `./rts package local`
* `./rts package local <package name>`

For more detailed information about the commands, you can use:

* `./rts package help`