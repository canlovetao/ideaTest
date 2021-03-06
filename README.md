# MCFNet：  Multi-layer Concatenation Fusion Network for Medical Image fusion




 Medical image fusion technique can help the physician execute combined diagnosis, preoperative planning, intraoperative guidance, and interventional treatment in many clinical applications by deriving the complementary information from medical images with different modalities. In this paper, we propose an end-to-end deep learning network, Multi-layer Concatenation Fusion Network(MCFNet), for feature extraction, feature fusion and image reconstruction without manually designing complex feature extraction and fusion rules. MCFNet
connects the feature map of each layer in the image reconstruction network with the source map which has the same resolution due to down-sampling. And the spatial information lost in the fused medical image during two down-sampling processes is supplemented. The up-sampling operation at the image reconstruction stage uses fast up-convolution to reduce the checkerboard effect of traditional deconvolution. The proposed fusion method is tested on many clinical medical images and compared with several commonly used image fusion methods. Experimental results show that the proposed fusion method can provide better fusion results in terms of visual quality and objective evaluation.

