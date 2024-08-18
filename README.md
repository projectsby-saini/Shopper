# eCommerce Website

An eCommerce application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). This project includes features like product browsing, cart management, order processing, and user authentication.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Screenshots](#screenshots)

## Introduction

This project aims to provide a full-fledged eCommerce platform where users can browse products, manage their cart, and place orders. It features user authentication, product management, and a responsive design for an optimal user experience across devices.

## Features

- User authentication and authorization
- Product browsing and searching
- Shopping cart management (add, update, remove items)
- Order processing and order history
- Responsive design for seamless use on different devices

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/ecommerce-website.git
    cd ecommerce-website
    ```

2. **Install dependencies for the backend:**
    ```bash
    cd ecommerce-backend
    npm install
    ```

3. **Install dependencies for the frontend:**
    ```bash
    cd ../ecommerce-frontend
    npm install
    ```

4. **Set up environment variables:**
    Create a `.env` file in the `ecommerce-backend` directory with the following variables:
    ```plaintext
    PORT=000
    MONGO_URI=your_mongodb_connection_string
    ```

5. **Run the backend server:**
    ```bash
    cd ecommerce-backend
    npm start
    ```

6. **Run the frontend server:**
    ```bash
    cd ../ecommerce-frontend
    npm start
    ```

## Usage

1. Navigate to the frontend application in your browser:
    ```
    http://localhost:3000
    ```

2. Register a new account or log in with existing credentials.

3. Explore the features such as browsing products, managing your cart, and placing orders.

## Project Structure

```plaintext
ecommerce-website/
├── ecommerce-admin/
│   └── [Admin-related files]
├── ecommerce-backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── .env
│   ├── server.js
│   └── [Other backend-related files]
├── ecommerce-frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── App.js
│   │   ├── index.js
│   │   └── [Other frontend-related files]
└── README.md
```

## Technologies Used

- **Frontend:** React.js, Redux, HTML, CSS, Bootstrap, Tailwind CSS
- **Backend:** Node.js, Express.js, MongoDB
- **Authentication:** JSON Web Tokens (JWT)
- **Other Tools:** Git, GitHub

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any inquiries or questions, please contact me at:
- **Email:** [divyanshsaini.mzn@gmail.com](mailto:divyanshsaini.mzn@gmail.com)

## Screenshots

![Screenshot 2024-08-18 234543](https://github.com/user-attachments/assets/d1b043d7-c938-46bc-9663-86cf1431343e)
![Screenshot 2024-08-18 234608](https://github.com/user-attachments/assets/fec53ce3-28d9-4c6c-9944-455801e23601)
![Screenshot 2024-08-18 234723](https://github.com/user-attachments/assets/82e36a70-2d5e-434a-b548-f545c9f1691c)
![Screenshot 2024-08-18 234648](https://github.com/user-attachments/assets/183bf07d-97a3-4177-b1b5-f05ee1ee525c)
![Screenshot 2024-08-18 234822](https://github.com/user-attachments/assets/72dba0b5-fe8c-4f8c-8d3a-8b6f06a91925)
