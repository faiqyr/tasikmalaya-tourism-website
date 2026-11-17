# TasikTour — Tasikmalaya Tourism Blog

A simple, responsive tourism information website that introduces several destinations in Tasikmalaya, West Java. This project was developed as part of a university Web Programming (Pemrograman Web) assignment to practice building a multi-page website with HTML and Bootstrap.

**Live Demo:** [portfoliofaiqfinal.vercel.app](https://portfoliofaiqfinal.vercel.app/)

**Repository:** [faiqyr/Proyek-Bootstrap-Pemweb](https://github.com/faiqyr/Proyek-Bootstrap-Pemweb)

---

## Overview

TasikTour presents a small collection of tourism destinations in Tasikmalaya through a blog-style interface. Visitors can browse destination summaries on the main page and open an article page containing more detailed information about TeeJay Waterpark.

The website is a static front-end project. It does not use a backend, database, or content management system.

## Features

- **Tourism destination listing** — displays destination cards with images, names, and short descriptions.
- **Destination content** — includes information about Curug Gado Bangkong, TeeJay Waterpark, Pantai Karang Tawulan, Situ Gede, Citiis, Pantai Cipatujah, Kawah Karaha Bodas, and Gunung Galunggung.
- **Article detail page** — provides a longer article about TeeJay Waterpark, including a description of its facilities and attractions.
- **Image gallery** — displays destination-related images on the article page and in the footer.
- **Responsive layout** — uses Bootstrap's grid, cards, spacing utilities, and responsive navigation components to adapt the layout to different screen sizes.
- **Bootstrap navigation components** — includes a collapsible navigation bar and dropdown menus.

> **Implementation note:** The search form, some navigation links, social media links, related-article cards, and previous/next controls are currently visual or placeholder elements. They are not connected to search logic, external social profiles, or a dynamic article system.

## Pages

| Page | File | Description |
| --- | --- | --- |
| Home / destination listing | `index.html` | Shows destination cards and short tourism descriptions. |
| Article detail | `artikel.html` | Shows a detailed article about TeeJay Waterpark, an image gallery, related-content previews, and sample comments. |

## Tech Stack

- **HTML5** — page structure and content.
- **Bootstrap 5.3.3** — responsive layout, grid system, cards, navbar, dropdowns, and utility classes.
- **CSS** — a small amount of custom styling is written in an inline `<style>` block; most visual layout uses Bootstrap classes.
- **Bootstrap Bundle JavaScript 5.3.3** — supports Bootstrap components such as the collapsible navbar and dropdown menus.

Bootstrap CSS and JavaScript are loaded from the jsDelivr CDN. An internet connection is therefore required for Bootstrap styling and JavaScript components to load when running the project locally.

## Project Structure

```text
Proyek-Bootstrap-Pemweb/
├── img/              # Images, logo, and icon assets used by the pages
├── artikel.html      # TeeJay Waterpark article page
├── index.html        # Main page with tourism destination cards
└── README.md         # Project documentation
```

## Getting Started

This is a static website and does not require a package manager, build command, or backend server.

### 1. Clone the repository

```bash
git clone https://github.com/faiqyr/Proyek-Bootstrap-Pemweb.git
```

### 2. Open the project directory

```bash
cd Proyek-Bootstrap-Pemweb
```

### 3. Run the website

Open `index.html` in a web browser, or use the **Live Server** extension in Visual Studio Code for local development.

To view the article page directly, open `artikel.html`.

## Learning Objectives

This project provided practice with:

- Structuring web pages using semantic HTML elements.
- Applying Bootstrap's grid system and responsive utility classes.
- Building navigation bars, dropdown menus, and content cards with Bootstrap.
- Organizing a small website into multiple HTML pages.
- Managing local image assets and linking them to page content.

## Current Scope and Possible Improvements

The current implementation focuses on static page layout and presentation. Possible future improvements include:

- Implementing a working destination search and filtering feature.
- Connecting all navigation, social media, and article links to their correct destinations.
- Creating a separate detail page for each tourism destination.
- Replacing placeholder timestamps and sample comments with meaningful content.
- Improving image alternative text and checking image attribution.
- Moving custom CSS into a dedicated stylesheet for easier maintenance.

## Academic Context

**Project type:** University coursework  
**Course area:** Web Programming (Pemrograman Web)  
**Project name:** TasikTour — Tasikmalaya Tourism Blog

This repository represents an early front-end learning project and is documented as academic coursework rather than a production-ready tourism platform.

## Author

**Faiq YR**  
GitHub: [@faiqyr](https://github.com/faiqyr)

---

*Built for learning and educational purposes.*
