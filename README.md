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

With this, we can move on to another page on our site, but first, this is a great point to push our work up to the remote repository.

```
git add .
git commit -m 'wrote our basic index.html'
git push
```

#### Creating `real-estate-listings.html`

The second HTML page we will make requires a lot of the same basic structure, and enough that developers will often use built-in text editor shortcuts or copy and paste from previously written pages. The only parts we need to change will be the visible content inside `<body>` and, our `<title>` content.

We'll use a similar title structure as before and this time, replacing 'About' with 'Real Estate Listings', and copy and paste in the two headings we wrote in `index.html`.

This time, instead of paragraph tags, let's add an `<h3>` with 'Property Archive' as the heading content, and below we'll add in a few `<h4>` tags for different archive years. Our page should look like:

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Exceptional Realty Group - Luxury Homes - Real Estate Listings</title>
  </head>
  <body>
    <h1>Exceptional</h1>
    <h2>Realty Group</h2>

    <h3>Property Archives</h3>
    <h4>2017</h4>
    <h4>2016</h4>
    <h4>2015</h4>
    <h4>2014</h4>
    <h4>2013</h4>
  </body>
</html>
```

Before moving on, now that we've got two pages worth of content:

```
git add .
git commit -m 'started real-estate-listings.html'
git push
```

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/text-formatting' title='Text Formatting'>Text Formatting</a> on Learn.co and start learning to code for free.</p>
