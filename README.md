# Matheson Library Printing Services

IS229 Assessment 3 responsive web design project by Joseph Seeto.

## Audience

The website is designed for students, staff, and members of the public who need library printing information or want to submit a print request.

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

## AI Use Declaration

AI tools were used as learning and review assistance. They helped identify HTML structure issues, suggest readable CSS Grid and Flexbox patterns, check responsive requirements, and explain accessibility and Git workflow choices. The project owner reviewed the changes and remains responsible for the final code, content, testing, and submission.
