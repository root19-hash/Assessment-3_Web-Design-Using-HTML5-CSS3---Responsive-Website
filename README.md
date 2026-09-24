# Matheson Library Printing Services

IS229 Assessment 3 responsive web design project by Joseph Seeto.

## Audience

The website is designed for students, staff, and members of the public who need library printing information or want to submit a print request.

## Finding Printing Service Information

Users can:

- View available printing and photocopying services
- See available paper sizes and printing types
- Read instructions for using the printing service
- Find relevant information before visiting the library

**Example user task:**

> "I want to know what printing services the library provides."

## Submit a Print Request

Users can complete a print request form containing information such as:

- Name
- Student/Staff ID
- Email
- Document name
- Number of copies
- Print type
- Paper size
- Additional instructions

This feature is especially useful because the assignment requires at least one substantial form with labels, suitable input types, and HTML5 validation.

## Find Contact and Service Information

Users can:

- Find the library's location
- View opening hours
- Find phone, email, and other contact details
- Get directions and other relevant information

**Example user task:**

> "I need to know where the printing service is and when it is open."

## Pages

- `index.html` - homepage and printing service overview
- `services.html` - available services, prices, paper sizes, and instructions
- `contact.html` - booking form, operating hours, contact details, and map
- `gallery.html` - printing examples, facilities, and walkthrough video
- `about.html` - service mission and reasons to choose the service

## Technologies and constraints

This is a static website using semantic HTML5 and custom CSS3. Layout uses Flexbox and CSS Grid with responsive changes below `640px`, from `640px` to `991px`, and from `992px` upward. No JavaScript or external frameworks are used.

## Assets

Images are stored in `Images/` and the video is stored in `Video/`. Relative paths preserve the existing folder capitalization and filenames.

## Responsive checks

The intended test viewports are:

| Viewport                      | Structural check                                          | Result                                                |
| ----------------------------- | --------------------------------------------------------- | ----------------------------------------------------- |
| Mobile, approximately 375px   | Navigation stacks and tables can scroll horizontally      | Implemented in CSS; browser inspection still required |
| Tablet, approximately 768px   | Two-column Grid layouts appear where appropriate          | Implemented in CSS; browser inspection still required |
| Desktop, approximately 1200px | Three-column content grids and wide layouts are available | Implemented in CSS; browser inspection still required |

## Verification completed

- All five pages link to `style.css`.
- HTML container tags were checked for balanced opening and closing tags.
- Local image and video paths were checked against the `Images/` and `Video/` folders.
- `git diff --check` passed after the latest edits.

## Project Structure

A3/
├── Images/
├── Video/
├── about.html
├── contact.html
├── gallery.html
├── index.html
├── LICENSE
├── README.md
├── services.html
└── style.css

## AI Use Declaration

AI tools were used as learning and review assistance. They helped identify HTML structure issues, suggest readable CSS Grid and Flexbox patterns, check responsive requirements, and explain accessibility and Git workflow choices. The project owner reviewed the changes and remains responsible for the final code, content, testing, and submission.
