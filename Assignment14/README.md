# Assignment 14: CSS Grid Layouts

**Name:** Aditya Kumar Maurya
**Roll No:** 2510303042

## 1. Experiment Title

CSS Grid Layouts using HTML and CSS.

## 2. Aim

To make a grid with equal columns, a responsive gallery and a layout with named areas.

## 3. Software / Tools Required

- Language: HTML5 and CSS3
- Web browser: Google Chrome / Microsoft Edge / Firefox
- IDE: VS Code
- Any text editor (if IDE is not available)

## 4. Theory

**1. CSS Grid:**
`display: grid` creates a two-dimensional layout of rows and columns.

**2. Columns and Gap:**
`grid-template-columns: 1fr 1fr 1fr` makes three equal columns. `gap` sets the space between boxes.

**3. Responsive Grid:**
`repeat(auto-fill, minmax(150px, 1fr))` fits as many columns of at least 150px as there is room for.

**4. Named Areas:**
`grid-template-areas` names parts of the layout and `grid-area` places an element in a named part.

## 5. Algorithm / Procedure

### Question 1: Equal Columns

1. Start.
2. Create `grid-first.html` with six boxes numbered 1 to 6.
3. Use `display: grid` with `grid-template-columns: 1fr 1fr 1fr`.
4. Set `gap: 12px`.
5. Save the file and open it in a browser.
6. Stop.

### Question 2: Responsive Gallery

1. Start.
2. Create `gallery.html` with the heading Club Photo Gallery.
3. Add six boxes Photo 1 to Photo 6.
4. Use `repeat(auto-fill, minmax(150px, 1fr))` and `gap: 10px`.
5. Save the file and open it in a browser.
6. Stop.

### Question 3: Named Areas

1. Start.
2. Create `dashboard-areas.html` with header, sidebar, main and footer divs.
3. Use `grid-template-columns: 200px 1fr`.
4. Define `grid-template-areas` and place each div with `grid-area`.
5. Save the file and open it in a browser.
6. Stop.

## 6. Input

The following values are used in the experiment:

**Question 1:**

- Numbers 1 to 6

**Question 2:**

- Photo 1 to Photo 6

**Question 3:**

- Columns = 200px and 1fr

## 7. Output

**Question 1:**

Six boxes in two rows of three, with small gaps.

**Question 2:**

As the window gets wider, more boxes fit in each row.

**Question 3:**

A header across the top, a sidebar on the left, a main area on the right and a footer at the bottom.

---

**Result:** All three HTML and CSS pages were successfully written and opened in the browser, and the output matched the expected result.
