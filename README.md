# NLTK

You will need 1 gigabyte of harddisk space

## Setup Apple Mac / Ubuntu


1) Open the Terminal

2) Download setup script that will install miniconda, jupiter and nltk (copy & paste the command)

```
curl  https://raw.githubusercontent.com/doylek1/NLTK/master/setup-mac.sh  --output /tmp/setup-mac.sh
```
or

```sh
wget -O /tmp/setup-ubuntu.sh https://raw.githubusercontent.com/doylek1/NLTK/master/setup-ubuntu.sh
```


3) Run the setup script (copy & paste the command)
```sh
sh /tmp/setup-mac.sh
```

or

```sh
sh /tmp/setup-ubuntu.sh
```



4) When asked **“proceed (y/n)”**  , then type `y` and hit `ENTER` key
    This will take a few minutes.  When downloading is complete, your computer is successfully setup to do work.  




5) Open a new terminal window

6) type `jupyter-notebook` in command line and hit `ENTER` key

7) This will open jupyter notebook in a new internet browser window



If for any reason, you need to re-install Miniconda (eg. broken download), then delete the minconda directory and try again

```sh
rm -rf ~/miniconda/
```







## Setup Windows


1) Download the `python 3 exe installer` from https://conda.io/miniconda.html 

2) Run the exe installer and install using default choices.  By clicking next.  (The installation might take a few minutes if the computer is slow, you can click "Show Details" to see the installation progress.

3) Open a program called `Select Anaconda Prompt`

This will open a black screen (it might keep blinking if the computer is slow).  Wait until you can start typing

4) Type `conda install jupyter nltk beautifulsoup4` and hit `ENTER` key
   
   This will take a a few minutes to download.
   
5) When download is complete, you may wish to change directory by entering  `cd c:\users\me` and `c:`.    

6) Type `jupyter-notebook` and press `ENTER` key.    This will start jupyter notebook in your default browser.   

