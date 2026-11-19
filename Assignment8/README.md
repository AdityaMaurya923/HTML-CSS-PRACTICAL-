# Assignment 8: Sign-Up Forms and Choices

**Name:** Aditya Kumar Maurya
**Roll No:** 2510303042

## 1. Experiment Title

Sign-Up Forms and Choices using HTML and CSS.

## 2. Aim

To make a labelled form with text, email and password fields, choices and a submit button.

## 3. Software / Tools Required

- Language: HTML5 and CSS3
- Web browser: Google Chrome / Microsoft Edge / Firefox
- IDE: VS Code
- Any text editor (if IDE is not available)

## 4. Theory

**1. Forms:**
`<form method="post" action="thanks.html">` collects user input and sends it to the page named in `action`.

**2. Input Types:**
`type="text"`, `type="email"` and `type="password"` (hides the characters). Each `<label for="id">` is linked to the field with the same `id`.

**3. Choices:**
Radio buttons with the same `name` allow only one selection. `<select>` with `<option>` makes a dropdown.

**4. Validation:**
The `required` attribute stops the form from being submitted when the field is empty. `placeholder` shows a hint inside the box.

## 5. Algorithm / Procedure

### Question 1: Sign-Up Form

1. Start.
2. Create `signup.html` with a form (method post, action thanks.html).
3. Add text, email and password inputs with unique ids.
4. Link each `<label>` to its input using `for`.
5. Save the file and open it in a browser.
6. Stop.

### Question 2: Radio Buttons and Dropdown

1. Start.
2. Create `choices.html`.
3. Add two radio buttons with the same `name` (Female, Male).
4. Add a `<select>` with options BCA and B.Tech.
5. Save the file and open it in a browser.
6. Stop.

### Question 3: Required Fields

1. Start.
2. Create `signup-required.html` with name and email fields.
3. Add `required` to both fields.
4. Add a `placeholder` to the name field.
5. Add a Submit button.
6. Save the file and open it in a browser.
7. Stop.

## 6. Input

The following values are used in the experiment:

**Question 1:**

- Full name, email and password fields

**Question 2:**

- Gender = Female / Male, Course = BCA / B.Tech

**Question 3:**

- Name and email left empty to test validation

## 7. Output

**Question 1:**

Three labelled boxes. The password box hides the characters you type.

**Question 2:**

Only one gender can be selected. The dropdown shows the two courses.

**Question 3:**

Leaving a required field empty shows a message from the browser.

---

**Result:** All three HTML and CSS pages were successfully written and opened in the browser, and the output matched the expected result.
