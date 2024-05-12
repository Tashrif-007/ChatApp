# ChatApp

Welcome to ChatApp, a React-based chat application powered by MongoDB, Express, DaisyUI, and Tailwind CSS.
It is learnt from *AS A PROGRAMMER* YouTube Channel.

## Getting Started

To run this application locally, follow these steps:

1. Clone the repository to your local machine:
```bash
git clone https://github.com/your-username/chatapp.git
```
2. Install Dependencies for both backend and frontend
```bash
cd chatapp/backend
npm install

cd ../frontend
npm install
```
3. Create a .env file in the root directory of the backend folder (chatapp/backend) with the following environment variables:
```
PORT=5000
JWT_SECRET_KEY=your_secret_key
MONGO_DB_URI=your_mongodb_uri
```
4. Update the socket context file located at frontend/src/context/socketcontext.jsx. Replace 'http://localhost:5000' with your local server URL.
5. Start the backend server:
```bash
cd ../backend
npm run server
```
6. Start the frontend development server:
```bash
cd ../frontend
npm run dev
```
7. Access the application in your web browser at 'http://localhost:*SERVER_URL*'
