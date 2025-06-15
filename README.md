# 📝 Task Manager
## Link - https://task-manager-production-0091.up.railway.app/

A minimal **Task Manager Web App** built with **Node.js**, **Express.js**, **EJS**, and **Tailwind CSS**.

Users can:
- ✅ Create tasks with a title and description  
- 📄 View a list of tasks  
- 🔍 Read full task details
- ✏️ Update (rename) existing tasks



---

## 📂 Features

- Create and save tasks as `.txt` files
- View all tasks dynamically from the `/files` directory
- Read each task in detail via `/file/:filename` route
- Beautiful and responsive UI using Tailwind CSS
- Smooth transitions and hover effects

---

## 🛠️ Tech Stack

- **Node.js** – Backend runtime
- **Express.js** – Web framework
- **EJS** – Templating engine
- **Tailwind CSS** – Styling
- **File System (fs)** – For storing task data

---

---

## ✏️ How It Works

- When a task is submitted, it's saved as a `.txt` file inside the `/files` directory.
- The homepage dynamically lists all the filenames using `fs.readdir()`.
- Clicking the “Read more” link sends the user to `/file/:filename`, where the content is displayed using `fs.readFile()`.

---

## 🔐 Notes

- This is a basic learning/demo project built for understanding backend and templating concepts.
- No user login or database is used.
- Input validation and sanitization are **not implemented** to keep the project simple.

---

## 🤝 Contributing

Have an idea, suggestion, or fix?  
Feel free to fork the project and open a pull request. Contributions are always welcome!

## Screenshots
<img width="1440" alt="Screenshot 2025-06-15 at 11 09 57 AM" src="https://github.com/user-attachments/assets/e14a6aea-4d14-4d35-b58c-940b164db3b1" />
<img width="1440" alt="Screenshot 2025-06-15 at 11 10 21 AM" src="https://github.com/user-attachments/assets/6a6c5616-d4f2-42a2-af20-80f59f60a753" />
<img width="1440" alt="Screenshot 2025-06-15 at 1 31 37 PM" src="https://github.com/user-attachments/assets/6a9957f6-bb73-4587-a142-54fe63fae869" />



 

