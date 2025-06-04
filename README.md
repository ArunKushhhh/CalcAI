# CalcAI 🧮✨

An intelligent calculator application that combines traditional mathematical operations with AI-powered problem solving capabilities. Built with React and Vite for a fast, modern user experience.

## 🚀 Features

- **Smart Calculator Interface**: Clean, intuitive calculator design for basic and advanced mathematical operations
- **AI-Powered Calculations**: Leverage artificial intelligence for complex problem solving
- **Real-time Computation**: Instant results as you type
- **Expression Parsing**: Natural language mathematical expression support
- **History Tracking**: Keep track of your previous calculations
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Modern UI/UX**: Beautiful, accessible interface built with modern web standards

## 🛠️ Technologies Used

- **Frontend**: React 18+ with TypeScript
- **Build Tool**: Vite for lightning-fast development and building
- **Styling**: CSS3 with modern layout techniques
- **Development**: ESLint for code quality and consistency
- **Hot Module Replacement**: Instant feedback during development

## 📦 Installation

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/ArunKushhhh/CalcAI.git
   cd CalcAI
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to see the application running.

## 🎯 Usage

### Basic Calculator Operations
- Click on numbers and operators to build your mathematical expression
- Press equals (=) or Enter to calculate the result
- Use Clear (C) to reset the current calculation
- Use backspace to delete the last entered character

### AI-Enhanced Features
- Enter complex mathematical expressions in natural language
- Get step-by-step solutions for complex problems
- Ask mathematical questions and receive intelligent responses
- Handle advanced calculations that go beyond basic arithmetic

### Keyboard Shortcuts
- `0-9`: Number input
- `+`, `-`, `*`, `/`: Basic operations
- `Enter` or `=`: Calculate result
- `Escape` or `C`: Clear calculator
- `Backspace`: Delete last character

## 🏗️ Project Structure

```
CalcAI/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── Calculator.tsx
│   │   ├── Display.tsx
│   │   ├── Button.tsx
│   │   └── History.tsx
│   ├── hooks/
│   │   ├── useCalculator.ts
│   │   └── useAI.ts
│   ├── utils/
│   │   ├── mathUtils.ts
│   │   └── aiUtils.ts
│   ├── styles/
│   │   └── calculator.css
│   ├── App.tsx
│   ├── main.tsx
│   └── vite-env.d.ts
├── package.json
├── vite.config.ts
├── tsconfig.json
└── README.md
```

## 🔧 Development

### Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality
- `npm run lint:fix` - Automatically fix linting issues

### Code Quality

This project uses ESLint with TypeScript support to maintain code quality. The configuration includes:
- React-specific rules
- TypeScript type checking
- Best practices enforcement
- Automatic formatting suggestions

### Recommended Development Setup

- **IDE**: VS Code with TypeScript and React extensions
- **Node Version**: Use Node.js 18+ for best compatibility
- **Package Manager**: npm or yarn (consistent with team preference)

## 🚀 Deployment

### Build for Production

```bash
npm run build
```

This creates a `dist` folder with optimized production files.

### Deploy to Static Hosting

The built files can be deployed to any static hosting service:
- **Vercel**: `npm i -g vercel && vercel`
- **Netlify**: Drag and drop the `dist` folder
- **GitHub Pages**: Use GitHub Actions for automatic deployment
- **Firebase Hosting**: `firebase deploy`

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Make your changes** and ensure they follow the coding standards
4. **Test your changes**: `npm run lint && npm run build`
5. **Commit your changes**: `git commit -m 'Add amazing feature'`
6. **Push to the branch**: `git push origin feature/amazing-feature`
7. **Open a Pull Request**

### Development Guidelines

- Write clear, descriptive commit messages
- Follow the existing code style and patterns
- Add comments for complex logic
- Test your changes thoroughly
- Update documentation as needed

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Arun Kushhhh**
- GitHub: [@ArunKushhhh](https://github.com/ArunKushhhh)
- Project Link: [https://github.com/ArunKushhhh/CalcAI](https://github.com/ArunKushhhh/CalcAI)

## 🙏 Acknowledgments

- React team for the amazing framework
- Vite team for the lightning-fast build tool
- The open-source community for inspiration and tools
- AI/ML community for advancing mathematical computation capabilities

## 📞 Support

If you have any questions, issues, or suggestions:
- Open an issue on GitHub
- Check existing issues for similar problems  
- Contact the maintainer through GitHub

---

<div align="center">
  <p>Made with ❤️ and ☕ by Arun Kushhhh</p>
  <p>⭐ Star this repo if you find it helpful!</p>
</div>