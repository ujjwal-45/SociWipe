# Social-media-app
![new screen](https://github.com/ujjwal-45/SociWipe/assets/106880198/2c7865f2-3df6-4ce5-9a22-5140794cb584)



## install packages
### 1.in root directory 
```bash
npm install
```
### 2. change to client directory by cd client
```bash
npm install
```

## create .env file in server folder
```bash
1. MONGO_URL = "" // this is the URL created from mongodb atlas database
2. PORT = 3001
3. JWT_SECRET = "superstrongpassword or anything"
```

## Start the App
### In two terminal
### 1. cd client
```bash
npm run start
```
### 2. cd server
```bash
npm start
```

## Add a .gitignore file
### This will ignore node modules and your secret environment variables to be commited to git
### /node_modules
### .env
