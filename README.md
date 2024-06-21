# Hot-Dog-Recognizing-AI
This project utilizes a deep learning model from Hugging Face's model hub to classify images as either "hot dog" or "not hot dog". The model is deployed as a Flask web application where users can upload images and instantly receive classification results.

Usage:

1. Clone the repository: git clone https://github.com/your-username/hot-dog-recognizer.git
cd hot-dog-recognizer

2. Set up your environment:
Create and activate a virtual environment (optional but recommended): python -m venv venv
. venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. Install Flask and other dependencies: pip install Flask requests python-dotenv

4. Obtain an API key from Hugging Face and update the .env file:
   HUGGING_FACE_API_KEY=your_api_key_here
   HUGGING_FACE_API_URL=https://api-inference.huggingface.co/models/julien-c/hotdog-not-hotdog

5. Run the application: python web.py

6. Play with the AI on your browser.




![1](https://github.com/RavenCunanan/Hot-Dog-Recognizing-AI/assets/63638637/4ccdfe00-edd4-4412-921e-6162c8ac3d3e)


![2](https://github.com/RavenCunanan/Hot-Dog-Recognizing-AI/assets/63638637/6e315961-ee9d-4058-8d5d-1891db032d06)

