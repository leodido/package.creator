**A simple shell script that automatically creates the boilerplate for the development of a new R package.**

It creates a new R package following [devtools](https://github.com/hadley/devtools) conventions.

### Usage

1. Download the script (or clone the repository)
2. Create a symbolic link to it (if you want)
3. Type `package-creator -d path/to/world/domination -n awesomepack`
4. Do an R awesome package now, you have no more excuses!

##### FYI

You can omit the specification of the installation directory, the default is `$HOME/Workspace/R/Packages`.

### Requirements

To work it requires:
* Rscript

&nbsp;&nbsp;&nbsp;&nbsp;To install on ubuntu you can type `sudo apt-get install littler` in the terminal.
* [devtools](https://github.com/hadley/devtools) R package installed
* R installed, clearly