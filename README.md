# A Hitchikers Guide To Quantum Computing: An introduction to quantum machine learning


This repo contains the notebook as well as data files for the talk on quantum machine learning. You can run this notebook using two methods. The first way is to clone this repo to your local device and run it, the second way is to use google colab. 

## Running on your device

Follow these steps to set up the project on your local machine.

### Prerequisites

Ensure you have Python installed. You can download Python from the official [Python website](https://www.python.org/).

### Step 1: Install Python

#### Windows

1. Download the installer from the [Python website](https://www.python.org/).
2. Run the installer and follow the instructions.
3. During the installation, ensure you check the box that says "Add Python to PATH".

#### macOS

1. Open Terminal.
2. Install Homebrew if you haven't already:
   ```sh
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
3. Install Python:
   ```sh
   brew install python
   ```

#### Linux

1. Open Terminal.
2. Install Python:
   ```sh
   sudo apt-get update
   sudo apt-get install python3
   ```

### Step 2: Create a Virtual Environment

A virtual environment helps to manage project dependencies and avoid conflicts.

1. Open your terminal or command prompt.
2. Navigate to your project directory.
3. Create a virtual environment:
   ```sh
   python -m venv my_env_name_here
   ```
4. Activate the virtual environment:

   - On Windows:
     ```sh
     venv\Scripts\activate
     ```
   - On macOS and Linux:
     ```sh
     source venv/bin/activate
     ```

### Step 3: Install Dependencies

1. Ensure your virtual environment is activated.
2. Install the required dependencies using the `requirements.txt` file:
   ```sh
   pip install -r requirements.txt
   ```
### Step 4: Clone this repo 

1. Clone this repository and save it to a local folder of your choice.

### Step 5: 

In your command line while your virutal envirnoment is active,

```
jupyter notebook
```

This will open up the jupyter notebook interface where you can navigate to the folder where the notebook is stored and open the notebook.

## Running the notebook using google colab

Log into [Google Colab](https://colab.research.google.com) using your google account. Click on FILE and OPEN then select github and copy the repo URL into the text box and open the notebook. 

You will also need to download all the CSV files and upload it to your google drive in the side pannel of colab so that you can use these files in your notebook.
