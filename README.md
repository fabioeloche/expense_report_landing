# N2F Expense Report Website

The N2F Expense Report Website is designed to showcase a user-friendly platform that simplifies expense report management for businesses of all sizes. The main objective of this site is to provide users with a clear understanding of the platform's features, including receipt scanning, corporate card integration, and seamless synchronization with existing company software. The website guides users through the software's benefits and offers a simple way to sign up for a free trial.

![Responsice Mockup](/assests/ScreenShots/N2F%20Responsive.png)

## Table of Contents
1. [Project Overview](#project-overview)
2. [Design](#design)
   - [Color Scheme](#color-scheme)
   - [Typography](#typography)
   - [Layout](#layout)
3. [Features](#features)
   - [Key Features](#key-features)
   - [User Journey](#user-journey)
4. [Code Structure Explanation](#code-structure-explanation)
   - [Header](#header)
   - [Main Content](#main-content)
   - [Hero Section](#hero-section)
   - [Benefits Section](#benefits-section)
   - [Features Section](#features-section)
   - [Footer](#footer)
5. [Future Enhancements](#future-enhancements)
6. [Testing](#testing)
   - [Responsive Design Testing](#responsive-design-testing)
   - [Cross-browser Testing](#cross-browser-testing)
   - [Form Validation Testing](#form-validation-testing)
   - [Validator Testing](#validator-testing)
   - [Unfixed Bugs](#unfixed-bugs)
7. [Deployment](#deployment)
8. [Technologies Used](#technologies-used)
9. [Credits](#credits)

## Project Overview
The N2F Expense Report Website serves as a hub for businesses to learn about the platform’s key features and quickly sign up for a trial. N2F enables companies to save time and resources by automating the process of tracking expenses, generating corporate cards, and integrating with existing accounting software. The website is designed to be responsive and visually appealing, allowing users to easily access the information they need on any device.

## Design

### Color Scheme
The website uses a sleek black background with white text, providing a clean and professional look. Orange and yellow gradients are used to highlight buttons and headers, adding visual emphasis to important calls-to-action, such as the sign-up button.

### Typography
The website uses two fonts from Google Fonts:
- **Oswald** for headings, providing a bold and modern look.
- **Lato** for body text, ensuring readability across different screen sizes and devices.

### Layout
The layout is designed to be responsive, ensuring a consistent user experience across desktops, tablets, and mobile devices. The grid system allows content to be displayed clearly, with enough space for users to navigate the site effortlessly.

## Features

### Key Features
- **Responsive Hero Video:** The homepage features a full-screen video that plays automatically, providing an immediate visual representation of the N2F platform. It engages users from the start and includes a prominent call-to-action for signing up.
- **Receipt Scanning:** Users can scan receipts in under 5 seconds using N2F’s built-in AI-powered OCR (Optical Character Recognition) technology. This feature is central to the platform and saves businesses valuable time.
- **Corporate Card Integration:** N2F allows companies to issue corporate cards to employees, which can be used for expense tracking and reporting. The integration of these cards into the platform ensures that all expenses are accounted for automatically.
- **Seamless Software Integration:** N2F integrates directly with a company’s accounting and payroll software, allowing for a smooth transfer of data and reducing the need for manual entry.

### User Journey
The website is designed to guide users through a seamless journey:
- **Homepage:** Visitors are welcomed with an engaging hero video and clear messaging about the platform’s key benefits. A prominent "Sign Up" button encourages users to start their free trial.
- **Features Page:** The features are outlined in detail, with easy-to-understand descriptions of each. This page focuses on the time and cost savings offered by N2F and the ease of integrating it with existing systems.
- **Sign-Up Page:** The sign-up process is kept simple, with a form that asks for basic details such as the user’s first name, last name, and email address. The goal is to reduce friction and make it easy for potential users to get started.

![Sign Up](/assests/ScreenShots/Sign%20up%20form.png)

- **Footer:** Available on every page, the footer provides links to N2F’s social media channels (Twitter, Facebook, YouTube) for further engagement.

## Code Structure Explanation

### Header
The header section of the site includes the logo and navigation menu. The navigation menu contains links to the Home, Features, and Sign-Up pages. On mobile devices, the navigation collapses into a menu that can be toggled by clicking an icon. This ensures that the site remains easy to navigate, regardless of the device being used.

![Header](/assests/ScreenShots/header%20section.png)

### Main Content
The main content of the site is divided into various sections, each with a clear focus. These sections include the hero, benefit, features, and footer sections.

### Hero Section
The hero section includes a full-screen video that auto-plays when the page loads. This video provides a dynamic and engaging introduction to N2F’s key features. Positioned over the video is a brief message that highlights the platform’s core benefit: saving time and money on expense management.

### Benefits Section
The benefits section emphasizes the time and cost savings that N2F can provide. A clear message is displayed, along with a button that leads users directly to the sign-up page. Additionally, a demo video is embedded to showcase how the platform works in a real-world scenario.

![Video](/assests/ScreenShots/Hero%20Section%20Video.png)

### Features Section
The features section uses a grid layout to showcase N2F’s five core features:
1. **Smart Scan** – Quickly scans receipts.
2. **Receipt Storage** – Stores receipts in compliance with legal requirements.
3. **Corporate Payment Cards** – Issuance of cards for business trips.
4. **Integration with Company Software** – Seamless integration with accounting software.
5. **Approval Workflow** – Automates the approval of reimbursements.

This section is designed to be easily scannable, allowing users to quickly grasp the platform’s main selling points.

![features](/assests/ScreenShots/Features%20Section.png)

### Footer
The footer provides links to N2F’s social media pages, encouraging users to follow and engage with the platform. It also reinforces the professionalism of the site by maintaining consistency across all pages.

![footer](/assests/ScreenShots/footer%20Section.png)

## Future Enhancements 
- **Enhanced Analytics Dashboard:** In future iterations, a detailed analytics dashboard could be added, providing businesses with insights into their spending patterns and helping them make data-driven decisions.
- **Multi-language Support:** To accommodate a global audience, language localization can be implemented, allowing users to view the site and use the platform in their preferred language.
- **Additional Payment Integrations:** More corporate payment card providers could be integrated into the platform, expanding N2F’s reach.

## Testing

### Responsive Design Testing
The site was thoroughly tested across various devices, including desktops, tablets, and smartphones, to ensure that the layout and design adapt seamlessly to different screen sizes.

### Cross-browser Testing
The site was tested on all major browsers, including Google Chrome, Firefox, Microsoft Edge, and Safari. No significant issues were found, and the site performed consistently across all platforms.

### Form Validation Testing
The sign-up form was tested to ensure that:
- All required fields are validated (first name, last name, email address).
- The email format is validated before submission to ensure accuracy.

### Validator Testing
- **HTML Validation:** The HTML files were validated using the W3C HTML Validator, and no significant issues were found. [Test W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2F8000-fabioeloche-expenserepo-cgapq5wdey2.ws-eu116.gitpod.io%2Findex.html)
- **CSS Validation:** The CSS files passed through the W3C Jigsaw Validator with no errors. [Test (Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2F8000-fabioeloche-expenserepo-cgapq5wdey2.ws-eu116.gitpod.io%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=it)
- **Accessibility Testing:** The website was evaluated using Lighthouse, achieving high scores in accessibility and performance.

### Unfixed Bugs
- **Legacy Browser Support:** Older versions of Internet Explorer do not fully support certain CSS3 features such as flexbox and grid. As a result, the layout may not appear as intended on these browsers.

## Deployment
The N2F Expense Report Website was deployed using GitHub Pages. To deploy the project, follow these steps:
1. Navigate to the GitHub repository’s **Settings** tab.
2. Select the **Pages** option under the "Code and Automation" section.
3. Choose the **main branch** as the source for deployment.
4. Save the settings, and the site will be deployed live.

The live version of the site can be found at: [N2F Expense Report](#).

## Technologies Used
- **HTML5:** For structuring the content of the website.
- **CSS3:** For styling the website and creating responsive layouts.
- **Font Awesome:** For adding social media icons to the footer.
- **Google Fonts:** For the Oswald and Lato fonts used throughout the site.
- **GitHub Pages:** For hosting the live version of the website.


