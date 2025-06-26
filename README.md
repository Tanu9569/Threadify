# 🧵< Threadify

**Threadify** is a full-featured social media web application that allows users to register, log in, share posts, like others' content, and manage their profiles with profile photos. It is built using Node.js, Express.js, MongoDB, and Tailwind CSS, with EJS for rendering dynamic views.

---

## 🌟 Features

- 🔐 User authentication (Register/Login using JWT)
- 🧑 Profile management with photo upload
- ✍️ Create, edit, like, and view posts
- 🌍 All Posts page with public content
- 🎨 Modern and responsive UI using Tailwind CSS

---

## 🔧 Tech Stack

| Layer      | Technology                  |
|------------|-----------------------------|
| Frontend   | HTML, Tailwind CSS, EJS     |
| Backend    | Node.js, Express.js         |
| Database   | MongoDB, Mongoose           |
| Auth       | JWT (jsonwebtoken), bcrypt  |
| Uploads    | Multer (for image uploads)  |
| Extras     | Cookie-parser, Express Middleware |

---

## 🖥️ Screenshots

### 🔐 Login Page
> 📷
> ![image](https://github.com/user-attachments/assets/63928521-30e5-4a7a-a7df-cb19b5d9e860)


### 👤 Profile Page
> 📷 
> ![image](https://github.com/user-attachments/assets/d79724ee-06a0-4d8b-b5ab-eaf96004a13f)


### 🌍 All Posts Page
>📷
> ![image](https://github.com/user-attachments/assets/c3a96e13-5991-4df1-8aec-25fa31e8e7b7)


## 📂 Project Structure

Threadify/
├── config/
│ └── multerconfig.js
├── models/
│ ├── user.js
│ └── post.js
├── public/
│ └── images/uploads/
├── views/
│ ├── index.ejs
│ ├── login.ejs
│ ├── register.ejs
│ ├── profile.ejs
│ ├── allposts.ejs
│ ├── viewpost.ejs
│ ├── edit.ejs
│ └── alreadyRegistered.ejs
├── screenshots/
│ ├── login.png
│ ├── profile.png
│ └── allposts.png
├── .gitignore
├── app.js
└── package.json

yaml
Copy
Edit

---

## 🚀 Getting Started

### 🛠️ Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Tanu9569/threadify.git
   cd threadify
Install dependencies:

bash
Copy
Edit
npm install
Set up MongoDB:

Ensure MongoDB is running locally or connect to MongoDB Atlas.

If needed, update the connection string in app.js.

Run the server:

bash
Copy
Edit
node app.js
Open http://localhost:3000 in your browser.

