# PDF to Word Converter

A web application built with Node.js for converting PDF files to Word (.docx) files. The app uses Cloudinary for uploading and storing images and files, providing a seamless and efficient conversion process.

## Features
- Upload PDF files and convert them to Word (.docx) format.
- Store and manage files using Cloudinary.
- Simple and user-friendly interface.
- Responsive design using Tailwind CSS.

## Technologies Used
- Node.js
- Express
- Cloudinary
- Mammoth.js for Word conversion
- pdf-lib for PDF manipulation
- Tailwind CSS for styling

## Getting Started
To get a local copy up and running, follow these steps.

### Prerequisites
- Node.js and npm installed on your machine.
- Cloudinary account for file storage.

### Installation
1. Clone the repo:
    ```sh
    git clone https://github.com/raj-bhanderi/pdf-to-word-converter-backend.git
    ```
2. Navigate to the project directory:
    ```sh
    cd pdf-to-word-converter-backend
    ```
3. Install dependencies:
    ```sh
    npm install
    ```
4. Create a `.env` file in the root directory and add your Cloudinary credentials:
    ```env
    CLOUDINARY_CLOUD_NAME=your_cloud_name
    CLOUDINARY_API_KEY=your_api_key
    CLOUDINARY_API_SECRET=your_api_secret
    ```

### Usage
1. Start the development server:
    ```sh
    npm start
    ```
2. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## License
Distributed under the MIT License. See `LICENSE` for more information.

Project Link: [https://github.com/raj-bhanderi/pdf-to-word-converter-backend](https://github.com/raj-bhanderi/pdf-to-word-converter-backend)
