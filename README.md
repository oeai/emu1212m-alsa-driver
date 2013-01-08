emu1212m-alsa-driver
====================

this is a patch for emu1212m users that will load the firmware, on this moment alsa driver not works properly

so i've changed some parts of the code and you need to put it in the alsa directories before compiling the driver
it is still not getting out of suspend, but at least after alsa-reload it works properly.
and really the formware is loading right now, sorry i don't have much time to write it properly by the @rules
i don't have time to read rules, i'm not a programmer really, just do what i can and what i like.
and i don't like to rewrite the code 3 times - sorry.
you need to find a directory in alsa driver  sound/pci/emu10k1 put these files there and do make -j4
