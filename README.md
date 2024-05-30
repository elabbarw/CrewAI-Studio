
# CrewAI Studio

Welcome to CrewAI Studio! This application provides a user-friendly interface for interacting with CrewAI, suitable even for those who don't want to write any code. Follow the steps below to install and run the application on Windows or Linux using either Conda or a virtual environment.

## Features

- **Multi-platform support**: Works on Windows and Linux.
- **No coding required**: User-friendly interface for interacting with CrewAI.
- **Conda and virtual environment support**: Choose between Conda and a Python virtual environment for installation.

## Installation

### Prerequisites

- **For Virtual Environment**: Ensure you have Python installed.

### Using Virtual Environment

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/crewai-studio.git
   cd crewai-studio
   ```

2. **Run the installation script**:
   ```bash
   ./install_venv.sh
   ```

3. **Run the application**:
   ```bash
   ./run_venv.sh
   ```

### Using Conda

Conda will be installed locally in the project folder. No need for a pre-existing Conda installation.

#### On Linux

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/crewai-studio.git
   cd crewai-studio
   ```

2. **Run the Conda installation script**:
   ```bash
   ./install_conda.sh
   ```

3. **Run the application**:
   ```bash
   ./run_conda.sh
   ```

#### On Windows

1. **Clone the repository**:
   ```powershell
   git clone https://github.com/yourusername/crewai-studio.git
   cd crewai-studio
   ```

2. **Run the Conda installation script**:
   ```powershell
   .\install_conda.bat
   ```

3. **Run the application**:
   ```powershell
   .run_conda.bat
   ```

If you do not have Git installed, you can download the repository as a ZIP file from the GitHub page and extract it.

## About CrewAI

CrewAI is a robust and flexible framework designed to facilitate the orchestration of autonomous AI agents. These agents can work together seamlessly, sharing goals and collaborating on tasks to achieve impressive results. Here are some key features of CrewAI:

- **Collaborative Intelligence**: CrewAI excels in scenarios where multiple agents come together to form a "crew." This collaboration allows for the delegation of tasks and spontaneous assistance, mirroring real-world teamwork.
  
- **Dynamic and Adaptable Processes**: The framework supports dynamic processes that can adapt to both development and production environments, making it versatile for various use cases.

- **Open Source and Extensible**: CrewAI is open-source and encourages contributions from the community. It integrates well with various AI models and tools, offering extensive customization options for specific needs.

- **Integration with LangChain**: Built on top of LangChain, CrewAI agents benefit from the extensive toolkits and tools provided by LangChain, enabling a wide range of functionalities out of the box.

## Configuration

Before running the application, ensure you update the `.env` file with your API keys and other necessary configurations. An example `.env` file is provided for reference.

