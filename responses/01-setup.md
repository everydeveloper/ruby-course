Alright, {{ inputUserName }} before we dive into the tutorial, there are a couple of steps we need to take to set up our work environment.
- [ ] Install Ruby onto our machine
- [ ] Check that Git is installed
- [ ] Clone this project repository onto our machine
- [ ] Install a text editor onto our machine 

## Install Ruby
You might not need to install Ruby on your machine if it is already installed. You can figure that out by opening up your command line and typing: 
```
ruby -v
```
If you see a Ruby version, then you're good to go. If you don't see a Ruby version, then you'll need to [install Ruby](https://www.ruby-lang.org/en/documentation/installation/) for your machine.

## Check that Git is Installed
You can check if Git is installed in a similar way. Type the following into your command line:
```
git --version
```
If you see a Git version, you're all set. If you don't see a Git version, then you'll need to [install Git](https://git-scm.com/downloads) for your operating system.

## Clone the Repository
Now that we've got Ruby and Git installed, we're going to clone this repository from Github so we can make changes. 

I'm going to have us clone the repo onto our desktops. To do that, type the following into the command line:
```
cd desktop
```
Now that we're in our desktop, we're going to clone the repo by typing:
```
git clone {{ repoUrl }}.git
```
You should see a folder called ruby-course on your desktop, and inside that folder you'll see three files:

* hello.rb – the first file we'll be working with where we go over both how to output strings and receive and use input from the user.
* montys-color.rb – the second file we'll be working with where we expand on the concepts of the first file by adding in our conditional statements, If/Else, to better control the output.
* README.md – a markdown introduction to this tutorial. 

## Install a Text Editor
Most machines come with a basic text editor that you can use to get started, though I recommend installing an editor that is a bit more robust. Some popular ones are [Atom](https://atom.io/), [VS Code](https://code.visualstudio.com/), and [Sublime Text](https://www.sublimetext.com/). 

With all that installed, we have what we need to begin writing our Ruby program!

*Close this issue for the next step*