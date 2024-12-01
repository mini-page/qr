# QR Code Generator

This project is a simple, interactive web application that allows users to generate QR codes from any URL or text input. The generated QR code can be downloaded as an image, and the application offers a light/dark theme toggle feature for better user experience.

## Features

- **QR Code Generation:** Generate QR codes from any URL or text input.
- **Download Option:** Download the generated QR code as a PNG image.
- **Dark/Light Theme Toggle:** Easily switch between light and dark themes.
- **Responsive Design:** Optimized for mobile, tablet, and desktop devices.

## Technologies Used

- **HTML5:** For the structure and layout of the page.
- **Tailwind CSS:** For responsive design and styling of the app.
- **JavaScript:** To implement QR code generation and theme toggling features.
- **QRCode.js Library:** For generating QR codes dynamically.
- **Font Awesome:** For adding icons (QR code, download, and theme toggler).

## How to Use

1. **Enter Text or URL:**
   - Type any URL or text you want to generate a QR code for into the input field.
   
2. **Generate QR Code:**
   - Click the "Generate QR Code" button to generate the QR code based on the entered input.

3. **Download QR Code:**
   - Once the QR code is generated, the "Download QR Code" button will appear. Click it to download the QR code as a `.png` image.

4. **Toggle Themes:**
   - Use the theme toggle button to switch between light and dark themes. The default theme is light.

## Code Explanation

### HTML Structure

- **Header:** Contains the app title and the theme toggle icon.
- **Main Container:** Includes the input field for URL/text, a button to generate the QR code, and a display area for the generated QR code.
- **Footer:** Displays credits for the creator and a link to the GitHub repository.
- **Cards:** Feature cards showcasing the app's functionalities, such as QR code generation, download option, and future customization plans.

### JavaScript Functionality

1. **QR Code Generation:**
   - Uses the `QRCode` library to generate a QR code when the "Generate QR Code" button is clicked. The generated QR code is displayed inside a div element.

2. **Download Button:**
   - The "Download QR Code" button becomes visible once the QR code is generated. Clicking it allows users to download the QR code as a PNG image.

3. **Theme Toggle:**
   - The theme toggle button allows users to switch between light and dark themes. The dark mode is activated by adding the `dark` class to the root HTML element.

### CSS Styling

- **Tailwind CSS** is used for styling the app, ensuring it is responsive and visually appealing.
- **Hover Effects:** Cards have a hover effect that includes scaling and adding a shadow, improving the user experience.

### Libraries Used

- **QRCode.js:** A JavaScript library for dynamically generating QR codes. [GitHub Link](https://github.com/davidshimjs/qrcodejs)
- **Font Awesome:** For incorporating icons like the QR code icon and the theme toggler icon. [Font Awesome Link](https://fontawesome.com/)
- **Tailwind CSS:** A utility-first CSS framework used for styling the app. [Tailwind CSS Link](https://tailwindcss.com/)

## Contributions

Contributions are welcome! If you find any issues or have suggestions to improve the project, feel free to submit an issue or pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, you can reach out to the creator on GitHub.
