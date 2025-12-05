# Todo Application (JavaScript)

A simple and responsive **Todo List Web Application** built using **HTML, CSS, and JavaScript**.  
This app allows users to **add, delete, and mark tasks as completed**, and it also **stores tasks in Local Storage** so data will not be lost on page reload.

---

## 🚀 Features
- Add new tasks  
- Delete existing tasks  
- Mark tasks as completed  
- Stores data permanently using **LocalStorage**  
- Responsive UI using **Bootstrap 4**  
- Clean JavaScript code

---

## 🛠️ Tech Stack
- HTML5  
- CSS3  
- Bootstrap 4  
- JavaScript  
- LocalStorage

---

## 📂 Project Structure
/project-folder
│── index.html
│── style.css
│── script.js
│── README.md

---

## 🔧 How to Use
1. Open **index.html** in any browser.  
2. Enter a task in the input field.  
3. Click **Add** to create a task.  
4. Click checkbox to mark task as **completed**.  
5. Click the **trash icon** to delete the task.  
6. Click **Save** to store the todo list in LocalStorage.

---

## 📦 LocalStorage Data Format
```json
[
  {
    "text": "Learn JavaScript",
    "uniqueNo": 1,
    "isChecked": false
  }
]
## 🧩 Main Functions

onAddTodo() → Adds a new task

onTodoStatusChange() → Toggles completed status

onDeleteTodo() → Deletes a task

createAndAppendTodo() → UI creation for each task

localStorage.setItem() → Saves data

## 🏁 Run the Project

Just open index.html
No installation required.

##📜 License

This project is open-source under the MIT License.