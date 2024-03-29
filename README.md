# AI Junior Developer Test - NLP Chatbot

## How to Run 🚀

This guide provides instructions on how to run the NLP Chatbot developed for the AI Junior Developer Test. The code has been tested using Python 3.8 on Linux Ubuntu 20.04.6 LTS and Docker version 20.10.24.

### Local Execution 🖥️

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/Ahsanmaqbool/science_chatbot.git
    cd science_chatbot
    ```

2. **Create and Activate Virtual Environment:**

    If `virtualenv` is not installed, install it using:

    ```bash
    pip install virtualenv
    ```

    Then, create and activate the virtual environment:

    ```bash
    python3.8 -m venv science_chatbot
    source science_chatbot/bin/activate  # On Windows, use `science_chatbot\Scripts\activate`
    ```

3. **Install Dependencies:**

    Use pip to install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Application:**

    Execute the provided `start.sh` script:

    ```bash
    ./start.sh
    ```

### Docker Container 🐳

1. **Build the Docker Image:**

    To build the Docker image, run the following command:

    ```bash
    docker build -t science_chatbot .
    ```

2. **Run the Docker Container:**

    Launch the Docker container using the following command:

    ```bash
    docker run -it science_chatbot
    ```
