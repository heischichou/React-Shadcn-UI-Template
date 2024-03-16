# React TypeScript Template

A React TypeScript + Tailwind template powered by CRACO.

## 🚀 Getting Started
Follow these steps to get started:
1. Clone the repository:

    ```bash
    git clone https://github.com/heischichou/React-Typescript-Template
    ```

2. Navigate to the project directory:

    ```bash
    cd react-typecript-template
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

4. Start the development server:

    ```bash
    npm run start
    ```

## 📜 Available Scripts
### Compiles and hot-reloads for development
Runs the app in the development mode at [http://localhost:3000](http://localhost:3000).\
The page will reload if you make edits. You will also see any lint errors in the console.
```
npm run start
```

### Run your tests
Launches the test runner in the interactive watch mode.
```
npm run test
```

### Compiles and minifies for production
Builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance.
```
npm run build
```

### Remove the project single build dependency
This command will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

**Note: This is a one-way operation. Once you `eject`, you can’t go back!**
```
npm run eject
```

## 📂 Project Structure

The project structure follows a standard React application layout:

```python
react-typescript-template/
  ├── node_modules/        # Project dependencies
  ├── public/              # Public assets
  ├── src/                 # Application source code
  │   ├── styles/          # CSS stylesheets
  │   │   └── App.css      # Default stylesheet
  │   ├── tests/           # App tests
  │   │   └── App.test.tsx # App test
  │   ├── App.tsx          # Application entry point
  │   ├── index.css        # Application stylesheet
  │   └── index.tsx        # Main rendering file
  ├── craco.config.js      # CRACO configuration
  ├── tailwind.config.js   # Tailwind CSS configuration
  └── tsconfig.json        # TypeScript configuration
```

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](https://choosealicense.com/licenses/mit/) file for details.