# FASTAI INSTALL UBUNTU SUBSYSTEM WINDOWS 10

## STEPS
[Install ubuntu 18.04](https://www.microsoft.com/en-ca/p/ubuntu-1804-lts/9n9tngvndl3q?rtc=1&activetab=pivot:overviewtab)

Do the rest of the steps in ubuntu subsystem terminal 

[Install python 3.7](https://linuxize.com/post/how-to-install-python-3-7-on-ubuntu-18-04/) 
    - I had to `sudo apt update` after adding the repository
    - Instead of python3.7 get python3.7-dev with `sudo apt install python3.7-dev`

- `vim ~/.bashrc`

Hit `I` to enter insert mode

insert `alias sudo='sudo '`
insert `alias python='python3.7'`
insert `alias jupyter-notebook="~/.local/bin/jupyter-notebook --no-browser"`

hit `ESC` and then type `:wq` to quit vim and save what you wrote

- `source ~/.bashrc`

- `sudo python -m pip install --upgrade pip`

- `sudo python -m pip install jupyter`

- `sudo python -m pip install fastai`

cd to a directory you are okay with the fastai content being on. I chose `/mnt/e/` as that is my E: drive

- `git clone https://github.com/fastai/course-v3`

## How to use notebooks

- `cd course-v3/nbs/dl1/`

- `jupyter notebook --no-browser --allow-root`

Use a broswer and go to the URL displayed on the terminal mine was `http://localhost:8888/`

I encourage you to read `00_notebook_tutorial.ipynb`

Make sure to shutdown the notebook when you're finished!
