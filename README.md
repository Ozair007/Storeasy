# Storeasy

Storeasy is a secure, user-friendly file storage and sharing platform built as an alternative solution to Google Drive and Dropbox. Developed with **Next.js**, **TailwindCSS**, and **Appwrite**, Storeasy provides a seamless experience for managing files online with an emphasis on simplicity, speed, and privacy.

## Features

- **Secure Cloud Storage**: Upload and manage your files securely in the cloud.
- **File Sharing**: Easily share files with others via links.
- **Real-Time Updates**: Instant syncing and access to updated files across devices.
- **Responsive Design**: Optimized for both desktop and mobile devices with TailwindCSS.
- **User Authentication**: Secure login and signup with Appwrite authentication.
- **Organized File Management**: Create folders, rename files, and manage your storage intuitively.

## Tech Stack

- **[Next.js](https://nextjs.org/)** - React framework for server-side rendering and static site generation.
- **[TailwindCSS](https://tailwindcss.com/)** - Utility-first CSS framework for fast and responsive design.
- **[Appwrite](https://appwrite.io/)** - Backend-as-a-service platform providing authentication, database, and storage.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.
- [Appwrite](https://appwrite.io/docs) instance configured for storage and authentication.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ozair007/storeasy.git
   cd storeasy
2. **Install dependencies:**
   ```bash
   npm install
3. **Configure Environment Variables:**
   ```bash
   NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
   NEXT_PUBLIC_APPWRITE_PROJECT=""
   NEXT_PUBLIC_APPWRITE_DATABASE=""
   NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=""
   NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=""
   NEXT_PUBLIC_APPWRITE_BUCKET=""
   NEXT_APPWRITE_KEY=""
4. **Run the development server:**
   ```bash
   npm run dev
5. **Open in Browser:** Visit http://localhost:3000 to start using Storeasy.

