# Ai-master.in
Ai discover 
**app.py (Python file)**
```
from flask import Flask, render_template
app = Flask(__name__)
@app.route("/")
def home():
  return render_template("index.html")
if __name__ == "__main__":
  app.run()
```
**index.html (HTML file)**
```
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <title>AiMaster.in</title>
 <link rel="stylesheet" href="styles.css">
</head>
<body>
 <h1>Bem-vindo ao AiMaster.in!</h1>
 <p>Nossa missão é fornecer soluções de IA inovadoras.</p>
 <button>Conheça mais sobre nós</button>
</body>
</html>
```
**styles.css (CSS file)**
```
body {
 background-image: url('https://images.pexels.com/photos/270373/pexels-photo-270373.jpeg');
 background-size: cover;
 font-family: Arial, sans-serif;
}
h1 {
 color: #fff;
 text-align: center;
 padding-top: 100px;
}
p {
 color: #fff;
 text-align: center;
}
button {
 background-color: #4CAF50;
 color: #fff;
 padding: 15px 32px;
 text-align: center;
 text-decoration: none;
 display: inline-block;
 font-size: 16px;
 cursor: pointer;
}
```
**Requirements.txt (Python libraries)**
```
Flask
```
