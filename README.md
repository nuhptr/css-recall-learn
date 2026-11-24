# CSS Recall Learn

Catatan dan latihan CSS berdasarkan video **[CSS Full Course Tutorial for Beginners – Part 1](https://www.youtube.com/watch?v=-G-zic_LS0A)** dari channel *Future Fullstack* (durasi ±11 jam 37 menit).

Proyek ini adalah lanjutan dari [`html-recall-learn`](../html-recall-learn). Course ini memakai proyek **Quill** yang sama, jadi HTML dari repo tersebut bisa dipakai lagi sebagai bahan untuk di-styling.

## Resource

- 📕 [Summary Cards](https://bit.ly/css-summary-cards)
- 🎥 [Presentation Slides](https://bit.ly/css-presentation-slides)
- 📋 [Quill starter HTML](https://bit.ly/quill-html-files)
- 🪶 [Quill completed HTML & CSS](https://bit.ly/quill-complete-html-css)
- ▶️ [Part 2](https://www.youtube.com/watch?v=1ra4yeyjFFc)

## Materi (Part 1)

### 1. Introduction → `app/01-introduction`
| Timestamp | Materi | Folder |
|---|---|---|
| 0:02:52 | Introduction to CSS: apa itu CSS, rule, selector, property, value | `introduction-to-css` |
| 0:17:37 | Including CSS: inline, internal (`<style>`), external (`<link>`) | `including-css` |

### 2. Text → `app/02-text`
| Timestamp | Materi | Folder |
|---|---|---|
| 0:32:05 | Text Styling: `font-weight`, `font-style`, `text-decoration`, `text-transform`, `text-align` | `text-styling` |
| 0:57:49 | Text Spacing: `line-height`, `letter-spacing`, `word-spacing`, `text-indent` | `text-spacing` |
| 1:16:39 | Text Size: `font-size` | `text-size` |
| 1:30:04 | Font: `font-family`, font stack, web font (Google Fonts) | `font` |
| 1:46:15 | Color: named, hex, `rgb()`, `hsl()`, alpha | `color` |
| 2:10:58 | Style Guide: menyusun palet warna & tipografi | `style-guide` |

### 3. Selectors → `app/03-selectors`
| Timestamp | Materi | Folder |
|---|---|---|
| 2:16:42 | Type Selector | `type-selector` |
| 2:21:20 | The Cascade: urutan & prioritas aturan | `cascade` |
| 2:27:32 | Grouping Selectors (`h1, h2 {}`) | `grouping-selectors` |
| 2:35:05 | Class & ID Selectors | `class-id-selectors` |
| 2:55:24 | Pseudo-classes: `:hover`, `:focus`, `:nth-child()`, dll. | `pseudo-classes` |
| 3:14:18 | Combinator: descendant, child `>`, sibling `+` `~` | `combinator-selectors` |
| 3:24:32 | Specificity | `specificity` |
| 3:35:06 | Inheritance: `inherit`, `initial`, `unset` | `inheritance` |
| 4:02:13 | Universal Selector `*` | `universal-selector` |
| 4:09:53 | Pseudo-elements: `::before`, `::after`, `::first-letter`, dll. | `pseudo-elements` |

### 4. Box Model → `app/04-box-model`
| Timestamp | Materi | Folder |
|---|---|---|
| 4:17:06 | Box Model Introduction: content, padding, border, margin | `introduction` |
| 4:22:55 | Background Color | `background-color` |
| 4:37:56 | Width & Height | `width-height` |
| 4:55:42 | Padding | `padding` |
| 5:13:22 | Border | `border` |
| 5:31:10 | Border Radius | `border-radius` |
| 5:41:04 | Box Sizing: `content-box` vs `border-box` | `box-sizing` |
| 5:55:51 | Margin, termasuk margin collapse & `auto` | `margin` |
| 6:18:41 | Display: `block`, `inline`, `inline-block`, `none` | `display` |
| 6:42:39 | CSS Reset | `css-reset` |
| 6:58:06 | Main Container | `main-container` |
| 7:09:43 | Max Width | `max-width` |
| 7:30:10 | Min Width | `min-width` |
| 7:41:09 | Max & Min Height | `max-min-height` |

### 5. Units → `app/05-units`
| Timestamp | Materi | Folder |
|---|---|---|
| 7:56:47 | Absolute vs Relative Units | `absolute-relative-units` |
| 8:03:06 | Percentages | `percentages` |
| 8:26:07 | `rem` & `em` | `rem-em` |
| 8:52:03 | `vw` & `vh` | `vw-vh` |

### 6. Functions → `app/06-functions`
| Timestamp | Materi | Folder |
|---|---|---|
| 9:02:15 | CSS Variables (`--var`, `var()`) | `css-variables` |
| 9:20:35 | CSS Calculations (`calc()`) | `css-calc` |

### 7. Flexbox → `app/07-flexbox`
| Timestamp | Materi | Folder |
|---|---|---|
| 9:31:15 | Introduction to Flexbox | `introduction` |
| 9:50:22 | Normal Flow vs Flexbox | `normal-flow-vs-flexbox` |
| 10:05:41 | `justify-content` | `justify-content` |
| 10:36:09 | `align-items` | `align-items` |
| 11:05:21 | `gap` | `gap` |
| 11:15:09 | Nested Flexbox | `nested-flexbox` |

## Materi berikutnya (Part 2, belum dibuat foldernya)

- **Flexbox (lanjutan):** centering, flex children, wrap
- **CSS Grid:** columns & rows, gap, alignment sel & container, grid items
- **Responsive Design:** media queries, breakpoints
- **Positioning:** `position`, `z-index` & stacking context, `transform`
- **Shadows & Transitions**
- **CSS Frameworks:** Bootstrap, Tailwind
