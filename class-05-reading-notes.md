HTML Chapter 5

Make sure not to rip off copyrighted images when you're working for a company - check.

Probably use an assets folder where pictures and other incidentals will go, as I build web applications.

The <img> tag lets us place images in HTML without having to use CSS to overlay it onto another element. It takes src attributes (its location), title (tooltip hover information) and alt (really important for accessibility, this is what will be displayed if the image fails to load and what is read by screen readers). Image tags also accept a height and width attribute, rather than needing to be set via CSS.

Image tags are INLINE elements. Images also have the align attribute. This can be applied for horizontal and vertical alignment (left/right, top/middle/bottom)... but probably, never use this. Manipulate position using CSS instead of deprecated HTML elements!

3 rules for creating images: Save images in the right format, save iages at the right size, measure images in pixels.

Use JPEG format for images with many colors, GIF or PNG for images with only a few, or images with a large area that is just one solid color.

Save images at the size you intend to use them for the web application - don't try to resize images using CSS or height/width attributes if you can.

SVGs are all the rage, and can be animated. Animated GIFs are old news, leave them on 4chan and imgur.

By opening an image on a web page in a new tab, viewing its info, or viewing its properties from a right mouse click, you can see the dimensions of the image.

<figure> and <figcaption> can be used to display a picture and its corresponding text caption.

HTML Chapter 11

The color property allows you to set the color of TEXT within an HTML element. It can be specified as RGB values (Red-Green-Blue), Hex codes, and by the color name.

The background-color property will let you set the color of the background, instead of the text of an element.

Make sure there is a high degree of contrast between text and background color. Nobody likes squinting to try reading what's there.

Opacity and transparency are things. Not sure I want to mess with them, but good to know that's an option.

Apparently HSL color (Hue-Saturation-Lightness) is a thing, in CSS instead of the other colors. How common is it in the wild?

HTML Chapter 12

There's a WHOLE BUNCH of typeface terminology that means... about nothing to me. I read what it was saying, but I don't know how I'm actually going to apply it?

Font-family, I understand. This is just the 'font' you're using in your text. Font-size does exactly what you'd think it would do, by the name. Type scales seem to be similar to font-size, but are determined by scales rather than relative ratios.

Use font-weight: bold for bold text, font-style: italic for italicized text, text-transform: uppercase and text-transform: lowercase for these. Text-decoration: underline, overline, line-through for these options.

Use the line-height property for 'ledding' or the vertical space between lines of text (actually, this seems really important).

Letter-spacing and word-spacing do just what they say. Text-align (left, right, center, justify) lets you change the alignment of text within its element.

:hover, :active, :focus, :link, and :visited are pseudo-properties I figure I should use frequently.