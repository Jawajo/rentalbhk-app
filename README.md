# RentalBHK - AI-Powered Property Rental Platform

RentalBHK is a modern, AI-powered property rental platform built with Next.js, Firebase, and Google's Genkit. It provides a seamless and secure experience for tenants to find properties and for owners to list and manage them.

## Key Features

- **AI-Powered Search**: Tenants can use natural language queries (e.g., "Find a 2BHK in Chennai under 25k") to discover properties.
- **AI-Assisted Verification**: Property listings are analyzed by an AI flow that compares submitted details with document information to provide a verification score, enhancing trust.
- **Secure Online Rentals**: A complete online flow for the first month's rent, including owner OTP confirmation, secure payments, and an official rental certificate.
- **Admin & Super Admin Dashboards**: Comprehensive dashboards to manage pending verifications, users, platform revenue, and financial settings.
- **User Authentication**: Secure sign-up and login for tenants, owners, and admins using Firebase Authentication.
- **Multi-Step Property Listing**: An intuitive, multi-step form for property owners to list their properties, including document uploads and live location detection.
- **Secure Chat**: A built-in, private communication channel between tenants and property owners.

## Technology Stack

- **Framework**: [Next.js](https://nextjs.org/) (App Router)
- **AI Framework**: [Genkit](https://firebase.google.com/docs/genkit) (with Google Gemini)
- **Backend & Database**: [Firebase](https://firebase.google.com/) (Firestore, Firebase Auth, App Hosting)
- **UI Components**: [ShadCN UI](https://ui.shadcn.com/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Form Management**: [React Hook Form](https://react-hook-form.com/) & [Zod](https://zod.dev/)

## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

- Node.js (v20 or newer recommended)
- npm or yarn

### Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/rentalbhk.git
    cd rentalbhk
    ```

2.  **Install NPM packages:**
    ```sh
    npm install
    ```

3.  **Set up environment variables:**
    Create a `.env` file in the root of your project and add your Firebase project configuration keys:
    ```
    NEXT_PUBLIC_FIREBASE_API_KEY=
    NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
    NEXT_PUBLIC_FIREBASE_PROJECT_ID=
    NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
    NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
    NEXT_PUBLIC_FIREBASE_APP_ID=
    ```

4.  **Run the development server:**
    ```sh
    npm run dev
    ```
    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Deployment

This application is configured for easy deployment with [Firebase App Hosting](https://firebase.google.com/docs/app-hosting). The `apphosting.yaml` file in the root directory contains the necessary build and run configurations.
cd path/to/your/rentalbhk-app
git init
git add .
git commit -m "Initial commit of RentalBHK project"
git remote add origin https://github.com/your-username/rentalbhk-app.git
git push -u origin main
