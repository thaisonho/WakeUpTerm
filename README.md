# WakeUpTerm

A python script that prints ascii art whenever you open the terminal

## Description

This Python script will print an ASCII image whenever you open your terminal. You have to manually adding your favorite image to the script. 
*I will adding automatic adding ASCII image in the future :)*

## How to use it

### Basic

Basically, user just need to copy & paste `git clone https://github.com/thaisonho/WakeUpTerm.git` to the terminal.
Then, open your shell configuration file *(in my case I use Powershell)*:

- **With Administrator permission** *(recommended)*:
Open **Powershell** config file `code $Profile.AllUsersAllHosts` then adding this to the file `python path\to\WakeUpTerm.py`
- **Without Administrator permission**:
Open **Powershell** config file `code $Profile` then adding this to the file `python path\to\WakeUpTerm.py`

### Configuration

- In **WakeUpTerm.py** file, adding your ascii image in `gallery`
- The image will print in pink. If you want to change the color, change the `set_color` variable in `WakeUpTerm.py`. *Note: you will have to use ANSI Escape Code to change color. Visit <https://pkg.go.dev/github.com/whitedevops/colors> to know about ANSI Escape Code*

## My last words

This project isn't finished yet. I will still work on this to make it more automatically for users :).
