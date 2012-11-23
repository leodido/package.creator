**A simple shell script that automatically creates the boilerplate for the development of a new R package.**

It creates a new R package following [devtools](https://github.com/hadley/devtools) conventions.

### Usage

1. Download the script (or clone the repository)
3. Type `path/to/package.creator -d path/to/world/domination -n awesomepack`
4. Wait that your computer bootstraps your R package structure in `path/to/world/domination/awesomepack`
5. Do an R awesome package now, you have no more excuses!

##### FYI

You can omit the specification of the installation directory, the default is `$HOME/Workspace/R/Packages`.

### Requirements

To work it requires:
* R installed, clearly
* Rscript installed
* [devtools](https://github.com/hadley/devtools) R package installed

##### FYI

To install Rscript on Ubuntu you can type `sudo apt-get install littler` in the terminal.

