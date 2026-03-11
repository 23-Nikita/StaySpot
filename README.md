# 🏠 StaySpot - Full-Stack Airbnb Clone

**StaySpot** ek full-stack web application hai jo Airbnb se inspired hai. Is project ka main goal users ko ek smooth platform dena hai jahan wo stays explore kar sakein, bookings dekh sakein aur apni properties list kar sakein.



---

## 📖 About StaySpot
StaySpot sirf ek clone nahi, balki ek complete property management system hai. Isme humne dhyaan rakha hai ki:
* **User-Friendly UI:** Mobile aur Desktop dono par seamless experience mile.
* **Search Accuracy:** Location, Country ya Title ke basis par accurate results milte hain.
* **Security:** User authentication aur authorization ko Passport.js se handle kiya gaya hai.

---

## 🚀 Current Status & Features
Abhi project initial setup phase se aage badh chuka hai aur niche diye gaye features live hain:

* **MERN Stack Integration:** MongoDB, Express, React (planned/EJS used), aur Node.js ka solid base.
* **Listing Model:** Har property ke liye title, description, price, location, aur category define ki gayi hai.
* **Database Seeding:** `init/data.js` ka use karke sample data initialize kiya gaya hai.
* **Category Filters:** Trending, Rooms, Iconic Cities, aur Mountains jaise multiple filters active hain.
* **Mapbox Integration:** Map par listings ki exact location dekhne ki functionality.

---

## 🛠️ Tech Stack
* **Backend:** Node.js, Express.js
* **Frontend:** EJS, Bootstrap 5, FontAwesome (for Icons)
* **Database:** MongoDB Atlas
* **Storage:** Cloudinary (for Image uploads)
* **Maps:** Mapbox SDK

---

## 📂 Folder Highlights
* `models/listing.js`: Schema definitions.
* `init/index.js`: Database initialize karne ka main script.
* `views/listings/`: Saare frontend templates (index, show, new, edit).



---

## 🔧 How to Run
1. Repo clone karein.
2. `npm install` chalayein.
3. `.env` file mein apni credentials daalein.
4. `nodemon app.js` se server start karein.