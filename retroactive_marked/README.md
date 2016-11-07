RetroActive Themes for RetroArch & Lakka
====================

About RetroActive
-----------------

The initial motivation was to complete the flatui icons by coloring those in the monochrome set, it ended up becoming much more. Every icon has been redrawn and adjusted, and new icons have been added to better complete the set. A translucent white border has been added to ensure they always look great on a dark or light background.

### Clean Theme

 * Clean icons do not have logos of any type and best embody the spirit of the original flatui and monochrome themes. In some cases, media label styles have been left in place to increase recognizability. An effort was also made to color-coordinate the label with the system when possible. Unbranded core system-level icons can only be found in this set. In order to complete the theme, ported game and system-level icons still have branding.  

### Marked Theme

 * Marked icons contain logos to represent the emulator core and stand-alone application projects. They also contain parody logos for the systems they represent. The labels are designed to mimic the style of the original system while highlighting the adaptive abilities of the Libretro project.  In some cases, the labels vary drastically by region, so multiple icons have been created.

Guidelines
----------

### Palette

 * Icons use the 60 color palette found in the color palette folder. 
 * The use of grayscale in 5% increments is encouraged as a baseline.  Once the icon looks great in grayscale, feel free to add color in order to make the icon as recognizable as possible.
 * Use of gradients is discouraged in favor of maintaining a flat look.
 * Translucency is discouraged except for the 8px white border, which should be set to 50% transparency. 

### Layout

 * The design should be easily recognizable.
 * The icons should be set to a 256x256 canvas and should be centered on a 64x64 grid. Snap design elements to the grid wherever possible to provide maximum clarity and scalability.
 * The icon must have a 8px white border and 8px margin, effectively reducing the icon size to 232x232.
 
### Style

 * The level of detail is expanded beyond the scope of the monochrome set, but favors flat design and recognizability over absolute realism.
 * Branded system icons use a variation of the Libretro brand as the manufacturer and a playful integration into the product name.  For example, the SNK NEO•GEO became the LIB NEO•RETRO.  Logos from the emulation projects are placed similar to third-party publisher logos are placed on a label.
 * Branded port

### Export

The SVG and PNG files can be created using the ImageMagick Mogrify command and Kivutar’s convert.sh script.
