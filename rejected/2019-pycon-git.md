# Title

Oh No Git! How to Quickly Recover From Git Mistakes and Avoid Losing Work

# Description

git has become a tool that we, as developers, have grown to both love and hate.

Collaborative source control allows us to work on open source projects, work closely with teammates, and easily organize our code into units of work called commits. But, with great power comes great responsibility. Because git is such a powerful tool, it's unfortunately easy to make workflow mistakes. We've all looked to Stack Overflow for help with git messes.

Unfortunately, when you apply cut-and-paste solutions to git problems without truly understanding what's going on under the hood, you can end up in some nasty situations. You can lose your own work, or even worse -- cause other people to lose theirs.

In this talk, you'll learn enough about how git works under the hood to use it as a tool when it really matters -- when you've made a git mistake and need to figure out the correct strategy and approach for undoing your situation. You'll learn which operations are permanently destructive and how to avoid them, as well as pick the right tool for the job to undo mistakes and errors.

# Who and Why (Audience)

This talk is useful for developers of any level. Expertise in a programming language doesn't translate to git knowledge. I've met expert developers who still struggle with git. This talk will teach any level of programmer what to do when git goes wrong.

# Outline

1. Introduction (2 minutes)
   - About me
2. Why we lose work in git (3 minutes)
   - The usual culprits
   - Running commands we don't understand
   - Stack Overflow can give bad advice
- Stack Overflow answers tend to be specific to a specific problem. Applying it to your own situation doesn't always achieve the results you want.
   - Blindly copying / pasting from Stack Overflow can result in lost work and a bigger problem
   - Additional issues can be caused by trying to use git in a way that it  wasn't designed for
3. Brief tour of how git works under the hood (5 minutes)
   - Need to know a bit of fundamentals to understand how to fix mistakes
   - Take a peek under the hood. "Porcelain vs Plumbing"
       - Porcelain - the git commands we interact with
       - Plumbing - how those commands are implemented under the hood
   - What is a commit?
   - What is HEAD?
   - What is a branch?
4. The three areas where code "lives" in git (5 minutes)
   1. Working area - Your local directory
   2. Staging area - Directing which changes should be placed in the repository next
   3. The Repository - The files git knows about, and a log of changes tracked.
   - The git commands that allow us to move our work between the three areas
5. Safe places for your work (5 minutes in 45 minute talk, cut from 30 minute talk)
   - Git stash
   - Stashing with the `--include-untracked` flag to stash files git doesn't already know about
   - How to create backup branches with `git branch` before performing destructive operations
6. Changing the past - cleaning up local commits. (5 minutes in 45 minute talk, cut from 25 minute talk)
   - Amend - Edit the last commit
   - Brief explanation of Rebase - Advanced commit manipulation. Add, remove, or delete commits completely.
   - Fixup - Rebase light. Add to an arbitrary commit without needing to know how rebase works.
   - Warning - never change history on publicly-shared commits.
   - Checkout
7. Fixing Mistakes (10 minutes)
       - Checking out files from the repository.
   - Reset
       - The 3 different modes of reset.
       - When you should use it, and when you shouldn't.
       - Resetting can change history.
   - Revert
       - What revert does.
       - Why it's safe to use when collaborating with others
       - Common misunderstanding - how to "revert" reverts.
   - Clean
       - Easily cleaning up your working directory
8. Danger Zone (3 minutes)
   - Irreversible Destructive Operations, and how to avoid them.
   - Local destructive operations
   - Remote destructive operations
   - Options for recovering lost work
   - Undoing merges
   - Last resort - using the `reflog`
9. Conclusion (2 minutes))
   - If you want to keep your work, don't blindly copy/paste from Stack Overflow
   - Examine you commit history, and choose one of the mentioned approaches to recover work
   - Don't forget to back-up your branches before destructive operations
   - Additional Resources
   - Thanks!


# Additional Notes

I would prefer a 45-minute slot, but I can cut down the talk to be 30 minutes if needed.

I recognize that this talk isn't Python specific, but I still think it would be a great fit for PyCon US. Git is a daily tool for many developers worldwide. It has become the defacto source control solution. Every developer, no matter how experienced, has found themselves losing work because of git. Frustrations can be avoided with a glimpse of git methodologies and a peek into how git works under the hood. I believe this talk will do a great job of covering those topics. Additionally, there have already been three git-specific talks given at PyCon US: [1](https://www.youtube.com/watch?v=RrdECLvHW6g) [2](https://www.youtube.com/watch?v=4EOZvow1mk4) [3](https://www.youtube.com/watch?v=zZ2hG6PMjk8).
These talks do an excellent job of describing what git is and how to use it, but none of these talks focus on what to do when git goes wrong.

I think I'd be a great candidate to give this talk because I've been a software engineer for over a decade, focusing on Python for the past 6 years. I'm also an experienced public speaker. I've spoken at PyCon US in 2015, 2016, and 2018. I've spoken at other Python-related conferences like DjangoCon US, PyCon Canada, EuroPython and North Bay Python. I've given keynotes at PyParis, PyconRussia, and All Things Open.

I'm extremely knowledgeable in git, and I've recorded a full-day in-depth git workshop as a screencast available [here](https://frontendmasters.com/courses/git-in-depth/), which I think makes me a great candidate to speak on the topic. I'll be drawing parts of this talk and diagrams from the material I prepared for my full-day workshop. The slides for the full workshop can be viewed [here](https://github.com/nnja/advanced-git/blob/master/presentation/slides.pdf) (warning, very large file!).

A selection of my previous talks can be watched here: https://www.youtube.com/playlist?list=PLU2JOyCJmabDwN3KYNaxwhl9ZyA3E3PP9

I'd prefer to have the talk scheduled for the first day, but that’s not a hard requirement.