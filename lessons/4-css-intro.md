---
layout: post
title: Introduction to CSS
lesson_num: 04
excerpt: "Cascading Style Sheets (CSS) allow us to add style such as colors, fonts, and layout to our pages. This lesson will be a review of the basic HTML covered in the last class and an introduction to CSS."
---

<p class="lead">Cascading Style Sheets (CSS) allow us to add style such as colors, fonts, and layout to our pages. This lesson will be a review of the basic HTML covered in the last class and an introduction to CSS.</p>

## HTML Review (together)

Together, let's mark up the [Husky Cupcakes](/lesson_files/husky_cupcakes.txt) page.

## HTML Review Activity (solo)

Let's practice marking up a document *without* our text editor. I've printed copies of this [Wikipedia excerpt](/lesson_files/love_supreme.pdf). Using a pen and paper, mark up this document as HTML.

## What is CSS?

Cascading Style Sheets, most of the time abbreviated as CSS, is a stylesheet language used to describe the presentation of a document written in HTML or XML (including various XML languages like SVG or XHTML). CSS describes how the structured element must be rendered on screen, on paper, in speech, or on other media.

CSS is one of the core languages of the open web and has a standardized W3C specification. Developed in levels, CSS1 is now obsolete, CSS2.1 a recommendation and CSS3, now split into smaller modules, is progressing on the standard track.

"What is CSS" is from [Mozilla's Developer Network Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS)

## CSS Activity (together)

We'll add some basic styles to our review HTML document we created earlier in class.

To do so, create a new file called `style.css` and add the following to the `<head>` of your HTML page:

```html
<link rel="stylesheet" href="style.css">
```

CSS works by using **selectors** to select HTML content and apply styles to them. Look below and take a guess as the the result:

```css
p {
  color: pink;
}
```

Together we will style the Husky Cupcakes page we created earlier.

## Common CSS Properties

Here is a list of some [common CSS Properties](http://www.openbookproject.net/tutorials/getdown/css/resources/lesson1/css_properties.html) and Mozilla's Developer Network maintains a [complete CSS reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

## CSS Activity (solo)

Use today's remaining class time to:

1. Style the Long Wharf Pizza menu you created in a previous class. Change the background color of the page, some text colors, font styles, and type sizes. Reference the common CSS properties link above.
2. Add a home page saved as `index.html`
3. Markup this [index page text](/lesson_files/pizza_index.txt)
4. Add an image to the home page
5. Add your stylesheet (the same one used for the menu) and add any necessary styles
6. Link your two pages together

## Reading

Read [The Dao of Web Design](http://alistapart.com/article/dao/). Though this article is 13 years old, it is still considered a "classic" of web design writing and is essential reading for any web designer.

## CodeAcademy practice

[Make a Website Unit 2](https://www.codecademy.com/en/skills/make-a-website/topics/css-properties-text/css-intro)
