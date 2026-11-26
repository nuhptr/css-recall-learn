# CSS Recall Learn

![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Status](https://img.shields.io/badge/status-in%20progress-yellow)
![License](https://img.shields.io/badge/license-MIT-blue)

A structured, hands-on repository for revisiting CSS from first principles to modern layout techniques. Each lesson is organized as an isolated exercise folder that follows the learning sequence of the [CSS Full Course Tutorial for Beginners](https://www.youtube.com/watch?v=-G-zic_LS0A) by **Future Fullstack**.

This project is the companion to [`html-recall-learn`](https://github.com/nuhptr/html-recall-learn). Both courses build the same **Quill** website, so the HTML produced there serves as the foundation for the styling work here.

## Table of Contents

- [CSS Recall Learn](#css-recall-learn)
    - [Table of Contents](#table-of-contents)
    - [Course Overview](#course-overview)
    - [Learning Roadmap](#learning-roadmap)
    - [Curriculum](#curriculum)
        - [A. Introduction](#a-introduction)
        - [B. Text](#b-text)
        - [C. Selectors](#c-selectors)
        - [D. Box Model](#d-box-model)
        - [E. Units](#e-units)
        - [F. Functions](#f-functions)
        - [G. Flexbox](#g-flexbox)
        - [H. CSS Grid](#h-css-grid)
        - [I. Responsive Design](#i-responsive-design)
        - [J. Positioning](#j-positioning)
        - [K. Shadows & Transitions](#k-shadows--transitions)
        - [L. CSS Frameworks](#l-css-frameworks)
    - [Project Structure](#project-structure)
    - [Getting Started](#getting-started)
    - [Conventions](#conventions)
    - [Acknowledgements](#acknowledgements)
    - [License](#license)

## Course Overview

|                      |                                                                                                                                                       |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Course**           | CSS Full Course Tutorial for Beginners — [Part 1](https://www.youtube.com/watch?v=-G-zic_LS0A) & [Part 2](https://www.youtube.com/watch?v=1ra4yeyjFFc) |
| **Instructor**       | Future Fullstack                                                                                                                                      |
| **Duration**         | ~20 hours 10 minutes (~11h 37m Part 1 + ~8h 32m Part 2)                                                                                               |
| **Level**            | Beginner to intermediate                                                                                                                              |
| **Prerequisite**     | Basic HTML (see [`html-recall-learn`](https://github.com/nuhptr/html-recall-learn))                                                                   |
| **Practice project** | Quill: a multi-page marketing website                                                                                                                 |

## Learning Roadmap

| Module | Topic                                           | Lessons | Status      |
| :----: | ----------------------------------------------- | :-----: | ----------- |
|   A    | [Introduction](#a-introduction)                 |    2    | Not started |
|   B    | [Text](#b-text)                                 |    6    | Not started |
|   C    | [Selectors](#c-selectors)                       |   10    | Not started |
|   D    | [Box Model](#d-box-model)                       |   14    | Not started |
|   E    | [Units](#e-units)                               |    4    | Not started |
|   F    | [Functions](#f-functions)                       |    2    | Not started |
|   G    | [Flexbox](#g-flexbox)                           |    9    | Not started |
|   H    | [CSS Grid](#h-css-grid)                         |    6    | Not started |
|   I    | [Responsive Design](#i-responsive-design)       |    3    | Not started |
|   J    | [Positioning](#j-positioning)                   |    3    | Not started |
|   K    | [Shadows & Transitions](#k-shadows--transitions) |    2    | Not started |
|   L    | [CSS Frameworks](#l-css-frameworks)             |    3    | Not started |

**Status legend:** `Not started` · `In progress` · `Complete`

## Curriculum

### A. Introduction

How CSS works and how it is applied to an HTML document. Directory: [`app/applying-css`](app/applying-css)

| Lesson              | Key concepts                               | Folder                                                        |
| ------------------- | ------------------------------------------ | ------------------------------------------------------------- |
| Introduction to CSS | Rules, selectors, properties, and values   | [`introduction-to-css`](app/applying-css/introduction-to-css) |
| Including CSS       | Inline, internal, and external stylesheets | [`including-css`](app/applying-css/including-css)             |

### B. Text

Typography fundamentals for readable, consistent content. Directory: [`app/formatting-text`](app/formatting-text)

| Lesson       | Key concepts                                                                   | Folder                                             |
| ------------ | ------------------------------------------------------------------------------ | -------------------------------------------------- |
| Text Styling | `font-weight`, `font-style`, `text-decoration`, `text-transform`, `text-align` | [`text-styling`](app/formatting-text/text-styling) |
| Text Spacing | `line-height`, `letter-spacing`, `word-spacing`, `text-indent`                 | [`text-spacing`](app/formatting-text/text-spacing) |
| Text Size    | `font-size` and type scale                                                     | [`text-size`](app/formatting-text/text-size)       |
| Font         | `font-family`, font stacks, and web fonts                                      | [`font`](app/formatting-text/font)                 |
| Color        | Named colors, hex, `rgb()`, `hsl()`, and alpha transparency                    | [`color`](app/formatting-text/color)               |
| Style Guide  | Defining a consistent color palette and type system                            | [`style-guide`](app/formatting-text/style-guide)   |

### C. Selectors

Targeting elements precisely and understanding how conflicting rules resolve. Directory: [`app/handling-selectors`](app/handling-selectors)

| Lesson                 | Key concepts                                                | Folder                                                                |
| ---------------------- | ----------------------------------------------------------- | --------------------------------------------------------------------- |
| Type Selector          | Selecting elements by tag name                              | [`type-selector`](app/handling-selectors/type-selector)               |
| The Cascade            | Source order and rule precedence                            | [`cascade`](app/handling-selectors/cascade)                           |
| Grouping Selectors     | Sharing declarations across selectors                       | [`grouping-selectors`](app/handling-selectors/grouping-selectors)     |
| Class & ID Selectors   | Reusable classes versus unique IDs                          | [`class-id-selectors`](app/handling-selectors/class-id-selectors)     |
| Pseudo-classes         | `:hover`, `:focus`, `:nth-child()`, and state-based styling | [`pseudo-classes`](app/handling-selectors/pseudo-classes)             |
| Combinator Selectors   | Descendant, child (`>`), and sibling (`+`, `~`) combinators | [`combinator-selectors`](app/handling-selectors/combinator-selectors) |
| Specificity            | Calculating selector weight                                 | [`specificity`](app/handling-selectors/specificity)                   |
| CSS Inheritance        | Inherited properties, `inherit`, `initial`, and `unset`     | [`inheritance`](app/handling-selectors/inheritance)                   |
| The Universal Selector | Using `*` effectively                                       | [`universal-selector`](app/handling-selectors/universal-selector)     |
| Pseudo-elements        | `::before`, `::after`, `::first-letter`, and more           | [`pseudo-elements`](app/handling-selectors/pseudo-elements)           |

### D. Box Model

Sizing, spacing, and layout behavior of every element on the page. Directory: [`app/learning-the-box-model`](app/learning-the-box-model)

| Lesson                   | Key concepts                                     | Folder                                                             |
| ------------------------ | ------------------------------------------------ | ------------------------------------------------------------------ |
| Box Model Introduction   | Content, padding, border, and margin             | [`introduction`](app/learning-the-box-model/introduction)         |
| Background Color         | Painting the element box                         | [`background-color`](app/learning-the-box-model/background-color) |
| Width & Height           | Explicit element dimensions                      | [`width-height`](app/learning-the-box-model/width-height)         |
| Padding                  | Inner spacing                                    | [`padding`](app/learning-the-box-model/padding)                   |
| Border                   | Border width, style, and color                   | [`border`](app/learning-the-box-model/border)                     |
| Border Radius            | Rounded corners and circles                      | [`border-radius`](app/learning-the-box-model/border-radius)       |
| Box Sizing               | `content-box` versus `border-box`                | [`box-sizing`](app/learning-the-box-model/box-sizing)             |
| Margin                   | Outer spacing, auto margins, and margin collapse | [`margin`](app/learning-the-box-model/margin)                     |
| Display                  | `block`, `inline`, `inline-block`, and `none`    | [`display`](app/learning-the-box-model/display)                   |
| CSS Reset                | Normalizing browser default styles               | [`css-reset`](app/learning-the-box-model/css-reset)               |
| Main Container           | Building a centered page wrapper                 | [`main-container`](app/learning-the-box-model/main-container)     |
| Maximum Width            | Constraining content width with `max-width`      | [`max-width`](app/learning-the-box-model/max-width)               |
| Minimum Width            | Preventing elements from shrinking too far       | [`min-width`](app/learning-the-box-model/min-width)               |
| Maximum & Minimum Height | Controlling vertical size limits                 | [`max-min-height`](app/learning-the-box-model/max-min-height)     |

### E. Units

Choosing the right unit for scalable, accessible designs. Directory: [`app/measuring-with-units`](app/measuring-with-units)

| Lesson                    | Key concepts                             | Folder                                                                          |
| ------------------------- | ---------------------------------------- | ------------------------------------------------------------------------------- |
| Absolute & Relative Units | `px` versus relative units               | [`absolute-relative-units`](app/measuring-with-units/absolute-relative-units) |
| Percentages               | Sizing relative to the parent            | [`percentages`](app/measuring-with-units/percentages)                         |
| rems & ems                | Root-relative and parent-relative sizing | [`rem-em`](app/measuring-with-units/rem-em)                                   |
| vw & vh                   | Viewport-relative sizing                 | [`vw-vh`](app/measuring-with-units/vw-vh)                                     |

### F. Functions

Writing maintainable, dynamic CSS values. Directory: [`app/native-css-functions`](app/native-css-functions)

| Lesson           | Key concepts                                | Folder                                                      |
| ---------------- | ------------------------------------------- | ----------------------------------------------------------- |
| CSS Variables    | Custom properties with `--name` and `var()` | [`css-variables`](app/native-css-functions/css-variables) |
| CSS Calculations | Mixing units with `calc()`                  | [`css-calc`](app/native-css-functions/css-calc)           |

### G. Flexbox

One-dimensional layout for aligning, distributing, sizing, and wrapping elements. Directory: [`app/organizing-with-flexbox`](app/organizing-with-flexbox)

| Lesson                      | Key concepts                                         | Folder                                                                                           |
| --------------------------- | ---------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| Introduction to Flexbox     | Flex containers and flex items                       | [`introduction`](app/organizing-with-flexbox/introduction)                                       |
| Normal Flow vs. Flexbox     | How flex changes default layout                      | [`normal-flow-vs-flexbox`](app/organizing-with-flexbox/normal-flow-vs-flexbox)                   |
| Justify Content             | Main-axis alignment                                  | [`justify-content`](app/organizing-with-flexbox/justify-content)                                 |
| Align Items                 | Cross-axis alignment                                 | [`align-items`](app/organizing-with-flexbox/align-items)                                         |
| Gap                         | Spacing between flex items                           | [`gap`](app/organizing-with-flexbox/gap)                                                         |
| Nested Flexbox              | Composing layouts with nested flex containers        | [`nested-flexbox`](app/organizing-with-flexbox/nested-flexbox)                                   |
| Centering                   | Horizontal and vertical centering with Flexbox       | [`centering`](app/organizing-with-flexbox/centering)                                             |
| Flex Children               | `flex-grow`, `flex-shrink`, `flex-basis`, and `flex` | [`flex-children`](app/organizing-with-flexbox/flex-children)                                     |
| Flex Wrap and Align Content | `flex-wrap` and multi-line cross-axis alignment      | [`flex-wrap-and-align-content`](app/organizing-with-flexbox/flex-wrap-and-align-content)         |

### H. CSS Grid

Two-dimensional layout system for rows, columns, and complex page grids. Directory: [`app/page-grid-layouts`](app/page-grid-layouts)

| Lesson                   | Key concepts                                      | Folder                                                                   |
| ------------------------ | ------------------------------------------------- | ------------------------------------------------------------------------ |
| Introduction to Grid     | Grid containers, tracks, and 2D layouts           | [`introduction`](app/page-grid-layouts/introduction)                     |
| Grid Columns and Rows    | `grid-template-columns`, `grid-template-rows`, `fr` | [`grid-columns-and-rows`](app/page-grid-layouts/grid-columns-and-rows) |
| Grid Gap                 | `gap`, `row-gap`, and `column-gap`                | [`grid-gap`](app/page-grid-layouts/grid-gap)                             |
| Grid Cell Alignment      | `justify-items` and `align-items`                 | [`grid-cell-alignment`](app/page-grid-layouts/grid-cell-alignment)       |
| Grid Container Alignment | `justify-content` and `align-content`             | [`grid-container-alignment`](app/page-grid-layouts/grid-container-alignment) |
| Grid Items               | Spanning tracks with `grid-column` and `grid-row` | [`grid-items`](app/page-grid-layouts/grid-items)                         |

### I. Responsive Design

Adapting layouts cleanly across screen sizes and device pixel densities. Directory: [`app/responsive-design`](app/responsive-design)

| Lesson                        | Key concepts                                   | Folder                                                                               |
| ----------------------------- | ---------------------------------------------- | ------------------------------------------------------------------------------------ |
| Introduction to Media Queries | `@media` rules and responsive styling          | [`introduction-to-media-queries`](app/responsive-design/introduction-to-media-queries) |
| Breakpoints                   | Mobile-first and desktop-first breakpoints     | [`breakpoints`](app/responsive-design/breakpoints)                                   |
| CSS and Physics Pixels        | Device pixel ratio, viewport meta, and scaling | [`css-and-physics-pixels`](app/responsive-design/css-and-physics-pixels)             |

### J. Positioning

Controlling document flow, stacking layers, and 2D/3D element transforms. Directory: [`app/stacking-and-positioning`](app/stacking-and-positioning)

| Lesson                       | Key concepts                                        | Folder                                                                               |
| ---------------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------ |
| Positioning                  | `static`, `relative`, `absolute`, `fixed`, `sticky` | [`positioning`](app/stacking-and-positioning/positioning)                            |
| Z-index and Stacking Context | Layering elements with `z-index`                    | [`z-index-and-stacking-context`](app/stacking-and-positioning/z-index-and-stacking-context) |
| Transform                    | `translate`, `scale`, `rotate`, and `skew`          | [`transform`](app/stacking-and-positioning/transform)                                |

### K. Shadows & Transitions

Adding depth, elevation, and smooth state changes. Directory: [`app/transitions-and-shadows`](app/transitions-and-shadows)

| Lesson      | Key concepts                                            | Folder                                                    |
| ----------- | ------------------------------------------------------- | --------------------------------------------------------- |
| Shadows     | `box-shadow` and `text-shadow`                          | [`shadows`](app/transitions-and-shadows/shadows)          |
| Transitions | `transition-property`, duration, timing-function, delay | [`transitions`](app/transitions-and-shadows/transitions)  |

### L. CSS Frameworks

Accelerating UI development with component-based and utility-first frameworks. Directory: [`app/using-css-frameworks`](app/using-css-frameworks)

| Lesson                         | Key concepts                             | Folder                                                        |
| ------------------------------ | ---------------------------------------- | ------------------------------------------------------------- |
| Introduction to CSS Frameworks | Pros, cons, and choosing a CSS framework | [`introduction`](app/using-css-frameworks/introduction)       |
| Bootstrap                      | Grid system and prebuilt UI components   | [`bootstrap`](app/using-css-frameworks/bootstrap)             |
| Tailwind CSS                   | Utility-first styling workflow           | [`tailwind-css`](app/using-css-frameworks/tailwind-css)       |

## Project Structure

```text
css-recall-learn/
├── app/
│   ├── applying-css/              # How CSS is written and applied
│   ├── formatting-text/           # Typography, color, and style guide
│   ├── handling-selectors/        # Selectors, cascade, specificity, inheritance
│   ├── learning-the-box-model/    # Box model, sizing, spacing, display
│   ├── measuring-with-units/      # Absolute, relative, and viewport units
│   ├── native-css-functions/      # Custom properties and calc()
│   ├── organizing-with-flexbox/   # Flexbox layout, alignment, and wrapping
│   ├── page-grid-layouts/         # CSS Grid tracks, gap, alignment, items
│   ├── responsive-design/         # Media queries, breakpoints, pixels
│   ├── stacking-and-positioning/  # Positioning, z-index, transform
│   ├── transitions-and-shadows/   # Box/text shadows and transitions
│   └── using-css-frameworks/      # Bootstrap and Tailwind CSS
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

## Conventions

- **Module folders** use descriptive, prefix-free names chosen so that their natural alphabetical order matches the learning sequence.
- **Lesson folders** use lowercase kebab-case names that mirror the chapter titles.
- **Lesson contents** typically include an `index.html`, a `style.css`, and any reference screenshots for that lesson.
- **Commits** follow [Conventional Commits v1.0.0](https://www.conventionalcommits.org/en/v1.0.0/).

## Acknowledgements

Course content and the Quill design are by [Future Fullstack](https://www.futurefullstack.com/). This repository contains personal study notes and exercises only.

## License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for details.
