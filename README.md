# pacpeek

Pacpeek is a small CLI tool, that is completely unnecessary, its just way cooler than 'pacman -Qi'.

It's compatible on every OS, ye i'm not joking, try it out!

## Installation

### AUR
```bash
yay -S pacpeek
```
(or your preferred AUR helper — paru, etc.)

### From source (GitHub)
```bash
git clone https://github.com/RustyWaffle/pacpeek
cd pacpeek
cargo build --release
sudo cp target/release/pacpeek /usr/local/bin/
```
## Usage

```
$ pacpeek firefox
```

## Why?

Well, its actually way quicker than 'pacman -Qi', pacpeek finishes in 0.002 sec, crazy right?

