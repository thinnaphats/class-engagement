**Class Engagement** - A web application that detects faces and expressions based on machine learning. 
It is to classify the pictures and make predictions. Web Bootstrap takes the machine learning model created in **[Lobe](https://lobe.ai/)**, 
and adds it to a project in the browser that uses **[React](https://reactjs.org/)**, **[Create React App](https://github.com/facebook/create-react-app)**, 
**[TypeScript](https://www.typescriptlang.org/)**, and **[TensorFlow.js](https://www.tensorflow.org/js)**.

# Class-Engagement

**Developed by** Mr.THINNAPHAT SODANAT, Code. 613040490-0, Computer Engineering, Khon Kaen University.

## How to run Class-Engagement on your computer (local server)
1. You need to download this project on your computer. **(make sure you download from branch Master)**
2. You need to install **[Node.js](https://nodejs.org/en/)** - to start the React app or start the local server.
3. In your project's folder, use command **"npm install"** and then use command **"npm start"** to start the local server and redirect to Class-Engagement.

## About the project
**1. Train model**
- Use more than 400+ pictures for each expressions(Happy, Sad and Neutral).
- Use model in Lobe(ResNet-50V2) optimize for accuracy.
- Split data at 80/20

**2. Test model**
- 92% of images are predicted correctly.
- 8% are incorrectly.
