# LangChain Chat Memory Practice

This project demonstrates how to use LangChain's chat models, prompt templates, chains, agents, and memory in Python. It includes several Jupyter notebooks that show different LangChain features, such as sequential chains, conversation memory, and agent tools.

## screenshot
!(images/prac.jpg)

## Project Structure

- `agents.ipynb`: Shows how to use LangChain agents with tools like LLM math and Wikipedia.
- `chat_format_chains.ipynb`: Demonstrates chat models, prompt templates, and running chains for multiple queries.
- `memory.ipynb`: Explains how to use conversation memory to remember previous interactions.
- `sequential_chain.ipynb`: Builds a sequential chain where the output of one query is used as the input for the next.
- `.env`: Stores your API key (e.g., for Google Gemini).
- `gitignore`: Ensures `.env` is not tracked by git.

## Setup

1. Clone the repository.
2. Install dependencies:
    ```sh
    pip install langchain python-dotenv
    ```
3. Add your API key to the `.env` file:
    ```
    GOOGLE_API_KEY=your-google-api-key
    ```
4. Open any notebook (`.ipynb`) in Jupyter or VS Code and run the cells.

## Example Usage

- **Sequential Chain**: Find the capital of a country, then its famous food, then the color of that food.
- **Memory**: Have a conversation where the model remembers your name.
- **Agents**: Use tools to answer questions that require calculations or external knowledge.

## Notes

- The code uses the `gemini-2.0-flash` model from Google via LangChain.
- Some LangChain features used in the notebooks may show deprecation warnings; refer to the latest LangChain documentation for updates.

---

Feel free to explore each notebook to learn more about LangChain's capabilities!