📋 Task Manager
A minimal Task Manager Web App built using Node.js, Express.js, EJS, and Tailwind CSS.

Users can:

✅ Create tasks with a title and description

📄 View a list of tasks

🔍 Read task details in a separate view

🚀 Features
🧾 Create and store task files as .txt

📂 View list of all tasks (auto-loaded from the files directory)

📑 Open individual tasks using dynamic routes (/file/:filename)

🎨 Beautiful UI using Tailwind CSS with smooth transitions

🛠️ Tech Stack
Technology	Use
Node.js	Server-side JavaScript
Express.js	Web framework
EJS	Templating engine
Tailwind CSS	Frontend styling
File System (fs)	File storage backend

✏️ How It Works
Tasks are created using a form and saved as .txt files inside the /files directory.

On the homepage, it lists all the files (task titles).

Clicking "Read more" sends you to /file/:filename, reading the file content using fs.readFile.

📌 Example .txt File
If you create a task titled "Buy Groceries", a file named BuyGroceries.txt is created inside /files with the description you wrote.

🔐 Security Note
This is a basic demo and does not include:

Authentication / Authorization

Input sanitization

Database storage (uses file system instead)

Use with caution or improve as needed.

🤝 Contributing
Pull requests and suggestions are welcome!
