# Single-Page-CV

# HTML-Only Curriculum Vitae Project

## Overview

This project focuses on creating a structured, single-page Curriculum Vitae (CV) using only HTML. The primary goal is to establish a semantic and well-organized foundation for the CV's content, including education, skills, and career history. Styling and visual presentation will be addressed in a subsequent project.

## Goal

To learn how to create a structured CV using semantic HTML elements.

## Key Requirements

* **Semantic HTML:** Utilize appropriate HTML5 tags (e.g., `<header>`, `<nav>`, `<article>`, `<section>`, `<ul>`, `<ol>`, `<li>`, `<dl>`, `<dt>`, `<dd>`) to structure the CV content logically.
* **SEO Meta Tags:** Include essential meta tags within the `<head>` section to improve search engine optimization. This will likely include:
    * `<meta charset="UTF-8">`
    * `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
    * `<meta name="description" content="A concise curriculum vitae for [Your Name]. Highlights education, skills, and career history.">` (Remember to replace `[Your Name]` with your actual name and customize the description.)
    * `<meta name="keywords" content="CV, Curriculum Vitae, Resume, [Your Name], [Your Skills], [Your Industry]">` (Replace the bracketed placeholders with relevant keywords.)
    * `<meta name="author" content="[Your Name]">` (Replace with your name.)
* **Open Graph (OG) Tags:** Implement Open Graph meta tags to enhance how the CV link appears when shared on social media platforms. Essential OG tags include:
    * `<meta property="og:title" content="[Your Name]'s Curriculum Vitae">` (Replace with your name.)
    * `<meta property="og:description" content="A concise curriculum vitae for [Your Name]. Highlights education, skills, and career history.">` (Match your SEO description or create a slightly different one.)
    * `<meta property="og:type" content="website">`
    * `<meta property="og:url" content="[The URL where your CV will be hosted]">` (Replace with the actual URL once deployed.)
    * `<meta property="og:image" content="https://www.reddit.com/r/AskGermany/comments/1c74wd1/its_better_to_add_photo_to_your_cv_or_not/">` (Optional, replace with an image URL if desired.)
* **Favicon:** Include a favicon (a small icon associated with your website) to be displayed in browser tabs. This will involve:
    * Creating a `.ico` file (or using other compatible formats like `.png` or `.gif`).
    * Linking to the favicon file within the `<head>` section using the `<link>` tag:
        ```html
        <link rel="icon" href="favicon.ico" type="image/x-icon">
        ```
        (Adjust the `href` path if your favicon is located in a different directory.)
* **Clear and Understandable Structure:** The HTML should be organized logically, making it easy to identify different sections of the CV (e.g., contact information, summary, education, skills, experience). The structure should be prepared for CSS styling in a future project.

## Next Steps

1.  **Create the `index.html` file:** This will be the main HTML file for your CV.
2.  **Structure the content:** Use semantic HTML tags to lay out the different sections of your CV. Focus on the logical flow of information.
3.  **Add meta tags:** Include the SEO and Open Graph meta tags within the `<head>` section of your `index.html` file.
4.  **Integrate the favicon:** Create or obtain a favicon file and link it correctly in the `<head>`.
5.  **Review and refine:** Ensure your HTML is well-formed and that the structure is clear and semantic.

## Future Considerations (Out of Scope for this Project)

* **Styling with CSS:** Enhancing the visual presentation of the CV using Cascading Style Sheets (CSS).
* **Responsiveness:** Ensuring the CV adapts well to different screen sizes and devices.
* **JavaScript Interactions:** Adding dynamic elements or functionalities (if needed for a more advanced CV).
