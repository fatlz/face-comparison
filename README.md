# Face Comparison AI Application

A browser-based web application to analyze facial similarity between two photos using Machine Learning technology.

## ⚠️ Important Disclaimer
This tool is for **educational, experimental, and entertainment purposes only.**
* **Accuracy Limitations:** The current model may show inconsistencies. In some cases, the same person might be rated as having low similarity, while different people might show unexpected results.
* **Determining Factors:** Accuracy is heavily influenced by image quality, lighting, facial angles, and expressions. This application is **not** intended for official identity verification or security purposes.

## 🚀 Key Features
* **Depth Analysis:** Detects age, gender, and emotional expressions.
* **Mathematical Metrics:** Calculates *Euclidean Distance* and *Cosine Similarity* as the basis for the similarity score.
* **Modern UI:** Built with a *glassmorphism* design for a clean, aesthetic look.
* **Local Processing:** Analysis is performed directly in the browser.

## 🛠 Tech Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript.
* **AI Library:** [face-api.js](https://github.com/justadudewhohacks/face-api.js) (powered by TensorFlow.js).

## 📋 How to Run
1. Save the source code into a file named `index.html`.
2. Open the file using any modern web browser (Chrome, Firefox, Edge).
3. Ensure you have an active internet connection on the first run to download the AI models (approx. 5-10MB).

## 💡 Tips & Troubleshooting
* **Model Loading:** If the app gets stuck on "Loading," please refresh the page.
* **Face Detection:** Ensure the faces in the photos are clear, front-facing, and well-lit for better results. Avoid using filtered images.

