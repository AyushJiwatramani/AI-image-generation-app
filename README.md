# AI Image Generation App

This repository contains the source code for an AI Image Generation App built using Node.js, Express.js, MongoDB, and React.js (forming the powerful MERN stack). The app leverages the capabilities of OpenAI's DALL-E model to generate images from text input. Additionally, the app utilizes the popular CSS framework Tailwind for styling and Cloudinary for cloud-based image storage.

## Features

- **Image Generation**: Users can input text descriptions, and the app will generate corresponding images using the powerful DALL-E model.
- **Cloud Storage**: Generated images are stored and managed using Cloudinary, a cloud-based image storage service.
- **MERN Stack**: The app is built using the MERN (MongoDB, Express.js, React.js, Node.js) stack, providing a robust and scalable foundation.

## Prerequisites

Make sure you have the following installed before running the app:

- Node.js (v12 or above)
- MongoDB
- Cloudinary account (with API credentials)

## Installation

1. Clone this repository to your local machine.
2. Install the dependencies by running the following command in both the root directory and the `client` directory:
   ```
   npm install
   ```
3. In the root directory, create a `.env` file and provide the necessary environment variables:
   ```
   MONGODB_URI=<your_mongodb_uri>
   CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>
   CLOUDINARY_API_KEY=<your_cloudinary_api_key>
   CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
   ```
4. Start the server by running the following command in the root directory:
   ```
   npm start
   ```
5. In a separate terminal, navigate to the `client` directory and start the React development server:
   ```
   npm start
   ```
6. Open your web browser and visit `http://localhost:5137` to access the app.

## Usage

1. Enter a text description in the input field.
2. Click the "Generate" button to generate an image based on the entered text.
3. The generated image will be displayed on the page.
4. To store the generated image, click the "Save" button. The image will be uploaded to Cloudinary and stored for future access.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.


## Acknowledgments

- The app utilizes OpenAI's DALL-E model for image generation. Learn more about DALL-E [here](https://openai.com/research/dall-e/).
- Tailwind CSS is used as the CSS framework for styling the app. Learn more about Tailwind [here](https://tailwindcss.com/).
- Cloudinary is used for cloud-based image storage. Learn more about Cloudinary [here](https://cloudinary.com/).
