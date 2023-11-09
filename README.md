# air - Monitor Mode Toggler Shortcut
air is a simple bash script that allows users to conveniently toggle the wireless network adapter to monitor mode and back.

## Requirements

- A Linux-based operating system. I recommend Kali Linux.
- airmon-ng
- net-tools
- grep

## Installation

- Download files:
```wget https://raw.githubusercontent.com/afridi7/air/main/air.txt```

- Check Shell environment:
```echo $SHELL```

***
⚠️WARNING‼️ :- Make a backup of ```.zshrc``` OR ```.bashrc``` file before proceeding any further.
***

- For ZSH shell:
```cat air.txt >> .zshrc```

- For BASH shell:
```cat air.txt >> .bashrc```

***
- Once Installation is done, restart the terminal.
***

## Usage

```air [interface] [Option] ```

## Options

on  - Puts interface in monitor mode.\
off - Puts interface in managed mode.\
-h, --help  - shows options
