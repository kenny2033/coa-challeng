# COA TAKE-HOME CHALLENGE

## Project Description

This project contains two main parts:

1. **UI Challenge**: .
2. **Coding Challenges**: .

## Table of Contents

1. [kalisa ndoli kenny](#ttps://github.com/kenny2033)
2. [Setup Instructions](#setup-instructions)
3. [Usage](#usage)
4. [Coding Challenges](#coding-challenges)
   - [Challenge 1: Subarray with Target Sum](#challenge-1-subarray-with-target-sum)
   - [Challenge 2: String Transformation](#challenge-2-string-transformation)

# Interactive Photo Gallery Project

This project implements an interactive photo gallery using HTML, CSS, and JavaScript. Additionally, it includes solutions to two coding challenges involving array manipulation and string transformation.

## Features

- Displays a grid of images.
- Hover effects on images for additional information.
- Clicking on "Catch on" opens the image in a full-screen modal.
- Modal can be closed with a button click.

## Technologies Used

- HTML
- CSS
- JavaScript

## File Structure

PhotoGallery/
├── assets/
│ ├── css/
│ │ └── styles.css
│ ├── images/
│ │ ├── image1.png
│ │ ├── image2.png
│ │ ├── image3.png
│ │ └── image4.png
│ └── js/
│ └── main.js
├── challenges/
│ ├── array-manipulation.js
│ └── string-transformation.js
├── index.html
└── README.md

## Setup Instructions

1. Clone the repository:

   ```bash git clone https://github.com/kenny2033

   ```

   Approach Explanation
   HTML (index.html)
   The HTML file provides the structure for the photo gallery. It includes a container for the images and a modal for displaying the full-size images. Each image is wrapped in a container that includes additional information and a "Catch on" button for viewing the image in full size.

CSS (assets/css/styles.css)
The CSS file styles the gallery layout and includes hover effects for the images. It also styles the modal for displaying full-size images.

Key Styles:

.images-container sets the layout for the image grid.
.image-container defines the size and position of each image.
.animal and .description styles add the hover effect with image details.
.modal and .full-size-photo styles handle the display of full-size images.
JavaScript (assets/js/main.js)
The JavaScript file adds interactivity to the gallery:

handleImageHover function adds hover effects on images, showing additional information.
handleFullSizeView function manages the display of the full-size image in a modal when "Catch on" is clicked.
Coding Challenges

1. Array Manipulation
   File: challenges/array-manipulation.js

Problem Statement
Write a function that takes an array of integers and returns the array sorted in ascending order without using built-in sort functions.
Solution
javascript
Copy code
function sortArray(arr) {
for (let i = 0; i < arr.length; i++) {
for (let j = 0; j < arr.length - i - 1; j++) {
if (arr[j] > arr[j + 1]) {
// Swap elements
[arr[j], arr[j + 1]] = [arr[j + 1], arr[j]];
}
}
}
return arr;
}

// Example usage
console.log(sortArray([5, 3, 8, 4, 2])); // Output: [2, 3, 4, 5, 8] 2. String Transformation
File: challenges/string-transformation.js

Problem Statement
Write a function that takes a string and returns a new string with each character shifted by 1 in the ASCII table.

Solution
javascript
Copy code
function shiftString(str) {
let result = '';
for (let i = 0; i < str.length; i++) {
result += String.fromCharCode(str.charCodeAt(i) + 1);
}
return result;
}

// Example usage
console.log(shiftString('abc')); // Output: 'bcd'

#### Author:

[Kalisa ndoli kenny](https://github.com/kenny2033)
