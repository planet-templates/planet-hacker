# `hacker` -  Pluto Planet Template Pack

Design and layout inspired by [Hacker News](http://news.ycombinator.com).


## What's Pluto?

Pluto is a feed reader that lets you build web pages from published
web feeds. More [Pluto Project Site »](http://feedreader.github.io)


## Usage

### Try It Yourself - How To Use the Hacker Template Pack

If you want to try it yourself, install (fetch) the new template pack. Issue the command:

    $ pluto install hacker

Or as an alternative clone the template pack using `git`. Issue the commands:

    $ cd ~/.pluto
    $ git clone git://github.com/feedreader/pluto.hacker.git

To check if the new template got installed, use the `list` command:

    $ pluto list

Listing something like:

    Installed templates include:
       top (~/.pluto/hacker/hacker.txt)

Showtime! Let's use the `-t/--template` switch to build a sample Planet Ruby. Example:

     $ pluto build ruby.ini --template hacker     or
     $ pluto b ruby -t hacker

Open up the generated planet page `ruby.hacker.html` in your browser. Voila. That's it.


## License

The `pluto` scripts are dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

## Questions? Comments?

Send them along to the [Planet Pluto and Friends Forum/Mailing List](http://groups.google.com/group/feedreader).
Thanks!
