# freeCodeCampProductLandingPage

Going to start with my normal pseudo-code.  Then let's see what special things they want to be used like sections or asides, and whatnot.  I'm guessing I have to build this one with grid, and I'm going to have to read a lot, even after doing the last project.

Have to use a header for the top fixed nav-bar

11-Sep-23
    I'm pretty happy that I have the media queries functioning the way I want them to.  Cool to see the layout actually act responsively.

    Okay, I made the header position fixed, and it stopped behaving as a block item.  Now the main-content is underneath it, and I can't get it to move down.....  

    I also added a .page-wrapper to try and force everything to flex, but that didn't seem to do anything at all.  May want to remove that.

    Fixed nav-bar current solution:
        I manually tested different margin pixel values to push the main content box down to where it ought to be.  Not really the solution I'd want to use, but it works for now.