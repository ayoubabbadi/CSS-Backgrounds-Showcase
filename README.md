# CSS Background Property Reference

This repository provides a technical reference and testbed for various CSS `background` properties. The project is contained in a single `background.html` file for easy inspection and local testing.

## Overview

This project serves as a live, interactive reference for common and advanced CSS background techniques. All markup and styling are encapsulated in `background.html`, allowing each technique to be isolated and examined without external dependencies.

---

### Implemented Techniques

The following CSS classes are implemented and demonstrated in `background.html`:

* **`.solid-color`**:
    Implementation of a basic `background-color`.
* **`.image-background`**:
    Demonstrates `background-image` using `background-size: cover` and `background-position: center` for responsive image scaling.
* **`.linear-gradient`**:
    A multi-stop `linear-gradient()` function.
* **`.radial-gradient`**:
    A multi-stop `radial-gradient()` function.
* **`.video-background`**:
    An embedded, muted, and looping `<video>` element positioned absolutely behind content via `z-index`.
* **`.repeating-background`**:
    Demonstrates `background-repeat: repeat` with a specified `background-size` to create a tiled pattern.
* **`.fixed-background`**:
    Uses `background-attachment: fixed` to create a parallax-like scroll effect where the background remains static.
* **`.multiple-backgrounds`**:
    Stacks multiple `background-image` layers (an image and a gradient) and demonstrates `background-blend-mode`.

---

## Usage

No server, compilation, or dependencies are required.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/ayoubabbadi/CSS-Backgrounds-Showcase.git
    ```
2.  **Navigate to the directory:**
    ```bash
    cd CSS-Backgrounds-Showcase
    ```
3.  **Run:**
    * Open `background.html` directly in any modern web browser.
    * Open the file in a code editor to inspect the embedded CSS.

---

## Project Manifest

* **`background.html`**: The core file containing all HTML markup and embedded CSS styles.
* **`img.jpg`**: Primary image asset used for `image-background`, `fixed-background`, and `multiple-backgrounds` demos.
* **`background repeat.jpg`**: A tileable pattern image used for the `repeating-background` demo.

---

##  Configuration Notes

The CSS in `background.html` references asset paths that may require local correction for all examples to render correctly.

* **Image Path Mismatch**: The CSS references `img.png`. This must be updated to `img.jpg` in all relevant classes to match the provided asset.
* **Missing Video Asset**: The `.video-background` class requires a `video.mp4` file. This file is **not included** in the repository. A local `.mp4` file must be added to the project root and named `video.mp4` for this section to function.
