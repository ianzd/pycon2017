
# PyCon 2017

Some highlights from PyCon this year:

## Several talks mentioned new features of Python 3.6
Python 3.6 brings significant improvements, including implementation of f-strings as detailed in [PEP 498](https://www.python.org/dev/peps/pep-0498/) 

More on [f-strings](https://cito.github.io/blog/f-strings/).

## Katy Huff's keynote: Do It For Science!
[Watch](https://www.youtube.com/watch?v=kaGS4YXwciQ)

## [Modern Python Dictionaries](https://us.pycon.org/2017/schedule/presentation/18/)

[Watch](https://www.youtube.com/watch?v=npw4s1QTmPg)

Raymond Hettinger on how dictionaries are implemented in Python, why they're fast, the trade-offs that come with speed, and the iterative process that led to improvements in 3.6.

## [Keynote: Python and Django at Instagram](https://www.youtube.com/watch?v=66XoCk79kjM)
Instagram's Lisa Guo and Hui Ding gave a keynote on their migration of Instagram's codebase from python 2 to 3.  They've been running 3.6 in production for several months now. Their motivation: Performance and development velocity.

## [Snek in the Browser](https://us.pycon.org/2017/schedule/presentation/51/)
[Watch](https://www.youtube.com/watch?v=1YmbZQjty3Y)

Snek is one of Beeware's ambitious projects aimed at getting Python to run in places it didn't run before. Snek is a implementation of the Python VM in Javascript -- your browser can run Python bytecode!

## [Packaging Let’s Encrypt: Lessons learned shipping Python code to hundreds of thousands of users](https://us.pycon.org/2017/schedule/presentation/291/)

[Watch](https://www.youtube.com/watch?v=WdhYa--Cahk)

Let's Encrypt is the largest certificate authority in terms of number of certs issued by a large margin! They support an enormous number of operating systems and versions of software.  "The long tail of supported OS is looooong." Packaging this application for a ton of platforms is complex.

## [Awesome Command Line Tools](https://us.pycon.org/2017/schedule/presentation/518/)

[Watch](https://www.youtube.com/watch?v=hJhZhLg3obk)

How can we more easily create command line tools like pgcli, mycli, and bpython that make features more easily discoverable? Enter [prompt_toolkit](https://pypi.python.org/pypi/prompt_toolkit), a library to add tab-completion, syntax highlighting and such to your own projects without much fuss.

## [Requests Under the Hood](https://us.pycon.org/2017/schedule/presentation/71/)

[Watch](https://www.youtube.com/watch?v=ptbCIvve6-k)

Requests is great to use, but under the relatively elegant surface is code that has to deal with the complex and often poorly defined world of HTTP. 

## [From blinking LEDs to a bike speedometer with MicroPython](https://us.pycon.org/2017/schedule/presentation/556/)

[Watch](https://www.youtube.com/watch?v=9BUakSTQwb4)

If you've played with an Ardunio or similar hardware and experienced the limitations of the platform, you'll appreciate what having a more powerful microcontroller that can run higher level languages can allow you do more easily.

## [Hacking Classic Nintendo Games with Python](https://us.pycon.org/2017/schedule/presentation/732/)

[Watch](https://www.youtube.com/watch?v=v75rNdPukuI)

This was a clever, fun demo. Why not allow a room full of people to poke values into the memory of an emulated NES?
