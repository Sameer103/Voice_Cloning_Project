# Voice_Cloning_Project
# Git: https://github.com/Sameer103/Voice_Cloning_Project.git

# YouTube
[![Alt text](https://img.youtube.com/vi/76HaHmmD9kY/0.jpg)](https://www.youtube.com/watch?v=76HaHmmD9kY)




This project is aimed at creating a voice cloning model using deep learning techniques. The model can generate speech that sounds like a specific person's voice. The project is hosted on Github and is open-source, meaning anyone can contribute to the development of the model.

## Getting Started

To get started with this project, you will need to clone the repository onto your local machine. Once you have done that, you can follow the instructions in the README file to set up the environment and install the necessary dependencies.
# (For any issue do consider the above Video)

## Dependencies

The following dependencies are required to run the voice cloning model:

- Python 3.9
- PyTorch 1.0+
- Librosa
- NumPy
- SciPy
- tqdm
- Unidecode
- Sound Device
- ffmpeg

## Setup
## 1. Install Requirements
Both Windows and Linux are supported. A GPU is recommended for training and for inference speed, but is not mandatory.
Python 3.7 is recommended. Python 3.5 or greater should work, but you'll probably have to tweak the dependencies' versions. I recommend setting up a virtual environment using venv, use python version 3.9 this will be suitable for your requirements.txt file.

Install ffmpeg. This is necessary for reading audio files.

Install PyTorch. Pick the latest stable version, your operating system, your package manager (pip by default) and finally pick any of the proposed CUDA versions if you have a GPU, otherwise pick CPU. Run the given command.

At last, Install the remaining requirements with pip install -r requirements.txt

## 2.  Download Pretrained Models
Pretrained models are now downloaded automatically. If this doesn't work for you, you can manually download them here (https://www.openslr.org/12).

## 3. Test Configuration
Before you download any dataset, you can begin by testing your configuration with

python demo_cli.py

If all tests pass, you're good to go.

This is to check every requirement is fulfilled, if not, do install the requirements

## 4. (Optional) Download Datasets
For playing with the toolbox alone, I only recommend downloading LibriSpeech/train-clean-100 (mentioned above). Extract the contents as <datasets_root>/LibriSpeech/train-clean-100 where <datasets_root> is your chosen directory. Other datasets are supported in the toolbox, see here. You're free not to download any dataset, but then you will need your own data as audio files or you will have to record it with the toolbox.

## 5. Launch the Toolbox
You can then try the toolbox:

python demo_toolbox.py -d <datasets_root>
or
python demo_toolbox.py

depending on whether you downloaded any datasets. If you are running an X-server or if you have the error Aborted (core dumped),



## Contributing

If you want to contribute to the development of this project, you can fork the repository and submit a pull request with your changes. Please make sure to follow the contribution guidelines outlined in the README file.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

## Acknowledgments

This project was inspired by the work of Corentin Jemine on his [Deep Voice 3](https://github.com/r9y9/deepvoice3_pytorch) project. Special thanks to him and all the contributors who have helped make this project possible.
