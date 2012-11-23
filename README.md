## package-creator


Simple shell script that creates the boilerplate for the development of a new **R** package.

It creates a new R package following [devtools](https://github.com/hadley/devtools) conventions.

### Requirements

To work it requires:
* Rscript
&nbsp;&nbsp;&nbsp;&nbsp;To install on ubuntu you can type `sudo apt-get install littler` in the terminal.
* [devtools](https://github.com/hadley/devtools) package installed

### Usage

* Download the script (or clone the repository)
* Create a symbolic link to it (if you want)
* Type `package-creator -d path/to/world/domination -n awesomepack`
* Do an R awesome package now, you have no more excuses!

FYI: you can omit the specification of the installation directory, the default is `$HOME/Workspace/R/Packages`.


