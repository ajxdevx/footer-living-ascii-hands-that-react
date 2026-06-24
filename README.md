# Footer — Living ASCII Hands That React

An animated footer where hand images are rendered as interactive ASCII art. The characters light up on hover, the hands follow your cursor with parallax drift, and the footer content reveals on scroll.

**Author:** AJ  
**Site:** [anassjid.dev](https://anassjid.dev)

## Features

- ASCII hand rendering from source images on canvas
- Hover clusters that ripple through nearby characters
- Mouse-driven parallax on both hands
- Scroll-triggered footer reveal with GSAP SplitText animations
- Smooth scrolling via Lenis

## Tech stack

- [Vite](https://vitejs.dev/)
- [GSAP](https://gsap.com/) (ScrollTrigger, SplitText)
- [Lenis](https://lenis.darkroom.engineering/)

## Getting started

```bash
npm install
npm run dev
```

Open the local URL Vite prints in the terminal (usually `http://localhost:5173`).

## Project structure

```
├── index.html
├── script.js      # ASCII rendering, hover, parallax, scroll animations
├── styles.css
└── public/
    ├── hand-left.jpg
    └── hand-right.jpg
```

## License

ISC
