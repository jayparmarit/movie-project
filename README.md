# 🎬 Movie Management API

A RESTful Movie Management API built with Node.js, Express.js, MongoDB, Multer, and Cloudinary.
This API allows users to add, view, update, and delete movies, including movie poster upload.

The project demonstrates CRUD operations, image upload using Multer, cloud storage with Cloudinary, and centralized error handling.


# 🚀 Features

🎬 Add new movie with poster image

📄 Get all movies

🔍 Get single movie by ID

✏️ Update movie details

❌ Delete movie

☁️ Image upload using Cloudinary

📦 File upload using Multer

⚠️ Centralized error handling

🗄️ MongoDB database integration


# 🛠️ Tech Stack

| Category                 | Technology |
| ------------------------ | ---------- |
| ⚙️ Runtime               | Node.js    |
| 🚀 Framework             | Express.js |
| 🗄️ Database             | MongoDB    |
| 🔗 ODM                   | Mongoose   |
| 📤 File Upload           | Multer     |
| ☁️ Cloud Storage         | Cloudinary |
| 🔑 Environment Variables | dotenv     |
| 🧪 API Testing           | Postman    |
| 🛠️ Development Tool     | Nodemon    |


# 📁 Project Structure

MOVIE-PROJECT <br>

├── config <br>
│   ├── cloudinary.js <br>
│   └── db.js <br>
│
├── controllers <br>
│   └── movieController.js <br>
│
├── middleware <br>
│   ├── httpError.js <br>
│   └── upload.js <br>
│
├── model <br>
│   └── Movie.js <br>
│
├── routes <br>
│   └── movieRoutes.js <br>
│
├── .env <br>
├── app.js <br>
├── package.json <br>
└── README.md

# 🌐 Live API

https://pr-movies-projects-node-js.onrender.com/


# 📦 Dependencies

✅ express

✅ mongoose

✅ multer

✅ cloudinary

✅ dotenv

✅ cors

✅ nodemon


# 📌 API Endpoints

🏠 Check Server

GET /

Response

{
  "message": "Movie API is running successfully"
}

# 🎬 Add Movie

POST /movies/add

Body (form-data)

| Field       | Type   |
| ----------- | ------ |
| title       | text   |
| description | text   |
| genre       | text   |
| rating      | number |
| releaseYear | number |
| image       | file   |

# 📄 Get All Movies

GET /movies/allMovies

🔍 Get Single Movie

GET /movies/:id

✏️ Update Movie

PATCH /movies/update/:id

❌ Delete Movie

DELETE /movies/delete/:id


# 🧪 API Testing (Postman)

📸 Screenshots

**Server Check**

<img width="1920" height="1080" alt="Screenshot 2026-03-11 122209" src="https://github.com/user-attachments/assets/564a54ac-28e6-4a64-a8f4-90f8f495e13e" />


**Add Movie**

<img width="1920" height="1080" alt="Screenshot 2026-03-11 122218" src="https://github.com/user-attachments/assets/5fb6f61c-bed7-4f0a-a549-4058254adc1f" />


**Get All Movies**

<img width="1920" height="1080" alt="Screenshot 2026-03-11 122258" src="https://github.com/user-attachments/assets/3f147e12-6f5b-4049-978c-1439a326ac52" />



**Get Single Movie**

<img width="1920" height="1080" alt="Screenshot 2026-03-11 122233" src="https://github.com/user-attachments/assets/ac73a160-71a0-4c3e-9fdb-baa9f93a2e80" />



**Delete Movie**

<img width="1920" height="1080" alt="Screenshot 2026-03-11 122250" src="https://github.com/user-attachments/assets/6869e3c4-664d-453d-8fcd-df309cfa5951" />




# ⚙️ Installation

1️⃣ Clone Repository

https://github.com/jayparmarit/movie-project

2️⃣ Go to Project Folder

cd movie-project

3️⃣ Install Dependencies

npm install

4️⃣ Create .env File

PORT=5000

MONGO_URL=your_mongodb_connection_string

CLOUD_NAME=your_cloud_name

CLOUD_API_KEY=your_api_key

CLOUD_API_SECRET=your_api_secret

5️⃣ Run Server

npm run dev

Server will run on:

http://localhost:5000



