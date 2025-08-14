# CodeWhisperer - Web-Based JavaScript IDE

A professional web-based code editor that replicates VS Code functionality, built with React and Monaco Editor. Features real-time JavaScript execution, IntelliSense, file management, and a modern development experience.

![CodeWhisperer Demo](https://github.com/user-attachments/assets/9330d3b4-81c7-4b7c-9e24-f84f6bd7442c)

## ✨ Features

### 🎯 Core Functionality
- **Real-time JavaScript Execution** - Run code instantly with live console output
- **Monaco Editor Integration** - Professional code editing with VS Code-like experience
- **IntelliSense & Auto-completion** - Smart code suggestions and custom snippets
- **Multi-file Management** - Create, edit, and organize files with tree-view navigation
- **Tab-based Editing** - Work with multiple files simultaneously

### 🎨 User Experience
- **Dark/Light Theme Toggle** - Comfortable coding in any lighting condition
- **Responsive Design** - Works seamlessly on desktop and tablet devices
- **Live Mode** - Auto-execute code as you type for rapid prototyping
- **Persistent Storage** - Your work is automatically saved to local storage
- **Code Sharing** - One-click code copying to clipboard

### 🛠️ Advanced Features
- **File System Operations** - Create, rename, delete files and folders
- **Context Menus** - Right-click operations for file management
- **Settings Panel** - Customize editor preferences (font size, theme, etc.)
- **HTML Editor** - Built-in HTML editor with live preview
- **GitHub README Viewer** - View GitHub content directly in the editor

## 🛠️ Tech Stack

### Frontend
- **React 18.3.1** - Modern component-based UI library
- **Monaco Editor** - Professional code editor (same as VS Code)
- **Tailwind CSS 4.0.3** - Utility-first CSS framework
- **Vite 6.0.5** - Fast build tool and development server

### Libraries & Tools
- **Lucide React** - Modern icon library
- **React Beautiful DnD** - Drag and drop functionality
- **React Resizable Panels** - Resizable UI panels
- **JSZip** - File compression for project export
- **VSCode Icons** - File type icons matching VS Code

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sahith53/codewhisperer.git
   cd codewhisperer
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   ```
   http://localhost:5173
   ```

### Build for Production
```bash
npm run build
npm run preview
```

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── FileExplorer.jsx    # File tree management
│   ├── OutputPanel.jsx     # Console output display
│   ├── Settings.jsx        # Editor settings panel
│   ├── Sidebar.jsx         # Navigation sidebar
│   └── TabBar.jsx          # File tab management
├── hooks/              # Custom React hooks
├── App.jsx             # Main application component
└── main.jsx            # Application entry point
```

## 🎯 Key Features Explained

### Real-time Code Execution
The editor uses JavaScript's Function constructor to safely execute user code in an isolated environment, capturing console output and displaying results in real-time.

### File Management System
Implements a tree data structure for hierarchical file organization with recursive operations for file creation, editing, and deletion.

### Persistent Storage
All user data (files, settings, open tabs) is automatically saved to localStorage, ensuring work persistence between sessions.

## 🔧 Customization

### Editor Settings
- Font size and family
- Theme customization
- Cursor style and behavior
- Code formatting options
- IntelliSense configuration

### Custom Code Snippets
The editor includes pre-built snippets for common JavaScript patterns:
- `cl` → `console.log()`
- `fn` → Function declaration
- `af` → Arrow function
- `obj` → Object creation
- And many more...

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Monaco Editor** - For providing the excellent code editing experience
- **VS Code** - For inspiration in UI/UX design
- **React Team** - For the amazing framework
- **Tailwind CSS** - For the utility-first CSS framework



⭐ **Star this repository if you found it helpful!**
# codewhisperer
