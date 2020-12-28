# FCC-Landing-Page-CCC

Building a Landing Page
a freeCodeCamp Challenge


Warming the Engine

As I round the last corner of my third FCC challenge, a few initial assessments should be punctuated. This, overall, has been the most education of the three. Throughout this endeavor, I have made use of some skills (learned previously) and been able to execute them with more ease. Also, I have found myself adhering to new concepts a bit more effectively.

Over the following summary, I will lightly detail a list of features I utilized in the creation of my landing page (for a silly, hypothetical business called ‘Choose Your CHOOCHOO ’.) Here goes…


Figma and Components

I press on with Figma this time and make a point to learn the functionality of components. These are simply set by defining an element as such. After doing so, forging spawns (called instances) is straight-forward and allows for distinctions between the parent (component) and the spawns (instances) themselves.

Taking advantage of this tool makes it much quicker when building cards, buttons and so on. As my prototypes get larger, I will really be able to experience the full capabilities of this option.


Using Cloudinary to Host Images

With my first two FCC challenges, I assumed it was okay to leave my images unaccessible. It never crossed my mind — that they could be made available online via an image hosting site (either cloud or server-based.)

By using cloudinary.com, this could not be a more rudimentary task. After uploading my image from its local location, all that was left to do is rename and readjust quality for sake of image size and (website) loading performance. Both of these tasks are actionable via Cloudinary’s free service. Now, each of my projects include the appropriate images, from favicon, logos and multiple other graphic insertions.


Figma and Element Alignment

Inspect is a crucial device in Figma’s toolbelt. By using ‘inspect’, the red lines for spacing will appear and applying correct distances for each item across my canvas was very streamlined. In addition to the red line features, Inspect will show the font characteristics, colors and even code for finished products. More on this later…


Figma and Multiple Viewports

My first thought when designing mobile, tablet and desktop viewports with Figma was that I would have to manually draw up each screen. This was the wrong idea.

The right idea was in opening a new (blank) resolution and selecting the entire element (or highest parent element of my project,) then duplicating it and maneuvering it onto the next resolution screen.

After the new resolution was gifted a clone of the previous version, the last step was in slightly resizing everything to match. This was a much less pain-free process than my initial plan.


Anchor Jumping Within the Page

Here’s another one which I wasn’t entirely sure of how to pull off — though I had a general idea.

I knew if I wanted to use an (on-page) anchor to navigate somewhere else on that same (existing) page, I would have to reference the element somehow. The answer lied in setting my ‘href’ equal to the desired ‘id’ and that’s it. Now every click on those links directs the user to my intended location on the page — all (ids, of course) preceded by a lone hashtag.


Embedding a Youtube Video with HTML5

My primary attempt in placing a Youtube video in my landing page was to pop the address into a ‘video’ tag. I assumed all would work seamlessly. I was also very wrong.

In order to insert a Youtube video with HTML, a ‘video’ tag just won’t cut it — an ‘iframe’ tag is actually necessary.

That said, there is yet anther step before gaining complete functionality. Once the ‘iframe’ tag is set (and before pasting the Youtube address,) the watch portion of the address must be swapped for embed instead.

By using an ‘iframe’ and recalibrating the address to embed the video, everything should go swimmingly.


PX, EM, REM, CH, EX, %, VW and VH

I could spend some time here and fully articulate each property of these sizes, but I will leave that for another time. What’s most important about this notion (in this setting,) is that I have found it useful to understand how my relative units measure in terms of pixels. So, I have been using a calculator to better estimate how each unit will behave before assigning them to their respective text. This method has saved me a bunch of time in guessing what will fit where and why.


Instantiating H (tags), Articles and Sections

Much like my previous comment on delving deep — I could spend plenty of time going on about the semantics of these tags. In the future, I may do so. But here, I mean to make a more concise observation.

As I built this page, the importance of ‘sections’ (for grouping large portions of content) and ‘articles’ (for grouping the more succinct) makes plenty more sense. 

In contrast, ‘h’ tags  provide a type of semantic skeleton running down the page, for heading each bit of information.


Uppercase Fonts and Text Transform

I used ‘Playfair Display SC’ as one of my fonts on this project. This is a fully uppercase font. For purposes of browsers or instances where this font is not available, I wanted to ensure my casing was kept.

My solution was in using ‘text-transform’ to make all respective text uppercase (regardless) then setting the back-up font to ‘sans-serif’.

This was a fix to my issue; though, there may (of course) be a better answer to the problem.


Sticky!

A(n (numbered)) objective for this FCC challenge was to keep the navigation bar/header at the top of the page.

The first thing I reached for was a ‘fixed’ ‘position’ on my ‘header’ element. Though, after learning about ’position: sticky;’ I understand it to be a much better way of dealing with this demand.

By using ‘sticky’, no margins or extra code is vital to keep the header in place and from causing problems. This was one of the most clear cut, clean finds of the entire project.


Background vs Background-Color

I  was not aware of the ‘background’ property until now. I was steadily using ‘background-color’, then stumbled into the ‘background’ property while researching another objective.

The ‘background-color’ property does just as promised — it sets the background to a specific color via CSS.

However, the ‘background’ property allows for several more values: color, image, repeat, attachment and position.


Box Sizing

I was faced with using many box element of different make-up and sizes. Upon putting together a few, I saw that some of them bled into places across the page for which I did not intend.

Then came ‘box-sizing’. Using this property merges the ‘padding’ and ‘border’ with the overall ‘width’ and ‘height’ of the element in question. After inserting these useful bits, everything squared up very nicely.


Hamburger

In my mobile resolution, I wrote code for a hamburger menu. That said, I won’t be going into detail here. I will (instead) write a full account on my approach to building this feature.


User Select

I learned with this challenge how to keep my elements from being (undesirably) selected. By placing the ‘user-select’ property, this is very achievable. 

What’s more is -webkit is for Chrome and Safari functionality, -ms (for Microsoft) and -moz (for Mozilla Firefox).


In Conclusion

I have taken a little more time in constructing this project, but have learned that much more. This is the most well-crafted challenge I have completed (thus far.)

All things considered, I am pleased with the outcome, but am very ready to move onto the next for more information and creation. See you on the other side!
