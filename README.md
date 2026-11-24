# CSS Recall Learn

![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Status](https://img.shields.io/badge/status-in%20progress-yellow)
![License](https://img.shields.io/badge/license-MIT-blue)

A structured, hands-on repository for revisiting CSS from first principles to modern layout techniques. Each lesson is organized as an isolated exercise folder that follows the learning sequence of the [CSS Full Course Tutorial for Beginners](https://www.youtube.com/watch?v=-G-zic_LS0A) by **Future Fullstack**.

This project is the companion to [`html-recall-learn`](https://github.com/nuhptr/html-recall-learn). Both courses build the same **Quill** website, so the HTML produced there serves as the foundation for the styling work here.

## Table of Contents

- [Course Overview](#course-overview)
- [Learning Roadmap](#learning-roadmap)
- [Curriculum](#curriculum)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Conventions](#conventions)
- [Resources](#resources)
- [License](#license)

## Course Overview

| | |
| --- | --- |
| **Course** | [CSS Full Course Tutorial for Beginners – Part 1](https://www.youtube.com/watch?v=-G-zic_LS0A) |
| **Instructor** | Future Fullstack |
| **Duration** | ~11 hours 37 minutes |
| **Level** | Beginner to intermediate |
| **Prerequisite** | Basic HTML (see [`html-recall-learn`](https://github.com/nuhptr/html-recall-learn)) |
| **Practice project** | Quill: a multi-page marketing website |

## Learning Roadmap

| Module | Topic | Lessons | Status |
| :---: | --- | :---: | --- |
| A | [Introduction](#a-introduction) | 2 | Not started |
| B | [Text](#b-text) | 6 | Not started |
| C | [Selectors](#c-selectors) | 10 | Not started |
| D | [Box Model](#d-box-model) | 14 | Not started |
| E | [Units](#e-units) | 4 | Not started |
| F | [Functions](#f-functions) | 2 | Not started |
| G | [Flexbox](#g-flexbox) | 6 | Not started |

**Status legend:** `Not started` · `In progress` · `Complete`

## Curriculum

Every timestamp links directly to the corresponding chapter in the video.

### A. Introduction

How CSS works and how it is applied to an HTML document. Directory: [`app/a-introduction`](app/a-introduction)

| Timestamp | Lesson | Key concepts | Folder |
| --- | --- | --- | --- |
| [0:02:52](https://www.youtube.com/watch?v=-G-zic_LS0A&t=172s) | Introduction to CSS | Rules, selectors, properties, and values | [`introduction-to-css`](app/a-introduction/introduction-to-css) |
| [0:17:37](https://www.youtube.com/watch?v=-G-zic_LS0A&t=1057s) | Including CSS | Inline, internal, and external stylesheets | [`including-css`](app/a-introduction/including-css) |

### B. Text

Typography fundamentals for readable, consistent content. Directory: [`app/b-text`](app/b-text)

| Timestamp | Lesson | Key concepts | Folder |
| --- | --- | --- | --- |
| [0:32:05](https://www.youtube.com/watch?v=-G-zic_LS0A&t=1925s) | Text Styling | `font-weight`, `font-style`, `text-decoration`, `text-transform`, `text-align` | [`text-styling`](app/b-text/text-styling) |
| [0:57:49](https://www.youtube.com/watch?v=-G-zic_LS0A&t=3469s) | Text Spacing | `line-height`, `letter-spacing`, `word-spacing`, `text-indent` | [`text-spacing`](app/b-text/text-spacing) |
| [1:16:39](https://www.youtube.com/watch?v=-G-zic_LS0A&t=4599s) | Text Size | `font-size` and type scale | [`text-size`](app/b-text/text-size) |
| [1:30:04](https://www.youtube.com/watch?v=-G-zic_LS0A&t=5404s) | Font | `font-family`, font stacks, and web fonts | [`font`](app/b-text/font) |
| [1:46:15](https://www.youtube.com/watch?v=-G-zic_LS0A&t=6375s) | Color | Named colors, hex, `rgb()`, `hsl()`, and alpha transparency | [`color`](app/b-text/color) |
| [2:10:58](https://www.youtube.com/watch?v=-G-zic_LS0A&t=7858s) | Style Guide | Defining a consistent color palette and type system | [`style-guide`](app/b-text/style-guide) |

### C. Selectors

Targeting elements precisely and understanding how conflicting rules resolve. Directory: [`app/c-selectors`](app/c-selectors)

| Timestamp | Lesson | Key concepts | Folder |
| --- | --- | --- | --- |
| [2:16:42](https://www.youtube.com/watch?v=-G-zic_LS0A&t=8202s) | Type Selector | Selecting elements by tag name | [`type-selector`](app/c-selectors/type-selector) |
| [2:21:20](https://www.youtube.com/watch?v=-G-zic_LS0A&t=8480s) | The Cascade | Source order and rule precedence | [`cascade`](app/c-selectors/cascade) |
| [2:27:32](https://www.youtube.com/watch?v=-G-zic_LS0A&t=8852s) | Grouping Selectors | Sharing declarations across selectors | [`grouping-selectors`](app/c-selectors/grouping-selectors) |
| [2:35:05](https://www.youtube.com/watch?v=-G-zic_LS0A&t=9305s) | Class & ID Selectors | Reusable classes versus unique IDs | [`class-id-selectors`](app/c-selectors/class-id-selectors) |
| [2:55:24](https://www.youtube.com/watch?v=-G-zic_LS0A&t=10524s) | Pseudo-classes | `:hover`, `:focus`, `:nth-child()`, and state-based styling | [`pseudo-classes`](app/c-selectors/pseudo-classes) |
| [3:14:18](https://www.youtube.com/watch?v=-G-zic_LS0A&t=11658s) | Combinator Selectors | Descendant, child (`>`), and sibling (`+`, `~`) combinators | [`combinator-selectors`](app/c-selectors/combinator-selectors) |
| [3:24:32](https://www.youtube.com/watch?v=-G-zic_LS0A&t=12272s) | Specificity | Calculating selector weight | [`specificity`](app/c-selectors/specificity) |
| [3:35:06](https://www.youtube.com/watch?v=-G-zic_LS0A&t=12906s) | CSS Inheritance | Inherited properties, `inherit`, `initial`, and `unset` | [`inheritance`](app/c-selectors/inheritance) |
| [4:02:13](https://www.youtube.com/watch?v=-G-zic_LS0A&t=14533s) | The Universal Selector | Using `*` effectively | [`universal-selector`](app/c-selectors/universal-selector) |
| [4:09:53](https://www.youtube.com/watch?v=-G-zic_LS0A&t=14993s) | Pseudo-elements | `::before`, `::after`, `::first-letter`, and more | [`pseudo-elements`](app/c-selectors/pseudo-elements) |

### D. Box Model

Sizing, spacing, and layout behavior of every element on the page. Directory: [`app/d-box-model`](app/d-box-model)

| Timestamp | Lesson | Key concepts | Folder |
| --- | --- | --- | --- |
| [4:17:06](https://www.youtube.com/watch?v=-G-zic_LS0A&t=15426s) | Box Model Introduction | Content, padding, border, and margin | [`introduction`](app/d-box-model/introduction) |
| [4:22:55](https://www.youtube.com/watch?v=-G-zic_LS0A&t=15775s) | Background Color | Painting the element box | [`background-color`](app/d-box-model/background-color) |
| [4:37:56](https://www.youtube.com/watch?v=-G-zic_LS0A&t=16676s) | Width & Height | Explicit element dimensions | [`width-height`](app/d-box-model/width-height) |
| [4:55:42](https://www.youtube.com/watch?v=-G-zic_LS0A&t=17742s) | Padding | Inner spacing | [`padding`](app/d-box-model/padding) |
| [5:13:22](https://www.youtube.com/watch?v=-G-zic_LS0A&t=18802s) | Border | Border width, style, and color | [`border`](app/d-box-model/border) |
| [5:31:10](https://www.youtube.com/watch?v=-G-zic_LS0A&t=19870s) | Border Radius | Rounded corners and circles | [`border-radius`](app/d-box-model/border-radius) |
| [5:41:04](https://www.youtube.com/watch?v=-G-zic_LS0A&t=20464s) | Box Sizing | `content-box` versus `border-box` | [`box-sizing`](app/d-box-model/box-sizing) |
| [5:55:51](https://www.youtube.com/watch?v=-G-zic_LS0A&t=21351s) | Margin | Outer spacing, auto margins, and margin collapse | [`margin`](app/d-box-model/margin) |
| [6:18:41](https://www.youtube.com/watch?v=-G-zic_LS0A&t=22721s) | Display | `block`, `inline`, `inline-block`, and `none` | [`display`](app/d-box-model/display) |
| [6:42:39](https://www.youtube.com/watch?v=-G-zic_LS0A&t=24159s) | CSS Reset | Normalizing browser default styles | [`css-reset`](app/d-box-model/css-reset) |
| [6:58:06](https://www.youtube.com/watch?v=-G-zic_LS0A&t=25086s) | Main Container | Building a centered page wrapper | [`main-container`](app/d-box-model/main-container) |
| [7:09:43](https://www.youtube.com/watch?v=-G-zic_LS0A&t=25783s) | Maximum Width | Constraining content width with `max-width` | [`max-width`](app/d-box-model/max-width) |
| [7:30:10](https://www.youtube.com/watch?v=-G-zic_LS0A&t=27010s) | Minimum Width | Preventing elements from shrinking too far | [`min-width`](app/d-box-model/min-width) |
| [7:41:09](https://www.youtube.com/watch?v=-G-zic_LS0A&t=27669s) | Maximum & Minimum Height | Controlling vertical size limits | [`max-min-height`](app/d-box-model/max-min-height) |

### E. Units

Choosing the right unit for scalable, accessible designs. Directory: [`app/e-units`](app/e-units)

| Timestamp | Lesson | Key concepts | Folder |
| --- | --- | --- | --- |
| [7:56:47](https://www.youtube.com/watch?v=-G-zic_LS0A&t=28607s) | Absolute & Relative Units | `px` versus relative units | [`absolute-relative-units`](app/e-units/absolute-relative-units) |
| [8:03:06](https://www.youtube.com/watch?v=-G-zic_LS0A&t=28986s) | Percentages | Sizing relative to the parent | [`percentages`](app/e-units/percentages) |
| [8:26:07](https://www.youtube.com/watch?v=-G-zic_LS0A&t=30367s) | rems & ems | Root-relative and parent-relative sizing | [`rem-em`](app/e-units/rem-em) |
| [8:52:03](https://www.youtube.com/watch?v=-G-zic_LS0A&t=31923s) | vw & vh | Viewport-relative sizing | [`vw-vh`](app/e-units/vw-vh) |

### F. Functions

Writing maintainable, dynamic CSS values. Directory: [`app/f-functions`](app/f-functions)

| Timestamp | Lesson | Key concepts | Folder |
| --- | --- | --- | --- |
| [9:02:15](https://www.youtube.com/watch?v=-G-zic_LS0A&t=32535s) | CSS Variables | Custom properties with `--name` and `var()` | [`css-variables`](app/f-functions/css-variables) |
| [9:20:35](https://www.youtube.com/watch?v=-G-zic_LS0A&t=33635s) | CSS Calculations | Mixing units with `calc()` | [`css-calc`](app/f-functions/css-calc) |

### G. Flexbox

One-dimensional layout for aligning and distributing elements. Directory: [`app/g-flexbox`](app/g-flexbox)

| Timestamp | Lesson | Key concepts | Folder |
| --- | --- | --- | --- |
| [9:31:15](https://www.youtube.com/watch?v=-G-zic_LS0A&t=34275s) | Introduction to Flexbox | Flex containers and flex items | [`introduction`](app/g-flexbox/introduction) |
| [9:50:22](https://www.youtube.com/watch?v=-G-zic_LS0A&t=35422s) | Normal Flow vs. Flexbox | How flex changes default layout | [`normal-flow-vs-flexbox`](app/g-flexbox/normal-flow-vs-flexbox) |
| [10:05:41](https://www.youtube.com/watch?v=-G-zic_LS0A&t=36341s) | Justify Content | Main-axis alignment | [`justify-content`](app/g-flexbox/justify-content) |
| [10:36:09](https://www.youtube.com/watch?v=-G-zic_LS0A&t=38169s) | Align Items | Cross-axis alignment | [`align-items`](app/g-flexbox/align-items) |
| [11:05:21](https://www.youtube.com/watch?v=-G-zic_LS0A&t=39921s) | Gap | Spacing between flex items | [`gap`](app/g-flexbox/gap) |
| [11:15:09](https://www.youtube.com/watch?v=-G-zic_LS0A&t=40509s) | Nested Flexbox | Composing layouts with nested flex containers | [`nested-flexbox`](app/g-flexbox/nested-flexbox) |

### Upcoming: Part 2

The following modules are covered in [Part 2](https://www.youtube.com/watch?v=1ra4yeyjFFc) and will be added once Part 1 is complete:

| Topic | Lessons |
| --- | --- |
| Flexbox (continued) | Centering, flex children, wrapping |
| CSS Grid | Columns and rows, gap, cell alignment, container alignment, grid items |
| Responsive Design | Media queries, breakpoints, media queries and pixels |
| Positioning | `position`, `z-index` and stacking context, `transform` |
| Shadows & Transitions | `box-shadow`, `text-shadow`, transitions |
| CSS Frameworks | Bootstrap, Tailwind CSS |

## Project Structure

```text
css-recall-learn/
├── app/
│   ├── a-introduction/   # How CSS is written and applied
│   ├── b-text/           # Typography, color, and style guide
│   ├── c-selectors/      # Selectors, cascade, specificity, inheritance
│   ├── d-box-model/      # Box model, sizing, spacing, display
│   ├── e-units/          # Absolute, relative, and viewport units
│   ├── f-functions/      # Custom properties and calc()
│   └── g-flexbox/        # Flexbox layout fundamentals
├── LICENSE
└── README.md
```

## Getting Started

No build tooling is required. Every exercise is plain HTML and CSS.

1. Clone the repository:

   ```bash
   git clone git@github.com:nuhptr/css-recall-learn.git
   cd css-recall-learn
   ```

2. Open any lesson's `index.html` directly in a browser, or serve it with a live-reload extension such as [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for VS Code.

3. Download the [Quill starter HTML](https://bit.ly/quill-html-files) if you want the same base markup used throughout the course.

## Conventions

- **Module folders** use an alphabetical prefix (`a-`, `b-`, `c-` …) so they sort in learning order.
- **Lesson folders** use lowercase kebab-case names that mirror the chapter titles.
- **Lesson contents** typically include an `index.html`, a `style.css`, and any reference screenshots for that lesson.
- **Commits** follow [Conventional Commits v1.0.0](https://www.conventionalcommits.org/en/v1.0.0/).

## Resources

| Resource | Link |
| --- | --- |
| Course video, Part 1 | [YouTube](https://www.youtube.com/watch?v=-G-zic_LS0A) |
| Course video, Part 2 | [YouTube](https://www.youtube.com/watch?v=1ra4yeyjFFc) |
| Summary cards | [Download](https://bit.ly/css-summary-cards) |
| Presentation slides | [Download](https://bit.ly/css-presentation-slides) |
| Quill starter HTML | [Download](https://bit.ly/quill-html-files) |
| Quill completed HTML & CSS | [Download](https://bit.ly/quill-complete-html-css) |
| MDN CSS reference | [developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Web/CSS) |

## Acknowledgements

Course content and the Quill design are by [Future Fullstack](https://www.futurefullstack.com/). This repository contains personal study notes and exercises only.

## License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for details.
