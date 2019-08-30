# Using Else Statements 
Often times we want control over what happens if certain conditions aren't met. In Ruby, we can do that by using _Else statements_. Else statements allow us to run a different block of code when the If statements condition returns false. 

Say we want our program to return, "I'm not a big fan of {color}" when the user inputs anything other than blue as their favorite color. To accomplish this, comment out the code on lines nine, ten, and eleven and uncomment the code on lines 15-19 in lesson five. You should have the following code:
```ruby
if color == "blue"
    puts "Wow! My favorite color is #{color} also!"
else
    puts "I'm not a big fan of #{color}."
end
```
Now when we save and run our program, if we enter yellow rather than blue, we'll see that our program isn't the biggest fan of yellow.

What's great about Else statements is it gives us developers control over what happens when conditions aren't met. Sometimes, we don't want anything to happen, and in those cases sticking with only an If statement will be all you need, but it's always nice to have a bit more agency in directing your code how you want. 

If/Else statements are powerful tools and knowing how to use them will prove fun and useful as you continue your journey of programming.

*Commit and push these final changes to the repo.*
```console
git add .
git commit -m"add else statement"
git push origin master
```