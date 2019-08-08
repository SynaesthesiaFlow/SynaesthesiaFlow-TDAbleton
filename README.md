# Welcome to Synaesthesia
High level description of stack.

## First things first... Get all the stuff.

All dependencies as submodules

    git clone --recurse-submodules -j8  git@github.com:synaesthesiaflow/Synaesthesia.git

#### Immediate goal of this repo - help needed!
The goal of this repo is "one liner" clone and all needed instruction to a useful and productive dev environment, to contribute to the art.  Laptop only.  No hardware needed.

Two years ago with the [Tree of Tenere](https://github.com/treeoftenere/tenere) project we provided a similar distributed development paradigm and had loads of great burner-sourced visual content that we ran on the actual tree!!  Now it's our chance to collectively create audio-visual content, and just like two years ago pull requests that *you* submit will very concretely contribute to the flow of the art-music experience.

+ Ableton audio effect presets
+ LX patterns/effects
+ Envelop spatialization effects
+ Pairings and Mappings between hardware sensors, inputs, and outputs.
+ Integration, integration, integration...


## Ableton <==> TouchDesigner
Touchdesigner acts as the connection layer for data in and out of Ableton.  Thanks Ivan.

The most up to date release is here:
http://www.derivative.ca/Forum/viewtopic.php?f=22&t=10573&p=40385#p40385

You'll need to follow the directions at the [official page](https://docs.derivative.ca/TDAbleton) to properly setup the "TouchDesigner" MIDI Remote Script, and get the two properly talking.  Basically it's a python MIDI Remote Script, so Ableton is "thinking" of the TDAbleton component as any other midi controller.

## LX
LX is an open source 3D pixel control library originally written by Mark Slee and most substantially developed in a fork that went proprietary 2 years ago.  Thus there are two options for this component.

#### open source instantiation of LX lighting engine
The most mature and featureful open source instantiation of LX is that which was used for the [Tree of Tenere](https://github.com/treeoftenere/Tenere).  If you're involved in the project SomaSteazyYa (nate) can lend you a Tenere MCU for you're own hacking enjoiment.

#### proprietary instantiation of LX lighting engine
SymmetryLabs is intending to release their application image "Volume" to collaborators who express interest to Nathan or Sam.  We can ping you a copy of the software.  SymmetryLabs is a for profit company and develops an excellent instantiation of LX, but it is closed source.

## Envelop
Envelop is open source tooling (also pioneered by Mark Slee, and Christopher Willets) for spatial audio.
[Envelop for Live](https://github.com/EnvelopSound/EnvelopForLive)



### That's it that's all folks.
Those are the current components of the system enumerated, and that's it for now.
This project is nascent and it's up to *you* to bring the game.
Let's start a wiki here to start pooling our knowledge.

