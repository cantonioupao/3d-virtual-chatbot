# 3d-virtual-chatbot
This is the repository for the master thesis project of a 3D virtual chatbot.
The repository consists of various google colab notebooks that can help you kickstart the project. 
Specifically, it supports a quick plug and play of various models, that are crucial for understanding the state-of-the-art and implementing novel solutions for 3D avatar reconstruction, inverse rendering based on a single image, synthetic image generation (GAN based) for expression transfer, 3D avatar animation along with voice synchronization :

## Tutorials

Dwelve into the world of 3D virtual chatbots, by trying the following Google Colab notebooks

|<img src="https://raw.githubusercontent.com/cantonioupao/3d-virtual-chatbot/main/gifs/stylegan_gif.gif" width="400"/>|<img src="https://raw.githubusercontent.com/cantonioupao/3d-virtual-chatbot/main/gifs/final_fs_gif.gif" width="400"/>|
|:-----------------------------------------------------------------------------------------------------------:|:--------------------------------------------------:|
| [Synthetic image generation - StyleGAN](https://github.com/cantonioupao/3d-virtual-chatbot/blob/main/stylegan.ipynb) | [Photorealistic video-to-video inference (few-shot)](https://github.com/cantonioupao/3d-virtual-chatbot/blob/main/vid2vid_Inference.ipynb)|

| <img src="https://raw.githubusercontent.com/cantonioupao/3d-virtual-chatbot/main/gifs/final_gif.gif" width="400"/> | <img src="https://raw.githubusercontent.com/cantonioupao/3d-virtual-chatbot/main/gifs/final_expression_gif.gif" width="400" />
|:------------------------------------------------------------:|:--------------------------------------------------:|
| [Reconstruct 3D FLAME mesh from single image](https://github.com/cantonioupao/3d-virtual-chatbot/blob/main/deca.ipynb)| [Expression Transfer from source image to target mesh](https://github.com/cantonioupao/3d-virtual-chatbot/blob/main/deca.ipynb)|

| <img src="https://raw.githubusercontent.com/cantonioupao/3d-virtual-chatbot/main/gifs/fit_flame_gif.gif" width="400"/> | <img src="https://raw.githubusercontent.com/cantonioupao/3d-virtual-chatbot/main/gifs/voca_gif.gif" width="400"/>
|:------------------------------------------------------------:|:--------------------------------------------------:|
| [Fit 3D avatar reconstruction pipeline](https://raw.githubusercontent.com/cantonioupao/3d-virtual-chatbot/blob/main/fit_FLAME_mesh.ipynb)| [3D Avatar animation based on audio signal - VOCA](https://github.com/cantonioupao/3d-virtual-chatbot/blob/main/voca.ipynb)|

| <img src="https://raw.githubusercontent.com/cantonioupao/3d-virtual-chatbot/main/gifs/text_to_speech.gif" width="400"/> | <img src="https://raw.githubusercontent.com/cantonioupao/3d-virtual-chatbot/main/gifs/nha.gif" height= "150" width="400"/>
|:------------------------------------------------------------:|:--------------------------------------------------:|
|[Text-to-audio synthesis](https://github.com/cantonioupao/3d-virtual-chatbot/text_to_speech.ipynb)|  [Inverse rendering for input video (NHA)](https://github.com/facebookresearch/pytorch3d/blob/main/docs/tutorials/render_densepose.ipynb)

| <img src="https://raw.githubusercontent.com/cantonioupao/3d-virtual-chatbot/main/gifs/unsup3d.gif" width="400"/> | <img src="https://raw.githubusercontent.com/cantonioupao/3d-virtual-chatbot/main/gifs/vis_mesh.gif" width="400" />
|:------------------------------------------------------------:|:--------------------------------------------------:|
| [Visualize Mesh](https://github.com/cantonioupao/3d-virtual-chatbot/visualize_mesh.ipynb) | [3D face mesh reconstruction from single-view image](https://github.com/cantonioupao/3d-virtual-chatbot/unsup3d.ipynb)| 

Our tutorials include code from the following models/papers/repositories:
 - [fs_vid2vid](https://github.com/NVlabs/imaginaire/blob/master/projects/fs_vid2vid/README.md) &rarr; fs_vid2vid_inference.ipynb
 - [VOCA](https://github.com/TimoBolkart/voca) &rarr; voca.ipynb
 - [DECA](https://github.com/YadiraF/DECA) &rarr;  deca.ipynb , DECAthlon.ipynb
 - [StyleGAN3](https://github.com/NVlabs/stylegan3) &rarr; stylegan.ipynb
 - [unsup3D] (https://github.com/elliottwu/unsup3d) &rarr; unsup3d.ipynb
 
The notebooks allow also, customized testing of the models. This means that any examples of face images or audio sequences can be used for inference or testing.
The novel implementation of an end-to-end Detailed Textured Avatar Enhancer named **DECAthlon** is also included in the repository.

## Getting Started
The Google Colab notebooks have detailed explanations on how ot install and run all models. Please refer to the respective notebooks, or follow the guidelines for a clean local installation (Linux based systems)

1. Clone github repo:
  ```git clone https://github.com/cantonioupao/3d-virtual-chatbot/```

## Citing
If you find our work useful to your research, please consider citing:





## Acknowledgements
For the Colab notebooks of external models, we aknolwedge that the codebase and scripts used within these notebooks do not belong to us. Here are some great resources we benefit from: 
 - [fs_vid2vid](https://github.com/NVlabs/imaginaire/blob/master/projects/fs_vid2vid/README.md) - Few-shot vid2vid
 - [VOCA](https://github.com/TimoBolkart/voca) - Voice Operated Character Animation
 - [DECA](https://github.com/YadiraF/DECA) - Detailed Expression Capture and Animation (SIGGRAPH2021)
 - [StyleGAN3](https://github.com/NVlabs/stylegan3) - Alias-Free Generative Adversarial Networks (StyleGAN3) (NeurIPS 2021)




