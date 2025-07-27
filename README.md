# Todo App with Context API and Local Storage

A modern, responsive Todo application built with React, featuring Context API for state management and local storage for data persistence.

## 🚀 Features

- **Add Todos**: Create new todo items with a simple form
- **Edit Todos**: Update existing todo content
- **Delete Todos**: Remove todos from the list
- **Toggle Completion**: Mark todos as complete/incomplete
- **Local Storage**: Todos persist across browser sessions
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI**: Clean, dark-themed interface with Tailwind CSS

## 🛠️ Technologies Used

- **React 19** - Frontend framework
- **Context API** - State management
- **Tailwind CSS** - Styling and responsive design
- **Vite** - Build tool and development server
- **Local Storage** - Data persistence

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd 10todoContextLocal
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the application

## 🏗️ Build Commands

- **Development**: `npm run dev`
- **Build for production**: `npm run build`
- **Preview production build**: `npm run preview`
- **Lint code**: `npm run lint`

## 📁 Project Structure

```
src/
├── components/
│   ├── TodoForm.jsx    # Form component for adding todos
│   ├── TodoItem.jsx    # Individual todo item component
│   └── index.js        # Component exports
├── contexts/
│   ├── TodoContext.js  # Context provider for todo state
│   └── index.js        # Context exports
├── App.jsx             # Main application component
└── main.jsx           # Application entry point
```

## 🎯 Usage

1. **Adding a Todo**: Type your todo in the input field and press Enter or click the add button
2. **Editing a Todo**: Click the edit icon on any todo to modify its content
3. **Completing a Todo**: Click the checkbox to mark a todo as complete
4. **Deleting a Todo**: Click the delete icon to remove a todo from the list

## 💾 Data Persistence

All todos are automatically saved to your browser's local storage, so your data will persist even after closing the browser or refreshing the page.

## 🤝 Contributing

Feel free to submit issues and enhancement requests!
