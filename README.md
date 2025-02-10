=======
# A format for making a CLI
Decription for Making a CLI
---


## Requirements:
* Git
* Python 3.6+

## Usage

### To Install:
  Run `make install` to install from local repository

  Run the following to install from GitHub: `pip3 install git+https://github.com/FOO/REPO@main` to install

### To read the Help:
  Run the following for help: `--help` at any level to see help: 
  Examples: `ENTRY_POINT --help` or `ENTRY_POINT list --help`

### To Use:
  Run the following: `ENTRY_POINT` and the actions you want to perform:


```
Usage: ENTRY_POINT [OPTIONS] COMMAND [ARGS]...

  Main function for CLI

Options:
  --help              Show this message and exit.

Commands:
  help  ENTRY_POINT [--help ] # If configured help account
```
### Werner Notes
  Search for FOO and REPO and change, also look at setup.py, and fill in new values.
