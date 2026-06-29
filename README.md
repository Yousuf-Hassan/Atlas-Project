# Atlas University Website

A clean, beginner-friendly university website built with **HTML and CSS only**.  
No JavaScript, no frameworks, no backend — pure HTML & CSS.

---

## Project Structure

```
Atlas-Project/
│
├── index.html                  ← Home page (entry point)
│
├── pages/                      ← All other pages live here
│   ├── about.html              ← About the university + testimonials
│   ├── courses.html            ← Course categories + featured courses
│   ├── contact.html            ← Contact form
│   ├── login.html              ← Login form
│   ├── signup.html             ← Sign-up / registration form
│   ├── welcome.html            ← Shown after successful login
│   └── thanks.html             ← Shown after successful sign-up
│
├── assets/
│   ├── images/                 ← All images used in the site
│   │   ├── atlas-logo.png
│   │   ├── campus-hero.jpg
│   │   ├── about-student.jpg
│   │   ├── testimonial-adam.jpg
│   │   └── testimonial-roy.jpg
│   └── icons/                  ← Reserved for future icons/SVGs
│
├── css/
│   ├── global.css              ← SHARED: colors, navbar, footer, typography
│   ├── home.css                ← Home page: hero section, vision & mission
│   ├── about.css               ← About page: banner, about section, testimonials
│   ├── courses.css             ← Courses page: category cards, course cards
│   ├── contact.css             ← Contact page: form + info layout
│   └── auth.css                ← Login, Sign Up, Thanks, Welcome pages
│
└── README.md                   ← This file
```

---

## How CSS Files Are Organized

Every page links **two** CSS files:

1. `global.css` — shared styles used by all pages (navbar, footer, colors, fonts)
2. A page-specific file — styles only used by that page

This way you don't duplicate the navbar or footer styles 8 times.

### Example (about.html):
```html
<link rel="stylesheet" href="../css/global.css">
<link rel="stylesheet" href="../css/about.css">
```

---

## CSS Variables (in global.css)

All colors and fonts are defined as variables so you can change the whole site's theme in one place:

```css
:root {
  --color-primary:     #033677;   /* Dark blue */
  --color-accent:      #2563eb;   /* Bright blue */
  --color-green:       #10b981;   /* Green highlights */
  --color-text-dark:   #1e293b;   /* Headings */
  --color-text-body:   #64748b;   /* Body text */
  --font-main: 'Oswald', sans-serif;
}
```

---

## Pages Overview

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero banner + Vision/Mission cards |
| About | `pages/about.html` | University info + student testimonials |
| Courses | `pages/courses.html` | 8 category cards + 3 course cards |
| Contact | `pages/contact.html` | Contact form + info |
| Login | `pages/login.html` | Login form |
| Sign Up | `pages/signup.html` | Registration form |
| Welcome | `pages/welcome.html` | Shown after login |
| Thanks | `pages/thanks.html` | Shown after sign-up |

---

## How to Run

Just open `index.html` in any web browser. No setup needed.

```
Double-click index.html → Opens in browser
```

Or with VS Code: Right-click `index.html` → **Open with Live Server**

---
## 🌟 Live Demo
Coming soon...
## Built With

- HTML5
- CSS3 (Flexbox, Grid, CSS Variables, Media Queries)
- [Oswald](https://fonts.google.com/specimen/Oswald) — Google Font
- [Font Awesome 6](https://fontawesome.com/) — Icons (courses page)

---
## 📞 Contact
Feel free to reach out via GitHub!
