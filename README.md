# Content Management System for Portfolios

This is a Content Management System (CMS) specifically designed for creating and managing portfolios. It provides a user-friendly interface for developers and technical writers to showcase their work and manage their portfolio websites. The CMS is built using TypeScript, React, Node.js, and Express.js.

## Features

- User-friendly interface for managing portfolio content
- Easy customization of portfolio websites using React components
- Seamless integration with MongoDB Atlas for data storage
- Secure authentication using JSON Web Tokens (JWT)
- Image uploading and storage using AWS S3 bucket

## Installation

To install and run this CMS locally, please follow these steps:
1. Clone the repository:
2. Navigate to the `portfolio-back-end` folder:
cd custom_portfolio_cms/back_end_node/node-CMS/portfolio-back-end

3. Install the dependencies:
yarn or if you are using NPM delete yarn.lock file and npm install 
4. Create a `.env` file in the `back_end_node` folder and add the following environment variables:
- MONGO_URL=your-mongo-db-atlas-link
- JWT_STRING=custom-string-for-JWT-token-authentication-for-admin-user
- AWS_BUCKET_NAME=s3-bucket-name
- AWS_ACCESS_KEY=aws-access-key
- AWS_SECRET_KEY=aws-secret-key
5. Start the server:
yarn start or npm start port is set `http://localhost:3000`
6. Navigate to the `portfolio-pannel` folder:
yarn or if you are using NPM delete yarn.lock file and npm install 

8. Start the React development server:
this is vite server, use yarn run dev or npm run dev

. press key O to Open your browser and visit dev server.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request.

Please ensure that your code adheres to the existing coding style and that you have tested your changes thoroughly.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your own purposes.

## Acknowledgments

We would like to thank the following resources for their valuable contributions:

- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) - Managed MongoDB service
- [AWS S3](https://aws.amazon.com/s3/) - Simple Storage Service for storing images
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework

## Contact

If you have any questions or suggestions, please feel free to contact me:

 
-  Developer: Giorgi kutateladze (g.kutateli@gmail.com)

We appreciate your interest and contributions to this project!
