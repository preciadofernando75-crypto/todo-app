# To-Do List Application

A simple, elegant to-do list application with local storage functionality. Built with vanilla HTML, CSS, and JavaScript.

## Features

✨ **Core Features:**
- ✅ Add new tasks
- ✅ Mark tasks as complete/incomplete
- ✅ Delete individual tasks
- ✅ Clear all completed tasks
- ✅ Filter tasks (All, Active, Completed)
- 💾 **Local Storage** - All data persists in browser
- 📱 **Responsive Design** - Works on desktop and mobile
- 🎨 **Modern UI** - Beautiful gradient design with smooth animations

## Installation

1. Clone the repository:
```bash
git clone https://github.com/preciadofernando75-crypto/todo-app.git
cd todo-app
```

2. Open `index.html` in your browser:
```bash
# Using a simple Python server
python -m http.server 8000
# Then navigate to http://localhost:8000

# Or just open the file directly
open index.html
```

## Usage

1. **Add a Task**: Type in the input field and click "Add Task" or press Enter
2. **Complete a Task**: Check the checkbox next to a task to mark it as complete
3. **Delete a Task**: Click the "Delete" button next to a task
4. **Filter Tasks**: Use the filter buttons to view All, Active, or Completed tasks
5. **Clear Completed**: Click "Clear Completed" to remove all finished tasks

## Local Storage

All your tasks are automatically saved to your browser's local storage:
- Tasks persist even after closing and reopening the browser
- Filter preference is also saved
- Data is stored locally - no server required

## File Structure

```
todo-app/
├── index.html      # Main HTML structure
├── styles.css      # Styling and responsive design
├── app.js          # Application logic and local storage
└── README.md       # Documentation
```

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Flexbox layout, gradients, animations
- **JavaScript (ES6+)** - DOM manipulation, Local Storage API
- **Browser Local Storage** - Client-side data persistence

## Browser Support

- Chrome/Chromium
- Firefox
- Safari
- Edge
- Any modern browser with LocalStorage support

## Future Enhancements

- [ ] Due date functionality
- [ ] Priority levels
- [ ] Categories/Tags
- [ ] Edit existing tasks
- [ ] Dark mode
- [ ] Cloud sync (Firebase)
- [ ] Export/Import functionality

## License

MIT License - Feel free to use this project for personal or commercial purposes.

## Author

Created by [preciadofernando75-crypto](https://github.com/preciadofernando75-crypto)
