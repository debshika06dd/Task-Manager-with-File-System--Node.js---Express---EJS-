# Task Manager with File System (Node.js + Express + EJS)

A simple **Task Management Web App** that allows users to **create, view, and rename tasks**. Instead of a traditional database, this app stores tasks as text files in the local filesystem. It is built using **Node.js, Express, EJS templates, and Tailwind CSS** for styling.

---

## 🚀 Features

* 📂 Create new tasks (saved as `.txt` files).
* 📜 View task details.
* ✏️ Rename existing tasks.
* 🎨 Clean UI with Tailwind CSS.
* ⚡ Lightweight file-based storage (no database required).

---

## 🛠️ Tech Stack

* **Backend**: Node.js, Express.js
* **Frontend**: EJS templates, Tailwind CSS
* **Storage**: Local file system (using Node’s `fs` module)

---

## 📂 Project Structure

```
.
├── index.js          # Main server file (Express app)
├── views/
│   ├── index.ejs     # Homepage (create & list tasks)
│   ├── show.ejs      # View single task
│   ├── edit.ejs      # Edit task filename
├── public/           # Static assets (CSS, JS, etc.)
├── files/            # Stores tasks as .txt files
```

---

## ⚙️ Installation & Usage

1. **Clone the repo**

   ```bash
   git clone https://github.com/your-username/task-manager-fs.git
   cd task-manager-fs
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Run the app**

   ```bash
   node index.js
   ```

4. **Open in browser**

   ```
   http://localhost:3000
   ```

---

## 🖼️ Screenshots

*(You can add screenshots here after running the app and capturing them.)*

---

## 🔮 Future Improvements

* Add **delete task** feature.
* Store task metadata (timestamps, status).
* Implement database support (MongoDB/SQLite).
* Add authentication for users.

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use and modify it.
