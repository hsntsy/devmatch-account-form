# DevMatch Form Evaluation

## 1. Heuristic Evaluation

The form was reviewed using basic usability principles.

### Findings

- Required fields are clearly marked with an asterisk.
- Related form controls are grouped into logical sections.
- Labels and help text explain the expected input.
- The form uses familiar controls such as dropdowns, radio buttons and checkboxes.
- The browser provides feedback when required information is missing.
- The layout changes from two columns to one column on smaller screens.

### Improvements

- Empty optional fields no longer appear green.
- Error feedback appears after the user tries to submit the form.
- Help text was added for username, email, password and GitHub fields.
- Form controls were made large enough for touch interaction.

## 2. Accessibility Evaluation

The form was checked for accessibility.

### Checks Completed

- Every input has a visible label.
- Related radio buttons and checkboxes use fieldset and legend.
- Help text is connected to form controls using aria-describedby.
- Keyboard focus is clearly visible.
- The form can be completed using the keyboard.
- Semantic HTML elements are used.
- Text and background colors have clear contrast.
- Required fields use native HTML validation.

## 3. Responsive Design Test

The form was tested using Chrome DevTools mobile view.

### Results

- No horizontal scrolling was found.
- Form fields fit inside the mobile screen.
- Two-column sections change to one column.
- Progress items appear vertically.
- Buttons and inputs are large enough for touch interaction.
- Text remains readable on a small screen.

## 4. Validation Test

The following validation tests were completed:

- An empty required field prevented form submission.
- The username field rejected values shorter than three characters.
- The username field accepted letters, numbers and underscores.
- The email field uses the email input type.
- The password requires at least eight characters, an uppercase letter, a lowercase letter and a number.
- The GitHub field checks the expected URL format.

## 5. Technologies Used

- HTML5
- CSS3
- Native HTML form validation
- No JavaScript
- No external libraries or frameworks