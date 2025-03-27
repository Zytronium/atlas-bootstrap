# Implement a Design with Bootstrap (Max's Version)
## AeroHobby RC Plane Shop

<img src="images/logo.webp" alt="AeroHobby RC Logo" width="240" height="240">


----

In this project, I have to create a website relating to a hobby of mine, using
Bootstrap. I can use minimal CSS, but it can't be structural (i.e., can't set
margins, but can change color). I must make at least 1–2 fully functional web
pages that utilize the wireframes provided with minimal instruction. This
project may be somewhat rushed, as I am falling behind on pace and starting to
get burnt out on coding.

For the hobby theme, I chose RC planes—more specifically, I am going to make
a shop website for RC planes and RC plane supplies.

**[You can view the web page online here](https://zytronium.github.io/atlas-bootstrap/)**

----

### ✅ Tasks checklist:
[//]: # ("​" comes before every number because otherwise, the
numbers will be formatted like "i, ii, iii, iv, etc." instead
of "1, 2, 3, 4, etc.". "​" is a zero-width space)
- [X] ​0. ReadMe
- [X] ​1. Header* (Come back to this to add proper links when ready)
- [X] ​2. Banner Section
- [X] ​3. Single Item Carousel
- [X] ​4. Multiple Item Carousel
- [X] ​5. Drop Down Menus
- [X] ​6. Section with an Aside
- [X] ​7. Free Section
- [X] ​8. Footer
- [X] ​9. Host to GitHub Pages


- [ ] Additional Sections
- [X] Final Tweaks


- [X] **Everything Done ✓**

----

# Tasks Sections Guide
[//]: # ("For each task, please include a guide in your ReadMe
          highlighting what section of your site should be graded. You dont
          need to have the sections in the order they are listed. You are also
          welcome to include more sections beyond what is listed!")

## 1. Header
The header contains the navbar at the top of every page. Everything in this task
is contained inside the `<header>` tag inside the body of all HTML files. The
styles for this task are in the top section of [styles.css](styles.css) under
the "Header Styles" comment.

The navbar has 5 nav items: Home, Shop, Categories, Contact, and Log In. The
Home link takes you to the Home page. The Shop link takes you to the Shop page.
The Categories button is a dropdown menu that takes you to several different
sections on the Shop page, and each section in that dropdown menu has another
dropdown menu for subsections. The Contact link takes you to the Contact section
of the Home page, where the user can find (fake) contact info for the company.
The Log In button is a dummy button that is not intended to work for this
project, but would if this were an actual shop. I mostly added it to give the
Categories dropdown menu some room on the right.

Each button/link has a hover and active color for both background color and text
color, though the text color change is less noticeable.

I spent WAY too much time on this one.

[//]: # (todo: Considder changing the dropdown for the "Planes" category. More info in the Dropdown task section.)


## 2. Banner Section
The banner section, between the navbar and the single item carousel and,
contains some promotional text and a call to action button that takes the
user to the shop page. The background is dimmed to make the text more readable,
and the background conatins an aerial photo of an RC jet flying over a snowy
field. This photo was taken by a member of a Discord server I'm in. At the
time of writing this, I'm trying to figure out who originally posted it and if
they'll allow me to use it in the final product. If I can't get permission,
I have a few others I can try. Image credit is shown in either the bottom left 
or bottom right corner, depending on if you are on mobile or desktop. On even
smaller screens, the credit text gets smaller.


## 3. Single Item Carousel
This is a single-item carousel that scrolls between the different main
shop categories. I planned to have the text display over a background image,
however, this still needs to have those separate, so instead, I have an image
on the side for each item. I thought it would look neat if it alternated 
between having the image on the left and on the right on desktop/tablet, so
that's what I did. On mobile, the image is on the bottom. Clicking the image
takes you to that category in the Shop page.


## 4. Multiple Item Carousel
The multiple item carousel on the Home page displays 8 popular products. 
Clicking on one of these should take you to that item's product page on an
external website that actually sells it. The carousel displays 4 items on
desktop, 2 on tablet, and 1 on mobile.

I also planed to fill the Shop page with multiple item carousels if there was time.


## 5. Drop Down Menus
I completed this one before I even realized it was a task. The drop down menus
are inside the nav bar. The "Categories" dropdown menu contains more dropdown
menus inside it. Each item in the "Categories" dropdown menu can be clicked to
go to that section, or hover over them to expand the dropdown menu of
subcategories.

For example, if you just want to look at planes, click or hover
on "Categories," then just click "Planes." However, if you're looking for a RTF
(Ready-to-Fly) kit specifically, hover over "Planes" and click "RTF
(Ready-to-Fly)." From there, it will take you to the Shop page and scroll to
the section you chose.

The mobile version has issues with the dropdown menus since you can't really
hover on mobile unless you connect a mouse (which is possible). Even so,
I've disabled context menus expanding on mobile due to issues that causes on
desktop windows small enough to trigger mobile CSS. Since the main categories
are also links, clicking on them to expand the subcategory dropdowns only takes
you to that category's section instead of expanding the dropdown. I will only
fix this issue if I have time, though I have an idea for how to fix it.

[//]: # (Note to self: the fix is to add an "All" subcategory for each category,
and then only show that subcategory on small screens. Then, disable the links
for the main categories on mobile.)

[//]: # (todo: Consider changing the dropdown for the "Planes" category. Change
          the first dropdown when hovering over "Planes" to contain "completion
          level," "skill level," and "type.")


## 6 **&** 7. Free Section with an Aside
This is the "RC Plane of the Month" section. On the primary section, it displays
the RC plane's name and a description of the plane and why it's the RC plane of
the month. Then, at the bottom of the primary section, there is a purchase
button that takes you to the product page on the HobbyTown website. 

The aside displays a more complete product name, an image of it, and some
product information like price, type, skill level, wingspan, etc. I tried to
make the aside take up 45% of the width on tablet and 33% on desktop, but it
wouldn't work.

If time permits, I will also create the Shop page, which will be filled with
multi-item carousels or just several large grids. Either way, products will be
sorted by category, and each category and subcategory will have a title for
that section. Clicking on any product will just take you to the product page
on an external website that actually sells it. (Probably HobbyTown since that's
where I got all the product images from)


## 8. Footer
The footer includes a moto for AeroHobby RC, some quick links, contact info,
and a copyright message. On mobile, these sections are aligned vertically, and
on desktop, horizontally.

----

## Initial Website Layout plan
###### Because I didn't have a whiteboard or paper with me to draw it out, so I put it here

### Home Page
**Nav Bar**  

**Banner section**  
Put something between the header navbar and the carousel. At the time of writing
this, I haven't decided what should go here yet.  
Ideas:
- Background image with quotes or a phrase about the company
- Scrolling background images of RC Planes taken "by our satisfied customers"

**Shop Categories Single-Item Carousel**  
A single-item carousel that scrolls through the different categories in the
Categories dropdown menu. (but not the subsections)

**RC Planes Multi-Item Carousel** *_Time permitting_  
A multi-item carousel that scrolls through some "popular" planes sold.

**Another Shop Items Multi-Item Carousel** *_Time permitting_  
A multi-item carousel that scrolls through some "popular" items sold
(other than plane kits).

**Footer**  
Include Contact info, copyright, etc.

### Shop Page
**Nav Bar**  

**Multi-item Carousels**  
Include a multi-item carousel for each subcategory of every product category.
For example, in the "Planes" section, include a multi-item carousel for RTF planes,
another for BNF planes, and so on.

**Footer**  
Include Contact info, copyright, etc.
