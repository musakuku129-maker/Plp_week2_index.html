Personal Budget & Expense Tracker - week 2
# Personal Budget & Expense Tracker - Week 2

This repository contains the Week 2 implementation of the Personal Budget & Expense Tracker project, building directly upon the foundational HTML and CSS structure established in Week 1.

## What was Built & Features

1. **Structured Expense Table (`index.html`)**:
   - Replaced placeholder text with a valid HTML table structure (`<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`).
   - Added 5 rows of hardcoded sample expense data covering key attributes: Name, Amount, Category, and Date.

2. **Upgraded Add Expense Form**:
   - Wrapped all input elements inside a proper `<form>` container.
   - Replaced the plain text category input with a `<select>` dropdown offering 5 options: **Food**, **Transport**, **Rent**, **Entertainment**, and **Other**.
   - Verified that all form fields feature semantic IDs (`id="expense-name"`, `id="expense-amount"`, `id="expense-category"`, `id="expense-date"`) for future JavaScript integration.
   - Added a button styled with a smooth hover effect and pointer cursor.

3. **Multimedia Elements**:
   - Embedded a logo image beside the header using the `<img>` tag equipped with a source URL, description, and width attribute.
   - Integrated an educational budgeting video using an `<iframe>` with correct dimension parameters and title attributes.

4. **Interactive Content**:
   - Included a collapsible `<details>` and `<summary>` guidance box explaining how users can interact with the tracker.

5. **Advanced CSS Selectors (`style.css`)**:
   - **Direct Child Selector (`#add-expense-section > form`)**: Targets the form element directly nested within the input section.
   - **Negation Pseudo-Class (`input:not([type="checkbox"])`) & Focus States (`input:focus`, `select:focus`)**: Applies consistent sizing/padding and a glowing accent outline when form fields are active.
   - **Descendant Selector & Position Pseudo-Classes (`.expense-table td`, `tr:nth-child(even)`, `tr:hover`)**: Provides zebra striping on alternating rows, custom cell padding, and interactive row highlighting.