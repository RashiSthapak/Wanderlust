# 🌍 WanderLust – Discover Unique Stays Worldwide

**WanderLust** is a full-stack web application that connects travelers with hosts offering unique homes and properties for short-term stays.
               Whether it's a cozy cabin in the mountains or a chic loft downtown, WanderLust helps you find and book unforgettable places to stay.

🔗 Live Demo: [wanderlust-jcro.onrender.com](https://wanderlust-jcro.onrender.com/listings)

---

## ✨ Features

- 🏠 **Browse Listings**: Explore diverse properties from around the globe.
- 🔐 **User Authentication**: Secure registration, login, and session management.
- 💬 **Reviews & Ratings**: Leave feedback and read others’ experiences.
- 🗺️ **Map Integration**: Visualize property locations using Mapbox.
- 💼 **Host Your Property**: Users can list their own properties with photos, descriptions, and prices.
- 📱 **Responsive Design**: Fully mobile-friendly experience.

---

## 🚀 Tech Stack

- **Frontend**: HTML, CSS, JavaScript, EJS, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB & Mongoose
- **Authentication**: Passport.js (Local Strategy)
- **Maps & Geocoding**: Mapbox API
- **Image Management**: Cloudinary
- **Validation**: Joi (form and request validation)
- **Templating**: EJS with custom layouts using `ejs-mate`
- **Deployment**: Render

Authentication---->

Method	Route	Description
POST	/register	Register new user
POST	/login	Log in user
GET	/logout	Log out current user


## 🛠️ Installation & Setup

To run this project locally:

1️⃣Clone the repository
   ```bash
   git clone https://github.com/RashiSthapak/wanderlust.git
   cd wanderlust

2️⃣ Install Dependencies
bash
Copy
Edit
npm install

3️⃣ Create a .env File
Create a .env file in the root directory with the following content:

4️⃣ Setup External Services
MongoDB Atlas – Create a database and get the connection string

Cloudinary – Set up an account and get your API keys

5️⃣ Start the Application
bash
Copy
Edit

npm run dev
Visit: http://localhost:8080
