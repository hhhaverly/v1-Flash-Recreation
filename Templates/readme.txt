Hello everyone, alottu here.
Here are the templates to use in the Flash versions.

THE FOLLOWING FILES ARE FOUND HERE -

logo-v1.fla - SECTION 1
- Instructions
- Fla structure
- Exporting
picto-v1.fla - SECTION 2
- Instructions
- Fla structure
- Exporting
polo-template.fla - SECTION 3 & 4
  1 / For making animations
- Instructions
- Exporting
  2 / For porting animations
- Instructions

There's no intro-v1.fla because you can't edit it in adobe animate.

SECTION 1 - LOGO-V1.FLA

 - Instructions
This is easily edited by changing the head symbol
After editing it, you must convert the symbol to a bitmap, 
so that it doesn't have an ugly effect when doing in-game fade.

 - Fla structure
This one has
   - Head
     - Sound (__FORGOT TO DELETE THIS__)
     - Eye stuff
     - Hairline
     - Heads
     - Hair

 - Exporting
To export it, just export it as .swf format
If you change the folder name (v1/) remember to change the file name
EXAMPLE:
(HTML)
Folder: v1/
(FOLDERS)
C:/v1/logo-((v1)).fla

SECTION 2 - PICTO-V1.FLA

 - Instructions
This works almost the same as the current incredibox,
But at the same time it is very different, FIRST
Each picto measures 40px (It is recommended to use SVG pictos)
Each one has a symbol what is called picto% (picto0, picto1... )

 - Fla structure
This one has
   - UNDEFINED (This fla has a LOT of layers.)

 - Exporting
To export it, just export it as .swf format
If you change the folder name (v1/) remember to change the file name
EXAMPLE:
(HTML)
Folder: v1/
(FOLDERS)
C:/v1/picto-((v1)).fla


SECTION 2 - POLO-TEMPLATE.FLA (MAKING ANIMATIONS)

 - Instructions
It works like the tam's bald heads
BUT it has some changes to make it work in flash versions
Has the head reference, Which is used to position the polo head in the game
Has the costume, Which is edited by entering the "Costume" symbol
It has a different size than the current game (164px, 410px)
To animate the heads, you have to enter the head symbol (not the reference) 
and animate the heads there, and for the head movement just move the symbol 
that is in the "Head (Animated)" layer. I don't know what will happen if you 
change the symbol to a graphic, you could try it.

SECTION 3 - POLO-TEMPLATE.FLA (PORTING ANIMATIONS)

 - Instructions
Copy and paste the "heads" symbol from your animation that you want to copy, 
and then copy the head movement timeline. I haven't really tried porting 
animations (basically because I'm new to this), but you do what you want.

TIPS - BECAUSE WHY NOT?
This has to do with the app.xml
In <duree> milliseconds are not used, seconds are used. 
TO AVOID DOING BORING MATHEMATICS, just put a period in the 2nd character
EXAMPLE:

<duree>5333</duree> (OLD)
<duree>5.333</duree> (NEW)

another is
To play you can use ruffle, but a better option is to use flashpoint!
ruffle is slow, First download any version in the Flash Point library, 
then go to C:\Flashpoint\Legacy\htdocs\www.incredibox.com and put your 
mod files there.

Thanks for reading this, because it took me a long time to do it.
Talking about thanks, A BIG THANKS TO...

Joalor64, who downloaded all the files from the Wayback Machine and modified 
them to look like the official 2018 site.

Seal, who made the animation renderer, This was a huge help in making this look like the original

If you want, you can download this project and modify it to your liking so that Flash mods don't die! 
Little miss (Chrismas Variant) is on the way.

