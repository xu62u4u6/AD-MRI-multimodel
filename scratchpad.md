# single model

## metadata 
難度: *
tree-based model

## MRI image
難度: ***
深度學習 -> Grad cam 確定有學到AD和一般人差別 -> 提取倒數第二層輸出作為embedding做後續利用

## pyradiomics
難度: **
利用pyradiomics生成紋理特徵的數值矩陣 -> tree based model

1. 全腦
2. 腦部ROI
   需要對腦先做分割
   a. 深度方法
     monai:https://monai.io/model-zoo#/model/wholeBrainSeg_Large_UNEST_segmentation
   b. freesurfer
     
