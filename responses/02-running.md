_That's correct!_

# Running Our Program
Now that we have our "Hello World!" program written, it's time to test it out by running it. Let's head back into our command line and execute our code with the *ruby* command followed by the name of our file. We do this by entering the following into the command line:
```
ruby hello.rb
```
Our program should execute and we should see in our terminal the output "Hello World!".

Your command line should look like this:
```
user$ ruby hello.rb
Hello World!
```
🎊Awesome! You've written and ran a "Hello World!" program.

The ruby command launches what's called the Ruby interpreter and that interpreter reads the file hello.rb and evaluates what's inside. The interpreter read our line of code and called the `puts` method. Our string was then passed to the method and printed to the screen. You'll notice that the quotes were not printed to the screen, and that's because the quotes are not part of the string, rather, they act as bookends to the string.

Now that we've changed our code, we have a newer version than our repository. If you want to check on that, you can type the following code into your command line: 
```
git status
```
You should see one file is modified. It's good practice to commit our changes early and often and back those changes up by pushing them to the remote repository. 

We can do just that by following these three steps:

Stage the files that have been changed: 
```
git add .
```

Commit the changes and enter a message describing the commit: 

```
git commit -m "Hello World"
```

Push the changes to the repository:
```
git push
```

*Push the changes to GitHub to continue*
