# wefax
Wefax interface for Atari

I'm a radio amateur (ham in some countries) and also a huge atari enthusiast. Sometime ago I found the wefax interface project in an old Antic magazine <a href="https://www.atarimagazines.com/v5n5/wefaxinterface.html">article</a> from 1986. Wefax is a FSK protocol to transmit weather fax over radio waves, mostly used for sea navigation, there are still plenty of <a href="https://weatherfax.com/stations/">wefax</a> radio stations operating daily all over the world.

I looked all over the internet and since I couldn't find the <a href="https://github.com/fcordov/wefax/blob/main/Gerber_wefax-interface_PCB_wefax-interface_2024-03-15b.zip">Gerber files</a> for the pcb I decided to draw it myself. Let me warn you, I'm no expert, actually this is the first schematic and pcb I've drawn, but to my surprise it <a href="https://github.com/fcordov/wefax/blob/main/434384029_10161609972608217_6442181129421848494_n.jpg">actually works</a>. However, feel free to take my implementation of the schematic and pcb and improve upon them, I am sure there is plenty of room for improvement. All credit and copyright goes to Antic magazine and <a href="https://www.atarimagazines.com/index/index.php?author=Bill+Marquardt&mag=antic">Bill Marquardt</a> who originally designed the interface and likely also wrote the decoder and test software. Here is the <a href="https://github.com/fcordov/wefax/blob/main/Schematic_wefax-interface_2024-03-31.pdf">schematic</a> too.

Besides the <a href="https://www.atarimagazines.com/v5n5/wefaxdecoder.html">software</a> needed to decode (and test software, all included in the Antic publication and atr file below), it's only a handful of components to put together the interface, you will also need a SSB radio receiver, an antenna and an Atari computer of course (it will work on both 8bit and ST models) to make all of this work. I'm still learning how to use the decoder program, to make things easier I created an <a href="https://github.com/fcordov/wefax/blob/main/wefax_comp.atr">atr image</a>  compiling the decoder and two pattern creators for testing purposes. It's truly  amazing getting to see weather maps on the 800xl caught from the radio waves.

In short, you connect the input of the interface to your receiver tuned to a wefax station, the output of the interface goes to your atari's joystick port #2, you run the decoder program and proceed to fiddle with both the potentiometers on the interface and settings on the decoder until you get a clear image. Piece of cake!

First <a href="https://github.com/fcordov/wefax/blob/main/434399756_10161609972643217_3180203896414987201_n.jpg">picture</a> shows the weather map decoded by my laptop with FlDigi, the <a href="https://github.com/fcordov/wefax/blob/main/434385109_10161609972668217_2253848846511608338_n.jpg">second one</a> (less resolution) is the same map decoded by my 800xl. It's supposed to be the north Atlantic (if you squint your eyes 🙂). So, would I take my 800xl on a boat trip across the Pacific Ocean? Definitely, of course to play games on it, probably not to exclusively rely on it for my weather forecast needs.
