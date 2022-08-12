# If you broke your path an ls, cd stops working? 

You will have changed your path to something incorrect and broken it by running an export $PATH command...


## What is a path? 

We can see the path by running the below in the terminal.

```
echo $PATH 
```
## Why?

 It will print a long list of directories. If you place an executable file in one of these directories, you do not need to set the path to the executable. You can run it by its name as a command. 

'$PATH' is an environment variable. The system will look for it in all of the directories specified in the PATH when you try to run a programme. 

By having the location of all the executable files in the PATH, when we try to run a program the computer will look in all of the specified locations for the executable. 


## Laymans terms

In layman's terms, a path (or the search path) is the list of directories that will be searched for anything that you type on the command line. If you type in a built-in command like ls, it will look for a specified list of directories.


## Troubleshooting

We can add any directories to our PATH that we’d like, but we must be sure to always include the $PATH variable like that in the list as we edit it, otherwise we might get stuck with no regular commands working anymore (like ls, pwd, wc, etc.). If that happens, don’t despair! We can open that ~/.bash_profile in any regular text editor (we may have to select “show hidden files” or something like that in the Finder window in order to see it), and then just delete whatever was added that messed things up. Then we’ll be able to launch a new terminal again that works just fine and try again!

### Useful notes on paths

https://astrobiomike.github.io/unix/modifying_your_path

