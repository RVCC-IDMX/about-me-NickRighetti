# About Me — Nick Righetti

[Netlify Status](https://api.netlify.com/api/v1/badges/0efe50e8-3052-40cd-884a-a9a7fd65a159/deploy-status)](https://app.netlify.com/projects/about-me-nickrighetti/deploys))  

## Description  

This project is my personal **About Me website**, created to showcase my skills, interests, and portfolio work as a web developer and aspiring cybersecurity professional. The website is fully responsive and designed with modern web standards in mind, including semantic HTML, accessible ARIA attributes, and CSS for layout and styling. Through this project, I have learned how to implement responsive navigation menus with a hamburger toggle, create visually engaging **hover effects** for images, and design a clean, professional layout that highlights content effectively. Each section of the site demonstrates specific skills: the **Hero section** introduces me with a styled avatar, the **Bio and Hobbies sections** use structured content to share my story, the **Gallery** includes images with interactive hover and focus effects, the **Blog** section showcases a research-based article with code snippets, and the **Contact form** demonstrates accessible form design with validation.  

## Color Scheme  

- **Primary Blue:** #004aad (RGB: 0,74,173)  
- **Accent Blue:** #2b6cf6 (RGB: 43,108,246)  
- **Background Gradient:** #f7f2e9 → #e4d9c6 (RGB: 247,242,233 → 228,217,198)  
- **Text:** #222 (RGB: 34,34,34)  
- **Light Background / Cards:** #ffffff (RGB: 255,255,255)  

The colors were chosen for **high contrast and readability**, ensuring a WCAG ratio above 4.5 for accessibility.  

## Hover Effects  

Images in the Gallery section have **hover and focus effects** applied via CSS. For example:  

```css
.gallery-item img:hover,
.gallery-item img:focus {
  transform: scale(1.04);
  filter: saturate(1.05) contrast(1.02);
  outline: 3px solid rgba(43,108,246,0.12);
}