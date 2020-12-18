# WireframsHTML

## Link To Tutorial

See the [Website Wireframing with HTML5 & CSS3]( https://www.udemy.com/course/website-wireframing-with-html5-css3/) on Udemy.

---

### Table of Contents

Brief TOC  here.

- [Description](#description)
- [Timetable](#timetable)
- [Long Comments](#long-comments)
- [Project Status](#project-status)
- [Tutorial Author Info](#author-info)

---

## Description

Essentially this is just a collection of notes about this short 3-hr course on building wireframes in HTML. I completely re-wrote the tutorial in BEM.

### Technologies

- HTML5
- CSS3

[Back To The Top](#wireframeshtml)

---

## Timetable

Time | Comments
-----|---------
12/13| Start fresh on project
09.08 | Create html and CSS structure with BEM
09.16 | Changing all px and % to vh and vw, all rgb to hex
09.31 | Fixed spacing files in this README file
09.57 | See comment [10.02 Working with divs inside a container...](#10.02)
10.32 | Instead of changing margins and padding to zero in the body, I used cssreset
10.33 | Commit 'Added CSSreset and containers inside header, footer, hero, organize, and get sections'.

[Back To The Top](#wireframeshtml)

---

## Long Comments

### 10.02

Working with divs inside a container and centering in vport

A couple of sections are divs inside of a section so it's difficult to use vport measurements to do this. Normally I would use margin: 0 auto; but that won't work in vport measurements. What seems to work is margin: 0 25%; (if the element is nested inside another element). However, you can't use 100vh for that container, you can use width: 100%

[Back To The Top](#wireframeshtml)

---

## Project Status

The current status of this project is in development.

[Back To The Top](#wireframeshtml)

---

## Author Info

- Geoff Blake on behalf of Stoneriver Learning - [TenTonOnline]( https://www.tentononline.com/)

[Back To The Top](#wireframeshtml)
