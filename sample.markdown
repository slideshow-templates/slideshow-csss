title: CSSS: Introduction
author: Lea Verou

%% todo: add support for breaking slides on h2 instead of h1 to s9 generator


!SLIDE

## What is it?

A simple framework for building presentations with modern web standards

- An HTML file contains the whole presentation
- Themes as CSS files
- JavaScript handles what CSS can't (keyboard shortcuts etc)


!SLIDE

## History

- I had to create a presentation for my talk at [Front Trends 2010](http://front-trends.com)
- The only web-based presentation systems I knew of didn't fit my needs
- ...so I rolled up my own
- FT2010 attendees asked me to release it
- and here it is! ;-)


!SLIDE

## Feature: Timer

- Timer in the form of a progress bar on the top
- Define the talk duration with the attribute `data-duration` on the `body`
- Style the timer and the end state with the selectors `#timer` and `#timer.end` respectively.


!SLIDE

## More Features

- IDs are dynamically assigned by JavaScript...
- ...but you can also assign your own, bringing the best of both worlds
- Incremental display of slide contents (just add `class="delayed"`)
- Slide scaling based on window size (size everything you want to be scalable in ems)
- Document.title changing according to slide title (fetched either from the `title`
  attribute or the slide's heading)


!SLIDE

## Drawbacks

- Only supports Firefox 3.6+, the latest Chrome/Safari or Opera 10.60+. Why?
  - More lightweight
  - Easier to understand code
  - It's a presentation, so the environment is controlled anyway
- No mouse click to advance to the next slide. I consider it annoying.


!SLIDE

## Continued...

To be done
