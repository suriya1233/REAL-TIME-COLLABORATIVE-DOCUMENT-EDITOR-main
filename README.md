Getting Started
Follow these steps to run RealTimeEdify locally:

Clone the repository:

git clone https://github.com/your-username/RealTimeEdify.git
cd RealTimeEdify
Install dependencies for frontend:

   cd src
   cd client
   npm i
Install dependencies for backend:
   cd src
   npm i
Set up .env variables by creating a .env file in the server directory and adding the following variables:
For server side:
 MONGODB_URI=your_mongo_db_uri
 JWT_SECRET=your_jwt_secret
 PORT=8000
 PASSWORD=your_app_password_for_email
 EMAIL=your_gmail_email
 BACKEND_URL=your_backend_url/api/v1
 FRONTEND_URL=your_frontend_url
 PRODUCTION=false
Replace your_mongodb_connection_string, your_jwt_secret, your_email_username, your_email_password, your_email_host, and your_email_port with your own values.

Note: If you are using Gmail for sending emails, you need to enable "Less secure app access" in your Google account settings.

For client side:
 VITE_APP_BACKEND_URL=your_backend_url/api/v1
 VITE_APP_SOCKET_URL=your_backend_url
Replace your_backend_url with the URL where the backend server is running.

Run the frontend
  cd src
  cd client
  npm run dev
Run the backend
  cd src
  npm run dev
Access the application in your browser at http://localhost:5173.

Create an account and start collaborating on documents!

Contributing
Contributions are welcome! Please refer to the Contributing Guidelines for more information.

License
This project is licensed under the MIT License - see the LICENSE file for details.
