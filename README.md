# Assignment #4. Forms and Validation

**Name:** Torekhan Taimas
**Group:** IT-2503

## Project files

| File | Content |
|------|---------|
| `index.html` | Index page with links to each part |
| `part1.html` | Part 1: Task 0 and Task 1 |
| `part2.html` | Part 2: Task 2 and Task 3 |
| `part3.html` | Part 3: Task 4 |

Each part is one page. Styles are written as internal CSS (a `<style>` tag in each file). No JavaScript is used.

---

## Part 1. Basic HTML Forms

### Task 0. Simple Contact Form
Create a basic contact form with the following fields: Name (text input), Email (email input), Message (textarea) and a Submit button. All fields must have proper `<label>` elements.

<img width="1101" height="840" alt="изображение" src="https://github.com/user-attachments/assets/845832f9-81f3-44fe-8ba9-43c706174090" />


### Task 1. Form with HTML5 Validation
Add built-in validation attributes (`required`, `type`, `minlength`, `maxlength`). Test how the browser enforces validation (for example, email format and empty fields).

Empty fields:

<img width="898" height="682" alt="изображение" src="https://github.com/user-attachments/assets/36d7a4ce-eb7c-4db6-8190-bf350d9e3900" />


Invalid email format:

<img width="875" height="682" alt="изображение" src="https://github.com/user-attachments/assets/be17f66b-1627-4c5d-921e-d59a1b961850" />

---

## Part 2. Bootstrap Forms

### Task 2. Bootstrap Form Styling
Recreate the contact form using Bootstrap form classes. Use the Bootstrap grid system to arrange the fields. Add placeholders and helper text where appropriate.

<img width="1017" height="643" alt="изображение" src="https://github.com/user-attachments/assets/d7d6a059-db62-4348-a1d3-6bdc7008e06a" />

### Task 3. Bootstrap Validation Styles
Apply Bootstrap validation feedback classes (`is-valid`, `is-invalid`). Show feedback messages below the inputs (for example, "Email is required", "Looks good!"). Test the form with valid and invalid data.

Invalid data:

<img width="907" height="756" alt="изображение" src="https://github.com/user-attachments/assets/6685da99-8f07-4f80-bed0-2ad9847ede85" />


Valid data:

<img width="917" height="742" alt="изображение" src="https://github.com/user-attachments/assets/bd2e048f-0ac0-4f46-a39c-0975ae838634" />

---

## Part 3. Advanced Form Project

### Task 4. Registration Form
Create a registration form with: First Name, Last Name, Email, Password + Confirm Password, Gender (radio buttons), Hobbies (checkboxes), Country (select dropdown), Submit and Reset buttons. Style it with the Bootstrap grid so it is responsive. Add HTML5 validation (for example, minimum password length) and Bootstrap validation feedback for error and success messages.

Invalid data:

<img width="982" height="832" alt="изображение" src="https://github.com/user-attachments/assets/f6cc2193-aa1a-4ce2-875e-0c2069c4ddc1" />


Valid data and success message:

<img width="1042" height="940" alt="изображение" src="https://github.com/user-attachments/assets/f329d135-8690-43e1-b579-b6e369f08a3f" />
<img width="967" height="205" alt="изображение" src="https://github.com/user-attachments/assets/a44a0ba9-e040-48eb-ba44-14546bcb19ec" />



Mobile view:

<img width="1005" height="1077" alt="изображение" src="https://github.com/user-attachments/assets/cfbb714d-42ba-472c-ae63-cfda382c04d1" />


---

## Summary of work process

I started with Part 1 and built the simple contact form, linking each `<label>` to its input with `for` and `id`. Then I added the HTML5 validation attributes (`required`, `minlength`, `maxlength`, `type="email"`) and tested them in the browser with empty and invalid values.

In Part 2 I rebuilt the same form with Bootstrap classes (`form-control`, `form-label`, `form-text`) and arranged the fields with the grid (`row`, `col-md-6`, `col-12`). For Task 3 I used the `is-valid` and `is-invalid` states with `valid-feedback` and `invalid-feedback` messages under each field.

In Part 3 I built the registration form with all required field types and made it responsive with the grid. Password length is checked with `minlength="8"`, radio buttons share one `name` so only one can be chosen, and the country select has an empty disabled first option so a real choice is required. Everything is done without JavaScript, so the Confirm Password field only checks that it is filled and has the minimum length. Comparing it with the Password field would need JavaScript.

---
