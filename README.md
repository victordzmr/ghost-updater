# Ghost updater
Bash script that performs a secure update of an existing Ghost installation to the latest version.

## License
This software is distributed under the MIT license. Please read LICENSE for information on the software availability and distribution.

## Installation
This bash script only requires execution permissions.

## Usage
```
sh ghost-updater [, directory_name]
```

* `directory_name` is the relative or absolute path to the directory in which Ghost is installed. Default: `./ghost`.

## Example
```
sh ghost-updater /home/victor/ghost
```

In this case, the script will update an existing Ghost installation in the directory `/home/victor/ghost` to the latest version.