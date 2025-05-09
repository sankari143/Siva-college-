# College Online Admission Chatbot with Voice Recognition

## Project Overview

This project involves developing a college online admission system using a voice recognition chatbot. The chatbot will guide users through the admission process, filling out the required forms based on voice commands, and assisting in submitting the application. The system is built with HTML, CSS, and Python for the backend, utilizing speech recognition to enhance user interaction.

## Features

* **Voice-Activated Form Filling**: Users can fill out the admission form through voice commands.
* **Chatbot Assistance**: The chatbot will guide users through the entire admission process.
* **Speech-to-Text Conversion**: Converts voice input into text for accurate form filling.
* **Responsive UI**: The web interface is responsive, designed with HTML and CSS.
* **Flask Backend**: The Flask web framework is used to handle voice commands and interact with the backend.

## Technologies Used

* **HTML**: For the front-end structure.
* **CSS**: For styling and making the website responsive.
* **Python (Flask)**: For backend development.
* **SpeechRecognition API**: For converting speech to text.
* **JavaScript**: For enabling the speech input functionality on the webpage.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/college-admission-chatbot.git
   ```

2. Navigate to the project directory:

   ```bash
   cd college-admission-chatbot
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask app:

   ```bash
   python app.py
   ```

5. Open your browser and visit `http://127.0.0.1:5000/` to start the chatbot.

## Project Structure

```
college-admission-chatbot/
│
├── app.py              # Flask backend
├── templates/
│   └── index.html      # Main HTML file for the front-end
├── static/
│   ├── css/
│   │   └── style.css   # Styling for the website
│   └── js/
│       └── script.js   # JavaScript for speech recognition functionality
└── requirements.txt    # List of required Python libraries
```

## How It Works

1. **Frontend**: The frontend is designed using HTML and CSS. It consists of a simple form for user input and a button to start the voice interaction.

2. **Voice Recognition**: When the user clicks the "Start" button, the SpeechRecognition API captures the voice input and converts it to text.

3. **Backend (Flask)**: The Flask server receives the data from the frontend, processes the form data, and guides the user through filling out the admission form.

4. **Submission**: After completing the form, the user can submit the details, and the application will be processed.

## Example Usage

1. Click the "Start" button to begin the voice registration.
2. Speak the details for each field (e.g., "My name is Siva" or "I want to enroll in Computer Science").
3. The chatbot will ask for all necessary information and fill the form based on your responses.
4. Submit the form once completed.

## Future Enhancements

* **Advanced Natural Language Processing (NLP)** for more sophisticated conversations.
* **Voice Feedback**: The chatbot can provide voice feedback to confirm user input.
* **Database Integration**: Store user data in a database for later retrieval.

## Contributing

Feel free to fork this project and contribute to its development! Create issues or pull requests for any new features or bug fixes.

---

Let me know if you need any additional modifications!
