# Welcome to Synaesthesia
High level description of stack.

### Ableton <==> TouchDesigner
Touchdesigner acts as the connection layer for data in and out of Ableton.  Thanks Ivan.

The most up to date release is here:
http://www.derivative.ca/Forum/viewtopic.php?f=22&t=10573&p=40385#p40385

You'll need to follow the directions at the [official page](https://docs.derivative.ca/TDAbleton) to properly setup the "TouchDesigner" MIDI Remote Script, and get the two properly talking.  Basically it's a python MIDI Remote Script, so Ableton is "thinking" of the TDAbleton component as any other midi controller.

### LX
LX is an open source 3D pixel control library originally written by Mark Slee and most substantially developed in a fork that went proprietary 2 years ago.  Thus there are two options for this component.

#### open source
The most mature and featureful open source instantiation of LX is that which was used for the [Tree of Tenere](https://github.com/treeoftenere/Tenere).  If you're involved in the project SomaSteazyYa (nate) can lend you a Tenere MCU for you're own hacking enjoiment.

#### proprietary
SymmetryLabs is intending to release their application image "Volume" for Synaesthesia which can be used to build functionality without writing code.  Link coming soon.

### Envelop
Envelop is open source tooling (also pioneered by Mark Slee, and Christopher Willets) for spatial audio.
[Envelop for Live](https://github.com/EnvelopSound/EnvelopForLive)



#### That's it that's all folks.
Those are the current components of the system enumerated, and that's it for now.
This project is nascent and it's up to *you* to bring the game.
Let's start a wiki here to start pooling our knowledge.


## Get all the stuff...

All dependencies as submodules

    git clone --recurse-submodules -j8  git@github.com:synaesthesiaflow/Synaesthesia.git
