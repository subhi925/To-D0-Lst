

# 📝 Task Manager Web App

A simple **to-do list / task management web app** built using **HTML, CSS, and JavaScript**.
This project allows you to create, edit, delete, and mark tasks as complete — all stored locally using **LocalStorage**, so your data is saved even after refreshing the page.

---

## 🌟 Features

✅ Add new tasks
✅ Edit existing tasks
✅ Delete tasks with confirmation
✅ Mark tasks as completed (or unmark them)
✅ Automatically saves all tasks to **LocalStorage**
✅ Simple, clean, and responsive design
✅ RTL (Right-to-Left) support for Hebrew text

---

## 🧠 How It Works

The app uses an array of `tasks` objects, where each task looks like this:

```js
{
  title: "קריאה",
  date: "15/10/2030",
  isDone: false
}
```

Each task includes:

* **title** → the task name
* **date** → creation date
* **isDone** → boolean value indicating if the task is complete

All tasks are stored in the browser’s **LocalStorage**, ensuring persistence between sessions.

---

## 🖥️ Technologies Used

| Technology                          | Purpose                        |
| ----------------------------------- | ------------------------------ |
| **HTML5**                           | Page structure                 |
| **CSS3**                            | Styling and layout             |
| **JavaScript (ES6)**                | App logic and DOM manipulation |
| **Google Fonts (Varela Round)**     | Custom typography              |
| **Material Symbols (Google Icons)** | Icons for buttons and actions  |
| **LocalStorage API**                | Persistent task storage        |

---

## 🚀 Getting Started

### 1. Clone or Download

```bash
git clone https://github.com/subhi925/To-D0-Lst.git
```

### 2. Open the Project

Simply open the `index.html` file in your browser.

---

## 📂 File Structure

```
task-manager/
│
├── index.html      # Main app file (HTML, CSS, JS all in one)
└── README.md       # Project documentation
```

---

## 🧩 Main Functions

| Function                      | Description                                     |
| ----------------------------- | ----------------------------------------------- |
| `fillTasksonThePage()`        | Renders all tasks from the array onto the page  |
| `storeTasks()`                | Saves all tasks into LocalStorage               |
| `deleteTask(index)`           | Deletes a specific task after user confirmation |
| `editTask(index)`             | Allows editing a task’s title                   |
| `toggleTaskCompletion(index)` | Toggles between completed and incomplete states |

---

## 💡 Future Improvements

* Add due dates and sorting
* Enable task filtering (e.g., show only completed tasks)
* Add animations for better UX
* Save and sync tasks using a backend (Firebase or Node.js)
* Support for multiple languages

---

## 👨‍💻 Author

**Subhi Hamed**
📧 [subhihamed88@gmail.com](mailto:subhihamed88@gmail.com)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).


