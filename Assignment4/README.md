# Assignment 4: Divs, Attributes and a Small Fix

**Name:** Aditya Kumar Maurya
**Roll No:** 2510303042

## 1. Experiment Title

Divs, Attributes and a Small Fix using HTML and CSS.

## 2. Aim

To group parts of a page with div elements, add a data attribute, and fix the errors in a broken page.

## 3. Software / Tools Required

- Language: HTML5 and CSS3
- Web browser: Google Chrome / Microsoft Edge / Firefox
- IDE: VS Code
- Any text editor (if IDE is not available)

## 4. Theory

**1. The div Element:**
`<div>` is a block-level container used to group content. A `class` can be shared by many elements, while an `id` must be unique on a page.

**2. Attributes:**
Attributes give extra information to a tag, written as `name="value"`.

**3. Custom Data Attributes:**
Attributes starting with `data-` (for example `data-topic`) store extra information that is not shown on the page.

**4. Common HTML Errors:**
Unclosed tags, wrongly closed tags (`<p>` used instead of `</p>`) and missing closing tags make a page invalid.

## 5. Algorithm / Procedure

### Question 1: Layout with div

1. Start.
2. Create `layout.html`.
3. Add a div with class `header`.
4. Add a div with class `main`.
5. Add a div with class `footer` and put text in each.
6. Save the file and open it in a browser.
7. Stop.

### Question 2: id and data attribute

1. Start.
2. Create `attributes.html`.
3. Add a div with `id="profile"`.
4. Inside it add a paragraph with `data-topic="hobbies"` and some text.
5. Save the file and open it in a browser.
6. Stop.

### Question 3: Fix the broken page

1. Start.
2. Read the broken page and find the errors.
3. Close the `<h1>` heading with `</h1>`.
4. Replace the second `<p>` in `<p>Asha: 92%<p>` with the closing tag `</p>`.
5. Save the corrected page as `attendance-fixed.html`.
6. Save the file and open it in a browser.
7. Stop.

## 6. Input

The following values are used in the experiment:

**Question 1:**

- Any text in each div

**Question 2:**

- id = profile, data-topic = hobbies

**Question 3:**

- The broken attendance page given in the question

## 7. Output

**Question 1:**

Three blocks in order: header, main and footer.

**Question 2:**

The paragraph text shows. The data-topic attribute is not visible on the page.

**Question 3:**

The corrected page shows the heading Attendance Report and two lines: Asha: 92% and Rohan: 85%.

**Errors fixed:** (1) `<h1>` was never closed, (2) `<p>Asha: 92%<p>` used an opening `<p>` instead of `</p>`.

---

**Result:** All three HTML and CSS pages were successfully written and opened in the browser, and the output matched the expected result.
