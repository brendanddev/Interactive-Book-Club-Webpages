# Book Club Web Pages

This project consists of two web pages designed for a book club. The pages demonstrate various types of links and navigation techniques using HTML and CSS, conforming to best practices in web development. The main page (`bookclub.html`) serves as the index of the book collection, while the secondary page (`nonfiction.html`) provides additional information on non-fiction books.

## Features

### Book Club Main Page (`bookclub.html`)
- **Header and Navigation**:
  - Includes a styled `h1` header that displays the page title and author’s name, centered using CSS.
  - The navigation menu features links to book sections organized alphabetically by book titles.
  - A link to a secondary page (`nonfiction.html`) for non-fiction books is included.

- **Book Information Sections**:
  - Each book entry is organized under its corresponding section based on the first letter of its title.
  - Each book entry includes:
    - Book title (`h2` heading styled with background and font colors).
    - An image of the book, which links to its respective Amazon purchase page.
    - A "Buy on Amazon" link, directing users to the book’s purchase page.
    - Author name and book description.
    - A "Back to Top" link that navigates to the top of the page.

- **Content Organization and Links**:
  - The main page (`bookclub.html`) features a "Book Collection" link to an external Excel file (`bookcollection.xlsx`) located in the `assets` folder.
  - The social media links in the footer include links to a sample email address and phone numbers formatted for calling applications.
  
### Non-Fiction Books Page (`nonfiction.html`)
- **Header**:
  - Styled similarly to the main page, maintaining consistency across both pages.

- **Content**:
  - A link to the Amazon Science and Math book list, directing users to relevant book collections.

- **Footer**:
  - Matches the style and content of the footer in `bookclub.html`, maintaining a cohesive design.

## Technical Implementation

- **HTML5 and CSS3**:
  - Semantic HTML is used to ensure clear content structure and adherence to web standards.
  - CSS is applied for layout and design, using external stylesheets for common elements and inline styles for specific sections.
  - Best practices are followed for accessibility and usability, ensuring all elements are keyboard and screen-reader friendly.

- **Navigation and Links**:
  - Uses external links for Amazon pages and documents.
  - Section links are used for in-page navigation, allowing users to jump between sections easily.
  - Anchor links provide smooth navigation to the top of the page.

- **Media and Assets**:
  - Images are organized in an `images` folder for efficient file management.
  - An Excel file (`bookcollection.xlsx`) is stored in an `assets` folder and linked from the main page.

## How to View

Download or clone the repository, and open `bookclub.html` in your preferred web browser to view the main page. Navigate to the non-fiction page using the link provided in the navigation bar. Ensure that the `images` and `assets` folders are in the same directory as the HTML files to view all content correctly.
