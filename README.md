# Installing Keras Theao Tensorflow with GPU on Windows 10

**Introduction**

Installing Keras, Theano, and Tensorflow to train Deep Learning models with CPU is an easy task. However, to use these libraries with the GPU, we need more time and effort. In this tutorial, I will show you a complete and step-by-step process to install the most important libraries for developing Deep Learning algorithms including Keras, Theano, and Tensorflow with GPU on Windows 10/64-bit.

**Installing process**

1. Update NVIDIA Driver 

   * Check your GPU and update its driver [here](http://www.nvidia.com/Download/index.aspx).

2. Install Visual Studio 2013 and Microsoft Visual C++ 2015 Redistributable Update 3

   * Download and install [Visual Studio 2013 Update 5](https://go.microsoft.com/fwlink/?LinkId=532495). This framework is use as a              compiler for CUDA source code.
   
   * Add *C:\Program Files (x86)\Microsoft Visual Studio 12.0\VC\bin* to your *%PATH%* as a environment variable.
   
   * Check the file MSVCP140.dll in your system. If it does not exist, dowload and install [Microsoft Visual C++ 2015 Redistributable Update 3](https://www.microsoft.com/en-us/download/details.aspx?id=53587)
   
3. Install CUDA 8.0

   * Dowload and install [CUDA 8.0](https://developer.nvidia.com/cuda-downloads).
   
   * Navigate to *C:\ProgramData\NVIDIA Corporation\CUDA Samples\v8.0* and compile Samples_vs2013.sln file. This step is to ensure that      your CUDA 8.0 works correctly.
   
4. Install Anaconda3 4.2 for Python 3.5 on Windows.

   * Dowload and install [Anaconda3 4.2 for Python 3.5 on Windows](https://repo.continuum.io/archive/index.html).
   
   * Open [Anaconda command prompt](https://www.quora.com/How-do-I-start-the-anaconda-command-prompt).
   
   
   
   
   
   
   


   










