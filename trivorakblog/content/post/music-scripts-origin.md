+++
title = 'Music Scripts Origin'
date = 2023-09-04T00:39:27-05:00
draft = false
+++

# Explaining Music Scripts (Origin)

Rundown on how to use some of the scripts that I created in my github repositories... midigen/imgnoise/calcnoise/music16

### Backstory

While living with a close friend he told me about an idea a co-worker and himself had. What if the hash from every git commit would make a raspberry pi play a little tune.

Over the years I would come across some sort of technology and hack away at trying to make this silly idea possible. 

That idea stuck with me for over 10+ years. It wasn't until years later while discovering Sonic Pi did this idea pop back into my mind as "doable." While Sonic Pi was a very cool program, it just wasn't what I needed. I was only ever able to generate a 4 to the floor kick drum pattern before I abandoned Sonic Pi all together.



### Ah-Ha

A couple key moments really unlocked how I thought about this projects. From a music point of view once I realized that midi is 128 values and so if I treat everything as 0-127 then conversion from binary/hex/int would be fairly smooth



### Key libraries

The main library that really unlocked a lot for me is the python library **MidiUtil**. This allows me to write data into a simple midi file. Although my projects do stray away from thei intial idea, I feel like I can do alot with softsynths in a DAW. All of my scripts basically generate a simple midi file.
