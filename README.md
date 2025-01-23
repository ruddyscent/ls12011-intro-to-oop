# Introduction to Python for AI Programmers

This repository contains examples and demo code for Udacity's **Introduction to Python for AI Programmers** lessons. The content is designed to teach object-oriented programming (OOP) principles and Python practices through hands-on exercises and real-world examples. Additionally, the repository includes a Docker Compose configuration to set up a local development environment easily.

## Repository Contents

The following directories contain example and exercise files that can be executed in a Jupyter Notebook environment:
* **exercise-oop-syntax-practice-part-1**: Part 1 of OOP syntax practice exercises.
* **exercise-oop-syntax-practice-part-2**: Part 2 of OOP syntax practice exercises.
* **exercise-code-the-gaussian-class**: Exercise for building and using a Gaussian class.
* **exercise-code-magic-methods**: Exercise focused on understanding and implementing Python magic methods.
* **exercise-inheritance-with-clothing**: Practice exercise on inheritance using a clothing class example.
* **demo-inheritance-probability-distributions**: Demo showing inheritance applied to probability distributions.
* **exercise-making-a-package-and-pip-installing**: Exercise on creating and installing a Python package with pip.

---
The following directories contain files meant for more advanced OOP topic exercises that are typically performed in an integrated development environment (IDE):
* **1_instruction_files**: Instructional files for advanced OOP topics.
* **2_modularized_code**: Examples demonstrating how to modularize Python code.
* **3b_answer_python_package**: Solution code for building and structuring a Python package.
* **4a_binomial_package**: Example code for implementing a binomial distribution package.
* **4b_answer_binomial_package**: Solution code for the binomial distribution package exercise.
* **5_exercise_upload_to_pypi**: Exercise files for uploading a Python package to PyPI.

## How to Use This Repository
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/udacity/ls12011-intro-to-oop.git
    ```

2. Navigate to the specific directory that matches your lesson or topic of interest.

3. Follow the instructions within the files to explore the examples, run the code, or complete exercises.

## How to Use the Containerized Jupyter Environment (Optional)
1. Ensure Docker and Docker Compose are installed on your system.

2. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/udacity/ls12011-intro-to-oop.git
    ```

3. Navigate to the project directory:
    ```bash
    cd ls12011-intro-to-oop
    ```

4. Set up the `.env` file:
   * Create a `.env` file in the root of the project directory to configure the container environment variables. Below is an example of what the file might include:

    ```bash
    # .env file
    JUPYTER_PORT=8888
    JUPYTER_TOKEN=your_custom_token
    ```
   * Replace `your_custom_token` with a secure token to access Jupyter Notebook.
   * Modify `JUPYTER_PORT` if you want to use a different port.

5. Build and start the Docker containers:

    ```
    docker-compose up --build
    ```

6.	Access the development environment:
    Open your web browser and navigate to `http://localhost:8888/?token=your_custom_token`. Use the token in your `.env` file (`JUPYTER_TOKEN`) to log in to the Jupyter Notebook interface.

## License

This repository is licensed under Udacity's terms. The LICENSE file in the repository provides more details.
