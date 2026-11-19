# Assignment 10: CSS Fundamentals

**Name:** Aditya Kumar Maurya
**Roll No:** 2510303042

## 1. Experiment Title

CSS Fundamentals using HTML and CSS.

## 2. Aim

To apply CSS in three ways (inline, internal and linked) and to use selectors and text styles.

## 3. Software / Tools Required

- Language: HTML5 and CSS3
- Web browser: Google Chrome / Microsoft Edge / Firefox
- IDE: VS Code
- Any text editor (if IDE is not available)

## 4. Theory

**1. Three Ways to Add CSS:**

- Inline: the `style` attribute on one element.
- Internal: a `<style>` block in the `<head>`.
- External (linked): a `.css` file added with `<link rel="stylesheet" href="style.css">`.

**2. Selectors:**
Element selector (`h1`), class selector (`.note`) and id selector (`#title`).

**3. Text Properties:**
`color`, `font-size`, `font-style: italic`, `text-decoration: underline` and `background-color`.

## 5. Algorithm / Procedure

### Question 1: Inline and Internal CSS

1. Start.
2. Create `inline-internal.html`.
3. In `<style>` make `h1` navy and `.highlight` yellow.
4. Add an h1, a paragraph with `style="color: red;"` and a paragraph with class `highlight`.
5. Save the file and open it in a browser.
6. Stop.

### Question 2: style.css

1. Start.
2. Create `style.css`.
3. Write rules: `h1` navy, `.note` italic, `#title` underlined, `p` font-size 18px and grey.
4. The file is linked in Question 3.
5. Save the file and open it in a browser.
6. Stop.

### Question 3: Linking style.css

1. Start.
2. Create `linked.html`.
3. Link `style.css` with `<link>` in the head.
4. Add an h1 with `id="title"` and two paragraphs with class `note`.
5. Save the file and open it in a browser.
6. Stop.

## 6. Input

The following values are used in the experiment:

**Question 1:**

- Any text

**Question 2:**

- No input required

**Question 3:**

- Any text

## 7. Output

**Question 1:**

A navy heading, one red paragraph and one yellow paragraph.

**Question 2:**

Once linked, the headings, notes and paragraphs use the new styles.

**Question 3:**

The page is styled only when style.css is in the same folder.

---

**Result:** All three HTML and CSS pages were successfully written and opened in the browser, and the output matched the expected result.
