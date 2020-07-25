# FASTAI INSTALL UBUNTU SUBSYSTEM WINDOWS 10

## STEPS
- [install ubuntu 18.04](https://www.microsoft.com/en-ca/p/ubuntu-1804-lts/9n9tngvndl3q?rtc=1&activetab=pivot:overviewtab)

- do the rest of the steps in ubuntu subsystem terminal 

- [install python 3.7](https://linuxize.com/post/how-to-install-python-3-7-on-ubuntu-18-04/) 
    - I had to `sudo apt update` after adding the repository

- `vim ~/.bashrc`

- Hit `I` to enter insert mode

- insert `alias sudo='sudo '`

- insert `alias python='python3.7'`

- hit `ESC` and then type `:wq` to quit vim and save what you wrote

- `source ~/.bashrc`

- `sudo python -m pip install --upgrade pip`

- `sudo python -m pip install fastai`

## SUCCSEEED
