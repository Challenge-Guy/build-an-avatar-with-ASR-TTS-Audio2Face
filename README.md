# Build an avatar with ASR, Sentence-transformer, Similarity Search, TTS and Omniverse Audio2Face
## Project Description
I'll show you how I used several Python packages and NVIDIA's Omniverse Audio2Face to quickly implement an avatar that can answer questions defined in a knowledge set or FAQ.

## Demo
[![IMAGE ALT TEXT](https://user-images.githubusercontent.com/104120636/166487700-9f14813c-13b9-42bc-b477-c0f8aff7db5d.png)](http://www.youtube.com/watch?v=G_c94cGIKgs "Video Title")
#### ***Omniverse Audio2Face***
![](https://i.imgur.com/7ioYQHj.png)

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
#### Download and Install Omniverse Launcher
[NVIDIA Omniverse](https://docs.omniverse.nvidia.com/prod_install-guide/prod_install-guide.html) is a development platform for 3D simulation and design collaboration, it is free for individual, you can download Omniverse Launcher [here](https://www.nvidia.com/en-us/omniverse/download/).

I also recommend you to watch this [video tutorial](https://www.youtube.com/watch?v=Ol-bCNBgyFw), which guides you through the installation process. 

| ![](https://i.imgur.com/4imNFt1.jpg) | 
|:--:| 
| *Omniverse Launcher* |

#### Install Omniverse Audio2Face
| ![](https://i.imgur.com/6kbTCRW.jpg) | 
|:--:| 
| *Omniverse apps* |

Once you got Omniverse Launcher installed, you can immediate access to all the apps, including [Omniverse Audio2Face](https://www.nvidia.com/en-us/omniverse/apps/audio2face/). Next, simply install Omniverse Audio2Face and you're good to go.

| ![](https://i.imgur.com/N94KDTc.png) | 
|:--:| 
| *Omniverse Audio2Face* |

#### Omniverse Audio2Face setup
To get our Python program interacts with Omniverse Audio2Face, you should use streaming audio player that allows developers to stream audio data from an external source or applications via the gRPC protocol. 

| ![](https://i.imgur.com/qZUQVS0.png) | 
|:--:| 
| *streaming audio player allows developers to stream audio data from an external source* |

This [tutorial](https://www.youtube.com/watch?v=qKhPwdcOG_w&t=17s) showcases how to create an audio player and connect it to the audio2face instance using the omnigraph editor.
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







