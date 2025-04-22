# feedback.com
body {
  font-family: Arial, sans-serif;
  background-color: #f3f3f3;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.feedback-container {
  background: white;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
  width: 300px;
}

.feedback-container h2 {
  margin-bottom: 20px;
  text-align: center;
}

input, textarea {
  width: 100%;
  margin-bottom: 15px;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  width: 100%;
  background-color: #4CAF50;
  color: white;
  border: none;
  padding: 10px;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background-color: #45a049;
}

#confirmation {
  margin-top: 15px;
  text-align: center;
  color: green;
}

.hidden {
  display: none;
}
