openWaffle
===============
open Waffle.io project board from CLI.
A small bash script that opens your project page on waffle from within a repository.

This is useful if you are often opening [Waffle.io](http://waffle.io) to create or view issues.

## Instructions ##

To use this script add to a folder in your path. I have a folder called '''.scripts''' in my home directory. 
It is important to add this to your path (.bash_profile or .bash_rc)

```
cd ~
mkdir .scripts
vim bash_profile
```

then add 
```
PATH="PATH=$PATH:$HOME/.scripts" 
export PATH
```
You then need to refresh your profile
You can do this by typing
```
source .bash_profile
```

Next you need to clone or download the script:

clone repo:    
    git clone https://github.com/oscarmorrison/openWaffle.git
or downloa: 
    curl -O https://raw.githubusercontent.com/oscarmorrison/openWaffle/master/openWaffle
to your new scripts directory
now you need to make executable
```
chmod 775 openWaffle
```

Now all you need to do is go to a bitbucket or github hosted repo and type
```
openWaffle
```
and it will open your browser to the repo online.

Enjoy!
