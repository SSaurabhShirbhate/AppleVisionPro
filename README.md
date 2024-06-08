# Apple Vision Pro Clone

This project is a clone of the Apple Vision Pro website, designed to replicate its look and feel. The clone is built using HTML, CSS, and JavaScript, with integrated 3D elements using HTML5 Canvas, and smooth scrolling powered by Locomotive Scroll and animations managed by GSAP.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Contributing](#contributing)
- [License](#license)

## Demo

Check out the live demo of the Apple Vision Pro Clone [here](https://github.com/SSaurabhShirbhate/AppleVisionPro). 
## Features

- **Responsive Design:** Ensures a seamless experience on various devices.
- **Interactive 3D Elements:** Utilizes HTML5 Canvas for 3D interactivity.
- **Smooth Animations:** GSAP and ScrollTrigger used for animations.
- **Modern UI/UX:** Mimics the design of the original Apple Vision Pro website.
- **Locomotive Scroll:** Provides smooth and parallax scrolling effects.

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript**
- **HTML5 Canvas**
- **Locomotive Scroll**
- **GSAP (GreenSock Animation Platform)**

## Installation

To get a local copy up and running, follow these simple steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/SSaurabhShirbhate/AppleVisionPro.git
    ```

2. **Navigate to the project directory:**
    ```sh
    cd AppleVisionPro
    ```

3. **Open the `index.html` file in your browser:**
    ```sh
    open index.html
    ```
    or manually open the `index.html` file in your preferred web browser.

## Usage

Once you have the project set up, you can:

- Explore the various sections of the website.
- Interact with the 3D elements on the canvas.
- Experience the animations and transitions as you navigate through the site.

## Code Overview

### HTML

The HTML file provides the structure of the website. Here’s a snippet:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apple Vision Pro</title>
    <link rel="shortcut icon" href="./assets/favicon.png" type="image/x-icon">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/locomotive-scroll@3.5.4/dist/locomotive-scroll.css">
</head>
<body>
    <div id="main">
        <div class="section">
            <video src="video-url.mp4" muted></video>
            <nav>
                <h3>Vision Pro</h3>
                <button>Notify me</button>
            </nav>
            <div class="section-bottom">
                <h3>Introduction</h3>
                <img src="logo-url.png" alt="">
            </div>
        </div>
        <!-- Additional sections here -->
    </div>
    <script src="https://cdn.jsdelivr.net/npm/locomotive-scroll@3.5.4/dist/locomotive-scroll.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.1/gsap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.1/ScrollTrigger.min.js"></script>
    <script src="script.js"></script>
</body>
</html>

Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to create an issue or submit a pull request.
