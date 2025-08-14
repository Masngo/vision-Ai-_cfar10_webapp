## vision-Ai-_cfar10_webapp

1. Folder Structure
cifar10_webapp/
│	
├── app.py                # Main Flask application
├── cifar10_demo_model.keras  # Your trained CNN model
├── requirements.txt      # List of Python packages (optional)
│
└── templates/
    └── index.html        # HTML file for web interface
Explanation:
•	app.py → Flask backend that handles image upload and predicts using the CNN model.
•	cifar10_demo_model.keras → Your trained CIFAR-10 model from Colab.
•	requirements.txt → Optional but useful for installing dependencies quickly:
flask
tensorflow
numpy
pillow
•	templates/index.html → Simple web page where users upload images and see predictions.
•	Flask automatically looks in the templates folder for HTML files.

2. How to Set Up & Run on CMD or VS Code
Step A — Install Python Packages
Open CMD or VS Code terminal in the cifar10_webapp folder:
pip install flask tensorflow numpy pillow
Or if using requirements.txt:
pip install -r requirements.txt

Step B — Run the Flask App
In CMD or terminal:
python app.py
•	You should see something like:
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

Step C — Open Web App
1.	Open your browser and go to:
http://127.0.0.1:5000/
2.	You’ll see the upload page.
3.	Upload a 32x32 image or any CIFAR-10-like image → click Predict.
4.	Flask will show the predicted class on the page.

3. Optional Tips
•	Use VS Code: Open the folder, then use the built-in terminal to run python app.py.
•	Debug mode: Already set in app.py (debug=True) — it reloads when you change code.
•	Custom images: Resize them to 32x32 pixels before uploading or add preprocessing in app.py.
•	Deployment: Later, you can deploy this app online using Heroku, Render, or PythonAnywhere.
4. Connect with Me
For networking and opportunities, feel free to connect with me on LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/masango-dewheretsoko-5ba182148)
5. Note for Future Students
As you embark on your projects, remember that perseverance and curiosity are key. Don't hesitate to explore beyond the basics and seek help when needed. Good luck, and I hope you enjoy the journey into machine learning and web development!



