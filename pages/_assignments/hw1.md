---
layout: assignment-two-column
title: "Make a fake portfolio website"
abbreviation: HW1
type: homework
due_date: 2022-09-12
ordering: 1
draft: 0
points: 16
---

<style>
    blockquote h2 {
        margin: auto !important;
        padding: 0px !important;
    }

    .frame {
        padding: 0;
    }

    .medium th:first-child, .medium td:first-child {
        width: 40px;
        max-width: 40px;
        min-width: 40px;
    }
</style>


## Hints (Updated 9/11 @12PM)
Several students contacted me about the "Contact" section and how to approach it. I decided to make a [video walkthrough](https://drive.google.com/file/d/1-I3NoIsFPK5jGVakLxjoWfp0Obj31K2A/view?usp=sharing) to help you with that one. If you want to use the debugging script I used in the video, just paste the following right before the close of the body tag:

```html
<script src="https://csci-185.github.io/fall2022/course-files/utilities/debug.js"></script>
<script>
    debug('#contact', 3); // first item is the selector; second is # of levels you want to highlight.
</script>
```


## Introduction
The goal of today's lab is to make a fake portfolio website. You will be given an `index.html` file, which controls the content. You will then style this content by making changes to the `styles.css` file that you are given. When you're done, your webpage should look exactly like the one shown in [this video](https://drive.google.com/file/d/1eLJVLW7AGQ_1EX6Hvqh_BVMAkPxKJZFX/view?usp=sharing). While this is mostly a CSS exercise, you are also welcome to change `index.html` to make things easier for you to style (optional, not required). Please download the starter files below to begin:

<a href="/fall2022/course-files/homework/hw01.zip" class="nu-button">Homework 1 Starter Files <i class="fas fa-download"></i></a>

## Your Tasks
In order to complete this assignment, please complete the 7 sets of tasks described below. Read the checklist carefully, to ensure that you receive full credit for this assignment.

1. [Navigation](#nav)
1. [Header](#header)
1. [About Me](#about)
1. [Projects](#projects)
1. [Contact](#contact)
1. [Footer](#footer)
1. [Publish to GitHub](#publish)

{:#nav}
### 1. Navigation
Style the `<nav></nav>` section so that it matches the style of the screenshot below. Specifically, you will:

{:.checkbox-list}
* Style the `<ul></ul>` so that it displays horizontally and aligned to the right, with the bullets removed.
* Ensure that the color of the links are white and that they do not have an underline. 
* Modify the link HTML so that when each link is clicked, the page scrolls down to the relevant section (see video).

<img class="large frame" src="/fall2022/assets/images/homework/hw01/01-header.png" />

{:#header}
### 2. Header
Style the `<header></header>` section so that it matches the style of the screenshot above. Specifically, you will:

{:.checkbox-list}
* Change the background color to a color that you like (but ensure that it's dark enough for the white text to be readable).
* Center the text and image.
* Style the image so that it's circular (hint: Google "border radius").
* Use a custom google font for the `<h1></h1>` tag, and change the color to white.

{:#about}
### 3. About Me
Style the `<section id="about"></section>` section so that it matches the style of the screenshot below. Specifically, you will:

{:.checkbox-list}
* Use a custom google font for the `<h2></h2>` tag (same font you used for the h1 tag).
* Use a simple font for the rest of your text tags (e.g., p, li, a, etc.) -- something that is well-suited for body copy.
* Ensure that the text has sufficient spacing from the sides of the screen and from the top and bottom, and that it is left-justified (see screenshot).

<img class="large frame" src="/fall2022/assets/images/homework/hw01/02-about.png" />


{:#projects}
### 4. Projects

Style the `<section id="projects"></section>` section so that it matches the style of the screenshot below. Specifically, you will:

{:.checkbox-list}
* Arrange your project "cards" into two columns.
* Ensure that there is adequate spacing between the cards (remember the principle of alignment).
* Change the background of the entire section to light gray.
* Ensure that the cards have sufficient spacing from the sides of the parent container.

<img class="large frame" src="/fall2022/assets/images/homework/hw01/03-projects.png" />

{:#contact}
### 5. Contact

Style the `<section id="contact"></section>` section so that it matches the style of the screenshot below. Specifically, you will:

{:.checkbox-list}
* Arrange the screen into two columns, where the left column displays the form and the right column displays the author's contact information.
* Arrange the form textboxes and button as shown in the screenshot.
* Ensure that the textboxes have a light gray background and some padding and marging (as shown in the screenshot).
* Ensure that the form and contact info have sufficient spacing from the sides of the parent container.

<img class="large frame" src="/fall2022/assets/images/homework/hw01/04-contact.png" />


{:#footer}
### 6. Footer
Style the `<footer></footer>` section so that it matches the style of the screenshot above, with center-aligned text and a light gray background color.

{:#publish}
### 7. Publish to GitHub

When you're done styling your fake portfolio website, you will:

{:.checkbox-list}
* Ensure that all of your folders and files are **lowercase** with **no spaces**.
* Ensure that your repository on GitHub is called **csci185-coursework** (and if it's not, rename it).
* Create a link to from your homepage (which you created during Tutorial 3) to the `index.html` you just made (which should be stored in the `homework/hw01` folder). Recall that your homepage is at the root of your `csci185` folder. 
* Commit and push all of your changes to GitHub (like we did in Tutorials 2-4).

Here is what my homepage looks like after I've published it, except for your HW1 will be a *completed* HW1 (versus the starter files):
* Webpage: [https://vanwars.github.io/csci185-coursework/](https://vanwars.github.io/csci185-coursework/)
* Code: [https://github.com/vanwars/csci185-coursework](https://github.com/vanwars/csci185-coursework)

## Rubric

{:.medium}
| | Task | Points | Description |
|--|--|--|--|
| 1. | Navigation | 2pts | [see requirements](#nav) |
| 2. | Header | 2pts | [see requirements](#header) |
| 3. | About Me | 1pts | [see requirements](#about) |
| 4. | Projects | 3pts | [see requirements](#projects) |
| 5. | Contact | 5pts | [see requirements](#contact) |
| 6. | Footer | 1pt | [see requirements](#footer) |
| 7. | Publish to GitHub | 2pts | [see requirements](#publish) |
|  | **Total** | **16pts** |  |


## What to Submit
**Please Read Carefully:** To submit Homework 1, please paste the following links into the Moodle under the Homework 1 submission section:

1. A link to your **homepage** (from Tutorial 3) on GitHub pages, which should link to your hw01 assignment (and previous tutorials and classwork you have done).
2. A link to your GitHub **code repository** (where your code files are stored).