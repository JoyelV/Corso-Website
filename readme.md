# Corso Training Website

## Overview
The Corso Training Website is a modern, responsive web application designed to deliver a comprehensive platform for training courses, workshops, and seminars. Built with Bootstrap, SCSS, and JavaScript, the website features a visually appealing design with a mix of light and dark color schemes, custom styles, and a professional aesthetic. It aims to empower learners—ranging from beginners to experienced professionals—by providing engaging video content, networking opportunities, and up-to-date industry insights.

<img src="./images/screen.png" />

## Features

- **Modern and Responsive Layout**: A clean, contemporary design with custom colors, styles, and background gradients, fully optimized for all devices.
- **Sticky Navigation Bar**: A fixed-top navbar that dynamically changes its appearance (e.g., background color) based on the user's scroll position.
- **Carousel Image Slider**: A header section with an interactive image slider to showcase promotional content.
- **Registration and Subscription Forms**: User-friendly forms for course registration and email subscriptions to enhance engagement.
- **Font Awesome Icons**: Integrated icons for social media, navigation, and other UI elements, ensuring a polished look.
- **Content-Rich Sections**: Organized sections (e.g., Discover, Summary, Takeaways, Seminars) provide detailed information about the platform’s offerings.
- **Social Media Integration**: Links to platforms like Facebook, Twitter, LinkedIn, Instagram, and YouTube for enhanced connectivity.
- **Customizable Styling**: Utilizes SCSS for modular and maintainable styles, with custom variables for colors, spacing, and typography.

## Technologies Used

- **HTML5**: Structures the website’s content.
- **CSS3/SCSS**: Manages styling, with SCSS for modular and maintainable code.
- **JavaScript**: Adds interactivity, such as the scroll-based navbar effect.
- **Bootstrap 5.2.3**: Provides responsive design and pre-built components.
- **Font Awesome 6.4.0**: Supplies icons for social media and UI elements.
- **Google Fonts**: Incorporates the Montserrat font for a modern, professional typography.
- **Node.js/NPM**: Manages dependencies and SCSS compilation.

## Project Structure

```
├── css/
│   ├── bootstrap.css
│   ├── font-awesome.css
│   ├── styles.css
├── images/
├── js/
│   ├── bootstrap.bundle.min.js
│   ├── script.js
├── scss/
│   ├── bootstrap.scss
│   ├── font-awesome.scss
│   ├── styles.scss
├── index.html
├── package.json
├── README.md
```

## Installation and Setup

To set up the Corso Training Website locally, follow these steps:

### Prerequisites
- **Node.js**: Install Node.js and NPM from [nodejs.org](https://nodejs.org/).
- **Git**: Required to clone the repository.

### Steps
1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd bs5-simple-starter
   ```

2. **Install Dependencies**:
   Install the required dependencies listed in `package.json`:
   ```bash
   npm install
   ```
   This will install Bootstrap, Sass, and Font Awesome.

3. **Compile SCSS to CSS**:
   Compile SCSS files into CSS using the provided NPM script:
   ```bash
   npm run sass:build
   ```
   To automatically recompile during development, use:
   ```bash
   npm run sass:watch
   ```

4. **Serve the Website**:
   Use a local server (e.g., Live Server in VS Code or a simple HTTP server) to view the website:
   ```bash
   npx http-server
   ```
   Alternatively, open `index.html` directly in a browser for static viewing.

5. **Access the Website**:
   Navigate to `http://localhost:8080` (or the port provided by your server) in a web browser.

## Usage

- **Navigation**: Use the sticky navbar to access sections such as Home, Discover, Summary, Takeaways, and Subscribe.
- **Registration**: Complete the registration form in the "Register" section to sign up for courses or seminars.
- **Subscription**: Subscribe to email updates via the form in the "Subscribe" section.
- **Explore Content**: Browse sections like Discover, Summary, and Takeaways to learn about the platform’s training and seminar offerings.
- **Join Seminars**: Register for upcoming events, such as the advertising and marketing seminar on December 22nd, via the call-to-action buttons.

## Customization

To customize the website, modify the following files:

- **Bootstrap Variables**: Add or override Bootstrap variables in `scss/bootstrap.scss`. Refer to `node_modules/bootstrap/scss/_variables.scss` for a complete list of variables. **Note**: Do not edit `node_modules/bootstrap/scss/_variables.scss` directly, as it will be overwritten during updates.
- **Custom Styles**: Add or modify styles in `scss/styles.scss` for custom design changes.
- **SCSS Variables**: Adjust colors, spacing, typography, or other properties in `scss/_variables.scss`.
- **JavaScript**: Enhance interactivity by editing `js/script.js` (e.g., modifying the scroll-based navbar effect).
- **Content**: Update `index.html` to change text, images, or structure.

After making changes to SCSS files, recompile them:
```bash
npm run sass:build
```

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author

Developed by Joyel Varghese.

## Contributing

Contributions are welcome! To contribute, fork the repository, create a new branch, and submit a pull request with your changes. Ensure your code adheres to the project’s coding standards and includes appropriate documentation.

## Contact

For inquiries or support, please contact the project maintainer at Varghesejoyel71@gmail.com