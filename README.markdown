# Slide Show (S9) Template Pack - CSSS

The [CSSS](https://github.com/LeaVerou/CSSS) package by Lea Verou bundled up into 
a Slide Show (S9) template pack.

Note, the package is configured to use the following headers in `slides.html.erb`:

    author: Your Name Here
    title: Your Slide Show Title Here
 
## Try It Yourself - How To Use the Template Pack

If you want to try it yourself, install (fetch) the new template pack. Issue the command:

    $ slideshow -f https://github.com/geraldb/slideshow-csss/raw/master/csss.txt

To check if the new template got installed, use the `-l/--list` switch/command:

    $ slideshow -l

Listing something like:

    Installed templates include:
       csss.txt (/home/gerald/.slideshow/templates/csss/csss.txt)

Now you're ready to use it using the `-t/--template` switch. Example:

    $ slideshow -t csss.txt tutorial

That's it. 


## Samples

See a sample in Markdown in the repo titled ['CSSS: Introduction'](https://raw.github.com/geraldb/slideshow-csss/master/sample.markdown).


## Questions? Comments?

Questions? Comments?
Send them along to the [Free Web Slide Show Alternatives (S5, S6, S9, Slidy And Friends) Forum/Mailing List](http://groups.google.com/group/webslideshow).
Thanks!

## What's Slide Show (S9)?

A Ruby gem that lets you create slide shows and author slides in plain text
using a wiki-style markup language that's easy-to-write and easy-to-read.
More [Slide Show (S9) Project Site &raquo;](http://slideshow.rubyforge.org)