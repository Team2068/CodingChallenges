# CodingChallenges

Periodic coding challenges to practice your programming skills.

## Who

### Programming Bucket

This is intended to be used by the Programming Bucket as a way to stretch your skills and get you thinking about solving different problems in a different way.

It's also an easy way to start exploring languages you know or are interested in.

### Anyone Else :)

Anyone interested in trying their hands at programming or just wants to see what all the fuss is about is encouraged to participate.

## What

The idea is to source or create programming challenges or katas for participants to practice.

Each challenge would hopefully include 2 - 3 challenges that cover a range of skills:

- Beginner
- Intermediate
- Expert

There are a number of resources to use as sources.  Some are included below for convenience as well as some search terms to get you going if you're looking to find some on your own.

### Sources

- [Project Euler](https://projecteuler.net/index.php?section=problems)
- [Ruby Quiz](http://rubyquiz.com/)
- [codewars](https://www.codewars.com/)

### Search Terms

- [code kata](https://duckduckgo.com/?q=code+kata)
- [programming challenges](https://duckduckgo.com/?q=programming+challenges)

## When

Periodically, of course :)

In the off season, it would be nice to have at least one for every practice.  If we have big gaps between practices, e.g. monthly, maybe we can get a challenge between practices too.

## Why

Think.  Grow.  Have Fun.

As students hopefully all you do is **Think**, **Grow** and **Have Fun**.

Still as students, and especially if you have a career in software you'll find, or notice others, that stagnate solving the same sorts of problems, the same way, with the same tools.

Solving short problems like these will help you:

- Try out new languages
- Explore parts of the language you haven't encountered
- Think differently
- Learn new tools
- Have Fun!

## How

The mechanics.

### Solving

#### Rules

The whole point of this is to practice, so please try to do these challenges without first looking for help in other peoples solutions, google or stack overflow.

Feel free to solve any or all of the challenges for the given cycle using any programming language you'd like.  Try to include in your solution a `results.txt` or equivalent file that shows you running the program with sample input.

We'll try to have them labelled but it's subjective, so what may seem like an **Intermediate** problem to some might be **Beginner** or **Advanced**.

**The point is to practice and grow, not to frustrate and discourage.**

If you're stuck after legitimately spending a solid 5 minutes thinking about the problem, talk to someone.  Preferrably someone on the team and with spoken words.  Mentors are happy to help guide you.

If you can't find someone to speak with IRL then resort to Discord and the Programming Bucket Channel.  Try to take it offline so as not to spoil the fun for others.

You're just looking for someone to be a sounding board, or to help nudge you in the right direction.  You don't get anything out of hoping for a solution to be given to you.

#### Getting the challenge and submitting your solution

Initially you'll need to `git clone` this repository.

Then interact with it normally:

- `git pull` to get the current challenge and solutions
- `git push` to submit your own solutions

Attempt the challenge and submit what you have before starting on the next challenge.  Submit partial code if you haven't finished the solution.  This is especially helpful if you're looking for help and the helper can `git pull` the repo and see what you already have.

Try to use our git practices and `commit` early and often using decent commit messages.

### Submitting Solutions

You should create a directory/folder under the `Solutions` folder for that challenge with your name (see [Structure] below) that should have the necessary files to build and run whatever code you have as well as a `results.txt` file showing the output of your work.

### Structure

```
└── challenges
    ├── Challenge - 1 - 2018-09-22
    │   ├── README.md
    │   └── solutions
    │       └── MrSchoolcraft
    │           ├── fizzbuzz.rb
    │           └── results.txt
    └── Challenge - 2 - 2018-10-06
        ├── challenge.md
        └── solutions
```

## Contributing

Pull requests are always welcome to help clarify, correct and improve this document and process.

### Submitting Challenges

To submit a challenge you should fork this repository and create a new directory structure for your challenge.

The problems themselves should live in a `README.md` file written in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) properly attributing any sources you may have used.

Try to label the challenges **Beginner**, **Intermediate**, **Advanced**.  Mentors and teammates can help adjust labels.  Labels are only rough estimates and are only there to help guide choices.  Labels may be removed completely in later iterations if they are more a detriment than help.

When you've finished writing up your challenge create and submit a pull request for it to be included in the challenges.  Mentors or bucket leads should work with you on getting your pull request accepted.

## Have Fun

There are only two hard problems in computer science:

1. Naming Things
2. Cache invalidation
3. Off by one errors