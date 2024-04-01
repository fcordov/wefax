# wefax
Wefax interface for Atari

I'm a radio amateur (ham in some countries) and also a huge atari enthusiast. Sometime ago I found the wefax interface project in an old Antic magazine from 1986 (https://www.atarimagazines.com/v5n5/wefaxinterface.html). Wefax is a way to transmit weather fax over radio waves, mostly used for sea navigation, there are still plenty of wefax radio stations operating daily all over the world (https://weatherfax.com/stations/)

I looked all over the internet and since I couldn't find the <a href="https://github.com/fcordov/wefax/blob/main/Gerber_wefax-interface_PCB_wefax-interface_2024-03-15b.zip">Gerber files</a> for the pcb I decided to draw it myself. Let me warn you, I'm no expert, actually this is the first schematic and pcb I've drawn, but to my surprise it actually works. However, feel free to take my implementation of the schematic and pcb and improve upon them, I am sure there is plenty of room for improvement. All credit and copyright goes to Antic magazine and Bill Marquardt who originally designed the interface.

Besides the software to decode (https://www.atarimagazines.com/v5n5/wefaxdecoder.html) (and test software, all included in the Antic publication), it's only a handful of components to put together the interface, besides that you will need a SSB radio receiver, an antenna and an Atari computer of course (it will work on both 8bit and ST models) to make all of this work.

I'm still learning how to use the decoder program, to make things easier I created an <a href="https://github.com/fcordov/wefax/blob/main/wefax_comp.atr">atr image</a>  compiling the decoder and two pattern creators for testing purposes.It's truly  amazing getting to see weather maps on the 800xl caught from the radio waves.

First picture shows the weather map decoded by my laptop, the second one (less resolution) is the same map decoded by my 800xl. It's supposed to be the north Atlantic (if you squint your eyes 🙂).
