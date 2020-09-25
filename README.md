# gop
	a cmd to fast change dir in terminal

# dependency
	python3

# install
	after pull code from github

	1.go to dir {gop_root}/shell, run 
		./worker init

	2.if init succss, run 
		source ~/.bash_aliases

# Functions
	gop add [alias] [absPATH]
		example: 
		gop add b /usr/local/bin

	gop del [alias] 
		example: 
		gop del b 

# Usage
	* after add an alias of a specific path , you can go to this path from whatever path or terminal you currently at by using cmd
		gop [alias]

	* alias rules: 
		1.can't be duplicated  
		2.can't start with a number[0 - 9]

	* delete an alias by gop del func
	
	* check currently added alias by 
		gop or gop -h
