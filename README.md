# Frontend Mentor - Chat app CSS illustration

## Overview

This is my solution to the **Chat app CSS illustration** challenge on Frontend Mentor for **SBA 3: Design and Development**. The goal is to build a responsive chat interface illustration matching the design reference and style guide, including a staggered initial-load animation.

### Links

- Repository URL: https://github.com/Nettec31/chat-app-css-illustration-master
- Live Site URL: *(Add your GitHub Pages / Vercel / Netlify link here if deployed)*

## Approach and Customizations

- **HTML & Tailwind CSS:** Structured the page semantically with `<main>`, `<header>`, `<section>`, and `<footer>`, and styled the layout, colors, gradients, and `Rubik` typography using Tailwind CSS utility classes and custom `@theme` variables matching the style guide.
- **Responsive Design:** Built a single-column layout for smaller screens that expands into a side-by-side phone illustration and description layout on desktop viewports.
- **Animation:** Added a staggered fade-up load animation for the chat messages and walk options, wrapped in a `prefers-reduced-motion` check for accessibility.

## Challenges and How They Were Addressed

- **Switching CSS Approaches:** I initially started exploring Bootstrap, then decided to use Tailwind CSS instead to keep styling consistent and clean across the custom bubbles, gradients, and layout.
- **Responsive Spacing & Overflow:** Tuned spacing and pill background positioning across viewport sizes so the layout stays centered and free of horizontal overflow.

## Reflection
Building this chat app illustration was actually really good practice for getting more comfortable with CSS. First I started out with Bootstrap because I fthought I would be able to do it, but it was a bit more complicated than I thought. I ended up switching over to Tailwind instead, and the setup felt a lot smoother and better to use as I went. It definitely helped me see how different styling tools work in practice. If I had a little more time with it, I’d probably go back and try to figure out Bootstrap.