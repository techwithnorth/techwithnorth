# Tuir - Reddit CLI client

To install it you will need the following

sudo pacman -S python-setuptools

git clone https://gitlab.com/ajak/tuir.git
cd tuir
python setup.py install

To my confort it's nice to have it in aliases. My example:
alias rt='tuir'

to enter specyfic subreddit use tuir -S <subreddit_name> or (rt for short

Basic usage keybindings:
u - opens default browser with login prompt
arrows or vim navigation keys - up, down, open close post
space - fold comments
/<subreddit name> - self explanatory

