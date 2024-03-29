<!--
    =====================================
    generator=datazen
    version=3.1.2
    hash=ad5708bfb5f04c664de6f889febe5476
    =====================================
-->

# Vaughn Kottler (vkottler)

[![Vaughn Kottler's GitHub stats](https://github-readme-stats.vercel.app/api?username=vkottler&show_icons=true&theme=github_dark&hide_title=true)](https://github.com/anuraghazra/github-readme-stats)

[![Vaughn Kottler's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=vkottler&theme=github_dark&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

# Quick Links

* [C++ Projects](#c-projects)
* [Python Projects](#python-projects)
* [TypeScript Projects](#typescript-projects)
* [Languages](#languages)

# Mission

**My long-term goal is to design electronics and write software that is
practical for everyday use at home.**

Having time and resources to put towards engineering is a luxury. Without
self-sufficiencies such as:
* Growing food and raising livestock
* Having a source of fresh water
* Having land or shelter to occupy and find community

...life could demand that more primitive survival needs take priority at any
moment.

What would you do if you made a routine visit to a grocery store and there was
no food? What if there was no voltage on the wires in the walls of your
home? No natural gas to provide heat in the winter or boil water on the stove?

**I'm interested in using technology to scale this infrastructure down** so
that the average home could be equipped with:
* An off-grid battery system
* Automated watering and management of outdoor (or indoor) crops
* General automation of household electronics from the local network

...and more.

**An additional long-term goal is to establish an ecosystem of iteractive
resources (both hands-on via physical kits, in-person sessions and on the web)
to provide a more enriching and enjoyable experience learning about software.**

Software is nothing without hardware to execute it, and software systems that
enable mechatronic work interest me the most. Understanding software systems
end-to-end requires engineering expertise beyond writing code (mechanical,
electrical and more!). For this reason, education about software
requires non-linearity and exploration of many engineering concepts.

Why study "data structures", "algorithms" or "design patterns" without
practical problems to apply such concepts to, and opportunity complete a
learning feedback loop?

# About

I'm an engineer working around the clock. I'm currently focused on trying to
own a home and start a family.

I can't pursue these goals or the [mission](#mission) full-time without a real
job, so that takes priority.

I also believe that the easiest way to get hooked on software is to get
first-hand experience with the highest gain factors: changing lines of code
and making things move. **Moving pixels is fun, but moving massive objects and
harnessing high amounts of physical power is something else entirely**.

As rewarding as such work can be, it's difficult to do as a hobby.

Compute hardware like [Raspberry Pi](https://www.raspberrypi.com/),
[Arduino](https://www.raspberrypi.com/) and many others present low-cost
opportunities for hobbyist engineers to design and build electronics at home.
Today, it's still difficult for a novice to do more than blink LEDs, rotate
small DC motors, or complete boilerplate projects *(let me know if you
disagree!)*. In my limited experience trying to teach kids about programming
and electronics with these tools: blinking LEDs or making noise with a small
speaker/buzzer just isn't captivating enough to keep them interested. It's
equally uninteresting as the instructor!

I've spent hundreds of hours with [LEGO](https://www.lego.com/en-us)'s as a
kid. Physically assembling something from step-by-step instructions seems to be
enjoyable and satisfying for many of us.

This satisfaction doesn't seem to translate to typing code from a booklet into
some desktop (or browser) computer application, or downloading pre-written code
from the internet.

Creating software for hardware can also require expensive tools (e.g.
oscilloscopes, protocol analyzers, in-circuit debuggers) and infrastructure
(real-time telemetry, commanding, text logging) to be productive and
successful. **Iterating on embedded software is
often extremely challenging even for veterans with decades of experience**.

This has been my personal experience trying to earn stripes as a software
engineer, but I feel that better tools could improve learning velocity and
shorten iteration times.

We have a long way to go. Let's get to work!

## C++ Projects

It is extremely difficult to be productive with C/C++. Build systems and
development workflows are hard to get right, and getting them wrong has
huge cost.

I implemented
[yet-another-meta-build-system](https://github.com/vkottler/yambs) because
I wanted a build system with a saner (and more minimal) configuration
interface.

Anothing missing piece is code generation, such as for network protocol
definitions or HAL interfaces for firmware. I use
[ifgen](https://github.com/vkottler/ifgen) for all code-generation needs.

*In the end my entire Python ecosystem exists mainly to support
mission-critical application development done in C/C++ (and soon: Rust).*

I use the following projects to test the build system, which supports nested
dependencies:
* [yambs-sample](https://github.com/vkottler/yambs-sample)
* [yambs-sample2](https://github.com/vkottler/yambs-sample2)
* [yambs-sample3](https://github.com/vkottler/yambs-sample3)

Real projects:
* [coral](https://github.com/vkottler/coral)

### Bare Metal

Current projects:
* [xmc](https://github.com/vkottler/xmc)
* [hal-xmc4700](https://github.com/vkottler/xmc)
* [pico](https://github.com/vkottler/pico)
* [hal-rp2040](https://github.com/vkottler/hal-rp2040)
* [picolibc-semihost](https://github.com/vkottler/picolibc-semihost)
* [firmware](https://github.com/project-81/firmware)

## Python Projects

*What's [Python](https://www.python.org/)?*

Check out the
[YouTube series](https://www.youtube.com/playlist?list=PLTPrK33wiSsn76rMdJ7IVA1tWTcdWX0Fy)
I'm working on where I go over my workflow and document notable feature
developments.

Packages I've created are derived from
[python-package-template](https://github.com/vkottler/python-package-template),
a custom [`cookiecutter`](https://cookiecutter.readthedocs.io/en/stable/) template.
A project template (that leverages a
[config](https://github.com/vkottler/config) repository to keep templates
synchronized in the long-term) makes it easier to start writing code as a next
step immediately after justifying a new project.

See also: [generated documentation](https://vkottler.github.io/python/pydoc/)
(created with [`pydoc`](https://docs.python.org/3/library/pydoc.html)).
Information about each project can be found on that project's `README.md`
linked below.

* [datazen](https://github.com/vkottler/datazen)
* [setuptools-wrapper](https://github.com/vkottler/setuptools-wrapper)
* [svgen](https://github.com/vkottler/svgen)
* [vcorelib](https://github.com/vkottler/vcorelib)
* [vmklib](https://github.com/vkottler/vmklib)
* [vtelem](https://github.com/vkottler/vtelem)
* [runtimepy](https://github.com/vkottler/runtimepy)
* [rcmpy](https://github.com/vkottler/rcmpy)
* [userfs](https://github.com/vkottler/userfs)
* [yambs](https://github.com/vkottler/yambs)
* [ifgen](https://github.com/vkottler/ifgen)
* [conntextual](https://github.com/vkottler/conntextual)

## TypeScript Projects

*What's [TypeScript](https://www.typescriptlang.org/)?*

I got
[typescript-package-template](https://github.com/vkottler/typescript-package-template)
into a usable state
(similar to the one I'm using for [Python projects](#python-projects)) and
spent time on [console](https://github.com/vkottler/console), but building
an application for a browser is too labor-intensive to be practical for
the kind of user-interface application(s) I'm looking to build.

It would be faster to implement a
[TUI](https://en.wikipedia.org/wiki/Text-based_user_interface) graphics library
from scratch in C++ than it would be to use TypeScript and web technologies
to build even a single application, so that's my current plan.

# Languages

[![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=vkottler&theme=github_dark&hide=Eagle&exclude_repo=vkottler.github.io,hal-rp2040,hal-xmc4700,senior-design,diymore-stm32f407&langs_count=16&layout=donut)](https://github.com/anuraghazra/github-readme-stats)
