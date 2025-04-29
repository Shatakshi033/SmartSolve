# SmartSolve - Virtual Math Tutor

SmartSolve is an interactive web-based application designed to help users solve mathematical equations. It uses the **Google Gemini API** to analyze and generate solutions for various mathematical problems, offering an AI-powered virtual math tutor. Users can upload an image of a mathematical question, and the app will extract and solve the problem, providing the solution with detailed explanations.

## Features

- **Image Upload for Math Questions**: Users can upload an image containing a mathematical equation or problem.
- **AI-Powered Solutions**: Using the Google Gemini API, the app processes the image, extracts the mathematical problem, and provides accurate solutions.
- **Mathematical Equation Handling**: Supports a wide range of mathematical problems, including algebra, calculus, and more.
- **Copy Solution**: Easily copy the solution to the clipboard for use elsewhere.
- **User-friendly Interface**: Designed with HTML, CSS, and JavaScript for a smooth and responsive user experience.

## Technologies Used

- **Frontend**:
  - **HTML**: Structuring the web pages.
  - **CSS**: Styling the application for an engaging user experience.
  - **JavaScript**: Handling user interactions, image uploads, API requests, and dynamic content generation.

- **API**:
  - **Google Gemini API**: Used to process and solve mathematical equations. The API is responsible for interpreting the input equations and generating solutions.

- **Image Recognition**:
  - **Tesseract.js**: A JavaScript OCR (Optical Character Recognition) library for extracting text from images.


### 📸 Demo

![Preview](https://github.com/Shatakshi033/SmartSolve/blob/main/Screenshot%20(13).png)

## How It Works

1. The user uploads an image containing a mathematical problem using the file upload feature.
2. The app uses **Tesseract.js** to extract the mathematical equation from the image.
3. The extracted equation is sent as a request to the **Google Gemini API** for processing.
4. The API returns the solution, which is displayed on the page.
5. The user can copy the solution to the clipboard for later use.

## Setup and Installation

To run this project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Shatakshi033/SmartSolve.git
