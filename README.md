<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

## Description

This project is a NestJS application designed to upload files to Cloudinary. It uses the NestJS framework along with Cloudinary integration to provide an efficient and scalable solution for cloud file management.

## Project Setup

Make sure you have pnpm installed on your system. Then, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/rody-huancas/upload-file-nestjs-cloudinary.git
   ```

2. Navigate to the project directory:
   ```bash
   cd upload-file-nestjs-cloudinary
   ```

3. Install dependencies:
   ```bash
   pnpm install
   ```

4. Configure environment variables:
   - Create a `.env` file in the project root.
   - Add the following variables:
     ```bash
     CLOUDINARY_NAME=your_cloud_name
     CLOUDINARY_API_KEY=your_api_key
     CLOUDINARY_API_SECRET=your_api_secret
     ```

5. Start the development server:
   ```bash
   pnpm run start:dev
   ```

## API Documentation

The API provides two main routes for file management:

1. **Upload a file:**
   - Method: POST
   - URL: `/api/upload`
   - Body: FormData with the file to upload
