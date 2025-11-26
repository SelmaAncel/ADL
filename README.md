# Advanced Deep Learning Project Code
This Gihub repository contains the code for the Advanced Deep Learning project by Selma Ancel.
For this project, seven different models were trained to assess their performance on a Land Use Land Cover (LULC) classification task.

**The seven models used are:**
- **Vision Transformer (ViT), by Dosovitskiy et al. (2021).**
  
  Code source: https://huggingface.co/timm/vit_base_patch16_224.mae
- **Compact Convolutional Transformer (CCT).**

  Code source: https://github.com/SHI-Labs/Compact-Transformers/tree/main
- **Data-efficiënt image Transformer (DeiT) by Touvron et al. (2021).**

  Code source: https://github.com/facebookresearch/deit/tree/main
- **Convolution-Enhanced Image Transformers (CeiT) by Yuan et al. (2021).**

  Code source: https://github.com/coeusguo/ceit
- **LocalVit by Li et al. (2021).**

  Code source: https://github.com/ofsoundof/LocalViT
- **Conformer by Peng et al. (2021).**

  Code source: https://github.com/pengzhiliang/Conformer
- **Convolutional vision Transformer (CvT) by Wu et al. (2021).**

  Code source: https://github.com/leoxiaobin/CvT

## Setup
The following files are included:
- **ADL code full:** Includes the ViT, CCT, DeiT, CeiT, LocalViT, Conformer and CvT pre-trained on ImageNet-1k and trained on the full EuroSaT dataset.
- **ADL code half:** Includes the ViT, CCT, DeiT, CeiT, LocalViT, Conformer and CvT pre-trained on ImageNet-1k and trained on half the EuroSaT dataset.
- **ADL code quarter:** Includes the ViT, CCT, DeiT, CeiT, LocalViT, Conformer and CvT pre-trained on ImageNet-1k and trained on a quarter of the EuroSaT dataset.
- **ADL code scratch:** Includes the ViT, CCT, DeiT, CeiT, LocalViT, Conformer and CvT trained from scratch on a quarter of the EuroSaT dataset.

## Data
The data used for this project was the EuroSAT dataset created by Helber et al. (2018). The dataset can be found [here.](https://github.com/phelber/EuroSAT)

## References relevant to the code
- Dosovitskiy, A., Beyer, L., Kolesnikov, A., Weissenborn, D., Zhai, X., Unterthiner, T., Dehghani, M., Minderer, M., Heigold, G., Gelly, S., Uszkoreit, J., & Houlsby, N. (2021). An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale.
- Hassani, A., Walton, S., Shah, N., Abuduweili, A., Li, J., & Shi, H. (2022). Escaping the Big Data Paradigm with Compact Transformers.
- Touvron, H., Cord, M., Douze, M., Massa, F., Sablayrolles, A., & Jégou, H. (2021). Training data-efficient image transformers & distillation through attention.
- Yuan, K., Guo, S., Liu, Z., Zhou, A., Yu, F., & Wu, W. (2021). Incorporating Convolution Designs into Visual Transformers.
- Li, Y., Zhang, K., Cao, J., Timofte, R., Magno, M., Benini, L., & Van Goo, L. (2023). LocalViT: Analyzing Locality in Vision Transformers. 2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 9598-9605.
- Peng, Z., Huang, W., Gu, S., Xie, L., Wang, Y., Jiao, J., & Ye, Q. (2021). Conformer: Local Features Coupling Global Representations for Visual Recognition. 2021 IEEE/CVF International Conference on Computer Vision (ICCV), 357-366.
- Wu, H., Xiao, B., Codella, N., Liu, M., Dai, X., Yuan, L., & Zhang, L. (2021). CvT: Introducing Convolutions to Vision Transformers. 2021 IEEE/CVF International Conference on Computer Vision (ICCV), 22-31. 
- Helber, P., Bischke, B., Dengel, A., & Borth, D. (2018). Introducing Eurosat: A Novel Dataset and Deep Learning Benchmark for Land Use and Land Cover Classification. IGARSS 2018 - 2018 IEEE International Geoscience and Remote Sensing Symposium, 204-207.
