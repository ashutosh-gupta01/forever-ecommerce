# Forever – Full Stack E-commerce Platform

Forever is a full-stack e-commerce web application built using the MERN stack. It provides an online shopping experience where customers can explore products, manage their shopping cart, and place orders. A dedicated admin dashboard supports product and order management, while Razorpay integration enables online payments.

## 🌐 Live Demo

- **Customer Website:** [Visit Forever](https://forever-ecommerce-frontend-qmfc.onrender.com/)
- **Admin Panel:** [Open Admin Dashboard](https://forever-ecommerce-admin-brfe.onrender.com/)
- **Backend API:** [Forever Backend](https://forever-ecommerce-backend-4cfh.onrender.com)
- **GitHub Repository:** [View Source Code](https://github.com/ashutosh-gupta01/forever-ecommerce)

##  Features

###  Customer Features

- **Product Catalog:** Browse products and view product details.
- **Product Filtering:** Explore products using available categories and filters.
- **Shopping Cart:** Add products to the cart and manage quantities.
- **User Authentication:** Register and log in to access account features.
- **Order Placement:** Place orders through the checkout flow.
- **Online Payments:** Razorpay integration for payment processing.
- **Order Management:** View order information and status, where implemented.
- **Responsive Interface:** User-friendly shopping experience across supported screen sizes.

###  Admin Features

- **Admin Dashboard:** Dedicated interface for store management.
- **Product Management:** Add and manage products.
- **Image Uploads:** Cloudinary integration for product image storage.
- **Order Management:** View orders and update order status, where implemented.
- **Protected Access:** Restrict administrative operations to authorized users.

##  Tech Stack

### Frontend
- React.js
- JavaScript
- Vite
- Tailwind CSS, where used
- Axios
- React Context API

### Backend
- Node.js
- Express.js
- RESTful APIs
- JWT Authentication

### Database and Integrations
- MongoDB
- Cloudinary for product image storage
- Razorpay for online payments

##  Project Structure

```text
forever-ecommerce/
├── frontend/      # Customer shopping application
├── admin/         # Admin dashboard
├── backend/       # Server and API endpoints
└── README.md
```

##  Getting Started

### Prerequisites

- Node.js and npm
- MongoDB database
- Cloudinary account for image uploads
- Razorpay account and API credentials

### 1. Clone the Repository

```bash
git clone https://github.com/ashutosh-gupta01/forever-ecommerce.git
cd forever-ecommerce
```

### 2. Install Dependencies

Install dependencies separately in each project directory.

**Frontend**

```bash
cd frontend
npm install
```

**Admin Panel**

```bash
cd ../admin
npm install
```

**Backend**

```bash
cd ../backend
npm install
```

### 3. Configure Environment Variables

Create the required `.env` files in the relevant directories. The exact variable names depend on your implementation.

Example backend configuration:

```env
PORT=4000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
```

Use the variable names expected by your source code. Configure the frontend and admin API URLs according to your local setup.

**Security:** Never commit real credentials, API keys, payment secrets, or database passwords to GitHub.

### 4. Run the Application

Open a separate terminal for each application and run the scripts configured in its `package.json`.

For Vite-based frontend and admin applications:

```bash
npm run dev
```

For the backend, use its configured start script. For example:

```bash
npm run server
```

Check each `package.json` to confirm the correct commands.

##  Key Learning Outcomes

- Building a full-stack application using the MERN stack.
- Developing reusable React components and responsive interfaces.
- Integrating frontend applications with RESTful APIs.
- Implementing authentication and protected administrative operations.
- Managing products, shopping cart data, and orders.
- Integrating Cloudinary for image uploads.
- Integrating Razorpay for online payment processing.
- Configuring environment variables and deploying application services.

##  Future Improvements

- Product reviews and ratings.
- Wishlist functionality.
- Discount coupons and promotional offers.
- Enhanced product search and filtering.
- Improved checkout and order tracking.

##  Author

**Aashutosh Gupta**

- **GitHub:** [ashutosh-gupta01](https://github.com/ashutosh-gupta01)
- **LinkedIn:** [Aashutosh Gupta](https://www.linkedin.com/in/ashutosh-kumar-gupta-0561ab265/)
- **Portfolio:** [Personal Portfolio](https://personalportfolio-bzqy.onrender.com)

---

If you find this project useful, consider giving the repository a star.
