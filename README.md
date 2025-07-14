# Running the AI Detector Web App Locally

This project requires serving the files from a local server to properly load the models and run the app.

## Option 1: Using Python HTTP Server (Python 3.x required)

1. Open a terminal (Command Prompt or PowerShell) in the project directory.
2. Run the following command:

```bash
python -m http.server 8000
```

3. Open your browser and go to: `http://localhost:8000`
4. The app should load, access your webcam, and perform real-time detection.

## Option 2: Using Node.js http-server (Node.js required)

1. If you don't have http-server installed globally, install it by running:

```bash
npm install -g http-server
```

2. Open a terminal in the project directory.
3. Run the server with:

```bash
http-server -p 8000
```

4. Open your browser and go to: `http://localhost:8000`
5. The app should load and work as expected.

## Note on app.js

The `app.js` file is currently incomplete and not used by the app logic in `index.html`. You can safely ignore or delete it to avoid confusion.

---

If you want me to help you remove `app.js` or assist further, please let me know.
