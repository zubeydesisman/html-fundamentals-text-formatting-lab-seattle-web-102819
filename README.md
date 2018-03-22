# Text Formatting

### Cloning Down Your Repository

If you already have a personal repository:

* In the terminal, type `git clone https://github.com/<your_username_here>/exceptional-realty`
* A folder with your previous work will appear in the IDE file tree.

If you want to use the demo repository to follow along:

* In your terminal, type `git clone https://github.com/learn-co-curriculum/exceptional-realty-demo`.
* Type `cd exceptional-realy-demo` to navigate into the folder.
* Type `git fetch text-formatting`, the branch for this lesson.
* Type `git checkout text-formatting`, and you're good to go!

**Remember to use `httpserver` to live test your webpage**

<iframe width="640" height="480" src="//www.youtube.com/embed/toswcv5oj9I?rel=0&modestbranding=1" frameborder="0" allowfullscreen></iframe>

<p><a href="https://www.youtube.com/watch?v=toswcv5oj9I">Text Formatting</a></p>

**Note that you may see some fancy autocomplete actions in this video**. Many of these shortcuts are dependent on specific text editors, in this case, Sublime. While it is good to learn that these exist, they are not critical to productivity, and often, as a new programmer, taking the time to write out content manually can be very beneficial.

### Text formatting

### Starting Out

This lesson is all about formatting text in HTML. Since we know from the last lesson that all viewable text is contained within the `<body>` tag, let's start off by typing `Hello World` inside the `<body>` tags. Open `index.html` in your browser or start up `httpserver` and check out your website. You should see the new text displayed on the page (if you don't, make sure to hit 'refresh').

Cool, we've got text on the page! Hit `return` twice so you're two lines below `Hello World`, and type `Hello Moon`. Head back over to your live website, and notice: The browser ignored the whitespace in your code! In order to actually format text, we will need to use HTML tags.

#### `<p>`

On the same line as `Hello World`, right before, add `<p>`, and immediately following, type `</p>`. If you do the same for `Hello Moon`, then refresh, on your web page, you'll now see that the two lines are separated. The `<p>` stands for _paragraph_, and is used to wrap text with some built in formatting rules. Always make sure to close your tags - if you've left a tag open, subsequent tags may be interpreted by the browser as _nested_ within the first tag.

#### `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, and `<h6>`

Aside from paragraphs, it would be nice to be able to indicate headings and subheadings in our page. The way we do this is by using the `h` tag, written from largest to smallest as `<h1>` down to `<h6>`. Headings are useful for search engine optimization, with the largest heading, `<h1>`, carrying the highest importance to search engines.

Above our `<p>` tags, inside `<body>`, write `Exceptional` within opening and closing `<h1>` tags, and then, on the next line, a smaller subheading that says `Realty Group` using `<h2>`. If we save and look at the HTML in our browser, refreshing the page, we can see that 'Exceptional' is much larger as an `<h1>` heading.

This page will serve as our about page as well as our homepage, so we would want to include some text on this page introducing the Exceptional realty company. For now, we can put in filler text to help visualize the look of the page.

```
<body>
  <h1>Exceptional</h1>
  <h2>Realty Group</h2>

  <p>
    "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur."
  </p>
  <p>
    "Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
  </p>
</body>
```

                "our paragraphs below that sublime text",
                "also offers a lot of amazing time savers",
                "for example you can use code completion",
                "to quickly and rapidly write tags so for",
                "example let's say that I wanted to put a",
                "paragraph here where I can do is type",
                "the name of the tag that I'm interested",
                "in creating and then simply hit the tab",
                "key and it will create those opening and",
                "closing tags for you again the way you",
                "do that is you simply just type in the",
                "name of the tag and then you hit the tab",
                "key we can also put place filler texts",
                "quickly and easily into this paragraph",
                "by typing the word lorem and hitting the",
                "tab key and that will put in this lorem",
                "ipsum place filler text"
            ]
        },
        {
             start_offset: "05:26",
               end_offset: "06:04",
                  bullets: [
                "all right and let's say for example that",
                "you know in one of these paragraphs here",
                "I wanted to actually push this text down",
                "to the next line so what I can do then",
                "is I can insert an element here called",
                "the BR tag like this and the BR element",
                "is going to take anything after this",
                "comma and push it down to the next line",
                "let's go ahead and take a look at that",
                "for a second",
                "so you can see here after the comma it",
                "gets pushed down okay let's go ahead and",
                "move on to the real estate listing page"
            ]
        },
        {
             start_offset: "06:04",
               end_offset: "7:35",
                  bullets: [
                "alright and taking advantage of code",
                "completion again we're going to save",
                "ourselves a lot of time so remember",
                "previously I made you write out the",
                "doctype element these HTML elements",
                "these head and body elements and it took",
                "us a while before we actually got to the",
                "point where we were able to fill in this",
                "text content okay but this time on the",
                "real estate listing page what I'd like",
                "you to do is use code completion so",
                "we're going to go ahead and hit shift in",
                "the number 1 to create an exclamation",
                "mark and then go ahead and hit the tab",
                "key and you're gonna see that's quickly",
                "going to write out the doctype tag the",
                "HTML tag this head which already has the",
                "meta and title in it as well as the body",
                "element down here so we can just quickly",
                "paste in the title from one of the other",
                "pages okay and then on this page we'll",
                "go ahead and paste in the heading that",
                "we have on the other page here",
                "and then under here we'll put in an h3",
                "header and we'll put in property archive",
                "and then under that we'll make an h4 and",
                "for each age for would be a different",
                "year"  

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/text-formatting' title='Text Formatting'>Text Formatting</a> on Learn.co and start learning to code for free.</p>
