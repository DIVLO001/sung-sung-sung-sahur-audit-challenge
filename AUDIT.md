## HTML Issues

1. Missing <!DOCTYPE html>
   Problem: Browsers may not render pages in HTML5 mode, causing layout issues.
   Plan: Add <!DOCTYPE html> to all HTML files.

2. Inconsistent file names
   Problem: Capitalization and spaces (e.g., LOG IN PAGE.HTML) can break links and hurt maintainability.
   Plan: Rename all files to lowercase without spaces (e.g., login.html) and update links.

3. Inputs missing attributes/labels
   Problem: Without type, name, or <label>, forms are less accessible and harder to validate.
   Plan: Add proper type, name, and <label> elements.

4. Missing <form> elements
   Problem: Inputs can’t be properly grouped or submitted.
   Plan: Wrap login and signup inputs in <form> tags.

5. Images missing alt attributes
   Problem: Reduces accessibility and breaks HTML best practices.
   Plan: Add descriptive alt text to all images.

## CSS Issues

1. Overuse of universal div selector
   Problem: Red background applied to all divs limits styling flexibility.
   Plan: Use specific class-based selectors.

2. Non-responsive layout
   Problem: Fixed widths and margins break layouts on smaller screens.
   Plan: Use relative units and responsive techniques.

3. Images not responsive
   Problem: Fixed widths can overflow or appear too large on small screens.
   Plan: Apply percentage-based widths with max-width limits.

4. Buttons lack interaction feedback
   Problem: Poor user experience; no hover/active states.
   Plan: Add hover and active styles.

5. Outdated layout methods
   Problem: Inline-block and manual spacing reduce flexibility.
   Plan: Implement Flexbox for layouts.

## Git / Structure Issues

1. File naming inconsistency & spaces
   Problem: Case differences and spaces reduce cross-platform compatibility.
   Plan: Standardize names to lowercase, no spaces.

2. Empty or unused files
   Problem: Confusing and suggests incomplete work.
   Plan: Remove or add content.

3. Poor folder structure & corrupted images
   Problem: HTML, CSS, images mixed in one folder makes project hard to manage.
   Plan: Organize into images/, css/, js/ folders.

4. No version control
   Problem: Hard to track changes and fix errors.
   Plan: Initialize Git repo and commit regularly.

5. Insufficient README/documentation
   Problem: README.txt exists but is too minimal, giving little information about project setup, structure, or features.
   Plan: Expand the README to clearly describe the project, file structure, how to run it, and list all key features.
