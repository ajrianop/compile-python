# compile-python
This is a repo for a compiling and installing python from scratch

## Compile Python and Create VirtualEnv with It

`sudo apt-get install build-essential gdb Icov libbz2-dev libff1-dev libgdbm-dev liblzma-dev libncurses5-dev libreadline6-dev libsqlite3-dev libssl-dev 1zma 1zma-dev tk-dev uuid-dev zlib1g-dev`

`wget https://www.python.org/ftp/python/3.12.1/Python-3.12.1.tgz`

`tar zxvf Python-3.12.1.tgz`

remove
`rm Python-3.12.1.tgz`

`./configure --enable-optimizations`

to use the four  cores
`make -j 4`

`sudo make altinstall`

`python`

`cd ..`
`/usr/local/bin/python3.12`

Go to
`vim ~/.bashrc`
and modify the alias of python as:
alias  python="/usr/local/bin/python3.12"

create also a new source venv
source ~/.venv/bin/activate

If this does not work, you can use the following code over the terminal
`virtualenv .env`
`source .env/bin/activate`

use .wq to exit and save the changes


`source ~/.bashrc`

`python -m venv ~/-venv`


`which python`

`python`

`make install`


Now open another terminal and write
`git status` 
`git add README.md`
`git add *`

Modify the gitignore adding to the list
.vscode

now after add the files
`git add .gitignore`
`git add *`

make the commit
`git commit -m "adding skeleton"` 

## Command allows what is happening with the machine
`htop`


