
![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)


# ContentifyAI

ContentifyAI is an innovative blogging platform built with Next.js and MongoDB, designed to simplify content creation with AI-powered tools like Gemini for text generation and Stable Diffusion for image generation. This app empowers users to effortlessly create, organize, and enhance blog content, making it an ideal tool for bloggers and content creators looking for intelligent content solutions.

## Features

- AI-Powered Text Generation: Gemini integration provides AI-suggested content, making blog creation faster and easier.

- AI Image Generation: Enhance posts with unique images created by Stable Diffusion, adding visual appeal.

- Organized Content: Manage posts with categories and tags for easy navigation and discoverability.

- User Authentication: Secure login and signup system using Auth0.

- Interactive Comments: Readers can engage with posts by leaving comments, fostering a community around content.

- Responsive Design: Optimized for both desktop and mobile devices for a seamless user experience.


## Demo

working....


## Installation

#### Prerequisites

- Node.js (v16+)
- MongoDB (self-hosted or MongoDB Atlas)
- Auth0 (for authentication)
- Environment Variables:

    `MONGODB_URI: MongoDB connection    string.`

    `AUTH0_DOMAIN` and `AUTH0_CLIENT_ID:Auth0 credentials.` 

    `GEMINI_API_KEY` and `STABLE_DIFFUSION_API_KEY:` API keys for AI integrations.


### Steps

- Clone the repository:
    ```bash
    git clone https://github.com/BilalShahid-13/ContentifyAI.git
    cd ContentifyAI
    ```

- Install dependencies:
    ```bash
    npm install
    ```

- Create a .env.local file and add your environment variables:
    ```bash
    MONGODB_URI=your_mongodb_uri
    AUTH0_DOMAIN=your_auth0_domain
    AUTH0_CLIENT_ID=your_auth0_client_id
    GEMINI_API_KEY=your_gemini_api_key
    STABLE_DIFFUSION_API_KEY=your_stable_diffusion_api
    ```

- Start the development server:
    ```bash
    npm run dev
    ```

- Open http://localhost:3000 to view the app in your browser.



    

       
## Usage

**Creating a Post**
Navigate to the "New Post" section. Use Gemini to generate text suggestions and Stable Diffusion for custom images.

**Managing Content:**
 Assign categories and tags to organize posts for easy navigation.

**User Interaction:** Users can comment on posts and interact with other community members.




## Entity Relationship Diagram (ERD)

This ERD outlines the database structure for ContentifyAI.

![App Screenshot](https://github.com/BilalShahid-13/ContentifyAI/blob/main/Readme_Stuff/DBMS%20ER%20diagram.png?raw=true)


## Feedback

If you have any feedback, please reach out to us at codingwithbilal.pro@gmail.com


## 🛠 Skills
Javascript, HTML, CSS,React,Nextjs,gsap...


## 🚀 About Me
I'm a full stack developer...

## Authors

- [@Bilal Shahid](https://www.github.com/BilalShahid-13)

## Badges

This project is licensed under the MIT License. See the LICENSE file for details.

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
