# Build an avatar with ASR, Sentence-transformer, Similarity Search, TTS and Omniverse Audio2Face
## Project Description
I'll show you how I used several Python packages and NVIDIA's Omniverse Audio2Face to quickly implement an avatar that can answer questions defined in a knowledge set or FAQ.

Omniverse Audio2Face is an application brings our avatars to life. With [Omniverse Audio2Face](https://www.nvidia.com/en-us/omniverse/apps/audio2face/), anyone can now create realistic facial expressions and emotions to match any voice-over track. The technology feeds the audio input into a pre-trained Deep Neural Network, based on NVIDIA and the output of the network drives the facial animation of 3D characters in real-time.

## How to Install and Run the Project
Before you begin, you'll need to clone the repository with the template code used in this repo. Open your Terminal app and find a directory where you'd like to store the code. Run this command to clone the GitHub App template repository:

```
$ git clone https://github.com/metaiintw/build-an-avatar-with-ASR-TTS-Transformer-Omniverse-Audio2Face.git
```
#### Creating an environment from an environment. yml file
Make sure Anaconda is installed on your local machine. Use the following command to install packages included in requirements.yml:
```
$ conda env create -f /path/to/requirements.yml
```
#### Bring Your Avatar to life
Now we're ready to bring our avatar to life, simply enter the following commands into your terminal. 
```
$ cd path_to_the_project_folder
$ conda activate avatar
$ jupyter lab
```
Execute the .ipynb notebook file named  ***1.Creating_a_simple_avatar.ipynb***, start building your first avatar!

| ![](https://i.imgur.com/YTSdxJT.png) | 
|:--:| 
| *1.Creating_a_simple_avatar.ipynb* |







