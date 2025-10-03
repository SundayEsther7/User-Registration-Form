# User-Registration-Form
User registration form created with HTML5 and CSS3, focusing on semantics and accessibility.
This repository contains a user registration form built with HTML5 and CSS3, focusing on semantic structure and accessibility best practices.
** Project Description**

This project implements a User Registration Form using HTML . It follows semantic HTML structure and accessibility standards using proper labels, grouping with fieldsets/legends, appropriate input types and Professional CSS practices for clean, responsive layout and interactive states

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
├── styles.css    # CSS styling for the form
└── README.md     # Project documentation (this file)

** Implementation Notes**

**HTML**
Uses <form>, <fieldset>, <legend>, <label>, <input>, <select>, <textarea>, <button>

Each input associated with <label> via for/id

Sections grouped with <fieldset> + <legend>

Input types optimized (email, tel, url, password, color, date/time, etc.)

Required agreements (Terms/Privacy) use required attribute

**CSS**
CSS Variables (:root) used for consistent color management

Box Model applied with margin, padding, border, and radius for clarity

Interactive States:

Hover, Focus, Active states for inputs and buttons

Smooth transitions for accessibility feedback

Accessibility:

High contrast between text/background

Red asterisk * for required fields

Visible focus outlines for keyboard navigation


**Accessibility:**


Labels clearly connected to inputs

Fieldsets provide grouping for screen readers

Required fields indicated with a red *

Inputs have clear focus styles for keyboard navigation

Styling Approach (CSS)

CSS Variables (:root) used for color palette

Box Model applied consistently (margin, padding, border, radius)

Flexbox used to align buttons (Reset left, Register right)

Interactive states added: hover, focus, active transitions

Custom styles for select dropdown, color picker, and other input types

**Color Palette**
Purpose	            Color Code
Primary Blue	    #2563eb
Primary Dark	    #1e40af
Primary Light	    #3b82f6
Background Light	#f9fafb
White	            #ffffff
Text Dark	        #1f2937
Text Light	        #6b7280
Border	            #d1d5db
Border Focus	    #2563eb
Success	        #10b981
Error	            #ef4444
Warning	        #f59e0b
Accent Purple	    #8b5cf6
Accent Pink	    #ec4899


**Features Implemented**

-Semantic and accessible HTML5 form

-Styled container with padding, rounded corners, and shadow

-Full-width inputs with consistent spacing

-Custom dropdown arrow and styled color picker

-Required fields marked with red *

-Prominent submit button with hover/active states

-Reset button styled as link for minimal visual weight

**Browser Compatibility**

 Chrome (tested)

 Edge (tested)

 Safari (tested)

 Firefox: :has() selector for required asterisk not fully supported yet

**How to View/Use**

Download or clone this repository.

Open index.html in any modern web browser.

Fill the form fields and submit (no backend processing included).

**Notes for Reviewers**

Correct semantic used

Clean, readable HTML5 structure.

No CSS/JS included.

External CSS with variables, flexbox, and transitions

README updated

** References (README writing)**

GitHub: About READMEs – https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes

Make a README – https://www.makeareadme.com/

Best README Template – https://github.com/othneildrew/Best-README-Template

