Laptop
======


Install
-------

First, install [GCC for OS X](https://github.com/kennethreitz/osx-gcc-installer). (requires OS X 10.6 or higher)

Then, run this one-liner:

    bash < <(curl -s https://raw.github.com/mooseknuckles/laptop/master/mac)

What it sets up
---------------

* Homebrew (for managing operating system libraries)
* QT (used by Capybara Webkit for headless Javascript testing)
* Postgres (for storing relational data)
* Redis (for storing key-value data)
* ImageMagick (for cropping and resizing images)
* RVM (for managing versions of the Ruby programming language)
* Ruby 1.9.3 stable (for writing general-purpose code)
* Bundler gem (for managing Ruby libraries)
* Rails gem (for writing web applications)
* Postgres gem (for making Ruby talk to SQL databases)
* Git Remote Branch gem (for faster git branch creation and deletion)

It should take about 30 minutes for everything to install, depending on your machine.
