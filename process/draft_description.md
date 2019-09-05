## What does it do?

* Preserves useful defaults, unlike many CSS resets.
* Normalizes styles for a wide range of elements.
* Corrects bugs and common browser inconsistencies.
* Improves usability with subtle modifications.
* Explains what code does using detailed comments.

## Context 

For years, people have started their custom CSS by building on top of a starter file. Eric Meyer's CSS Reset 
bit of history / Normalize....

CSS FOOBAR is not attempting to reset all styling to zero. And it's not specifically about making all browser behave the same. The purpose of FOOBAR is simple — to pay off as much technical debt of the evoluation of CSS as possible. 

The first CSS specification was [published in 1996](https://en.wikipedia.org/wiki/Cascading_Style_Sheets#History). 
our ideas of how to write good specs has changed
we've learned a lot, and have gotten much better at it
there are a lot of things we might do differently now, if we'd known back then what we know now. In fact, the CSS Working Group keeps [a running list](https://wiki.csswg.org/ideas/mistakes) of things to change, in case anyone invents a time machine.

Why don't browser makers just make these changes? Well, it would break the web. 

For example, it's clear now that `box-sizing` should default to `border-box`. But if the browsers suddenly started applying `box-sizing: border-box;` to websites, millions of websites would have browkn layouts overnight. We can't make such changes. But you don't have to live in the past. You can apply many of the more modern ideas to your website, through the use of this starter file. 

Changes to the design of CSS itself are limited by the requirement that all new CSS standards [maintain backwards compatibility](https://www.w3.org/People/Bos/DesignGuide/compatibility.html). 

## Design Principles

This project sets out to:

1. Bring your CSS up to the latest possibilities.  

2. Remain unopinionated. 

The CSS Working Group doesn't encourage projects to use a certain naming convention for CSS, or way of organizing code. That remains completely up to each team to decide. What's 'best' really depends on the situation. This project also stays away from evangelizing such opinions. Use whatever naming conventions, code structure, content management system, build process, framework, etc that is best for you. Perhaps this starter code will be included inside of such a tool. It's designed to work with any of them.

3. Respect browser default styling.

Unlike CSS Reset, this project is not attempting to remove all default styling. Many developers prefer to remove all margins, all padding, make all headlines be normal text size. It feels good, perhaps, to wipe the slate clean and start from nothing. The downside of that approach is that then you are responsible for styling everything. If all default styling is removed from `pre` and definition lists, then you must remember to create custom styling for such elements, even if you aren't using them often. 

This project takes a different approach. Rather than placing the burden on the Author (the web developer) to remember to style _everything_, we are going to do what the user agent stylesheet does. This project respects a lot of the default UA styling, overriding what we think we can improve, leaving the rest. Read through the code of our project, and see if you agree. You can alwas fork or override this project as you build your own. 

4. Provide consistent form control styling.

The W3C Working Groups have long held that the styling of forms, form controls, scrollbars, etc are the job of each unique browser, to handle as the browser maker wishes. Many people believe that things like dropdown select lists are part of the computer operating system or browser software, and not part of a website. Compare how iOS handles a number input keyboard vs a Linux desktop browser, and you can see how this philsophy makes sense. 

Conversly, most stakeholders running web projects believe that the forms for a website should reflect the branding for that site. Especially on projects where great efforst have been made to design a brand carefully and apply it consistently across a wide range of materials -- the people running those projects insist the select dropdowns are styled to match the site. Having some kind of unstyled operating-system based form control feels unfinished and inconsistent. Attempting to style form controls is one of the more painful parts of any project. 

Normalize approaches this problem by applying styling to any such thing that can be styled, and creating a consistent look, no matter the browser. While the Normalize style likely does not match your brand, it does give you an easy place to rewrite or override such code, instead of being left to hunt down how / whether or not you can in fact style some part of a form or form control. 

We are taking the same approach as Normalize. We'll apply a consistent style to forms and form controls, where possible. Giving you a helpful start at customzing such elements for your project. 

5. Allow websites to not look the same in every browser.

Websites don't have to look the same in every browser. In fact, no matter what they do, they never will. The intention of this project is not to iron out every difference. We are letting many of those differences stay. 
