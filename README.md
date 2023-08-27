# Phishing_website_Detection
ML Model to Predict Phishing Websites

## Steps to Run This Model

Follow these steps to set up and run the phishing website detection model:

**1. Clone the Repository**

   Clone this GitHub repository to your local machine using the following command:
   ```
   git clone https://github.com/your-username/phishing-detection.git
   ```

**2. Create a Virtual Environment**

   Navigate to the project directory and create a virtual environment to isolate project dependencies. You can use `venv` or `conda`, depending on your preference. Here's an example using `venv`:

   ```
   cd phishing-detection
   python -m venv venv
   ```

**3. Activate the Virtual Environment**

   Activate the virtual environment to install and run the project within a controlled environment. Use the appropriate command for your operating system:

   - **On Windows:**
     ```
     venv\Scripts\activate
     ```

   - **On Unix or Linux:**
     ```
     source venv/bin/activate
     ```

**4. Install Dependencies**

   Install the required Python packages listed in `requirements.txt` using `pip`:

   ```
   pip install -r requirements.txt
   ```

**5. Run Model Training**

   Run the model training script to train the phishing website detection model:

   ```
   python model_training.py
   ```

   This will generate the trained model and evaluation results.

**6. Run the Web Application**

   Start the web application using Streamlit:

   ```
   streamlit run app.py
   ```

   This will launch the web application locally, allowing you to interact with the model through a web interface.

Follow these steps carefully to set up and use the phishing website detection model. Feel free to explore and customize the code to suit your specific needs.

