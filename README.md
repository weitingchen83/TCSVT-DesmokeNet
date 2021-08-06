# DesmokeNet: A Two-stage Smoke Removal Pipeline Based on Self-Attentive Feature Consensus and Multi-Level Contrastive Regularization

## Accepted by IEEE Transactions on Circuits and Systems for Video Technology


# Abstract:
In image processing, smoke may degrade visibility and deteriorate the performance of high-level vision applications. Therefore, single image smoke removal is crucial for computer vision. Currently, existing smoke removal algorithms mainly leverage handcrafted priors. Moreover, these methods usually apply haze removal methods to perform smoke removal due to the similarity between smoke and haze. However, these methods cannot sufficiently address the degradation of thick smoke and may suffer from residual smoke and color distortion problems due to the non-global and non-homogeneous distribution of smoke. In this paper, to solve the aforementioned problems, an end-to-end deep neural network called DesmokeNet is proposed. We construct a two-stage recovered pipeline to remove the smoke in different thicknesses. The light and thick smoke is first removed locally by the smoke removal network (SRN). The missing pixels in the thick smoke are then recovered by the pixel compensation network (PCN). Moreover, we proposed the thickness-aware pixel loss and the dark channel loss to suppress the residual smoke. To further increase the discriminative ability of the DesmokeNet, we proposed self-attentive feature consensus loss and multi-level contrastive regularization loss to improve the performance of smoke removal. Finally, to train the proposed method, we construct the first large-scale dataset containing synthetic and real-world data. Extensive experiments show that the proposed method outperforms favorably against other state-of-the-art methods quantitatively and qualitatively.


We will provide more detail information of this project. (coming soon !!!)



[[Paper Download]]()
[[Dataset Download]]()

# Citations
Please cite this paper in your publications if it is helpful for your tasks:    


Bibtex:
```
@inproceedings{chen2021Desmoke,
    title     = {DesmokeNet: A Two-stage Smoke Removal Pipeline Based on Self-Attentive Feature Consensus and Multi-Level Contrastive Regularization},
    author    = {Chen, Wei-Ting, and Lou, Hao-Lun, and Fang, Hao-Yu, and Chen, I-Shiang, and Chen, Yi-Wen, and Ding, Jian-Jiun, and Kuo, Sy-Yen},
    booktitle = {IEEE Transactions on Circuits and Systems for Video Technology},
    year      = {2021}
}
```

