# enter
![usage](screencast.gif)

Start hacking on your projects fast. Quickly select among your projects and open a tmux session for it. 

For an explanation of the reason behind this little tool check out this [post](http://smcabrera.github.io/enter-enter/)

## Installation

### OSX

enter can be installed using brew

    $ brew install enter

### Linux

Haven't added this to any linux package managers yet but you can download the latest release here and create an executable 

```
$ wget https://github.com/smcabrera/enter/archive/1.0.0.tar.gz
$ tar -xvzf 1.0.0.tar.gz
$ cd enter-1.0.0
```

And then move `enter` to an executable path like `~/bin/`

## Usage

`enter` follows a convention where all of your projects are in folders in a folder called `workspace` in your home directory. Once you've moved all your projects to a single folder and named that folder `workspace` all you need to do is:

```
$ enter
```

And you'll get a fuzzy search of all the projects in your workspace. Whichever one you select will get its one tmux session.

