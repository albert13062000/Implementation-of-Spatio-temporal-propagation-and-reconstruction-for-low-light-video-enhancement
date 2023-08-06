# Implementation-of-Spatio-temporal-propagation-and-reconstruction-for-low-light-video-enhancement

This is a final exams project on Digital Signal Processing worked on by Albert Ankomah Dodoo and Patrick Komla Dogbatse

1. Intoduction

   This paper reports the development of a novel spatio-temporal propagation and reconstruction (STPR) framework for low-light video enhancement. Capturing images and videos under poor illumination conditions can lead to subpar performance in recognition, tracking, and classification. The task of low-light image/video enhancement involves reconstructing visually appealing counterparts from low-quality inputs. Recent advancements in deep learning for low-light image enhancement have demonstrated promising results. However, directly applying these methods to low-light video enhancement poses challenges, including severe artifacts and flickering due to the lack of temporal consistency.
   To address these issues, the paper proposes a novel approach called the Spatio-Temporal Propagation and Reconstruction (STPR) Network.The proposed framework consists of two stages: spatio-temporal propagation and reconstruction. In the spatio-temporal propagation stage, high-frequency details are first extracted from bright frames and then propagated to low-light frames using a spatio-temporal propagation model. In the reconstruction stage, low-light frames are reconstructed by fusing the propagated details with the low-light frames. Experimental results on both synthetic and real-world low-light videos demonstrate that the proposed method can effectively enhance the quality of low-light videos.

2.Motivation

Low-light video enhancement is a challenging problem due to the limited amount of light available. This can lead to poor image quality, such as noise, blur, and lack of contrast. Traditional methods for low-light video enhancement typically focus on improving the quality of individual frames. However, this can lead to temporal inconsistencies in the video, as the frames may not be aligned or may have different brightness levels.

The research paper "Spatio-temporal propagation and reconstruction for low-light video enhancement" addresses this problem by proposing a novel method that combines spatial and temporal information. The proposed method, called STPR, consists of three main components:

Pyramid recursive residual dense subnet: This subnet is used to extract multi-scale features from the video sequences.
Feature propagation subnet: This subnet is used to align and fuse features from adjacent frames in the video sequence.
Spatio-temporal feature reconstruction subnet: This subnet is used to reconstruct the target frame in the video sequence.
The STPR method is able to achieve state-of-the-art performance on several low-light video datasets. The method is able to reduce noise, increase brightness, and improve the sharpness of low-light videos. Additionally, the STPR method is able to preserve the temporal consistency of the video, which is an important property for many applications.

The motivation for the STPR method is to address the limitations of traditional methods for low-light video enhancement. By combining spatial and temporal information, the STPR method is able to improve the quality of the enhanced video while also preserving the temporal consistency.

The STPR method is a promising new approach to low-light video enhancement. The method is able to achieve state-of-the-art performance, and it is relatively efficient. The STPR method is a good choice for applications where it is important to improve the quality of low-light videos, such as surveillance, security, and medical imaging

3. Methodology

● Input (Video frames)
● Flow estimation module
● Optical flow
● Feature fusion module
● Pyramid recursive dense subnet
● Spatio-temporal feature reconstruction subnet
● Output

Link to research paper

https://www.sciencedirect.com/science/article/abs/pii/S1051200423001665
 
