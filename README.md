# CSS Remedy

Start your project with a remedy for the technical debt of CSS.
A gift to you from Mozilla Developer Relations.

_This project is just getting started. It's too early to distribute it as part of other frameworks. Feel free to read the files and take inspiration, but do know we have a ways to go before it's really "ready to use"._


## Contribute

We'd love to have you contribute to this project.
See the [contributing guidelines](CONTRIBUTING.md) for more detail.


## What Is This?

For years, base or reset stylesheets have helped web developers get started faster.

Early resets eliminated all visual styling, putting the burden of defining styles for every element on the webmaster. This made sense when there weren't as many elements or  properties, and when each browser did something very different than the others. By zeroing everything out, you start from a blank page. There were many reset stylesheets that took this approach. Eric Meyer's became the most popular.

More recently, Normalize and similar projects took a different approach. Rather than removing all styling, they set out to create sensible defaults and eliminate browser bugs. Use one of these and you get a consistent base across all browsers.

CSS Remedy takes a slightly different approach. These days, browsers are far more consistent in how they render CSS. But there are limitations on how far browsers can improve their User Agent Stylesheet. The defaults for the web have to be consistent with the past. Many desirable changes would break millions of existing websites.

You, however, don't have to stay in the past. You can override the UA styles with more modern ideas of how CSS should work by default. Introducing CSS Remedy.

> *‘Because that’s what Mosaic did’* is exactly the kind of reasoning CSS Remedy is trying to leave behind.
>
> ---Eric Meyer

## Guiding Ideas

CSS Remedy sets CSS properties or values to what they would be if the CSSWG were creating the CSS today, from scratch, and didn't have to worry about backwards compatibility.

We provide:
- A core `remedy.css` that we recommend using broadly across most projects.
- A secondary `reminders.css` with more opinionated or situational remedies that should be reviewed and considered on a case-by-case basis.
- Additional specialized remedy files (such as `quotes.css`) that can be used as-needed, but may not be required generally.

The current set of features can be extended along those lines, with opportunities for light-weight form-styling and other useful defaults. This is a living project, and we're excited to see where it goes!

## Browser Support

We will actively support modern browers, IE 11 and up. For older browsers:

- We will add proven fixes when they are light-weight and non-invasive. We're not trying to ensure full interoperability, but we do want to help encourage reasonable fallbacks.
- We won't "support" older browsers with any sense of urgency, priority, or completeness.
- We're not trying to polyfill new CSS features like grid, or recreate the full html5 "shiv"

## Inspiration and History

* [How browsers are supposed to render things](https://html.spec.whatwg.org/multipage/rendering.html)
* [Requests on Twitter](https://twitter.com/jensimmons/status/1082396940237750272)
* [Incomplete List of Mistakes in the Design of CSS](https://wiki.csswg.org/ideas/mistakes)
* [Reboot, created by the Bootstrap team, 2017](https://getbootstrap.com/docs/4.0/content/reboot)
* [Web Typography, a book by Richard Rutter, 2017](http://book.webtypography.net)
* [Sanitize, created by Jonathan Neal](https://csstools.github.io/sanitize.css)
* [Formalize, created by Nathan Smith](https://formalize.me)
* [Normalize, created by Nicolas Gallagher and Jonathan Neal, 2011-2019](http://necolas.github.io/normalize.css)
* [HTML5 Reset Stylesheet, by Richard Clark, 2010](http://html5doctor.com/html-5-reset-stylesheet)
* [CSS Reset, created by Eric Meyer, 2007-2011](https://meyerweb.com/eric/tools/css/reset)
* [Tantek’s CSS Reset: UndoHTML, 2004](http://tantek.com/log/2004/undohtml.css)
* [A look at CSS Resets in 2018, article by Ire Aderinokun](https://bitsofco.de/a-look-at-css-resets-in-2018)
* [A Roundup of CSS Resets, from before 2007 (there were many)](https://perishablepress.com/a-killer-collection-of-global-css-reset-styles)
