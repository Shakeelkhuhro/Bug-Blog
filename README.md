# Bug Blog

**Bug Blog** is a blogging web application built with the MERN stack, allowing users to create their own blogs, view and react to others' blogs, and share their thoughts with each other.

## Environment Variables

To run this project, you will need to add the following environment variables:

### Server (.env file)

- `MONGO_PASSWORD`
- `SALT_ROUNDS`
- `JWT_SECRET`
- `CLOUD_NAME`
- `API_KEY`
- `API_SECRET`

### Client (.env.local file)

- `REACT_APP_BASE_URL`

## Deployment

The web app is deployed on Netlify and can be accessed through the following link:

[Bug Blog on Netlify](https://bugblog.netlify.app/)

## Tech Stack

- **Client:** React, React-Bootstrap, CKEditor 5
- **Server:** Node.js, Express.js, MongoDB
- **Deployment:**
  - Frontend: Netlify
  - Backend: Render

## Run Locally

To run the project locally, follow these steps:

1. Clone the project repository:

   ```bash
   git clone https://github.com/shakeelkhuhro/Bug-Blog.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Bug-Blog
   ```

3. Install dependencies for both client and server:

   ```bash
   cd server
   npm install

   cd ../client
   npm install
   ```

4. Set up the `.env` file for the server and `.env.local` for the client with the necessary environment variables.

5. Start both the server and client on separate terminals:

   For the server:

   ```bash
   cd server
   npm run dev
   ```

   For the client:

   ```bash
   cd client
   npm start
   ```

## Features

- Rich Text Editor for Blog Writing
- Search for Blogs
- Like and Comment on Blogs
- Secure Account Encryption

## Feedback

If you have any feedback, feel free to reach out to us.

## Contributing

Contributions are always welcome! Please feel free to submit a pull request.

## Author

- **Shakeel Khuhro** - [GitHub](https://github.com/shakeelkhuhro)

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).
