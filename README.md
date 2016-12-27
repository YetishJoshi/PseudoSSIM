# PseudoSSIM
----

JM H.264/AVC code modified to support PseudoSSIM model during prediction assessment in 4x4 and 8x8 sub-blocks

This work compliments the following paper:

"A novel low complexity Local Hybrid Pseudo-SSIM-SATD distortion metric towards perceptual rate control"
by Yetish G. Joshi; Jonathan Loo; P. Shah; Shahedur Rahman and Yoong Choon Chang

Published in: Broadband Multimedia Systems and Broadcasting (BMSB), 2013 IEEE International Symposium on 

http://dx.doi.org/10.1109/BMSB.2013.6621695

Abstract:

"The front-end block-based video encoder applies an Image Quality Assessment (IQA) as part of the distortion metric. Typically, the distortion metric applies uniform weighting for the absolute differences within a Sub-Macroblock (Sub-MB) at any given time. As video is predominately designed for Humans, the distortion metric should reflect the Human Visual System (HVS). Thus, a perceptual distortion metric (PDM), will lower the convex hull of the Rate-Distortion (R-D) curve towards the origin, by removing perceptual redundancy and retaining perceptual clues. Structured Similarity (SSIM), a perceptual IQA, has been adapted via logarithmic functions to measure distortion, however, it is restricted to the Group of Picture level and hence unable to adapt to the local Sub-MB changes. This paper proposes a Local Hybrid Pseudo-SSIM-SATD (LHPSS) Distortion Metric, operating at the Sub-MB level and satisfying the Triangle Equality Rule (≤). A detailed discussion of LHPSS's Psuedo-SSIM model will illustrate how SSIM can be perceptually scaled within the distortion metric space of SATD using non-logarithmic functions. Results of HD video encoded across different QPs will be presented showing the competitive bit usage under IbBbBbBbP prediction structure for similar image quality. Finally, the mode decision choices superimposed on the Intra frame will illustrate that LHPSS lowers the R-D curve as homogeneous regions are represented with larger block size."

[![DOI](https://zenodo.org/badge/76972435.svg)](https://zenodo.org/badge/latestdoi/76972435)
