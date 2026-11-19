# Assignment 11: Units and CSS Variables

**Name:** Aditya Kumar Maurya
**Roll No:** 2510303042

## 1. Experiment Title

Units and CSS Variables using HTML and CSS.

## 2. Aim

To use CSS units and to store colours and spacing in variables.

## 3. Software / Tools Required

- Language: HTML5 and CSS3
- Web browser: Google Chrome / Microsoft Edge / Firefox
- IDE: VS Code
- Any text editor (if IDE is not available)

## 4. Theory

**1. Absolute Unit:**
`px` is a fixed size in pixels.

**2. Relative Units:**
`%` is relative to the parent box, and `rem` is relative to the root font size (1rem is normally 16px).

**3. CSS Variables:**
A variable such as `--main-color` is defined in `:root` and used with `var(--main-color)`. Changing it in one place updates the whole page.

## 5. Algorithm / Procedure

### Question 1: Units

1. Start.
2. Create `units.html`.
3. Add `.box1` with width 200px and height 40px.
4. Add `.box2` with width 50% and height 40px.
5. Give both a background colour and set the paragraph to 1.5rem.
6. Save the file and open it in a browser.
7. Stop.

### Question 2: CSS Variables

1. Start.
2. Create `variables.html`.
3. Define the three variables in `:root`.
4. Use `var()` for the body colour and padding and for the h1 colour.
5. Save the file and open it in a browser.
6. Stop.

### Question 3: tokens.css

1. Start.
2. Create `tokens.css` with four variables (primary, accent, heading size, spacing).
3. Use them for the body colour and padding and for the h1 colour and size.
4. Link it to `tokens.html` to test.
5. Save the file and open it in a browser.
6. Stop.

## 6. Input

The following values are used in the experiment:

**Question 1:**

- Box 1 = 200px, Box 2 = 50%, text = 1.5rem

**Question 2:**

- --main-color: #1d3557, --accent-color: #e63946, --page-padding: 20px

**Question 3:**

- #1d3557, #e63946, 2rem, 16px

## 7. Output

**Question 1:**

A 200 pixel box, a half-width box and larger text.

**Question 2:**

The heading uses the accent colour. The text uses the main colour.

**Question 3:**

Linked to a page, the file sets the colours, heading size and spacing.

---

**Result:** All three HTML and CSS pages were successfully written and opened in the browser, and the output matched the expected result.
