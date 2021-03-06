#          GNU nano -- a simple editor, inspired by Pico
<p align="center">
<a href="./LICENSE.md"><img src="https://img.shields.io/badge/license-GPLv3-blue.svg"></a> 
    
## Overview

    The nano project was started because of a few "problems" with the
    wonderfully easy-to-use and friendly Pico text editor.

    First and foremost was its license: the Pine suite does not use
    the GPL, and (before using the Apache License) it had unclear
    restrictions on redistribution.  Because of this, Pine and Pico
    were not included in many GNU/Linux distributions.  Furthermore,
    some features (like go-to-line-number or search-and-replace) were
    unavailable for a long time or require a command-line flag.  Yuck.

    Nano aimed to solve these problems by: 1) being truly free software
    by using the GPL, 2) emulating the functionality of Pico as closely
    as is reasonable, and 3) including extra functionality by default.

    Nowadays, nano wants to be a generally useful editor with sensible
    defaults (linewise scrolling, no automatic line breaking).

    The nano editor is an official GNU package.  For more information on
    GNU and the Free Software Foundation, please see https://www.gnu.org/.

## How to compile and install nano

    Clone the latest nano source version, then:

        cd nano
        ./autogen.sh
        ./configure
        make
        sudo make install

    It's that simple.  Use --prefix with configure to override the
    default installation directory of /usr/local.

    If you haven't configured with the --disable-nanorc option, after
    installation you may want to copy the doc/sample.nanorc file to
    your home directory, rename it to ".nanorc", and then edit it
    according to your taste.

## Web Page

    https://nano-editor.org/

## Mailing Lists

    There are three nano-related mailing-lists.

    + info-nano@gnu.org is a very low traffic list used to announce
      new nano versions or other important info about the project.
    + help-nano@gnu.org is for those seeking to get help without
      wanting to hear about the technical details of its development.
    + nano-devel@gnu.org is the list used by the people that make nano
      and a general development discussion list, with moderate traffic.

    To subscribe, send email to <name>-request@gnu.org with a subject
    of "subscribe", where <name> is the list you want to subscribe to.

## Bug Reports

    To report a bug, please file a description of the problem on nano's
    bug tracker (https://savannah.gnu.org/bugs/?group=nano -- hover on
    "Bugs", then click "Submit new").  The issue may have already been
    reported, so please look first.

## Current Status

    Since version 2.5.0, GNU nano has abandoned the distinction between
    a stable and a development branch: it is now on a "rolling" release
    -- fixing bugs and adding new features go hand in hand.

## Copyright Years

    When in any file of this package a copyright notice mentions a
    year range (such as 1999-2011), it is a shorthand for a list of
    all the years in that interval.
