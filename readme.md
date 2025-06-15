````markdown
# TenPlus - Move Beyond Hydration

This project is a landing page for TenPlus, a hydration mix product, showcasing its features, flavors, benefits, and user testimonials.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Author](#author)

## Features

- **Header Navigation**: A responsive header with brand logo and navigation links.
- **Hero Section with Video Background**: Engaging "Available in 6 Flavours" section with a looping background video and an interactive display of product flavors.
- **Electrolytes Benefits Section**: Highlights the key electrolyte content (Sodium, Potassium, Magnesium) and their benefits for rehydration and performance.
- **Product Information Section**: Details about Tenplus's blend of electrolytes, vitamins, and no added sugar.
- **Icons Bar**: A concise display of key product advantages like fast absorption, all-day hydration, essential vitamins, no added sugar, and natural flavors.
- **User Testimonials/Community Section**: Showcases user-generated content (images) with a hover effect to simulate video playback.
- **Footer**: Comprehensive footer with company logo, "About," "Shop," "Community," and "Support" links.
- **Responsive Design**: Optimized for various screen sizes using Tailwind CSS.

## Technologies Used

- **HTML5**: For the basic structure of the webpage.
- **Tailwind CSS**: A utility-first CSS framework for styling and responsive design.
- **Google Fonts (Inter)**: For custom typography.
- **Vanilla JavaScript**: (Implicitly, though no explicit JS in the provided snippet, typically used for interactive elements like the flavor cards' hover states or potential future features).

## Installation

To set up this project locally, follow these steps:

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/cookiesblack/tenplus_landing.git](https://github.com/cookiesblack/tenplus_landing.git)
    cd tenplus_landing
    ```

    (Note: Replace `tenplus_landing` with the actual repository name if it exists, otherwise, this is a placeholder instruction.)

2.  **Ensure Tailwind CSS is configured:**
    The project uses a CDN for Tailwind CSS, so no local installation is strictly required to view the page.
    ```html
    <script src="[https://cdn.tailwindcss.com](https://cdn.tailwindcss.com)"></script>
    ```
    If you plan to extend or customize the Tailwind CSS, you might want to set up a local Tailwind build process. Refer to the [Tailwind CSS documentation](https://tailwindcss.com/docs/installation) for more details.

3.  **Place assets:**
    Make sure to place `images03.png` in an `assets/images/` directory and `main.css` in an `assets/css/` directory relative to your `index.html` file, as referenced in the HTML:
    -   `assets/css/main.css`
    -   `assets/images/images03.png`
    -   The testimonial images and flavor images are linked directly from `mytenplus.com` and `w3schools.com` respectively.

## Usage

Simply open the `index.html` file in your web browser.

```bash
open index.html
````

## File Structure

```
.
├── index.html
├── assets/
│   ├── css/
│   │   └── main.css  (For custom CSS, if any, beyond Tailwind)
│   └── images/
│       ├── images03.png
│       └── images04.png
└── README.md
```

## Author

**Edwin R. Pelleng**
✉️ [ewinpelleng@gmail.com](mailto:ewinpelleng@gmail.com)
🔗 [ewin.my.id](https://ewin.my.id)
🐙 [github.com/cookiesblack](https://github.com/cookiesblack)

```
```