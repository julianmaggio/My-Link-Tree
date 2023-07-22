# My Link Tree

Welcome to My Link Tree! This is a simple HTML page that serves as a link tree, allowing you to share multiple website links in one place. The page utilizes Bulma CSS framework for styling and Google Fonts to apply a custom font called 'Syne' for a visually appealing experience. Additionally, there is a JavaScript function to display a warning popup before redirecting to the clicked link.

## Table of Contents
- [Introduction](#introduction)
- [Usage](#usage)
- [Customization](#customization)
- [Images and Videos](#images-and-videos)
- [License](#license)

## Introduction

The Link Tree page consists of a background image, a title, and a list of buttons that represent different websites you want to share with your visitors. When a button is clicked, a warning popup appears, asking for confirmation before redirecting to the associated website. This precautionary step aims to ensure the safety and trustworthiness of the links you provide.

## Usage

To use this Link Tree page, you have the following options:

1. **Clone the Repository**: If you have access to the source code, you can clone the repository to your local machine and customize it as needed.

2. **Modify the Code Directly**: Alternatively, you can directly modify the HTML, CSS, and JavaScript code in your favorite code editor or text editor.

3. **Host the Page**: After customizing the page according to your preferences, you can host it on a web server or any static hosting platform of your choice.

4. **Adding/Removing Links**: To add or remove links/buttons, locate the `links-container` div within the HTML code. Inside this div, you can add more anchor tags with the class `button is-primary is-fullwidth` and specify the `href` attribute as the URL of the website you want to link to.

5. **Background Image**: Replace the `background-image.jpg` file in the `images` folder with your preferred background image. Don't forget to adjust the file path in the CSS code under the `.background-container` class.

## Customization

You can customize this Link Tree page to match your preferences and branding. Here are some areas you may want to consider customizing:

- **Background Image**: Replace the current background image with your own image by updating the file path in the CSS code.

- **Fonts**: If you prefer a different font, you can change the `font-family` property in the CSS code under the `body` class.

- **Button Colors**: Modify the CSS code for the `.button` class to change the appearance of the buttons, such as background color, text color, or size.

- **Popup Text**: Customize the warning popup text in the JavaScript code by updating the `You will now enter ${url}` string to provide more context for your visitors.

## Images and Videos

![Screenshot 1](https://git.kukikugames.com/Julian/My-Link-Tree/raw/commit/932caf35a19d511abeb3137cd2a870007f2f185d/screenshots/Skærmbillede%202023-07-22%20172853.png)
![Screenshot 2](https://git.kukikugames.com/Julian/My-Link-Tree/raw/commit/932caf35a19d511abeb3137cd2a870007f2f185d/screenshots/Skærmbillede%202023-07-22%20172908.png)

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code according to the terms of the license.