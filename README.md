🌱 AgroLens - Intelligent Farming Assistant
🚀 How to Set It Up
🛠️ Follow These Steps

📦 Download & Unpack the Code

Clone or download this repository as a ZIP file.

Extract the contents to a desired directory, e.g., C:\Users\YourName\Projects\AgroLens.

💻 Launch the Command Prompt

Hit Win + R, type cmd, and press Enter to open the terminal.

📁 Move to the Project Directory

Use the command below to switch to the app folder (update the path as needed):

cd C:\Users\YourName\Projects\AgroLens\AgroLens


📲 Start the React Native Frontend

In the root project folder, run:

npx expo start


This will launch Expo DevTools in your browser.

Open the Expo Go app on your smartphone and scan the QR code.

🌿 Launch the Crop Suggestion API

Open a new terminal window.

Navigate to the crop model folder:

cd C:\Users\YourName\Projects\AgroLens\AgroLens\flask_server\crop_recommendation_model


Run the Flask server:

python app.py


🍂 Launch the Leaf Disease Detection API

Open another terminal window.

Navigate to the plant disease model directory:

cd C:\Users\YourName\Projects\AgroLens\AgroLens\flask_server\leaf_disease_model


Start the backend server:

python app.py


✅ Try Out the App

Open the Expo Go app on your device.

Scan the QR code from step 4 to load the app.

Enter soil and weather data to get crop recommendations.

Upload a leaf image to detect potential plant diseases.

⚠️ Things to Keep in Mind

🔁 Run Both Backends Together: Make sure both Flask servers are active for full functionality.

📡 Same Network: Ensure your smartphone and computer are connected to the same Wi-Fi network.

📦 Install Dependencies First Time:

npm install
pip install -r requirements.txt


⚡ Live Flask Servers Needed: Predictions only work while servers are running.

🌿 Empowering Smart Farming with AI! 🚜
