# ERNet
Semantic Consistency Network with Edge Learner and Connectivity Enhancer for Cervical Tumor Segmentation from Histopathology Images

Lisha Pang, Peng He*, Yue Han, Hao Cui, Peng Feng, Chi Zhang*, Sukun Tian, Pan Huang*

Ours manuscript is in the peer review, and we will completely open our code and dataset after the peer review.


# Introduction
Accurate tumor grading and regional identification of cervical tumors are important for diagnosis and prognosis. Traditional manual microscopy methods suffer from time-consuming, labor-intensive, and subjective bias problems, so tumor segmentation methods based on deep learning are gradually becoming a hotspot in current research. Cervical tumors have diverse morphologies, which leads to low similarity between the mask edge and ground-truth edge of existing semantic segmentation models. Moreover, the texture and geometric arrangement features of normal tissues and tumors are highly similar, which causes poor pixel connectivity in the mask of the segmentation model. To this end, we propose an end-to-end semantic consistency network with the edge learner and connectivity enhancer, i.e., ERNet. First, the edge learner consists of a stacked shallow convolutional neural network, so it can effectively enhance the ability of ERNet to learn and represent polymorphic tumor edges. Second, the connectivity enhancer learns the detailed information and contextual information of tumor images, so it can enhance the pixel connectivity of the masks. Finally, edge features and pixel-level features are adaptively coupled, and the segmentation results are additionally optimized by the tumor classification task as a whole. The results show that, compared with those of other state-of-the-art segmentation models, the structural similarity and mean intersection over union of ERNet are improved to 88.17% and 83.22%, respectively, which reflects the excellent edge similarity and pixel connectivity of the proposed model. Finally, we conduct a generalization experiment on laryngeal tumor images. Therefore, the ERNet network has good clinical popularization and practical value.

---
![image](https://github.com/Baron-Huang/ERNet/blob/main/Image/main.jpg)


# Dataset
You could finds and applies our datasets by the link: https://drive.google.com/drive/folders/1bq8VS7r6Cn9dYqieGe-VzjQYu5dxW9B6?usp=drive_link
