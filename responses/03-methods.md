# Prompting Us for Input
Knowing how to print strings is great, but it can get stale printing the same output over and over again. The next concept we are going to learn is how to make our program address us by name! We can do that by prompting for user input and then using that input to return an output with the unique input.

Let's start by heading back into our *hello.rb* file and we'll change our output from saying "Hello World!" to a question asking our name. Modify line three to the following:
```ruby
puts "What is your name?"
```
We are now using the `puts` method to output a question asking us our name. Below that we have our second lesson which will allow us to enter our name and capture our input. Uncomment the code on line seven so that it looks like this:
```ruby
name = gets
```
The seventh line introduces a new method, `gets`, and a variable called `name`.

What the `gets` method does is tell the computer to pause for input from the user. Our program will pause to allow us to enter in any text we want, and when we're ready to resume the program, we can press the ENTER key. Our inputs are then captured and converted to a string.

Variables are a way to store information. Similar to how methods are used to store code that can later be used by calling the method, variables store information like strings that can later be accessed by calling the variable. For example, if I assign the string `{{ inputUserName }}` to the variable `name`, I could then call `puts name` and the output would be the string `{{ inputUserName }}`. 

We put this to use in our eighth line of code. Uncomment the eighth line and your project should have the following code:
```ruby
puts "Hey, #{name}! Nice to meet you!"
```
This new line introduces another new Ruby feature called _string interpolation_. String interpolation is used to take the content within a variable and insert it into a string. For example, the `puts` method above will output the value within the variable `name` rather than the word name itself.

We can see this in action by saving our file and running our Ruby file in the command line again. Our program should now ask us our name. We will then be able to enter our name and after entering our name and pressing the ENTER key, we will see a new output with our name in that output.

It may not look how we expect because of an unexpected line break after our name. That's because the `gets` method captures *all* the keystrokes *including* the ENTER key. The ENTER key inside a string creates a _newline character_, and that newline character is what creates the line break. There is a way we can fix this though by using a method called `chop` on the captured string. 

The `chop` method takes a string and removes the very last character of that string, in this case, the newline character.

Let's head back into our hello.rb file and add the `chop` method after our `gets` method. Modify the seventh line so that it looks like this: 
```ruby
name = gets.chop
```
Save the file and now if we run our program in the terminal we should see that the line break is no longer. Our output now looks as we expect it to and we've successfully created a Ruby program that outputs strings, prompts us for input, and outputs new strings using our inputs. 

Your *hello.rb* file should look like this:
```ruby
# Lesson 1: Outputting a String

puts "What is your name?"

# Lesson 2: Prompting User Input

name = gets.chop
puts "Hey, #{name}! Nice to meet you!"
```

*Before moving forward to the next section, let's commit and push our changes to the repo following the steps outlined above.*
```console
git add .
git commit -m"add ruby methods"
git push
```