# Radio primer

This repository is just a primer, documenting my first steps in exploring the realm of radio frequencies and all the voodoo that goes along with it.

In case you found this repo and want some hints on how to start, i go with the

## Prerequisites

Hats off to the people who experimented with rf circuits way back in the 1930s to 1990s as a hobbyist. Approaching this topic and really understand, what is
going on in rf circuits is not for the faint of heart and it got so much easier
since affordable rf test equipment appeared on the market in the 2010s. Even a low
bandwidth oscilloscope was far out of reach back in the day. Frequencies were estimated on Lecher lines, rf filters tuned with dip meters. Todays technology enables you
to play with frequencies way over 1GHz on a reasonable budget, that barrier RF professionals call the start of
AC. Below 1GHz ... giggle ... it's still DC. I say, if you hit the 1MHz mark, still tinkering
with stuff operating at such frequencies on a mundane breadboard, you will start to witness all
this weird stuff, which makes absolutely no sense, seems unexplainable and if you ask your
favorite search engine, tells you something about bypass capacitors, stray capacity, stray and lead inductance, without ever telling you what that even is.
When i started out with some Arduino projects and played arround with some vintage ics, i
needed a clock generator at 3.759MHz, which i build with a crystal, a hex schmitt trigger, a
resistor and some capacitors. I was unable to verify if my bodged circuit was working, but
quickly found out, i could watch a picture, of what is going on on the output of my clock generator. So tip no 1:

**get an oscilloscope**


