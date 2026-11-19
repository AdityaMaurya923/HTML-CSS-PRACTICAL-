# Assignment 9: Tables with Headers and Footers

**Name:** Aditya Kumar Maurya
**Roll No:** 2510303042

## 1. Experiment Title

Tables with Headers and Footers using HTML and CSS.

## 2. Aim

To build a table with a caption, a header, rows and a footer, and to add scope attributes.

## 3. Software / Tools Required

- Language: HTML5 and CSS3
- Web browser: Google Chrome / Microsoft Edge / Firefox
- IDE: VS Code
- Any text editor (if IDE is not available)

## 4. Theory

**1. Table Structure:**
`<table>` holds rows (`<tr>`) made of header cells (`<th>`) and data cells (`<td>`). `<caption>` gives the table a title.

**2. Row Groups:**
`<thead>`, `<tbody>` and `<tfoot>` group the header, body and footer rows.

**3. Scope Attribute:**
`scope="col"` and `scope="row"` tell screen readers whether a header cell describes a column or a row.

**4. Average:**
Average = (sum of marks) / (number of students).

## 5. Algorithm / Procedure

### Question 1: Marks Table

1. Start.
2. Create `marks.html` with a table and the caption *Marks of Class A*.
3. Put the header row Name, Maths, Science in `<thead>`.
4. Add three rows (Asha, Rohan, Neha) in `<tbody>`.
5. Save the file and open it in a browser.
6. Stop.

### Question 2: Table with Average

1. Start.
2. Create `marks-average.html` with the same caption and header.
3. Keep only the Asha and Rohan rows.
4. Calculate Maths average = (78 + 64) / 2 = 71 and Science average = (85 + 70) / 2 = 77.5.
5. Add a `<tfoot>` row *Class average* with 71 and 77.5.
6. Save the file and open it in a browser.
7. Stop.

### Question 3: Accessible Table

1. Start.
2. Create `marks-accessible.html` with the same caption, header and two rows, without the footer.
3. Add `scope="col"` to each header cell.
4. Make each name a `<th scope="row">` cell.
5. Save the file and open it in a browser.
6. Stop.

## 6. Input

The following values are used in the experiment:

**Question 1:**

- Asha 78 85, Rohan 64 70, Neha 91 88

**Question 2:**

- Asha 78 85, Rohan 64 70

**Question 3:**

- Asha 78 85, Rohan 64 70

## 7. Output

**Question 1:**

A table with a header row and three student rows.

**Question 2:**

The footer row at the bottom shows the two averages (71 and 77.5).

**Question 3:**

The table looks the same. The header and name cells carry scope attributes (check in the Elements panel).

---

**Result:** All three HTML and CSS pages were successfully written and opened in the browser, and the output matched the expected result.
