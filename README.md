# <p align="center">Open-World Pose Transfer via Sequential Test-time Adaption</p>

## <p align="center">Abstract</p>
Pose transfer aims to transfer a given person into a specified posture, has recently attracted considerable attention. A typical pose transfer framework usually employs representative datasets to train a discriminative model, which is often violated by out-of-distribution (OOD) instances. Recently, test-time adaption (TTA) offers a feasible solution for OOD data by using a pre-trained model that learns essential features with self-supervision. However, those methods implicitly make an assumption that all test distributions have a unified signal that can be learned directly. In open-world conditions, the pose transfer task raises two independent signals: OOD appearance and skeleton, which need to be extracted and distributed separately. To address this point, we develop a SEquential Test-time Adaption (SETA). In the test-time phrase, SETA extracts and distributes external appearance texture by augmenting OOD data for self-supervised training. To make non-Euclidean similarity among different postures explicit, SETA uses the image representations derived from a person re-identification (Re-ID) model for similarity computation. By addressing two independent signals in the test phrase sequentially, SETA greatly improves the generalization performance of current pose transfer models. In our experiment, we first show that pose transfer can be applied to open-world applications, including Tiktok reenactment and celebrity motion synthesis.
## <p align="center">Open-World Applications</p>

### Skeleton-driven Tiktok Reenactment.
<p float="center">
<img src="tiktok_video/00035_00043.gif" width="400px"/> <img src="tiktok_video/00225_00043.gif" width="400px"/>
<img src="tiktok_video/00058_00104.gif" width="400px"/> <img src="tiktok_video/00165_00035.gif" width="400px"/>
</p>

### Open-World Celebrity Motion Synthesis.
<p float="center">
<img src="image/图片1.png" width="800px"/>
</p>

## <p align="center">Qualitative Results</p>

### More Visual Comparison on SHHQ.
<p float="center">
<img src="image/image_000847.gif" width="400px"/> <img src="image/image_002954.gif" width="400px"/>
<img src="image/image_001006.gif" width="400px"/> <img src="image/image_002689.gif" width="400px"/>
</p>



