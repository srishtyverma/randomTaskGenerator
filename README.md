# Random Task Generator 🎯

A simple **Node.js + Express** web application that generates random tasks for users using an external API.
Built with **EJS templating** and styled with basic CSS for a clean and minimal UI.

---

## 🚀 Features

* 🔄 Generates a random task on each refresh
* 🌐 Fetches tasks from an external API
* 📩 Demonstrates **GET and POST request handling**
* 🎨 Clean and simple user interface
* ⚡ Lightweight and beginner-friendly project

---

## 🛠️ Tech Stack

* **Node.js**
* **Express.js**
* **EJS (Embedded JavaScript Templates)**
* **HTML / CSS**
* **Bored API** (for random tasks)

---

## 🔗 API Used

* [https://bored-api.appbrewery.com/random](https://bored-api.appbrewery.com/random)

This API provides random activities/tasks which are displayed to the user.

---

## 📁 Project Structure

```
RANDOMTASKGENERATOR/
│── node_modules/
│
├── public/
│   └── styles/
│       └── main.css        # Styling file
│
├── views/                  # EJS templates
│
├── .gitignore
├── index.js                # Main server file
├── package.json
└── package-lock.json
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

```
git clone <your-repo-link>
```

2. Navigate to the project folder:

```
cd RANDOMTASKGENERATOR
```

3. Install dependencies:

```
npm install
```

4. Run the server:

```
node index.js
```

5. Open your browser and go to:

```
http://localhost:3000
```

---

## 🔄 How It Works

* The server is built using **Express.js**
* When a user visits the page:

  * A **GET request** is sent to fetch a random task from the API
  * The task is rendered using **EJS templates**
* If forms or interactions are used:

  * A **POST request** handles user input and updates the UI accordingly

---

## 📚 Concepts Used

* Express server setup
* Routing (GET & POST requests)
* API integration using HTTP requests
* Server-side rendering with EJS
* Static file handling in Express

---

## 📌 Example Use Case

* Get random productivity ideas
* Find fun activities when bored
* Learn API integration basics

---

## 💡 Future Improvements

* Add task categories filter
* Save favorite tasks
* Add animations or better UI
* Convert into a full-stack app with database

---

## 🤝 Contributing

Feel free to fork this project and improve it. Contributions are welcome!

---

## 📄 License

This project is open-source and free to use.

---
