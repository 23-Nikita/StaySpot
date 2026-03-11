# 🏠 StaySpot - Full-Stack Airbnb Clone

**StaySpot** is a full-stack web application inspired by Airbnb. The primary goal of this project is to provide users with a seamless platform to explore stays, manage bookings, and list their own properties.

---

## 📖 About StaySpot
StaySpot is more than just a clone; it is a complete property management system. We have focused on:
* **User-Friendly UI:** Ensuring a seamless experience across both mobile and desktop devices.
* **Search Accuracy:** Providing accurate results based on Location, Country, or Title.
* **Security:** Secure user authentication and authorization handled via Passport.js.

---

## 🚀 Current Status & Features
The project has moved past the initial setup phase and currently features the following:

* **MERN Stack Integration:** Built on a solid foundation of MongoDB, Express, and Node.js (with EJS for dynamic rendering).
* **Listing Model:** Every property includes a title, description, price, location, and defined category.
* **Database Seeding:** Initialized with sample data using the `init/data.js` script.
* **Category Filters:** Active filters like Trending, Rooms, Iconic Cities, and Mountains.
* **Mapbox Integration:** Real-time map functionality to view exact listing locations.

---

## 🛠️ Tech Stack
* **Backend:** Node.js, Express.js
* **Frontend:** EJS (Embedded JavaScript), Bootstrap 5, FontAwesome (Icons)
* **Database:** MongoDB Atlas
* **Storage:** Cloudinary (for Image Uploads)
* **Maps:** Mapbox SDK

---

## 📂 Folder Highlights
* `models/listing.js`: Schema definitions.
* `init/index.js`: Main script to initialize the database.
* `views/listings/`: All frontend templates (index, show, new, edit).

---

## 🔧 How to Run
1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Add your credentials in a `.env` file.
4. Start the server using `nodemon app.js`.