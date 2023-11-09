# Air - Monitor Mode Toggler
Air is a monitor mode shortcut for the Linux Shell environment. This simple bash script allows users to conveniently switch the wireless network adapter to monitor mode and back. It is designed to streamline the process of toggling monitor mode for network analysis and related tasks.

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

- For ZSH shell: 
```cat air.txt >> .zshrc```

- For BASH shell: 
```cat air.txt >> .bashrc```
