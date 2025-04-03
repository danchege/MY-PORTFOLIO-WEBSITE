# MY-PORTFOLIO-WEBSITE

This project is a personal portfolio website showcasing my skills, education, projects, and contact information. Below is a step-by-step explanation of how the code was written and formatted using HTML and CSS only.
-**Link**: https://danchege.github.io/portfolio/

---

## 1. **HTML Structure**
The `index.html` file is the main entry point of the website. It is structured as follows:
- **Header Section**: Includes a video background created using Canva design and a welcome message.
- **Navigation Bar**: Contains links to different sections of the page using `id` attributes for navigation.
- **Content Sections**: Each section (`About Me`, `Skills`, `Education`, `Interests`, `Projects`, and `Contact Me`) is defined using `<section>` tags with unique `id` attributes.
- **Footer**: Displays copyright information.

### Key Features:
- The `<style>` tag in the `<head>` section defines global styles for the body, headings, and paragraphs.
- The `<nav>` element uses an unordered list (`<ul>`) to create navigation links.
- The `<video>` tag is used to embed a looping video in the header.

---

## 2. **CSS Styling**
The `styles.css` file is used to style the website. Below are the key styling decisions:
- **Section Visibility**: By default, all sections are set `display: contents;`. The `:target` pseudo-class is used to display the section when its corresponding navigation link is clicked.
- **Navigation Bar**:
  - Styled with `flexbox` for alignment and spacing.
  - Links are styled with hover effects using `transition`.
- **Content Sections**:
  - Each section is styled with `text-align: justify` for better readability.
  - A maximum width of `900px` is applied to ensure content is centered and not stretched across the screen.
- **Social Media Icons**:
  - Displayed in a flex container with `gap` for spacing.
  - Icons are clickable and link to respective social media platforms.

---

## 3. **Media and Assets**
- **Images**: Stored in the `images/` folder and used for social media icons and the background.
- **Video**: A portfolio video is embedded from the `video/` folder.
- **Documents**: A downloadable CV is stored in the `documents/` folder.

---

## 5. **Content Details**
### About Me Section:
- Provides a brief introduction to my background and interests in technology.

### Skills Section:
- Highlights my technical expertise in Python, HTML, CSS, and MySQL.

### Education Section:
- Details my academic background and how it complements my passion for technology.

### Interests Section:
- Explains my enthusiasm for technology and problem-solving.

### Projects Section:
- Lists links to GitHub repositories for projects I have worked on, with descriptions of each project.

### Contact Me Section:
- Displays social media icons and links for easy communication. Includes a contact form with validation.

---

## 6. **Responsive Design**
The website uses `flexbox` and media queries to ensure proper alignment and spacing on different screen sizes.

---

## 7. **How to Run the Project**
1. Clone or download the repository to your local machine.
2. Open the `index.html` file in any modern web browser.
3. Navigate through the sections using the links in the navigation bar.

---

## 8. **Future Improvements**
- Add animations for section transitions.
- Implement a backend for storing contact form submissions.
- Include a blog section for sharing articles and updates.

---

## 9. **Credits**
- All content and assets are created and owned by Daniel Chege.
- Icons and images are sourced from personal designs using Canva, pexels.com, and public resources.

---

Thank you for visiting my portfolio website!
