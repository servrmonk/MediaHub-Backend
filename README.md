# Mini YouTube Backend
(Some Features like video uploading are still underdeveloped :))

## Overview
The Mini YouTube Backend is a RESTful API built with Node.js, Express, and MongoDB, enabling users to create, manage, and interact with video content securely.

## Key Features
- **Subscription Management**: Users can subscribe to channels, enhancing community engagement and personalization.
- **Watch History Tracking**: Maintains personalized watch history for easy access to favorite videos.
- **Dynamic Video Management**: Users can upload, edit, and manage video content, including titles and descriptions.
- **MongoDB Aggregation & User Authentication**: Leverages MongoDB aggregation pipelines for efficient data processing and secure registration/login using JWT and OAuth.
- **Robust Security & Error Handling**: Middleware ensures role-based access control, while custom error handling provides consistent API responses.

## Installation
1. Clone the repository:
   ```bash
2. Install dependencies
 npm install
3. Set up environment variables in a .env file:
MONGODB_URI=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret
4. Configure Db
5. Run the apk :  npm run dev


