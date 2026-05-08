# AI Medical Chatbot (Medibot)

Medibot is an AI-powered healthcare assistant designed to provide medical information and guidance. It leverages OpenAI's GPT-3.5-turbo for natural language understanding and response generation, ensuring that conversations stay strictly on healthcare and medical topics.

## Features

*   **Intelligent Medical Assistant:** Powered by OpenAI, capable of answering questions about symptoms, treatments, prevention, and various medical fields.
*   **Safety Filtering:** Implements a robust keyword-based filtering system to ensure the chatbot strictly provides medical information and rejects non-medical queries.
*   **Interactive Web Interface:** 
    *   Sleek frontend built with basic web technologies (`index.html`, `login.html`, `about-page.html`).
    *   Chatbot interactive UI built using **Gradio** for Python, making testing and interacting seamless.
*   **Audio Element:** Includes audio cues/interactions (`bot.mp3`).

## Technologies Used

*   **Python:** Core backend logic.
*   **OpenAI API:** LLM engine for conversational AI (GPT-3.5 architecture).
*   **Gradio:** For rapid deployment of the Python web UI.
*   **HTML/CSS:** For static front-end pages associated with the project.

## Setup Instructions

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Nandhagopal23/Medibot.git
    cd Medibot
    ```

2.  **Install the dependencies:**
    You will need Python installed. Install the necessary Python packages:
    ```bash
    pip install openai gradio python-dotenv
    ```

3.  **Configure API Keys:**
    Create a `.env` file in the `buildathon project` directory (you can copy `.env.example` to `.env`) and add your OpenAI API key:
    ```env
    OPENAI_API_KEY=your_actual_api_key_here
    ```

4.  **Run the application:**
    Navigate to the project folder and run the Gradio app:
    ```bash
    cd "buildathon project"
    python chatbot.py
    ```

5.  **Access the Interface:**
    Once running, a local URL (and a public share URL using `share=True`) will be provided in your terminal. You can click these on your local browser to interact with the bot!

## Disclaimer

**Medibot is not a substitute for professional medical advice, diagnosis, or treatment.** Always seek the advice of your physician or other qualified health provider with any questions you may have regarding a medical condition.

## Contributing

Feel free to open issues or submit pull requests with improvements to the project.