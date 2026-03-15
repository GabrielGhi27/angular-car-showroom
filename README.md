# Angular Workshop


## 📚 Introduction

This project is a hands-on learning application designed to teach the fundamentals of Angular framework. It demonstrates core concepts including component architecture, routing, data binding, services, and component communication patterns. This README serves as a comprehensive reference guide for students to review after the workshop.

**What you'll learn:**
- How to create and structure Angular applications
- Core Angular concepts and best practices
- Component-based architecture
- Routing and navigation
- Data binding and event handling
- Services and dependency injection

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** (v18 or higher) - [Download here](https://nodejs.org/)
- **npm** (comes with Node.js)
- A code editor (VS Code recommended)

### Creating a New Angular Application

Follow these steps to create a new Angular project from scratch:

#### 1. Install Angular CLI globally
```bash
npm install -g @angular/cli
```

#### 2. Create a new Angular project
```bash
ng new my-angular-app
```

During setup, you'll be asked:
- **Which stylesheet format would you like to use?** → CSS (or your preference)

#### 3. Navigate to your project
```bash
cd my-angular-app
```

#### 4. Start the development server
```bash
ng serve
```

Navigate to `http://localhost:4200/` in your browser. The app will automatically reload when you make changes.


## 🔗 Useful Resources

- **Official Angular Documentation**: https://angular.io/docs
- **Angular CLI Reference**: https://angular.io/cli
- **Angular Style Guide**: https://angular.io/guide/styleguide
- **RxJS Documentation**: https://rxjs.dev/
- **TypeScript Handbook**: https://www.typescriptlang.org/docs/

---

## 🚦 Running This Project

### Development Server
```bash
ng serve
```
Navigate to `http://localhost:4200/`

### Build for Production
```bash
ng build --configuration production
```
Build artifacts will be stored in the `dist/` directory.

### Running Tests
```bash
ng test
```

---

## 💡 Key Takeaways

1. **Components** are the building blocks - everything is a component
2. **Data flows down, events flow up** - Parent-child communication pattern
3. **Services** centralize shared logic and data
4. **Routing** enables SPA (Single Page Application) navigation
5. **TypeScript** adds type safety and modern JavaScript features
6. **Angular CLI** automates common development tasks
7. **Reactive programming** with RxJS is powerful for async operations

