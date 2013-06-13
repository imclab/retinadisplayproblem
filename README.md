Retina Mac External Display Problem
===================================

#### Warning: This may cause your external monitor to stop displaying. Be prepared to close the browser tab for your monitor to function

What
----

There seems to be a problem where if a 1st-gen Retina Macbook Pro is attached to an external display, when a certain image pattern is attempted to be drawn, the external monitor will shut off.

The monitor will start to show some artifacting patterns, then shut off, unable to draw the screen.

How
---

Either get the code:

1. Clone the repository
2. Pick any browser, make it full-screen, or at least full-width
3. Open the index.html page from your local repo in the browser
4. Wait until the monitor shows artifacting and/or shuts off

Or open one of these web pages:

* [Dan Fraser](http://www.capybara.org/~andrew/noise/)'s reproduction of the bug.
* [My version](https://people.mozilla.com/~oyiptong/retinadisplayproblem/index.html) with progressive animation to find the "breaking point"

Dan's will make the screen go blank faster, (instantly in my case). Mine will progressively add the repeating pattern on-screen until the problem occurs.

Affected gear
-------------

Computer:

* MacbookPro10,1

Monitors:

* Dell U2410
* Samsung S27B350
* LG 23EN43
* LG W2442PA
* LG W2240V
* Apple 23" Cinema Display
* Samsung SyncMaster P2770

OS:

* Mac OS X 10.8
* Windows 7 via bootcamp

Footage
-------

* [Dell U2410](https://vimeo.com/68238157)
* [LG Flatron W2240V](https://vimeo.com/68255631) courtesy of [unr](https://github.com/unr)
* [LG W2442PA](https://vimeo.com/68274344) courtesy of [Byron Jones](https://github.com/globau)
