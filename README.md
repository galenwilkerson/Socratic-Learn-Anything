# Socratic: Learn Anything

![Socratic Method](./socratic.png)

This repository contains a Python script for teaching any topic using the Socratic method. The program guides the user through a series of questions, gradually increasing in complexity, to deepen their understanding of a topic.

## What is the Socratic Method?

The Socratic method is a form of cooperative argumentative dialogue between individuals, typically based on asking and answering questions to stimulate critical thinking and to draw out ideas and underlying presuppositions. It is named after the classical Greek philosopher Socrates and is introduced by him in Plato's 'Theaetetus' as midwifery (Maieutics).

## Features

- **Incremental Learning**: Questions start at a high-school level and gradually increase in complexity to college or graduate level.
- **Customizable Iterations and Levels**: Users can specify the number of iterations and the starting and ending complexity levels.

## How to Use

1. Clone the repository:
    ```sh
    git clone https://github.com/galenwilkerson/Socratic-Learn-Anything.git
    ```
2. Navigate to the repository directory:
    ```sh
    cd Socratic-Learn-Anything
    ```
3. Ensure you have the necessary API keys and libraries installed.
4. Save your OpenAI API key in a file named `api_key.txt` in the root directory.
5. Run the Jupyter notebook:
    ```sh
    jupyter notebook Socratic\ Teacher.ipynb
    ```
6. Follow the prompts to enter the topic you want to learn, confirm the generated prompt, and specify the teaching iterations and complexity levels.

## Installation

Ensure you have the required Python libraries:
```sh
pip install openai requests IPython
```

## Configuration

You will need an API key for OpenAI. Store this key in a file named `api_key.txt` in the root directory.

## Example Usage

Upon running the notebook, you will be prompted to:
- Enter the topic you want to learn.
- Confirm the rich prompt generated by ChatGPT.
- Specify the number of iterations (default is 50).
- Set the starting and ending complexity levels (default is high-school to graduate).

The program will then guide you through a series of questions to help you learn the topic deeply.

## Contributions

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
