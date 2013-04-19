#1
===
My talk on David: A tool to help you with your NodeJS dependencies

#3
===
You're looking at David.

#5
===
!! David inspects dependencies (or devDependencies) and figures out what is out of date.
Repeat for devDependencies.

#12
===
Point out embeddable badge

#13
===
Not only unique to your project, but unique to the specific dependency versions your project depends on, and the dependency versions your dependencies depends on and so on and so forth. 

#15
===
Major, Minor, Bugfix

Avoid breaking changes whilst automatically getting the benefits of bug and security fixes.

It is saying: If the major or minor version increases then I need to retest my code to check it works on the new version, so don’t depend on that. Although, if there are bug fixes, I want them, and whilst I understand that a bugfix release could break my software, it isn’t meant to, so I’m willing to take the gamble.

#16
===
Orange -> Pinned dependencies do not count towards your status badge. 

I’ve seen a lot of absolute versions for dependencies, which is fine -> reasons

I also see a lot of reckless version ranges: >= 0.3.14, *, latest which are just mad. How can you possibly know your code will still work as your dependencies transition between major and minor version numbers?

#22
===
Indicator of your project health by association of how healthy your dependencies are!  

1. I'd like to know if the modules I'm depending on are the best choices for me.

Do they do the job efficiently? Are they being used by others?

2. Are they well maintatined? Do they have regular contributions, releases, bug fixes, security fixes?

I'd like to know what went into (or was removed from) a new release since the last version, so I can make an informed decision about whether or not to upgrade.

Maybe we can show changelogs? Or, have some indication of how important the update is? - e.g. plug a security hole or just add new features?

3. All of which is related to having visibility on the complexity of your dependencies - where we have already made some inroads, but we could do more! 