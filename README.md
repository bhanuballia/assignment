PORTFOLIO
File structure setup
Save the code above as index.html.
Create a small icon file named favicon.ico and place it in the same directory as index.html. For example, a simple 16x16 pixel icon.
Key semantic and accessibility features
<header>: This contains the website's title and main navigation, providing a consistent entry point.
<nav>: This clearly indicates navigation links, making it easier for screen readers to interpret and navigate. The aria-label attribute clarifies its purpose.
<main>: This wraps the unique and main content of the page. It appears only once and is not nested within other landmark tags.
<section>: This groups related content into thematic sections, such as "About" and "Projects," each with its own heading.
<article>: This defines self-contained content blocks within sect
<article>: This defines self-contained content blocks within sections, like a blog post or project entry.
<h1>: A single <h1> is used for the primary heading, which is the website title, ensuring a proper heading hierarchy.
<h2> and <h3>: Subsequent headings are correctly ordered to structure the content logically for screen readers and search engines.
<img>: Every image element has a descriptive alt attribute, which is crucial for accessibility.
<ul> and <ol>: Unordered lists are used for skills, while an ordered list is used for education, correctly describing the content's nature.
<footer>: This contains copyright and social media links, representing the end of the document.
Favicon: The <link> tag in the <head> correctly points to the favicon file, adding a professional touch.
HTML Entities: The copyright symbol (&copy;) is used correctly.



REGISTRATION FORM

Key features of this implementation:
registration.html: The file uses the specified filename.
Semantic Structure: The code uses <header>, <main>, <form>, <fieldset>, <legend>, and <footer> for a logical, semantic structure.
Form Attributes: The <form> element includes action="/submit-registration", method="post", and enctype="multipart/form-data" to handle the file upload correctly.
Input Validation:
required is used for mandatory fields (Full Name, Email, and Terms).
type="email" automatically validates for an email format.
type="number" with min="0" and max="20" enforces the experience range.
type="date" provides a date picker for easier input.
type="file" with accept="image/*" restricts file selection to image types.
Labels and Accessibility: Every input has a corresponding <label> with a for attribute matching the input's id. This links the label to the input, improving accessibility and user experience.
Field Grouping: fieldset and legend are used to logically group related form elements, making the form easier to read and understand.
Dynamic Range Slider: A small JavaScript snippet is added to update the display value of the programming experience slider in real-time, providing immediate feedback to the user.
Buttons: The form includes both a submit and reset button.
