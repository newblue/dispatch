*dispatch version 0.0_5*

Package dispatch provides goroutine dispatch and concurrency limiting

About dispatch
=============

Package dispatch provides an object Dispatch which is a queueing system for
concurrent functions. It implements a dynamic limit on the number of
routines it is runs simultaneously. It also implements an interface Queue,
allowing for alternate queue implementations (I''m working on some new
implementations).

Dependencies
=============

You must have Go installed (http://golang.org/). 

Documentation
=============
Installation
-------------

Use goinstall to install godirs

    goinstall github.com/bmatsuo

General Documentation
---------------------

Use godoc to vew the documentation for dispatch

    godoc github.com/bmatsuo/dispatch

Or alternatively, use a godoc http server

    godoc -http=:6060

and view the url localhost:6060/pkg/github.com/bmatsuo/dispatch

Author
======

Bryan Matsuo <bmatsuo@soe.ucsc.edu>

Copyright & License
===================

Copyright (c) 2011, Bryan Matsuo.
All rights reserved.

Use of this source code is governed by a BSD-style license that can be
found in the LICENSE file.
