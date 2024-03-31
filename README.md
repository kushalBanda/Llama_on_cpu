# Llama2-on-CPU-Machine

Llama2-on-CPU-Machine is a lightweight implementation of the Llama 2 model, optimized to run efficiently on CPU-based systems. This guide will help you set up and run the project on your machine.

## Prerequisites

- Git
- Conda (Anaconda or Miniconda)
- Python 3.8

## Installation

### Step 1: Clone the Repository

Start by cloning the repository to your local machine:

```bash
git clone https://github.com/https://github.com/kushalBanda/Llama_on_cpu.git
```


### Step 2: Set Up the Virtual Environment

1. Create a new Conda environment named `cpullama`:

    ```bash
    conda create -n cpullama python=3.8 -y
    ```

2. Activate the newly created environment:

    ```bash
    conda activate cpullama
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

### Step 3: Download the Llama 2 Model

Download the Llama 2 model file `llama-2-7b-chat.ggmlv3.q4_0.bin`:

1. Visit the following link:

    [Llama 2 Model Download](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main)

2. Download the `llama-2-7b-chat.ggmlv3.q4_0.bin` file.

3. Place the downloaded file in the `model` directory of your cloned repository.

## Running the Application

After setting up, you can run the application:

```bash
python app.py
```

## Support

For any issues or questions, please open an issue on the GitHub repository.

---
