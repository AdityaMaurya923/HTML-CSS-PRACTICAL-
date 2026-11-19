# Assignment 15: Responsive Pages with Media Queries

**Name:** Aditya Kumar Maurya
**Roll No:** 2510303042

## 1. Experiment Title

Responsive Pages with Media Queries using HTML and CSS.

## 2. Aim

To use a media query to change a layout, to make a picture scale with its box, and to set text sizes with rem units.

## 3. Software / Tools Required

- Language: HTML5 and CSS3
- Web browser: Google Chrome / Microsoft Edge / Firefox
- IDE: VS Code
- Any text editor (if IDE is not available)

## 4. Theory

**1. Viewport Meta Tag:**
`<meta name="viewport" content="width=device-width, initial-scale=1.0">` makes the page fit the width of a phone.

**2. Mobile-First Design:**
Base styles are written for phones, then `@media (min-width: 600px)` adds changes for wider screens.

**3. Responsive Images:**
`max-width: 100%` with `height: auto` lets a picture shrink with its container but not grow past its own size.

**4. rem Units:**
`rem` is relative to the root font size, so text scales consistently.

## 5. Algorithm / Procedure

### Question 1: Mobile-First Cards

1. Start.
2. Create `mobile-first.html` with the viewport meta tag.
3. Add a `.cards` div with two `.card` elements.
4. Write base styles (cards stack).
5. Add `@media (min-width: 600px)` to show the cards side by side.
6. Save the file and open it in a browser.
7. Stop.

### Question 2: Responsive Image

1. Start.
2. Create `responsive-image.html` with a heading and an image from the `images` folder.
3. Set `max-width: 100%` and `height: auto` on the image.
4. Save the file and open it in a browser.
5. Stop.

### Question 3: Responsive Text

1. Start.
2. Create `responsive-text.html` with an h1 and a paragraph.
3. Set body to 1rem and h1 to 1.5rem.
4. Add a media query for 600px and up that sets h1 to 2.5rem.
5. Save the file and open it in a browser.
6. Stop.

## 6. Input

The following values are used in the experiment:

**Question 1:**

- Two cards

**Question 2:**

- Image = images/photo.jpg (replace with the file name your instructor gives)

**Question 3:**

- Window width 700px (above 600px)

## 7. Output

**Question 1:**

On a phone the cards stack. At 600px and up they sit two per row.

**Question 2:**

On a narrow window the picture shrinks to fit. On a wide window it keeps its own size.

**Question 3:**

The heading is larger when the window is 600px wide or more.

---

**Result:** All three HTML and CSS pages were successfully written and opened in the browser, and the output matched the expected result.
