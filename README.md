# tfile

```
 _______  _______  ___   ___      _______ 
|       ||       ||   | |   |    |       |
|_     _||    ___||   | |   |    |    ___|
  |   |  |   |___ |   | |   |    |   |___ 
  |   |  |    ___||   | |   |___ |    ___|
  |   |  |   |    |   | |       ||   |___ 
  |___|  |___|    |___| |_______||_______|
```

TFile - is a Terraform-based tool that allows anyone to target all resources in a specific file

## Installation

To install the tool, move it to executable path:

```bash
chmod +x tfile

mv tfile /usr/bin/tfile
```

## Usage

```
Syntax:

    tfile [-options] apply|plan|destroy path_to_file

options:

    -h | --help       Print this help.
    -v | --verbose    Terraform verbose mode.
```

## License

[License](./LICENSE)