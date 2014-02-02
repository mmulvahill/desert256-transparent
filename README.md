desert256-transparent.vim
=========================

## Description

Modified Vim theme with transparency support by Evan Klitkze

These are the colors of the "desert" theme by Hans Fugal with a few small
modifications (namely that I lowered the intensity of the normal white and
made the normal and nontext backgrounds black), modified to work with 88-
and 256-color xterms.

The original "desert" theme is available as part of the vim distribution or
at http://hans.fugal.net/vim/colors/.

The real feature of this color scheme, with a wink to the "inkpot" theme, is
the programmatic approximation of the gui colors to the palettes of 88- and
256- color xterms.  The functions that do this (folded away, for
readability) are calibrated to the colors used for Thomas E. Dickey's xterm
(version 200), which is available at http://dickey.his.com/xterm/xterm.html.

I struggled with trying to parse the rgb.txt file to avoid the necessity of
converting color names to #rrggbb form, but decided it was just not worth
the effort.  Maybe someone seeing this may decide otherwise...

## From the owner repository

I created this repository because I could not find the original repository.
I think to this day he did not have a repository.

## License

Licensed under the GNU GPL License either version 2, or (at your option) any
later version.

© Henry So, Jr.
© Evan Klitkze
