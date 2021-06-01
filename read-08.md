# CSS layouts enable developers to write really meaningful and robust styling rules with just a few keystrokes.


Programming languages make websites feel alive, but at the core of every web page stands the good old HTML.
When we discuss layouts, we must consider factors that make a good layout: responsiveness,
viewing ports, display devices, browsers, and users’ screen sizes.

*A great layout not only looks great but can preserve the original intent by fitting in every possible display ratio.
This correction is produced through CSS. In this article, we will examine two powerful properties: CSS Flexbox and CSS Grid.*


## Start with your content. 

* Design starts with your content (headlines, text, links, photographs, etc.), not with colors, fonts, or icons. It is the page message that should dictate the design.

> For example, if the goal of a student organization page is to get more students to join, you can put a large photo of the members doing something fun or interesting, together   with quotes from them. Then you use style to make them compelling.

* Mock up your design. Don't start your design with code, start with a drawing. Using a drawing program (Paint, Photoshop, Illustrator, etc.) gives you freedom to explore different colors, fonts, images, and positioning, without having to write code. This way you can experiment faster with many choices. If your page needs user interface elements such as buttons, tabs, etc. you can use the free stencil kit from Yahoo, together with Photoshop.

* Identify the boxes. Once you are satisfied with your mockup, you can start thinking about the HTML structure. Basically you need to identify which elements look like individual boxes, because they will have to be in container tags in your HTML.

* Remember background images. Very often, you can more easily place an image with the background-image property than the <img> tag. This is because you can put other information on top of this image. However, you should know that background images are not printed, thus, don't put important information (such as maps) as background.


* Layering elements. Tools like Photoshop use the notion of layers to float several things on top of each other.

*   To do the same on a web page, there are two options: use the background-image property to put text on top of images, or use the position property to lay images or icons on top of text. You can't use float to make content overlap.
  
* Don't forget margins and paddings. Often, you might not need to use sophisticated CSS for layout. A good use of the margin and padding properties can take you really far (especially when combined with the background image property).


 # *div elements are often used as containing elements to group together sections of a page.*
  
>  Browsers display pages in normal flow unless you 
   specify relative, absolute, or fixed positioning.
  
>  The float property moves content to the left or right 
   of the page and can be used to create multi-column 
   layouts. (Floated items require a defined width.)
  
>  Pages can be fixed width or liquid (stretchy) layouts.
  
>  Designers keep pages within 960-1000 pixels wide, 
   and indicate what the site is about within the top 600 
   pixels (to demonstrate its relevance without scrolling).
  
>  Grids help create professional and flexible designs.
  
>  CSS Frameworks provide rules for common tasks.
  
>  You can include multiple CSS files in one page.
