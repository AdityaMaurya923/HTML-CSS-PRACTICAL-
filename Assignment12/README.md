# Assignment 12: Box Model, Cards and Scrolling

**Name:** Aditya Kumar Maurya
**Roll No:** 2510303042

## 1. Experiment Title

Box Model, Cards and Scrolling using HTML and CSS.

## 2. Aim

To compare the box sizing types, to style a card and to make a box scroll.

## 3. Software / Tools Required

- Language: HTML5 and CSS3
- Web browser: Google Chrome / Microsoft Edge / Firefox
- IDE: VS Code
- Any text editor (if IDE is not available)

## 4. Theory

**1. Box Model:**
Every element is a box made of content, padding, border and margin.

**2. box-sizing:**

- `content-box` : width is only the content, so padding and border are added (200 + 40 + 10 = 250px).
- `border-box` : width includes padding and border (total stays 200px).

**3. Card:**
A card uses `background-color`, `border`, `border-radius` and `padding`.

**4. Overflow:**
`overflow: auto` adds a scroll bar when the content is larger than the box.

## 5. Algorithm / Procedure

### Question 1: Box Sizing

1. Start.
2. Create `box-model.html` with two divs.
3. Give both width 200px, padding 20px and border 5px.
4. Use `box-sizing: content-box` for the first and `border-box` for the second.
5. Save the file and open it in a browser.
6. Stop.

### Question 2: Card

1. Start.
2. Create `card.html` with a div of class `card`.
3. Style it with a background, 2px border, 12px radius and 16px padding.
4. Put an h3 and a paragraph inside.
5. Save the file and open it in a browser.
6. Stop.

### Question 3: Scrolling Box

1. Start.
2. Create `scroll.html` with a div box.
3. Set height 120px and `overflow: auto`.
4. Add five paragraphs, Line 1 to Line 5.
5. Save the file and open it in a browser.
6. Stop.

## 6. Input

The following values are used in the experiment:

**Question 1:**

- width 200px, padding 20px, border 5px

**Question 2:**

- Any heading and text

**Question 3:**

- Five lines of text

## 7. Output

**Question 1:**

The content-box box is wider (250px) than the border-box box (200px).

**Question 2:**

A card with rounded corners, a border and a coloured background.

**Question 3:**

The lines do not fit in the box, so the box can be scrolled.

---

**Result:** All three HTML and CSS pages were successfully written and opened in the browser, and the output matched the expected result.
