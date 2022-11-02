# Transfer-Learning-for-Classification-of-Materials-Based-on-Visual-Images-and-Optical-Roughness

The physical objects possess visual and haptic attributes that aid in object recognition
and perception. Additionally, the perception of material surfaces depends on visual and
textural information. Understanding surface properties has gained increasing interest in
the research of the visual-sensory domain. One of the components of micro-irregularities
on the surface is the roughness parameter of the material. Primarily, a combination
of visual impression images and roughness parameters can be used together for surface
material recognition. In the current research, transfer learning methods are
presented to study the infuence of visual and optical roughness data on how well the
materials are classified. In comparison to the existing material classification techniques
using Convolutional Neural Networks (CNN), which rely on tactile and visual data,
the dataset adopted in the research is based on the output of the optical profilometer
TRACEiT device. Experiments were performed individually on each visual, optical
roughness data, and compared the test accuracy to the fusion approach, which is
a combination of both features. Thereby, indicating that the results of the fusion
model performed better than the individual feature set. In an overall comparison to
the individual Densenet121 architecture trained on visual impression images, the test
accuracy for the fusion network was 98.18%.

## Acknowledgements
 - [Technische Universität Chemnitz](https://www.tu-chemnitz.de/informatik/mc/index.php.en)
 - [Innowep](https://innowep.com/)
 
 ## Installation
 Anaconda environment needs to be installed on either windows or linux
 https://docs.anaconda.com/anaconda/install/windows/
 
 ## Configurations
 1. Hardware configuration:
    - Procesor - Intel(R) Core(TM) i7-6820HQ CPU @ 2.70GHz, 2.71 GHz, Lenovo Thinkpad laptop
    - RAM - 16.0 GB
    - Windows 10 operating system
    - Nvidia Quadro M2000M 4GB
    - TRACEiT device and software
 2. Software configuration:
    - Programming language: Python 3.7
    - Libraries: 
      - Computed Unified Device Architecture (CUDA) 11.0 tool kit for GPU acceleration
      - NVIDIA CUDA Deep Neural Network (cuDNN) 7.5
      - tensorflow 2.3.0
      - keras 2.4.3
    - Dependencies:
      - numpy 1.20.1
      - jupyter 1.0.0
      - opencv 4.0.1
      - pandas 1.2.4
      - matplotlib 3.3.4
      - scikit-learn 0.24.1
  ## Dataset
  The dataset for classification was created using Innowep's TRACEiT profilometer which cannot be made public.
  A similar material dataset can be downloaded at [https://zeus.lmt.ei.tum.de/downloads/texture/]. TUM material dataset was also used in the project.
  
