# PDF QnA Frontend

This is the frontend for the PDF QnA application, enabling users to upload PDF documents, ask questions about their content, and view AI-generated answers in a user-friendly interface.

---

## Features

- Responsive UI for uploading PDFs and asking questions.
- Displays uploaded files and generated answers.
- Communicates with the backend to process PDFs and retrieve answers.
- Built using React and TailwindCSS for styling.

---

## Getting Started

### Prerequisites

- Node.js and npm (or Yarn)
- A running instance of the [PDF QnA Backend](../backend/README.md)

---

### Installation

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd frontend

    Install Dependencies

npm install

Set Up Environment Variables Create a .env file in the root of the frontend directory:

    VITE_API_BASE_URL=http://127.0.0.1:8000

Usage

    Start the Frontend

npm run dev

Access the Application Open your browser and go to:

    http://127.0.0.1:5173

Scripts

    Start Development Server

npm run dev

Build for Production

npm run build

Preview Production Build

    npm run preview

Styling

This project uses TailwindCSS for utility-first styling.

    To modify styles, edit the src/index.css or update the Tailwind configuration in tailwind.config.js.
