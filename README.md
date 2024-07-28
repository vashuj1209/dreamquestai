# dreamquestai

# DreamQuestAI - built and founded by vaishali jha @2024

**DreamQuestAI** is an AI-backed and personalized career development co-pilot designed to assist high school students in exploring career paths, developing essential skills, and making informed decisions about their future. This tool provides tailored career advice, skill-building resources, and mentorship opportunities, all at the fingertips of every student.

## Features

- **Personalized Career Guidance**: Get customized career recommendations based on your interests and strengths.
- **Interactive Q&A**: Ask questions about careers, college planning, job readiness, and more.
- **Skill Development Tips**: Receive suggestions for relevant courses, internships, workshops, and online resources.
- **Networking and Mentorship**: Connect with professionals and mentors in various fields.

## Installation

To set up DreamQuestAI, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/dreamquestai.git
    cd dreamquestai
    ```

2. **Create a virtual environment**:
    ```bash
    python3 -m venv career-co-pilot-env
    source career-co-pilot-env/bin/activate
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up environment variables**:
    Create a `.env` file in the root directory and add your OpenAI API key:
    ```env
    OPENAI_API_KEY=your-api-key
    ```

## Usage

1. **Run the FastAPI application**:
    ```bash
    uvicorn main:app --host 0.0.0.0 --port 8000
    ```

2. **Access the application**:
    Open your browser and go to `http://localhost:8000`.

3. **Interact with DreamQuestAI**:
    Use the web interface to ask career-related questions and get personalized advice.

## Example Requests

Here are some example interactions you can have with DreamQuestAI:

- **Career Options**:
    ```json
    {
        "question": "What are some good career options for someone interested in science?"
    }
    ```

- **Skill Development**:
    ```json
    {
        "question": "How can I prepare for a career in engineering?"
    }
    ```

- **Mentorship**:
    ```json
    {
        "question": "How can I find a mentor in my desired career field?"
    }
    ```

## Contributing

We welcome contributions from the community! If you’d like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Open a pull request.




