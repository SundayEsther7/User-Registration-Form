# User-Registration-Form
User registration form created with pure HTML5, focusing on semantics and accessibility.
This repository contains a user registration form built with pure HTML5, focusing on semantic structure and accessibility best practices.
** Project Description**

This project implements a User Registration Form using HTML . It follows semantic HTML structure and accessibility standards using proper labels, grouping with fieldsets/legends, appropriate input types.

** Purpose of the Form**

Collect structured user data across clear sections:

Personal Information

Contact & Address

Preferences & Interests

Account Security

Feedback & Additional Info

**Repository Structure**
.
├── index.html    # Complete semantic HTML form
└── README.md     # Project documentation (this file)

** Implementation Notes**

Semantic elements: <form>, <fieldset>, <legend>, <label>, <input>, <select>, <textarea>, <button>

**Accessibility:**

Every input is associated with a <label> via matching for / id

Related controls grouped with <fieldset> + <legend>

Proper type attributes (e.g., email, tel, date, url, password, file, color, range, time, month, week)

Required agreements (Terms, Privacy) use required

**HTML5 best practices:**

Uses <!DOCTYPE html> and lang attribute

Logical heading hierarchy

Inputs include helpful placeholder where appropriate

orm Sections & Fields (Overview)

Personal Information: first name, last name, date of birth, age, gender (radio), profile photo (file)

Contact & Address: email, phone, website URL, street address, country (select), ZIP/Postal, preferred contact time

Preferences & Interests: favorite color, experience (range), birth month, available week, keywords, interests (checkboxes), education level (select)

Account Security: password, confirm password

Feedback & Additional Info: about yourself, suggestions, registration date & time, “how did you hear about us?” (select), resume upload, newsletter (checkbox), terms & privacy (required checkboxes)

Submit button

** How to View/Use**

Download or clone this repository.

Open index.html in any modern web browser.

Fill the form fields and submit (no backend processing included).

** Notes for Reviewers (Assessment Focus)**

Correct semantic grouping with <fieldset>/<legend>

Accurate input types and accessible labels

Clean, readable HTML5 structure

No CSS/JS included (per brief)

Clear documentation in this README

** References (README writing)**

GitHub: About READMEs – https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes

Make a README – https://www.makeareadme.com/

Best README Template – https://github.com/othneildrew/Best-README-Template

