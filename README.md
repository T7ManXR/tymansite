# Personal Portfolio Site with Bootstrap
My Personal Portfolio website is a single index.html and styles.css page, condensing the
original five required pages into one. This is designed to reduce duplicate elements,
such as having one navigation bar and footer, and can help lower the size of HTML and
CSS files. Instead of loading a new page, the navigation items will jump to CSS IDs
linked to diQerent sections, simplifying the programming process for setting up mobile-
responsive interfaces.

[Click here to access site](www.tymansite.ca).

## Bootstrap Breakpoints for Mobile Devices
In my HTML file, I included 43 lg (Screen size ≥ 992px), 14 md (Screen size ≥ 768px), and
13 sm (Screen size ≥ 576px) bootstrap breakpoint shorthands to accommodate all
responsive website sizing from 576px until max width. To start, “d-none d-sm-block”
hides elements on screens below md, which is applied to carousel caption containers.
Next, “col-sm-8” allows the hero image to fit 8 instead of 12 columns wide at the sm
breakpoint. The “row-cols-sm-2” for two card groups under the gallery is to have two
cards per row at sm or above and only one card below sm. Lastly, “col-sm-3” and “col-
sm-6” applied to the first grid under resume ensure text within the grids does not
overflow on every breakpoint, as below sm will be single rows at full viewport width.
## Usability Principles
Web usability principles referenced for my professional portfolio site include
availability, clarity, recognition, credibility, and relevance (99 Designs Team, 2021).
Firstly, the webpage is designed for devices without overflow issues from 576 pixels and
above until the container-fluid width at 1400 pixels. Beyond this width, all element sizes
will be constant, while only the left and right paddings will expand. For clarity, the site is
intended for anyone wishing to have academic, career, or social connections with me.
Afterward, a one-page site aims to improve recognition through a sticky navbar, navbar
items with ID selectors, and a fixed order of sections. Adding tooltips further increases
the eQiciency of user understanding, while a robust resume with blogs as scholarly
articles boost site credibility. To end, my portfolio site is relevant to all target audiences.
## WCAG 2.0 Accessibility Principles
1. Perceivable: This website is carefully designed for all users with a wide range of
visibility needs through color contrast tests between foreground and respective
backgrounds. Connecting the color palette, black text is always placed on yellow, light
green, and light blue backgrounds, while other colored texts are matched with desirable
contrast backgrounds. All necessary elements are visible and annotated either by
default or after the mouse cursor hovers on the desktop version, where tooltips and
color animations further inform the user before an action. No content overflows across
all breakpoints, at least from sm, as 576 pixels and above tested on many devices.
2. Operable: All navbar items link to corresponding sections, while some buttons link to
my external sites, including cloud files, social media, and my online store. Disabled
elements typically labeled as under development or coming soon are not present, and
all animations on my portfolio operate as expected.
3. Understandable: All texts explain the intended result of each HTML element on my site.
As the destinations of these elements are explained, buttons and hyperlinks open
external sites. The site is also not text-heavy, and its contents are creatively written to
increase others' interest in social, career, or academic networking.
4. Robust: My portfolio site is compatible with any device beyond the sm breakpoint
without overflow. ARIA labels are also included to work with the system's built-in screen
readers. These labels are included on all navbar and footer elements, images (from the
alt class), buttons, and the contact form. Selecting any other element on the site will
trigger the screen reader. In the form, all placeholder text will be spoken.
