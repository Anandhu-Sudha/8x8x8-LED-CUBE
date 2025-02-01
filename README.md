# 8x8x8-LED-CUBE
 After the failure of LED Display board, I made an even more complex LED Cube.

#throwback
April-2023

![image alt](https://github.com/Anandhu-Sudha/8x8x8-LED-CUBE/blob/04f7b4797f768a1bcd3fb71a5b9799adf722df24/pictures/IMG20230527215619%20copy.jpg)

This may look easy to make, but the process was quite tedious. The first task was obviously to make the LED Cube structure itself, it's an 8x8x8 setup (512 LEDs in total). Each layer had 64 LEDs connected. 
All the Negative pins of LEDs are connected together in a layer and all the positive pins are connected in columns. By this setup each individual LED can be controlled.

(picture of connection.)

To make a single layer, I've made a LED holding board with plywood. with this each layers dimension will be identical , even the small changes in the dimensions of the layer will make the structure hard to integrate.
Also the each LEDs pins are twisted in a way to create a hole to insert a thin copper rod through this holes, by this the LEDs are more secure.

(picture)

Like this 8 Layers of 8x8 LEDs are made, 

(picture)

since I didn't want to rush the procedure and make mistakes, I gave importance to perfection. As a result this whole project took about 3 months to finish

After this, the assembling of the structure was the next step, and it really a herculean task, even though all the layers looked identical, the millimeter variations happened while soldering, 
It was really hard to stack layer by layer on top of each other. The process was not just stacking but also to align all *64 copper rods* to the holes in the legs of LEDs. It was a two person job to finish this... ( sadly there was no one to take the video of this). My dad Helped me and somehow we stacked 8 layers of LEDs after hours of hard work.

During this procedure we've also made a box to conceal the components & circuit boards used in this by combining two PVC boxes. The LED cube is fixed on a piece of Mica as a supporting platform.

All LEDs were tested and 3-4 of them were not working so had to replace those, which was also a headache.

(picture).

This is how it looked After the assembling of the whole structure.

(picture).

Now it comes to the circuitry, The circuit was built on a zero PCB as mentioned in the tutorial, every components were removable except the resistors. Male and Female headers were used to connect the mosfets and the LEDs.

(picture)

The first run 
The code is flashed to the UNO and turned on for the first time and Turned ON, Boom!... 

(video)

Nothing happened...

After a lot of debugging it turned out to be there was some problem with the MOSFET part, and I had to change it to normal Transistor circuit.

Second Round
(video)
It turned on & was working, but the patterns were not properly coming...
Pins had to be interchanged.

Third Round 
(video)
After interchanging some pins and LEDs Connection it was working fine.

Now it's time to Seal everything up. It needed to cut the remaining piece of copper rods poking out.

(picture)

Usually I disassemble immediately everything and use it for some other projects like this again😂. But for this, It was a menace to build something like this so I decided to preserve it and kept a promise to myself that I will never open this again to take some components during an emergency (but within a year, I opened it again and took the UNO out, I'm not proud about this act😶‍🌫️).  

So after packing everything up. The LED structure had no protection... So my dad made a tranparent Cover with acrylic sheets for this Cube to enclose the LED structure. 

(picture).

This is the final look...

(picture).
