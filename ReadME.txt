NO SNOW for ymaps 

remove snow coverage from floor for ymaps or shells without portal settings

process:
-use always the image from: SNOW_REMOVE.ytd
you will need only to rename this file!

- on codex search for snowcov-xmas & the equivalent for snowcov-xmas-secondary
lets make example with this files like in the video: snowcov-xmas-121 & snowcov-xmas-secondary-121

get the snowcov-xmas-secondary-121 and export the texture.dds - not the ytd

edit it - where you don't want snow: paint it BLACK
go deep, there are many pixels, on buildings leave a space otherwise you can have snow inside/near walls
on ymaps buildings, play around in more natural ways..circles, how you wish :)

save it as png with paint.net
go in codex and upload the new texture with option dx1/bc1 mipmaps.
then, you must edit on details window (codex) the miplevels to 1
edit the VFT (also on details) to this nr: 5378212016
save it with the name you will need: example snowcov-xmas-secondary-121.ytd

close codex, open it again, check if miplevels are set to 1 and VFT 5378212016 (probably game wont load this VFT detail but make it like this)

put both snow_remove_renamed.ytd + snowcov-xmas-secondary-numer.ytd (for our eg:snowcov-xmas-121 & snowcov-xmas-secondary-121) on your streaming resource and voilá. 
No snow coverage in this area!

