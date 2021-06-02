# Instructions

## Media rules with the <picture> element
1. Add a `<source>` element for each of the coloured images to the `<picture>` element.
2. Provide a `srcset` and a `media` attribute for each size of image.
3. Provide a `type` attribute for the WEBP image, so that it is ignored on Safari
4. Arrange the `<source>` elements in the correct order so that the appropriate order so that the WEBP image is downloaded if the browser can handle it.

## Media rules in CSS
5. In the CSS file, et the `display` of the `<main>` element to `flex`
6. Create a default layout for a device in portrait mode. The picture should be above the text. The text and the picture should fit the available width.
7. Provide a CSS @media rule for `orientation: landscape`. Use a row layout, with the text and the picture each taking half of the page width. Place the picture to the right of the text.
8. Test using the Device Toolbar in Google Chrome's Elements Inspector
