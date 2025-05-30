# Teachable Machine Workshop: Happy & Sad Emoji App

👋 Welcome to the Teachable Machine Workshop!  
In this project, you'll learn how to train a computer to recognize your facial expressions (Happy and Sad) using Teachable Machine, and then use HTML and JavaScript to display matching emojis in a fun interactive app.

---
________________________________________
😊 Step 1: Train Your Emotion Model
1.	Go to Teachable Machine (https://teachablemachine.withgoogle.com/)
2.	Click “Get Started” > Choose “Image Project” > “Standard Image Model”
3.	Create two classes:
•	Happy
•	Sad
4.	Use your webcam to record at least 30 images for each expression.
5.	Click “Train Model” and wait for it to finish.
6.	Click “Export Model” > Choose “TensorFlow.js”
7.	Click ‘Upload my model’
8.	Copy the model URL (it should end with a /)
 
 
Step 2: Use the Code
1.	Open the p5.js editor https://editor.p5js.org/
2.	Click on the ‘Arrow’ button
3.	Select ‘Index.html’ and delete the code
4.	Open the provided HTML file (studentCode.html)
5.	Replace the code in index.html with studentCode.html
6.	Replace this line in the code:
let modelURL = "PASTE_YOUR_MODEL_URL_HERE";
 
with your own model URL from Teachable Machine.

3.	Save the file and open it in a browser.
4.	Allow webcam access.
5.	Try your happy and sad faces — you should see the emoji change!

 
Challenge: Add a Neutral Expression
Want to go further?
1.	Go back to Teachable Machine and add a third class called Neutral.
2.	Record your neutral face and retrain the model.
3.	Export the new model and update the model URL in your code.
4.	In the code, find this part:
// Map emotion labels to emojis
      if (label === "Happy") emoji = "😄";
      else if (label === "Sad") emoji = "😢";
      else emoji = "🤖";

5.	Add a new line for your neutral expression:
else if (label === "Neutral") emoji = "😐";

6.	Save and test it out!


---

## 💻 HTML Code

You can view and copy the HTML code used in this project:

1. Click on the `studentCode.html` file in this repository.
2. Click the **"Raw"** button to view the full code.
3. Right-click and choose **"Select All"** > **"Copy"**.
4. Paste it into your own code editor 

---

## 📄 Workshop Document

To follow along with the full instructions, download the Word document:

👉 Click on 3 dots to download the worksheet

## 🚀 What You'll Learn

- How to train a model using Teachable Machine
- How to use ml5.js and p5.js to classify webcam input
- How to display emojis based on facial expressions
---

Happy coding! 😄
