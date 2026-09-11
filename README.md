WeirdTux
========
Last update: September 9, 2026

Description
-----------

SuperTux is a jump'n'run game with strong inspiration from the
Super Mario Bros. games for the various Nintendo platforms.

Run and jump through multiple worlds, fighting off enemies by jumping
on them, bumping them from below or tossing objects at them, grabbing
power-ups and other stuff on the way.

WeirdTux fork
-------------

WeirdTux is a fork of SuperTux v0.3.5a that is intended to be like my 
own small little strange fork of SuperTux v0.3.5a.

Here's what it will add / remove / change:
- [x] Removal of data-lowres folder (seems to be unused)
- [ ] Forest World remake (but before that, removal so Icy Island can be focused on)
- [ ] Removal of unnecessary graphics (nightsky.png, forest1.jpg, dummyguy, cherry bomb, juicebox, etc...)
- [x] Removal of unnecessary add-ons (Incubator, Bonus Island 3)
- [x] Removal of unused graphics and music (cut down the file size a lot) (sort of done)
- [ ] A little bit of reorganization
- [ ] Desert Island (World 3)
- [ ] Various bug fixes from SuperTux v0.4, possibly v0.5?
- [x] Removal of contrib folder (all it has is just few very old things that probably don't work anymore)
- [x] Compilation fixes

Story: Penny gets captured!
---------------------------

Tux and Penny were out having a nice picnic on the ice fields of
Antarctica. Suddenly, a creature jumped from behind an ice bush, there
was a flash, and Tux fell asleep!

When Tux wakes up, he finds that Penny is missing. Where she lay
before now lies a letter. "Tux, my arch enemy!" says the letter. "I
have captured your beautiful Penny and have taken her to my fortress.
The path to my fortress is littered with my minions. Give up on the
thought of trying to reclaim her, you haven't got a chance! -Nolok"

Tux looks and sees Nolok's fortress in the distance. Determined to
save his beloved Penny, he begins his journey.

Running the game
----------------

SuperTux makes use of proc to see where it is. In other words, it does
not have any need to be installed and can be run from anywhere. This
makes it possible to click in the executable in your filemanager (i.e.
Konqueror or Nautilus) as opposed to many other Linux games.

Options can be reached from the menu, so you don't need to specify
arguments, but if you want, type `supertux2 --help` to check the ones
that are available. Also, notice that SuperTux saves the options, so
it's often enough to specify them once. For example, fullscreen mode
causes problems on some setups, so just run `supertux2 --window` and
you should be set.

The game uses OpenGL to render the graphics. You will either need a
CPU with about 10 GHz (which is impossible) or an accelerated video 
card with the vendor's drivers. (On Linux, the team recommends using 
cards from Nvidia with the proprietary drivers or AMD, but ATI or another 
vendor should do)

If only Intel made GPUs... oh wait, they do. Never heard of them much so
I can't really recommend them for now.

Playing the game
----------------

Both keyboards and joysticks/gamepads are supported. You can change
the controls via the Options menu. Basically, the only keys you will
need to use in-game are to do the following actions: jump, duck,
right, left, power and 'P' to pause/unpause the game. There isn't much
to tell about the first few, but the "action" key allows you to pick
up objects and use any powerup you got. For instance, with the fire
flower, you can shoot bullets (note that this is the only power
currently implemented that allows you to shoot bullets).

The Ice Flower will be removed later.

Other useful keys include the Esc key, which is used to go to the menu
or to go up a level in the menu. The menu can be navigated using the
arrow keys or the mouse.

In the worldmap, the arrow keys are used to navigate and Enter to
enter the current level.


Development status
------------------

This version of WeirdTux is still under development, even though the
0.3 line of versions is somewhat aged. This means that badguys,
features, levels, graphics or anything else may be removed in the
future.

Especially the Forest World included in this package may be subject to
drastic changes. These changes will go as far as removing the world
altogether for at least a little while to release WeirdTux v0.3.6.

If the Forest World is removed, it is guaranteed to come back later on.


The End
-------

Thanks for trying out WeirdTux.

Vaesea
