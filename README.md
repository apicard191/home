# Home
A bin to access to your docker directory form your project directory

## Install
Clone or download this project and add the line to your file `~/.bash_profile`
```
export PATH=$PATH:_PATH_/home
```

## setup
Run `home setup` in you project directory to setup the link between your project directory and your docker directory.
```
Docker path: [~/docker/environment] 
```
The command ask you the path to your docker directory.
```
Wich file do you want to use ?
    1/ .env (default)
    2/ .env.local
    3/ .home_env
```
And in wich file that you want to save this path. (the command will creat it if is not exist).

## Run your command
To run any commands in your docker directory from your project directory add `home` in the beginning of your command.
```bash
home ls -al
```

## Run Makefile
To run any commands in the Makefile of your docker directory add `home` in the beginning of your command. You do not need to add make to your command.
```bash
home start
```
