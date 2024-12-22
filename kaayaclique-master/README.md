# KaayaClique

## Overview
**KaayaClique** is a full-stack application that offers personalized skincare solutions to users. It combines advanced data analysis, e-commerce features, and intelligent recommendations to provide tailored suggestions for skincare products based on individual needs. The platform aims to enhance user experience by integrating seamless navigation and secure payment options.

---

## Features
- **Personalized Recommendations**: Users can input their skin type and concerns to receive curated skincare product suggestions.
- **E-Commerce Functionality**: Browse and purchase skincare products directly through the platform.
- **Secure Payments**: Supports payments via **Braintree/PayPal**.
- **User Authentication**: Enables account creation and login using **Google OAuth**.

---

## Tech Stack
### Frontend
- **ReactJS**: Component-based UI design.
- **Tailwind CSS**: For a responsive and modern UI.

### Backend
- **NodeJS**: Handles server-side operations.
- **ExpressJS**: Simplifies API and server management.

### Database
- **MongoDB**: Stores user data and product information efficiently.

### Additional Libraries and Tools
- **PassportJS**: Authentication middleware for Google OAuth.
- **Braintree/PayPal**: Integrates secure payment gateways.
- **Google APIs**: For OAuth authentication and enhanced user experience.

---

## Installation
Follow these steps to set up the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ShiviTripathi13/kaayaclique
   cd KaayaClique
   ```

2. **Install Dependencies**:
   - For the server:
     ```bash
     cd server
     npm install
     ```
   - For the frontend:
     ```bash
     cd src
     npm install
     ```

3. **Set Up Environment Variables**:
   - Create a `.env` file in the `server` directory with the following:
     ```env
     PORT=8000
     MONGO_URI=your_mongodb_connection_string
     PAYPAL_CLIENT_ID=your_paypal_client_id
     GOOGLE_CLIENT_ID=your_google_client_id
     GOOGLE_CLIENT_SECRET=your_google_client_secret
     ```

4. **Start the Development Server**:
   - Start the backend:
     ```bash
     cd server
     npm run dev
     ```
   - Start the frontend:
     ```bash
     cd src
     npm start
     ```

5. **Access the Application**:
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Folder Structure
```
KaayaClique/
├── node_modules/
├── public/
├── server/
│   ├── config/
│   ├── controllers/
│   ├── db/
│   ├── helpers/
│   ├── middlewares/
│   ├── model/
│   ├── routes/
│   ├── node_modules/
│   ├── server.js
│   ├── package.json
│   └── package-lock.json
├── src/
│   ├── assets/
│   ├── Components/
│   ├── context/
│   ├── hooks/
│   ├── Pages/
│   ├── UserProtectedRoutes/
│   ├── App.css
│   ├── App.js
│   ├── App.test.js
│   ├── index.css
│   ├── index.js
│   ├── logo.svg
│   ├── reportWebVitals.js
│   ├── setupTests.js
│   ├── tailwind.config.js
│   └── postcss.config.js
├── .gitignore
├── package.json
├── package-lock.json
├── tailwind.config.js
├── postcss.config.js
└── README.md
```

---

## Future Enhancements
- **Machine Learning Integration**: Implement a recommendation engine using a Random Forest Classifier for advanced product suggestions.
- **Mobile App Development**: Extend the platform to mobile devices.
- **Image Analysis**: Implement image-based skin analysis using computer vision.
- **Subscription Plans**: Add subscription-based personalized skincare regimens.
- **Enhanced Recommendations**: Incorporate user feedback to refine product suggestions.

---

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---



## Contact
For any queries or feedback, please reach out to:
- **Shivangi Tripathi**
- **GitHub**: [ShiviTripathi13](https://github.com/ShiviTripathi13)
