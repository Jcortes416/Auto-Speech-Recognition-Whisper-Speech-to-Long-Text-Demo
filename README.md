
# Auto Speech Recognition for Long Recordings with Whisper and Demo

## Description
This project is tailored for automatic speech recognition (ASR) of longer audio recordings using OpenAI's Whisper model, incorporating an interactive demo built with Gradio. It showcases the model's ability to handle extended audio files, providing an intuitive interface for users to upload their recordings and receive transcriptions in real-time. The included Jupyter notebook guides users through the process of data preparation, utilizing the model for ASR, and deploying a Gradio demo for live interaction.

## Installation

Ensure that Python is installed on your system. Using a virtual environment is highly recommended for managing dependencies effectively.

Install the necessary packages with this command:

\```bash
pip install transformers datasets soundfile librosa gradio
\```

Dependencies include libraries for running the machine learning model, data processing, audio file manipulation, and creating interactive web demos.

## Usage

Follow these steps to start using this project for long audio speech recognition:

1. **Clone the repository** to your local environment.
2. **Open the `Auto Speech Recognition LONG (Whisper Speech to Text) with DEMO.ipynb` notebook** in Jupyter Lab or Jupyter Notebook.
3. **Execute the notebook cells in order**, adhering to any provided instructions. The notebook will walk you through the steps for preparing your data, leveraging the Whisper model for transcription, and setting up a Gradio interface for live demo testing.

## Features

- Efficient data preparation and loading with the `datasets` library.
- Application of the Whisper model for transcribing long audio recordings.
- A live demo interface using Gradio for an interactive testing experience.

## Contributing

Your contributions are welcome! For any improvements or fixes, please fork the repository, apply your changes, and open a pull request. For substantial changes, we recommend opening an issue first to discuss your proposed changes.

## License

This project is released under the MIT License. Refer to the LICENSE file for more details.
