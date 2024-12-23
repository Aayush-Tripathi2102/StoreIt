# Storage Management Solution

A web application built with Next.js, Appwrite, and Tailwind CSS, allowing users to store, manage, and share files securely. The platform supports account creation, file storage up to 2GB, file sharing, sorting, and deletion.

## Features

- **User Accounts**: Create and manage user accounts.
- **File Upload and Storage**: Upload and store files up to 2GB per user.
- **File Management**: Organize, delete, and sort files.
- **File Sharing**: Share files with others securely.
- **Responsive Design**: A fully responsive UI built with Tailwind CSS.

## Tech Stack

- **Frontend**: Next.js, Tailwind CSS
- **Backend**: Appwrite (for authentication, file storage, and database management)
- **Authentication**: Appwrite's built-in authentication system
- **File Storage**: Appwrite for secure file storage
- **UI**: Tailwind CSS for a sleek, responsive design

## Installation

### Prerequisites

- Node.js and npm
- Appwrite (set up Appwrite server locally or use a cloud instance)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Aayush-Tripathi2102/StoreIt.git
2. Navigate into the project directory:
   ```bash
   cd storeIt-main
3. Install the dependencies:
   ```bash
   npm install
4. Set up the Appwrite client and API keys:
   - Create an Appwrite project and configure the necessary services (Auth, Storage).
   - Add your Appwrite endpoint and project ID to a `.env.local` file.
5. Start the application:
   ```bash
   npm run dev
  The app should now be running on `http://localhost:3000.`
  
## Usage

  - **Create Account:** Sign up or log in using the authentication system.
  - **Upload Files:** Upload files up to 2GB and manage them in your personal space.
  - **Organize Files:** Sort and organize your files for better management.
  - **Delete Files:** Remove unnecessary files from your storage.
  - **Share Files:** Share files with others via links or access permissions.

## Hope you enjoy StoreIt!

Thank you for using StoreIt. We hope it makes your file storage and management easier and more efficient. Have fun exploring!


