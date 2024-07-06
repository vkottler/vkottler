<!--
    =====================================
    generator=datazen
    version=3.1.4
    hash=0ccc0367f8f8ab9715c1ca7d0a4effe0
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

## C++ Projects

It is extremely difficult to be productive with C/C++. Build systems and
development workflows are hard to get right, and getting them wrong has
huge cost.

I implemented
[yet-another-meta-build-system](https://github.com/vkottler/yambs) as an
attempt to make recurring build-system interactions a bug rather than a
feature.

Anothing missing piece is code generation, such as for network protocol
definitions or HAL interfaces for firmware. I use
[ifgen](https://github.com/vkottler/ifgen) for all code-generation needs.

*In the end my entire Python ecosystem exists mainly to support
mission-critical application development done in C/C++.*

I use the following projects to test the build system, which supports nested
dependencies:
* [yambs-sample](https://github.com/vkottler/yambs-sample)
* [yambs-sample2](https://github.com/vkottler/yambs-sample2)
* [yambs-sample3](https://github.com/vkottler/yambs-sample3)

Real projects:
* [coral](https://github.com/vkottler/coral)
* [yambs-wasm-dev](https://github.com/vkottler/yambs-wasm-dev)

### Bare Metal

Current projects:
* [xmc](https://github.com/vkottler/xmc)
* [hal-xmc4700](https://github.com/vkottler/xmc)
* [pico](https://github.com/vkottler/pico)
* [hal-rp2040](https://github.com/vkottler/hal-rp2040)
* [picolibc-semihost](https://github.com/vkottler/picolibc-semihost)
* [firmware](https://github.com/project-81/firmware)
* [hal-rt1176-cm7](https://github.com/vkottler/hal-rt1176-cm7)
* [hal-rt1176-cm4](https://github.com/vkottler/hal-rt1176-cm4)

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
* [quasimoto](https://github.com/vkottler/quasimoto)

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

[![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=vkottler&theme=github_dark&hide=Eagle&exclude_repo=vkottler.github.io,hal-rp2040,hal-xmc4700,hal-rt1176-cm7,hal-rt1176-cm4,senior-design,diymore-stm32f407&langs_count=16&layout=donut)](https://github.com/anuraghazra/github-readme-stats)
