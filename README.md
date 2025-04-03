# My-Portfolio
Welcome to my Portfolio Website 
### README

# Portfolio Website

This project is a **Portfolio Website** designed to showcase personal information, skills, projects, and contact details. It is built using **HTML** and **CSS** with a responsive layout and interactive features.

---

## Features

1. **Navigation Bar**:
   - A responsive navigation bar that links to different sections of the page.
   - Smooth scrolling behavior for better user experience.

2. **Hero Section**:
   - A welcoming section with a centered heading.

3. **About Me Section**:
   - A card displaying personal information and goals.

4. **Skills Section**:
   - A card listing programming languages and technical skills.

5. **Projects Section**:
   - A card showcasing projects with a link to the GitHub repository.

6. **Contact Me Section**:
   - A structured contact form with fields for name, email, and message.
   - Includes a LinkedIn link for professional networking.

7. **Responsive Design**:
   - Adjusts layout for smaller screens using media queries.

8. **Styling**:
   - Gradient backgrounds for input fields and text areas.
   - Hover effects for buttons and links.
   - Smooth scrolling and dark color scheme.

---

## File Structure

### HTML
- **File**: cyria.html
- Contains the structure of the website, including sections for navigation, hero, about me, skills, projects, and contact form.

### CSS
- **File**: styles.css
- Contains the styling for the website, including layout, colors, typography, and responsiveness.

---

## How to Use

1. Clone or download the repository.
2. Open cyria.html in a web browser to view the website.
3. Modify the content in cyria.html to personalize the portfolio.
4. Update styles.css to customize the design.

---

## Key CSS Highlights

### Navigation Bar
```css
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 20px;
    background: #333;
    color: #ffffff;
}
.navbar ul li a {
    color: #ffffff;
    text-decoration: none;
}
```

### Hero Section
```css
.hero {
    height: 20vh;
    display: flex;
    justify-content: center;
    align-items: center;
    color: whitesmoke;
    text-align: center;
    font-size: 2em;
    padding: 20px;
}
```

### Cards
```css
.card {
    background: url(background.jpeg) no-repeat center center/cover;
    color: #3c0008;
    padding: 40px;
    border-radius: 0;
    box-shadow: 2px 2px 10px rgba(5, 56, 2, 0.1);
    text-align: left;
    cursor: pointer;
    transition: transform 0.2s;
    height: 300px;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    width: 100%;
    overflow: auto;
}
```

### Contact Form
```css
.contact-form {
    display: flex;
    flex-direction: column;
    gap: 15px;
    width: 100%;
}
.form-group input,
.form-group textarea {
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    background: linear-gradient(135deg, rgba(255, 255, 255, 0.8), rgba(200, 200, 200, 0.5));
    color: #333;
    font-size: 1em;
    outline: none;
}
```

---

## Responsive Design

### Media Query for Small Screens
```css
@media (max-width: 600px) {
    .navbar ul {
        flex-direction: column;
        align-items: center;
    }
    .hero {
        font-size: 1.5em;
    }
}
```

---

## Future Improvements

1. Add animations for card hover effects.
2. Include a backend to handle form submissions.
3. Add more sections, such as testimonials or a blog.

---

## License

This project is open-source and free to use. Feel free to review and recommend improvements and distribute it as needed.

---

## Author

**Andiswa Cyria Molangathi**  
[LinkedIn](https://www.linkedin.com/in/andi-cyria-molangathi)  
[GitHub](https://github.com/AndiswaCyria)  

---
