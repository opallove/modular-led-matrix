# modular-led-matrix
this is a modular led matrix that will let me build custom size and shape led matrix's

the led matrix is using WS2812 LED's but that might change depending on further testing.
the 8x8 matrix that is documented here is not modular. It is the first test to make sure i have my circuit boards wired correctly.
IT IS NOT MODULAR YET!!!!!!!
a modular version of this display is in the works and will be out of the prototyping stage around the start of next year. A finished design will be out some time after that. (not sure when that will be yet because there is some tests that need to be ran before i go all out and buy all of the circuit boards for a larger scale display.)

some information about the modular display.
- it will not be a bunch of 8x8 displays that you can connect together. it will be 2x2 displays instead, that way they can be made into different sizes easier.

- the LED's that will be used on the display may change if testing shows poor refresh rates on bigger displays.

- the display is very small so if you are a beginner to this kind of stuff i will eventually have circuit boards that use bigger LED's so that you can make them without having to worry about the size.

- the current design is made up of 4 unique circuit boards. and the size of the boards are arround 6 mm leingth and width. so keep that in mind if you plan on making one. (each board is 6 mm long and wide and they have 4 LED's on them, each led has 4 pads on it so that is 16 pads in a 36 mm^2 area.)

- the files for the circuit boards may or may not get uploaded here it just depends on what i want to do with this project later.

- there will be a video out on my patrion at some point showcasing the overall design of the circuit board and how it works. as well as a video tutorial on how to solder the lED's to the circuit board. you will also be able to get in touch with me about the displays and get real time help with making the displays and other stuff relating to this project on my patrion.

- for right now the code for the display will not be posted on here because it still needs to be optimised. (i dont want to give out poorly optimised code to anyone who may want to make one of these displays.)

- at some point i plan on figuring out a way to connect the display to a pc so that you can use it to display information like (spotify, pc temps, videos, games, and anything else you may want it to display.) if this does end up happening it will probably be done through a program on the pc that comunicates to a rpi to send video data from the pc to the rpi. From there the rpi will convert the incoming data into the bitmap and display it. this means it will not be fast and the display may be behind on displaying stuff. However i will try my best to make it as fast as possible to provide a quality experiance when using the display.




More updates on the progress of this project comming soon.
if you are interested in this project and would like to support me and get access to exclusive content on this project you can do so here---> ( https://www.patreon.com/user?u=128994880 )



a special shout out to PGtheVRguy @ ( https://github.com/PGtheVRguy ) he is the programmer fro this project. and he has helped make the code that runs on the rpi. he also made a code that converts gif's in to 8x8 24bit bitmap frames that are used on the pi to tell the display what led to light up when. verry cool guy he went out of his way to make the gif conversion code for this project.

here is a link to his gif to bitmap convertion code ( https://github.com/PGtheVRguy/ImageGif-To-Bitmap ) go check it out. it will be usefull if you plan on making one of these displays yourself.
