# Title

Debug Python in a Hands-On Way
Goodbye Print Statements, Hello Debugger!
Debug Like a Pro in Python 3
Hands-on Debugging in Python 3

# Description

Still debugging your code with print statements? Learn how to level up your ability to troubleshoot complex code situations by using the power of a fully-featured debugger in this talk aimed at all levels of programming ability.

Debuggers allow you to examine your program state, watch as the values of important variables change, and even modify the content of variables on the fly. Once I gave up print statements, my productivity as a programmer increased, and yours can too!

I'll showcase the variety of debugger tools available - from `pdb`, the simplest command line debugger that's part of the standard library, to fancy graphical debuggers available in Python IDEs. Join me as we walk through real code together using debugger tools in a hands-on way to help us diagnose problems and bugs. The skills you'll learn in this talk will allow you to quickly use these tools in your own code bases for fun, school, or work.

# Who and Why (Audience)

This talk will be incredibly useful to novice and intermediate developers who have been afraid of trying out debugging tools because they look too complex. They'll learn that by picking up a few straightforward concepts, the debugger can be an incredibly easy to learn tool that allows them to quickly and efficiently diagnose problems and troubleshoot bugs.

# Outline

TODO: should be doing demos with breakpoint() and ipdb instead?

1. Intro (2 minutes)
	- About me
	- Talk overview
2. The foundation of debugging - the breakpoint (2 minutes)
	- What is a breakpoint? What's going on under the hood?
3. Available tools, and how to set a breakpoint in each (8 minutes)
	- pdb
		- Most basic debugger, included in the Python standard library
		- Show how to set a breakpoint
	- ipdb
		- More advanced debugger with a lot of advantages
		- Cover the advantages over the built-in debugger
		- Show how to set a breakpoint
	- breakpoint() in Python 3
		- Brief explanation of why breakpoint() is so powerful, and show how to use it.
	- Briefly showcase graphical debuggers, like those present in Python IDEs
		- Explain how to set breakpoints in an IDE and showcase other useful tools, such as temporarily removing all the set breakpoints in a codebase, debugging templates, and more
		- Cover advantages of this approach, such as removing the possibility of leaving debugger statements in checked-in code
	- Strategies for preventing debugger statements in production code
		- Explain why debugger statements in checked-in code are a huge problem: they can cause the whole program to halt
		- Explain how linting and git pre-commit hooks can prevent this scenario from occurring
4. Hands-on debugging with ipdb and brief hands-on demos to demonstrate each debugger concept. All demos will be pre-recorded as well. (10 minutes)
	- What makes the debugger more powerful than print statements?
	- Actions
		- Step in
		- Step over
	- Frames
		- Stepping up and down in context
	- Examining exceptions
	- Conditional breakpoints
	- Watching and examining variables and statements
		- Tip: pretty printing, built-in to ipdb with a useful shortcut
	- Tips and tricks
		- ipdb commands are powerful - they allow you to quickly look up help and method parameters, paste in code, export debugger statements, and much more
		- Breaking out of loops
		- Showing more context by displaying code on the surrounding lines
5. Conclusion (3 minutes)
	- More tips:
		- Debugging unit tests
		- Strategies to prevent debugger statements from ending up in checked-in code
	- Summary of what we learned
	- Links to repo with sample code, talk slides, and useful links to additional resources
	- Thank you!


# Additional Notes

There were two debugging talks in 2017, but both focused on slides. In my opinion, they were both excellent talks, but focused on the theoretical without giving attendees a hands-on overview of how debuggers work when using them on real code. I believe my talk will be valuable addition to Pycon in 2019 because I plan on taking a different approach - I'd like to make the talk more exciting and educational by making some sections interactive, and showing attendees exactly how they'd use the debugger and what steps they'd need to take to troubleshoot a real program.

The demo sections will be brief, but I'll still pre-record these parts so that I can show a recorded video in case anything goes wrong with the demo. I'll be using a small web-based application that hits an API to showcase various debugger tools. The skills that attendees learn will allow them to quickly use these tools in their own code bases - whether for fun, school, or work.

I'm qualified to give this talk because I've been a software engineer for over a decade, focusing on Python for the past 6 years. I'm also an experienced public speaker. I've spoken at PyCon US in 2015, 2016, and 2018. I've spoken at other Python related conferences like DjangoCon US, PyCon Canada, EuroPython, and North Bay Python, and I've given keynotes at PyParis, PyconRussia, and All Things Open.

A selection of my previous talks can be seen here: https://www.youtube.com/playlist?list=PLU2JOyCJmabDwN3KYNaxwhl9ZyA3E3PP9

I would prefer if my talk was scheduled for the first day, but that's not a hard requirement.