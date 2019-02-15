# Title

Light Up Your Life - With Python and LEDs!

# Description

Lately, Python has opened a whole new world of working with hardware such as wearable electronics. MicroPython and CircuitPython are variants of Python that can run with just 256k of storage space and 16k of RAM. Using these tools, you can write Python code to program an exciting variety of electronics platforms, some smaller than a quarter.

In this talk, you’ll learn how to design, program, and assemble fun electronics projects in Python, no soldering required! Demonstrations will use the Adafruit Circuit Playground Express, one of the easiest and most affordable beginner electronics platforms.

You’ll learn how to program a type of LED (called a NeoPixel) with CircuitPython, what tools and editors to use, and go over common pitfalls and gotchas. I’ll be showcasing some of my own example projects, as well as interesting projects shared by the community from sites like Adafruit and Instructables. By the end of the talk, you’ll know how to control LEDs with Python and light up your life with code and creativity.

# Who and Why (Audience)

The content in this talk will be approachable to any level of developer. Novice developers will learn all about the ecosystem of Python hardware projects with LEDs and how to get started. Intermediate and Advanced developers can use this talk as a head start for creating more complex projects.

# Outline

Python opens a whole new world of working with hardware platforms and wearable electronics. MicroPython and CircuitPython are Python variants that can run with just 256k of storage space and 16k of RAM. You can use them to program electronics platforms, some smaller than a quarter.

This talk will teach you how to design, program, and assemble fun electronics projects in Python, no soldering required!

Demonstrations will use the Adafruit CircuitPlayground, because it’s affordable and easiest to get started with for beginners. I’ll cover how to program a type of LED commonly called a NeoPixel (WS2812). I’ll also cover the BBC micro:bit education toolkit, as well as tools like EduBlocks and the Mu editor that make it easier than ever to get started programming hardware in Python. I’ll be showcasing some of my own example projects, as well as interesting projects shared by the community from sites like Adafruit and Instructables.

### Talk Outline

1. Intro (2 minutes)
2. Hardware in Python - Current State of the Ecosystem (5 mins)
   - MicroPython and CircuitPython, what is it?
   - Tooling
       - MuEditor for beginners, or your editor of choice
   - Hardware platforms
       - Adafruit ecosystem: [Circuit Playground Express](https://www.adafruit.com/product/3333), [Hallowing](https://www.adafruit.com/product/3900)
       - Other platforms, BBC Microbit
3. Programming the [Circuit Playground Express](https://www.adafruit.com/product/3333) hardware platform with Python (10 mins)
   - Circuit Playground Express Overview - My Favorite Affordable all-in-one hardware platform
       - Sensors, buttons, switches.
       - Powering your project
       - How to interact with and read them in Python
   - Programming the Circuit Playground with Python
       - Structure of a program
       - Gotchas
       - Printing program output and debugging
   - LED overview
       - RGB color system
       - How to address individual LEDs
       - Programming patterns
4. Advantages, Disadvantages, and Gotchas (5 mins)
   - Advantages
       - Ease of use - just writing the Python code you already know and love
       - Auto reloading code on the device - no need to constantly re-upload code changes with a finicky tool called avrdude or the Arduino IDE. Using Python, you can just save a file on the board, and it’ll reload automatically.
       - Easy to debug via the serial port — see print statements from your programs in the terminal
   - Disadvantages
       - Lack of libraries - Micro and Circuit Python don’t feature the same rich set of libraries yet. That can change with community contributions.
       - Speed - Python programs run slower than their C++ counterparts. This is fine for most applications, but I’ll cover the common gotchas you may come across, and scenarios where Python might not be the best fit.
5. Conclusion (3 minutes)
   - Community project sharing sites - Adafruit, Instructables, Thingaverse and other resources
   - Short demo of a more advanced project (pre-recorded video available on standby) - my [Python-powered LED earrings](https://twitter.com/nnja/status/1074770502449647616), and a [link to the codebase](https://github.com/nnja/pyearrings) to show what's possible past the beginner project level.
   - By the end of the talk, I hope that attendees will be inspired learn how to program LEDs with Python, to light up their life with code and creativity.


# Additional Notes


I've been a software engineer for over a decade, focusing on Python for the past 6 years. I'm also an experienced public speaker. I've spoken at PyCon US in 2015, 2016, and 2018. I've spoken at other Python related conferences like DjangoCon US, PyCon Canada, EuroPython and North Bay Python. I've given keynotes at PyParis, PyconRussia, and All Things Open.

I'm a hobbyist in the hardware space, but I'm confident that my experience with programming Python software, as well as the successful [hardware](https://github.com/nnja/pyearrings) and [LED projects](https://www.instagram.com/p/BcOctItlEyK/) I've accomplished make me qualified to give a talk on the topic.

A selection of my previous talks can be watched here: https://www.youtube.com/playlist?list=PLU2JOyCJmabDwN3KYNaxwhl9ZyA3E3PP9

I would prefer if my talk was scheduled for the first day, but that’s not a hard requirement.

I'd like to show off sending code to a live Circuit PlayGround Express by utilizing a small tripod and webcam on the podium. I'll be pre-recording all the demos as short videos that I can play back and talk over in case anything goes wrong with the live demo set-up.
