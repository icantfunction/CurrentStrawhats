# Strawhats Gallery

This repository contains a simple web page displaying a gallery of the current Strawhats characters from the One Piece anime. The gallery is built using HTML and CSS.

## Files

The repository contains two main files:

1. `StrawGall.html`: This is the main HTML file that structures the web page. It contains a header and a gallery of images.

2. `style.css`: This is the CSS file that styles the web page. It includes styles for the body, header, and gallery, as well as specific styles for the `.usopp` and `.franky` classes.

## Structure

The `StrawGall.html` file contains a `header` element with a title, and a `div` element with the class `gallery` that contains all the images.

Each image in the gallery is an `img` element with a `src` attribute pointing to the image file, and an `alt` attribute providing alternative text for the image. The `.usopp` and `.franky` classes are applied to specific images to give them unique styles.

The `style.css` file contains global styles for the `body` and `header` elements, as well as styles for all `img` elements within the `gallery` class. The `.usopp` class scales the image up and prevents it from overflowing its container, and the `.franky` class adjusts the position of the image within its container.

## Usage

To view the web page, open the `StrawGall.html` file in a web browser. The page should display a gallery of images with the styles defined in the `style.css` file.

## Customization

You can customize the styles by modifying the `style.css` file. For example, you can change the size and position of the images, the layout of the gallery, or the styles of the header. You can also add more images to the gallery by adding more `img` elements to the `gallery` div in the `StrawGall.html` file.