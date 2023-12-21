# Todo App with Next.js, Firebase, and Chakra UI

- User authentication using Firebase.
- CRUD operations for managing todos.
- Real-time synchronization with Firestore.
  
```markdown

## Demo

Include a link to the live demo of your application.

## Features

- List key features of your Todo App.

## Getting Started

### Prerequisites

- Node.js and npm installed.
- Firebase project created.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/todo-app.git
cd todo-app
```

2. Install dependencies:

```bash
npm install
```

## Configuration

Configure your Firebase project:

1. Create a new Firebase project at [Firebase Console](https://console.firebase.google.com/).
2. Obtain your Firebase configuration (apiKey, authDomain, projectId, etc.).
3. Create a `.env.local` file in the project root and add your Firebase configuration:

```env
NEXT_PUBLIC_FIREBASE_API_KEY=your-api-key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your-auth-domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your-project-id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your-storage-bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
NEXT_PUBLIC_FIREBASE_APP_ID=your-app-id
```

## Usage

1. Run the development server:

```bash
npm run dev
```

2. Open your browser and navigate to [http://localhost:3000](http://localhost:3000).
