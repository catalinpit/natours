# natours
 Natours Project

[Live Preview](https://catalinpit.github.io/natours/)

*Taking notes while building the application from Jonas's tutorial => [Advanced CSS and SASS](https://udemy.com/course/advanced-css-and-sass).*

*The application might look different from the one from the tutorial. I am trying to change it as much as possible.*

# TABLE OF CONTENTS
- [natours](#natours)
- [TABLE OF CONTENTS](#table-of-contents)
- [THE THREE PILLARS TO WRITE GOOD HTML AND CSS](#the-three-pillars-to-write-good-html-and-css)
- [HOW CSS WORKS: A LOOK BEHIND THE SCENES](#how-css-works-a-look-behind-the-scenes)

# THE THREE PILLARS TO WRITE GOOD HTML AND CSS

**Responsive design**

* Fluid layouts
* Media queries
* Responsive images
* Correct units
* Desktop-first vs mobile-first

**Maintainable and scalable code**

* Clean
* Easy-to-understand
* Growth
* Reusable
* How to organize files
* How to name classes
* How to structure HTML

**Web performance**

* Less HTTP requests
* Less code
* Compress code
* Use a CSS preprocessor
* Less images
* Compress images

# HOW CSS WORKS: A LOOK BEHIND THE SCENES

**What happens to CSS when a webpage is loaded?**

Load HTML => Parse HTML => The browser builds the `Document Object Model (DOM)` (where the entire decoded HTML code is stored).

Parse HTML => Load CSS => Parse CSS => `CSS Object Model (CSSOM)`.

Parse CSS

* Resolve conflicting CSS declarations (cascade)
* Process final CSS values