# WedsIn Website

A modern React-based web application for WedsIn, featuring a comprehensive pressroom, job listings, and information about the company.

## Overview

This project is the frontend website for WedsIn, built using React. It includes various sections such as a blog (Pressroom), contact information, FAQs, and job opportunities. The application utilizes React Router for navigation and Bootstrap for styling.

## Key Features

- **Pressroom/Blog**: A dedicated section for news and articles, including individual blog post views.
- **Company Information**: Detailed "About Us" and "Contact Us" pages.
- **Support**: A Frequently Asked Questions (FAQ) section.
- **Careers**: A "Jobs" section for listing open positions.
- **Legal**: Privacy Policy and Terms of Service pages.
- **Responsive Design**: Built with Bootstrap and custom CSS for a responsive layout.
- **Carousels**: Integrated `react-slick` and `react-multi-carousel` for dynamic content display.

## Technology Stack

- **Frontend Framework**: React 18
- **Routing**: React Router DOM 6
- **Styling**: Bootstrap 5, Slick Carousel CSS
- **Build Tool**: React Scripts (Create React App)

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm (Node Package Manager)

### Installation

1.  Clone the repository:

2.  Install dependencies:
    ```bash
    npm install
    ```

### Usage

1.  Start the development server:
    ```bash
    npm start
    ```
    Runs the app in the development mode.\
    Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

2.  Build for production:
    ```bash
    npm run build
    ```
    Builds the app for production to the `build` folder.\
    It correctly bundles React in production mode and optimizes the build for the best performance.

3.  Run tests:
    ```bash
    npm test
    ```

## Project Structure

- `src/MainApp.js`: Main entry point setting up routes.
- `src/Website`: Core website components.
- `src/Pressroom`: Blog and press related components.
- `src/ContactUs`: Contact page components.
- `src/AboutUs`: About page components.
- `src/Faq`: FAQ page components.
- `src/Jobs`: Jobs page components.
