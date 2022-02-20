# css-zen-garden
My CSS Zen Garden is hosted <a href="https://smith-sj.github.io/css-zen-garden/" target="blank"> here</a>.

The CSS Zen Garden challenge can be summed up in 3 simple steps:

  Step 1. Download the HTML and CSS documents at this <a href="http://www.csszengarden.com" target="blank">link</a>.<br>
  Step 2. Style the webpage by only editing the CSS document.<br>
  Step 3. Don't touch the HTML document.

Simple? Yes. Easy?... <b>Hell, no.</b>

...well, not for a newbie anyway.

In terms of classes, you get what you're given. There is <b>NO</b> touching the HTML document, meaning you're stuck with author Dave Shea's document layout.
As beautifully and expertly crafted as the document is, if an element isn't classed, you need to use pseudo selectors to get at them.

This alone made the challenge worth it for me. As a new programmer, I had no idea of the power of CSS pseudo selectors. Had I been permitted to insert
images into the HTML file, I'd have never discovered that the ::before and ::after selectors can insert content. Not only that, but if you insert an empty string,
you can then set the background to an image and resize the empty string's box to effectively resize the image! <i>(you're probably reading this thinking, "no, duh"
but this seriously blew my mind.)</i>

That wasn't the only cool trick I discovered. Turns out you can do all sorts of things with the CSS mix-blend-mode property, which I used throughout the 
project. The white sections of the webpage are simply paragraph elements with white backgrounds. By setting the text to be black and then changing 
the mix-blend-mode to "screen" it has the effect of cutting the text out of the background. This made all the text in those sections the same coloured gradient 
as the main background.

Using a combination of the above two tricks, I managed to cut icon shapes out of the white section backgrounds, creating awesome transparent icons. This was
achieved by setting the H3 elements' backgrounds to the desired icons. Using various background properties to position each icon and padding to offset titles,
I could then set the mix-blend-mode to "screen" to cut the icons out of the white and reveal the main gradient background.

I could probably write an entire essay about the things I learned during this challenge, alas, I am actually procrastinating from doing my assignments right now
and should probably leave it at that.

I'll finish by saying that the creators of this challenge have done an amazing service to the CSS community and newbies who need to be thrown in the deep end and 
encouraged to think outside the box. CSS Zen Garden is a wonderful example of the true power of CSS and the fact that it has been around since 2003 and is still 
inspiring programmers 20 years later, just goes to prove the ingeniousness of its conception.
