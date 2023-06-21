NO SNOW for ymaps 

remove snow coverage from the floor in any map are, ymaps or shells without portal settings

video tutorial
https://streamable.com/akeej8

process:

- always use the seamless image from: SNOW_REMOVE.ytd
you will need only to rename this file!

- on Codex search for snowcov-xmas & the equivalent for snowcov-xmas-secondary
lets make example with this files like in the video: snowcov-xmas-121 & snowcov-xmas-secondary-121

get the snowcov-xmas-secondary-121.ytd and export the texture.dds 

edit it with paint.net
- where you don't want snow: paint it in **BLACK** color
there are many pixels on this image so you can zoom in very well on buildings or areas that you want to clean
make a bigger area than the building area otherwise you can have snow inside/near walls
play around in any more natural ways.. how you wish :)

save this edited file as png with paint.net
go in codex and upload the new texture with option dx1/bc1 generate mips active.
then, on codex go to the detail window of this file and you must edit the miplevels from 8 to 1
also edit the VFT (also on details) from 0 to this: 5378212016 (probably game wont load this VFT detail but make it this way)
save it with the name you will need: example snowcov-xmas-secondary-121.ytd

close codex, open it again so it updates the new files, check if miplevels are set to 1 and VFT 5378212016 and if all is correct

put both files snow_remove_renamed.ytd + snowcov-xmas-secondary-numer.ytd (eg:snowcov-xmas-121 & snowcov-xmas-secondary-121) on your streaming resource and tha's it! 
No snow coverage in this area!



