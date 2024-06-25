# Batman-Chatbot-with-LLM-Integration

### Batman Chatbot with LLM Integration

#### Overview
This project is a chatbot application that leverages the strengths of Large Language Models (LLM) to handle natural language queries specifically related to Batman. The chatbot is developed using Flowise and integrates the LLaMA3 LLM. The application allows users to interact with the chatbot through a user-friendly interface and provides accurate responses about Batman.

#### Features

- **Domain:** The chatbot focuses on Batman, providing information and answering queries related to the Batman universe.
- **LLM Integration:** Utilizes the LLaMA3 model integrated into Flowise for query processing.

#### Components Used

- **Ollama Embeddings:** For embedding queries and context.
- **ChatOllama:** The main chat interface for interaction.
- **Conversational Retrieval QA Chain:** For retrieving relevant information.
- **In-Memory Vector Store:** To store and retrieve embeddings.

#### User Base
The application is designed for fans of Batman who want to learn more about the characters, storylines, and universe. It helps users by providing quick and accurate responses to their queries about Batman.

#### Getting Started

##### Prerequisites

- Node.js (v14 or higher)
- npm
- Flowise

##### Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/LissaRodrigues/Batman-Chatbot-with-LLM-Integration/new/main?readme=1

2. **Navigate to the project directory:**
    ```sh
    cd chat-bot-with-llm-integration
    ```

##### Running the Application

1. **Start Flowise:**
    ```sh
    npx flowise start
    ```

2. **Open your browser and navigate to** `http://localhost:3000` **to access the chatbot interface.**

3. **Make sure your ollama app is running in** `http://127.0.0.1:11434/`.

4. **Now run** `chatbot.html` **using Live Server.**

##### Usage

- Type your query related to Batman into the input box.
- The chatbot will process your query and provide a relevant response based on the LLaMA3 model.

#### Evaluation and Testing
The application has been tested with a variety of queries related to Batman to ensure its performance, accuracy, and usability. Below are some example queries:

Video Demonstration
A detailed video walkthrough of the application demonstrating its features and usage can be found here https://youtu.be/E_KrBf2L5Gs



- "Who is Batman?"
- "Tell me about the Batmobile."
- "What is the storyline of The Dark Knight?"

By following these steps, you will be able to set up and interact with a Batman-focused chatbot that leverages the power of LLaMA3 and Flowise for comprehensive and accurate responses.
