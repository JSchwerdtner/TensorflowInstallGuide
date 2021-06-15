# Tensorflow-GPU InstallGuide Prerequisites

Tensorflow Installation Tutorial:

First step is to have a Geforce GPU

1. Delete all Drivers of Geforce and Visual Studio

2. Download and install Cuda v9.0 and download CUDNN 8.0

Googledrivelink for CUDNN 8.0: https://drive.google.com/file/d/19emjtDPahu-zGadjKRLR-9bgPc4RQiqH/view?usp=sharing

3. Put the file cudnn64_6.dll into C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v9.0\bin folder

4. Download and install Visual Studio 2015 

5. Download and install Anaconda3 5.3.1 64-bit

6. Update your GPU Driver

7. check evironment variables for: C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v9.0\bin

C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v9.0\libnvvp

Youtube Tutorial: https://www.youtube.com/watch?v=k5QJV_TFWGw&ab_channel=JanSchwerdtner

edit 2021: Tensorflow 2 is now available and the prerequisites are quite similar for the tf-gpu installation. You need to add the necessary .dll-files to your path.
