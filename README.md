# Podcast

Podcast is a web application designed to create, manage, and share podcasts. It features advanced capabilities such as AI-powered podcast creation, text-to-speech conversion, and random image generation.

## Features

- **User Authentication:** Secure user sign-in and registration using Clerk.
- **Podcast Management:** Create, edit, and delete podcast episodes.
- **Text-to-Speech:** Users can type text and choose a voice to have it read aloud.
- **AI Integration:** Leverage OpenAI for generating random images for podcast content.
- **Responsive Design:** A seamless experience across devices.

## Technologies Used

- **Next.js:** A React framework for server-side rendering and building static web applications.
- **React:** A JavaScript library for building user interfaces.
- **Tailwind CSS:** A utility-first CSS framework.
- **Clerk:** Authentication and user management.
- **React Hook Form:** A library for managing form state and validation in React.
- **OpenAI:** Integration for AI-powered content generation and image creation.
- **Radix UI:** A collection of accessible and customizable React components.
- **Convex:** Real-time data and event handling.

## Getting Started

### Prerequisites

Ensure you have Node.js and npm installed on your machine.

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Tommysons/podcast.git
    cd podcast
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

### Environment Variables

Create a `.env.local` file in the root directory and add your environment variables:
```env
CONVEX_DEPLOYMENT=your_convex_deployment
NEXT_PUBLIC_CONVEX_URL=your_convex_url

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
CLERK_WEBHOOK_SECRET=your_clerk_webhook_secret

# Next Clerk Sign In/Sign Up URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL='/sign-in'
NEXT_PUBLIC_CLERK_SIGN_UP_URL='/sign-up'

# OpenAI
OPENAI_API_KEY=your_openai_api_key
