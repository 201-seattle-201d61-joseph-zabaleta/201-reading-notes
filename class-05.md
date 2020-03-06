# Reading Notes 5  

## HTML Readings  

### Chapter 5: “Images” (pp.94-125)  
Let's talk about images. They should be  
  - relevent  
  - convey information  
  - convey the right mood  
  - be instantly recognisable    
  - fit the color palette  
  
Storing images on your site  
  - Create a folder called images or img  
  - You can also create subfolders to sort images by section or topic  
  
Tags and attributes  
  - <img> is used to display image  
  - <src> attribute tells the browswer where to find the image
  - <title> attribute gives additionl information for the image  
  
Size of the image  
  - Can be controlled by setting the following
    - height  
    - width  
  
Placement of your image  
  1. Before a paragraph  
    - The paragrpah starts on a new line after the image.  
  2. Inside the start of a paragraph  
    - The first row of text aligns with the bottom of the image.  
  3. In the middle of a paragraph  
    - The image is placed between the words of the paragraph that is appears in.  
  
  NOTE: 
    - Block elements always appear on new line.  
    - Inline elements sit within the block level element and do not start on a new line.  
  
OLD CODE:
  - Old methods used align attribute to position an image on a page.  
  - Old methods used top, middle, bottom attributes to align image vertically.  
  - These has been removed in HTML5 and the new standard is to use CSS to style.  
  
* Three rules for Creating Images  
  1. Save images in the right format  
  2. Save images at the right size  
  3. Measure images in pixels  
  
### Chapter 11: “Color” (pp.246-263)  
Color value allows you to color text inside an element either inline or using css  

Three ways to achieve this is:  
  - RGB Values  
  - Hex Codes  
  - Color Names  
  
background-color allows you to fill the boxes created by each element in html.  
  
Contrast  
- Ensure that when picking colors for your website that they have a goo contrast, as in easy to read.  

Opacity  
- You can change the opacity of an image to see through it.  
  
New CSS3 HSL Colors  
- This introduced hue, saturation, and lightness values for colors.  
  -hsl, and hsla attributes. the a is for alpha, or opacity


### Chapter 12: “Text” (pp.264-299)  

Typeface terminology  
  * Serif  
    - Serif fonts have extra details on the ends of the main strokes of the letters. These details are known as serifs.  
  * Sans-serif  
    - Sans-serif fonts have straight ends to letters, and therefore have a much cleaner design.  
  * Monospace  
    - Every letter in a monospace (or fixed width) font is the same width. (non-monospace fonts have different widths).  

Attributes  
  * Weight
    -Light, mediuam, bold, black  
  * style  
    - normal, italic, oblique  
  * stretch  
    - condensed, regular, extended  
  
NOTE: IMPORTANT  
When choosing a typeface it is important to understand that a browser will usually only display it if its installed on that users computer.  

Techniques  
  - Specifying typefaces  
    - font-family  
  - Size of type  
    - font-size  
  - Bold  
    - font-weight  
  - italic  
    - font-style  
  - Uppercase & Lowercase  
    - text-transform  
  - Underline & Strike  
    - text-decoration  
  - Leading  
    - line-height  
  - Letter & Word spacing  
    - letter-spacing, word-spacing  
  - Alignment  
    - text-align  
  - Vertical Alignment  
    - vertical-align  
  - indenting text  
    - text-indent  
  - CSS3: Drop Shadow  
    - text-shadow  
  - First letter or line  
    - :first-letter, :first-line  
  - Styling Links  
    - :link, :visited  
  - Responding to users  
    - :hover, :active, :focus  