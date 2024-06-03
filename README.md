# Becoming a Hacker Training Website
This is the code for the website documenting the [Becoming a Hacker Bootcamp](https://becomingahacker.com).
change

## Description

Becoming a Hacker is a two-day intensive boot-camp providing insight and
real-world examples into the techniques used to bypass, evade and exploit
vulnerabilities. This class will cover a range of vulnerabilities and
weaknesses starting from basic network reconnaissance, service and
vulnerability enumeration, initial and secondary exploitation, evasion and
exploit writing.

More information can be found here:  https://becomingahacker.com

## Learning Outcome

While this is an introductory course, attendees will learn how to break things
in the hopes of learning how to author and deploy securely.

## Prerequisites

A mind ready for abstract concepts!

## Student Equipment

1. Laptop (Windows, OS X or Linux)
2. A Web Browser

## Instructor Equipment

Whiteboard, Projector with screen, Sound speakers for video

## Class Size

40 students

## Source Code Layout

* `modules`: each module has its own markdown page here
* `os_files`: a bunch of static pictures, js, css, etc.
* `non-published`: stash stuff here that you don't wanna publish

* `_config.yml`: Jekyll config
* `_includes`: re-usable web components; these are called inside other files
* `_layouts`: templates that wrap content
* `_site`: when Jekyll builds the site, it puts it here by default

Anything else (with some exceptions) in the root folder will be available to the site by default; e.g. `my_file.png` will be accessible in the website as `/my_file.png`.
