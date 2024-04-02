# face-recognition-auth-reactjs

A simple authentication page with face recognition and face verification built with ReactJS and Face-api.js.

## Features

- **Face recognition and verification (Login/Register)**
- **Similarity Test Widget**
- **Matching Test Widget**

Minor features:

- Comparison between different pre-trained neural networks.
- Computation of Euclidean distance and Manhattan distance on `Labeled Faces in the Wild` dataset.
- Evaluation of false positive and false negative matching.
- Encryption/decryption of biometric data.

## System Requirements

- **NODE.JS** (tested on v14.19.3)
- **NPM**
- **MongoDB**

## Installation

```python
git clone git@github.com:albertovalerio/face-recognition-auth-reactjs.git
```
Install frontend dependencies
```python
cd ~/path/to/your/face-recognition-auth-reactjs/frontend_app
```
```python
npm install
```
```python
npm start
```
Install backend dependencies
```python
cd ~/path/to/your/face-recognition-auth-reactjs/backend_app
```
```python
npm install
```
```python
npm run dev
```
Configure `.env` file
```python
cp .env.example .env
```
```python
API_PORT=3001
FRONTEND_URL='http://localhost:3000'
MONGO_URI='mongodb+srv://<USERNAME>:<PASSWORD>@cluster0.bckok.mongodb.net/<DATABASE_NAME>?retryWrites=true&w=majority'
TOKEN_KEY='...' (used by JWT, recommended 50/60 chars)
PRIVATE_KEY='...' (used by Bcrypt, must be of 32 chars)
```


## Acknowledgments

- **[@reactjs](https://reactjs.org/)**
- **[@redux_toolkit](https://redux-toolkit.js.org/)**
- **[@mongodb](https://www.mongodb.com/)**
- **[@faceapi.js](https://github.com/justadudewhohacks/face-api.js/)**

 My site View 
 FRONTEND WEBSITE look like this
first register your account with name login-id and password ,also detect your face 
![Screenshot 2024-04-02 190002](https://github.com/Ayushisri29/face_detection_frontend/assets/92778552/496c081e-838b-401c-bd1a-ab82bdec069b)
then login after detect your all information 

![Screenshot 2024-04-02 183437](https://github.com/Ayushisri29/face_detection_frontend/assets/92778552/3dc6ddd6-2005-4d46-9971-d9786683f29d)

BACKEND WEBSITE look like this 
AFTER REGISTRATION AND LOGIN WHEN YOU entered into the system
![Screenshot 2024-04-02 183411](https://github.com/Ayushisri29/Facerecognization_app/assets/92778552/feec7a75-2c02-4667-8031-1c12efbc2e87)


