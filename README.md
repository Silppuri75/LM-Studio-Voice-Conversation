# LM-Studio-Voice-Conversation

Welcome to the guide for setting up and running the LM-Studio-Voice-Conversation Python application. This application enhances voice conversations using local Large Language Models (LLMs) and incorporates Whisper for speech-to-text capabilities. It is designed with a focus on privacy and accessibility, providing a user-friendly interface for interactive voice-based interactions with AI.

## Getting Started

This section will guide you through preparing your local machine for running the LM-Studio-Voice-Conversation project, including installing prerequisites, setting up the Python environment, and running the project.

### Prerequisites

Before you begin, ensure you have the following installed:

- **Anaconda**: Download and install from [Anaconda's official site](https://www.anaconda.com/).
- **LM Studio**: Access and information available at [LM Studio's website](https://lmstudio.ai/).

### Setting Up Your Python Environment

Follow these steps to prepare your environment:

1. **Install Anaconda**: Follow the Anaconda installation instructions for your operating system available on the Anaconda website.

2. **Create a New Conda Environment**:
   ```bash
   conda create -n myenv python=3.9.18

   Replace `myenv` with a name of your choice for the environment.

3. **Activate the Environment**:
   ```bash
   conda activate myenv
   ```

### Clone the Repository
Get the project code by cloning the LM-Studio-Voice-Conversation repository:
```bash
git clone https://github.com/VideotronicMaker/LM-Studio-Voice-Conversation
```

4. **Install Required Packages**:
   Navigate to the cloned directory and install the necessary packages:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Project
- **LLM Python Script (`speak.py`)**: Main script for the language model.

To run the script, execute this command in your terminal:
```bash
python speak.py
```
Below is a clear, step-by-step guide on how to run the `run_script.bat` batch file, including navigating to the appropriate directory, running the script, activating the Conda environment, checking directory changes, running a Python script, and reviewing the output.

```markdown
# How to Run `run_script.bat`

This guide will walk you through the process of running the `run_script.bat` file from the Command Prompt. Follow these steps to execute your script successfully.

## 1. Open Command Prompt

Press `Win + R`, type `cmd`, and press Enter to open the Command Prompt.

## 2. Navigate to the Directory

If you're not already in the directory where the `run_script.bat` file is located, use the `cd` command to navigate to the directory where your code is stored. Replace `<code_directory>` with the actual path to your code directory:

```batch
cd /d <code_directory>
```

Make sure to replace `<code_directory>` with the actual path to the directory containing the `run_script.bat` file.

## 3. Run the Batch Script

Once you are in the correct directory, simply execute the `run_script.bat` file by typing its name and pressing Enter:

```cmd
run_script.bat
```

## 4. Activate Conda Environment

The batch script will attempt to activate the Conda environment named `python`.

## 5. Check Directory Change

It will check if the directory change was successful. If it encounters an issue and cannot find the specified path, it will display an error message: "The system cannot find the path specified."

## 6. Run Python Script

If the directory change is successful, it will proceed to run the Python script named `speak.py`.

## 7. Completion and Pause

After executing the Python script, the batch script will pause, allowing you to review any output or messages displayed by the Python script.

You should see the output of the Python script in the Command Prompt window. If there are any issues with the script or its execution, error messages will be displayed in the Command Prompt, helping you identify and address any problems.

Copy and paste this Markdown code into your documentation or README file as needed to provide clear instructions for running the `run_script.bat` file.
```

Ensure to replace the placeholders like `<code_directory>` with actual values when you prepare your repository documentation. This template is structured to help users understand each step in the process, from opening the Command Prompt to executing the `run_script.bat` file and beyond.


## Development Environment Setup

For detailed instructions on setting up and using Visual Studio Code with this project, please see [VSCode Instructions](VSCodeSetup.md).



## Need More Help?
If you're new to using command line interfaces for tasks like navigating directories, creating folders, or managing Python environments, resources like ChatGPT or Gemini Pro can provide detailed, step-by-step guidance.
