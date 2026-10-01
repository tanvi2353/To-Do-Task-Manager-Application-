# My Tasks — To-Do List

A clean, responsive, browser-based To-Do List application built with **HTML, CSS, and JavaScript**.

✉️Live Demo :-https://smart-task-manager-alpha-two.vercel.app/

## ✨ Features

- Add new tasks
- Mark tasks as completed or pending
- Delete individual tasks
- Clear all completed tasks
- Live task statistics:
  - Total tasks
  - Completed tasks
  - Pending tasks
  - Completion percentage
- Progress ring with completion percentage
- Responsive layout for desktop, tablet, and mobile
- Simple theme/brightness toggle
- Toast notifications for user actions
- Data is saved automatically in the browser using `localStorage`
- Input validation for empty tasks
- Confirmation dialog before deleting or clearing tasks
- No backend or database required

## 🛠️ Technologies Used

- **HTML5** — page structure
- **CSS3** — responsive UI, gradients, cards, animations, and layout
- **JavaScript (ES6)** — task management and interactions
- **LocalStorage API** — persistent task data in the browser

## 📁 Project Structure

```text
my-tasks-github/
├── index.html
├── style.css
├── script.js
└── README.md
```

## 🚀 How to Run

### Option 1 — Open directly

1. Download or clone this repository.
2. Open `index.html` in any modern web browser.
3. Start adding tasks.

### Option 2 — Use VS Code

1. Open the project folder in Visual Studio Code.
2. Open `index.html`.
3. Use the **Live Server** extension if installed.
4. The application will open in your browser.

## 💾 Data Storage

This project uses the browser's `localStorage`.

Tasks are stored locally under the key:

```text
my_tasks_standalone_v1
```

Because the data is stored in the browser, tasks remain available after refreshing the page on the same browser/device.

## 🌐 GitHub Pages Deployment

You can host this project for free using GitHub Pages.

1. Create a new GitHub repository, for example:

   `my-tasks-to-do-list`

2. Upload these files:

   - `index.html`
   - `style.css`
   - `script.js`
   - `README.md`

3. Open the repository's **Settings**.
4. Go to **Pages**.
5. Select the branch containing your project files.
6. Save the GitHub Pages settings.
7. GitHub will provide your live website URL.

## 🎯 Project Purpose

The project demonstrates how a front-end web application can manage user-generated data without a server. It is suitable as a beginner-friendly web development or college mini-project.

## 🔮 Future Improvements

Possible upgrades include:

- Edit existing tasks
- Task categories
- Priority levels
- Due dates and reminders
- Search and filter
- Dark mode with proper theme colors
- Drag-and-drop task ordering
- Cloud database integration
- User login and authentication
- Firebase or another backend for cross-device synchronization

## 👩‍💻 Author

**C.B. Tanvi**

## 📄 License

This project is available for educational and personal use.
