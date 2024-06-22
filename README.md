### System tools and configs

### Important Commands

- Reflector
	- > reflector --verbose --sort rate -l 50 -p https --save /etc/pacman.d/mirrorlist

- Pacman
	 -pc -Ss `search packages in aur` 
	- pc -Sy `updates repos`
	- pc -R  `rm package`
	- pc -Rs `rm pkg+dependencies`
	- pc -Q  `query pkg`
	- pc -Qdtq `lst orpan pkg`


### Commands

### Packages

- **File Automations**
	
	- `ripgrep`

		- > similar to ctrl+f but in file

- **File Management**
	
	- `exa`

		- >  A ls replacement with more features and customizations
	
	- `autojump`

		- > j for jumps to most popular folders

- **Dev Tools**

	- **Dev_Environment_tools**
		
		- `direnv`

			- > Env var based on dir
