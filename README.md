# Chatbot

1. Open a Terminal or Command Prompt.

2. Navigate to the Desired Directory:
Use the cd command to navigate to the directory where you want to clone the project.
For example:
```
cd path/to/desired-directory
```

4. Clone the Repository:
Run the following command to clone your GitHub repository:
```
git clone https://github.com/ChintanRP11/chatbot.git
```


6. Navigate and Move into the cloned directory:

7. install backend dependencies
```
npm install
```

9. Create environment files
```
PORT=3001
MONGODB_URI=your-mongodb-connection-string
SECRET_KEY=your-secret-key
```

or use these environment variables
```
PORT=3001
MONGODB_URI="mongodb+srv://chintanrp11:qGkf9Gb9wMvsYvAZ@cluster0.es4yzzq.mongodb.net/"
SECRET_KEY=f38a6b58a3e4d4e2e94fb8a48e6a1338c309684a038fc4d10c1b86ff19b5a1d7
```

7. start backend server:
```
npm start
```

9. start frontend:
```
npm install -g serve
serve -s build
```

11. Open this link in browser
- Local:    http://localhost:3000  
