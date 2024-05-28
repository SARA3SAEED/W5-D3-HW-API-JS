# HTTP Cat Images Display

## Overview

This repository contains a simple web application that displays images of cats corresponding to various HTTP status codes. The images are fetched from the [http.cat](https://http.cat/) website and displayed in a responsive grid layout.

## Features

- Displays images for a wide range of HTTP status codes.
- Each image is clickable and links to the respective HTTP status code page on [http.cat](https://http.cat/).
- Responsive design ensures the layout adapts to different screen sizes.

## Code Structure

- `index.html`: The main HTML file that sets up the structure of the webpage.
- Inline JavaScript: Fetches the images based on HTTP status codes and appends them to the webpage.
- Inline CSS: Styles the layout to be responsive and visually appealing.

## HTTP Status Codes Displayed

The application displays images for the following HTTP status codes:

```jax
const resCodes = [
  100, 101, 102, 103, 200, 201, 202, 203, 204, 206, 207, 208, 214, 226, 300,
  301, 302, 303, 304, 305, 307, 308, 400, 401, 402, 403, 404, 405, 406, 407,
  408, 409, 410, 411, 412, 413, 414, 415, 416, 417, 418, 420, 421, 422, 423,
  424, 425, 426, 428, 429, 431, 444, 450, 451, 497, 498, 499, 500, 501, 502,
  503, 504, 506, 507, 508, 509, 510, 511, 521, 522, 523, 525, 530, 599,
];
```

## Demo Live:
Check out the live demo [here](https://sara3saeed.github.io/W5-D3-HW-API-JS/)
