# 3D Website Repository

Welcome to my 3D website repository! This repository is inspired by a tutorial available on [YouTube](https://www.youtube.com/watch?v=Q7AOvWpIVHU).

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Contributing](#contributing)

## Description <a name="description"></a>

This repository contains the code for my 3D website. While it hasn't been hosted yet, feel free to clone the repository and customize it to suit your needs. I've made commits at every step along the way. Watch the YouTube video above for a better understanding.

## Features <a name="features"></a>
- **3D background elements**: This project uses a cube, sphere, and torus.
- **Camera movement linked to page scroll**
- **Page sectioned in the form of a grid**: All the elements of the HTML document are adjusted based on the grid template determined in the `main` tag. This is an interesting way to style a page and easy to visualize as well. Check the last commit in `style.css`:
  ```css
  main {
    grid-template-columns: repeat(12, 1fr);
  }
  ```

## Technologies Used <a name="technologies-used"></a>

- **Frontend**: HTML, CSS, JavaScript, three.js

## Setup Instructions <a name="setup-instructions"></a>

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Venkatesh-4/3d_website
   cd 3d_website
   ```

2. **Install dependencies:**
   ```bash
   npm create vite@latest
   npm install three
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **Open your browser and navigate to:**
   ```bash
   http://localhost:3000
   ```

## Contributing <a name="contributing"></a>

Contributions are welcome! Here's how you can contribute:

1. Fork the repository and create your branch from `main`.
2. Clone the forked repository to your local machine.
3. Make your changes and thoroughly test them.
4. Create a pull request explaining your changes.
