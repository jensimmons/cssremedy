# CSS Remedy

Start your project with a remedy for the technical debt of CSS. Created by Mozilla Developer Outreach. 


## Contribute

We'd love to have you contribute to this project. [Create or comment on an issue](https://github.com/mozdevs/cssremedy/issues).


## What Is This? 

For years, base or reset stylesheets have helped web developers get started faster. 

Early resets eliminated all visual styling, putting the burden of defining styles for every element on the webmaster. This made sense when there weren't as many elements or  properties, and when each browser did something very different than the others. By zeroing everything out, you start from a blank page. There were many reset stylesheets that took this approach. Eric Meyer's became the most popular. 

More recently, Normalize and similar projects took a different approach. Rather than removing all styling, they set out to create sensible defaults and eliminate browser bugs. Use one of these and you get a consistent base across all browsers.

CSS Remedy takes a slightly different approach. These days, browsers are far more consistent in how they render CSS. But there are limitations on how far browsers can improve their User Agent Stylesheet. The defaults for the web have to be consistent with the past. Many desirable changes would break millions of existing websites. 

You however, don't have to stay in the past. You can override the UA styles with more modern ideas of how CSS should work by default. Introducing CSS Remedy. 


## Guiding Ideas

CSS Remedy...
* Sets CSS properties or values to what they would be if the CSSWG were creating the CSS today, from scratch, and didn't have to worry about backwards compatibility.
* Applies basic styling to form elements and controls, getting you started with custom styling. We want to find the balance between providing a base for implementing a custom design, and allowing OS-level control over how form inputs work (like how a number pad works on iOS). 
* Provides a very lightweight starter file, with generic visual styling that you will want to replace. This isn't as robust or opinionated as a starter-theme or framework. We've leaned toward specifying less, so you have less to override. (We haven't defined any font families, for example.)



## Inspiration and History

* [Incomplete List of Mistakes in the Design of CSS](https://wiki.csswg.org/ideas/mistakes)
* [Tantek’s CSS Reset: UndoHTML, 2004](http://tantek.com/log/2004/undohtml.css)
* [CSS Reset, created by Eric Meyer, 2007-2011](https://meyerweb.com/eric/tools/css/reset)
* [HTML5 Reset Stylesheet, by Richard Clark, 2010](http://html5doctor.com/html-5-reset-stylesheet)
* [Normalize, created by Nicolas Gallagher and Jonathan Neal, 2011-2019](http://necolas.github.io/normalize.css)
* [Formalize, created by Nathan Smith](https://formalize.me)
* [Sanitize, created by Jonathan Neal](https://csstools.github.io/sanitize.css)
* [Reboot, created by the Bootstrap team, 2017](https://getbootstrap.com/docs/4.0/content/reboot)
* [Web Typography, a book by Richard Rutter, 2017](http://book.webtypography.net)
* [A look at CSS Resets in 2018, article by Ire Aderinokun](https://bitsofco.de/a-look-at-css-resets-in-2018)
* [A Roundup of CSS Resets, from before 2007 (there were many)](https://perishablepress.com/a-killer-collection-of-global-css-reset-styles)
* [Requests on Twitter](https://twitter.com/jensimmons/status/1082396940237750272)


## Browser support
(TBD)
* Chrome
* Edge
* Firefox ESR+
* Internet Explorer 10+
* Safari 8+
* Opera
