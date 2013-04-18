#1
===
Informal short talk on David
A tool to help you with your NodeJS dependencies

#3
===
You're looking at David.

#5
===
!! David inspects dependencies (or devDependencies) and figures out what is out of date.
Repeat for devDependencies.

#15
===
Major, Minor, Bugfix
It is saying: If the major or minor version increases then I need to retest my code to check it works on the new version, so don’t depend on that. Although, if there are bug fixes, I want them, and whilst I understand that a bugfix release could break my software, it isn’t meant to, so I’m willing to take the gamble.

#16
===
I’ve seen a lot of absolute versions for dependencies, which is fine (you know who you are, you have your reasons), but I also see a lot of reckless version ranges: >= 0.3.14, *, latest which are just mad. How can you possibly know your code will still work as your dependencies transition between major and minor version numbers?