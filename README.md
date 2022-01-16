# myps
**myps** - bash utility which interacts with proc filesystem and represents information about processes (ps alternative).

## Build
1. Download latest .deb package from [releases](https://github.com/1Lorde/myps/releases).
2. Install by running: `sudo apt-get install ./myps_[version]_all.deb`.

## Usage
### Select options
You can get info about processes, which are:
- executed in current terminal (selection option: `--current-sid`)
- with specified command name (selection option: `--cmd`)
- with specified UID or username (selection option: `--User`)
- assigned with current tty by tty number (selection option: `--current-tty`)
- not deamons by two conditions (selection option: `--no-deamons`)

![select options](https://github.com/1Lorde/myps/blob/master/img/select_options.png?raw=true)

### Format options
Also you can specify output formatting options.
![format options](https://github.com/1Lorde/myps/blob/master/img/format_options.png?raw=true)

## Examples
![examples](https://github.com/1Lorde/myps/blob/master/img/examples.png?raw=true)
