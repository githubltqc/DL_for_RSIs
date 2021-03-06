## Wide Contextual Residual Network (WCRN)

Author  : Shengjie Liu, Haowen Luo (Equal Contribution)

License : http://www.apache.org/licenses/LICENSE-2.0

If it helps, please STAR the project and CITE our papers.

This is a wide contextual residual network (WCRN) with active learning (AL) for remote sensing image (RSI) classification.

Though ResNets have achieved great success in various applications, its performance is limited by the requirement of abundant labeled samples. As it is very difficult and expensive to obtain class labels in real world, we integrate the proposed WCRN with AL to improve its generalization by using the most informative training samples.

Specifically, we first design a WCRN for RSI classification, and then integrate it with AL to achieve good machine generalization with limited number of training sampling. Experimental results on Pavia University and Flevoland datasets demonstrate that the proposed WCRN with AL can significantly reduce the needs of samples.

Environment:
> We run the scripts in Windows OS. </br>
> Spyder with Python 3.6 </br>
> Keras 2.0.8 using Tensorflow 1.2.1 backend </br>
> SSM.py

Script:
> Pavia_University </br>
> WCRN.py:         the definition of the network. </br>
> SSM.py:          a sample manager. </br>
> PU_train.py:     an example script for Pavia University, used for training. </br>
> PU_predict.py:   an example script for Pavia University, used for predicting.

The Hyperspetral RSI of Pavia University is available at: [Hyperspectral Remote Sensing Scenes - Grupo de Inteligencia Computacional (GIC)](http://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes)

![poster](https://raw.githubusercontent.com/codeRimoe/DL_for_RSIs/master/WCRN/wcrn_igarss_poster.jpg)

Reference:

[S. Liu, H. Luo, Y. Tu, Z. He and J. Li, "Wide Contextual Residual Network with Active Learning for Remote Sensing Image Classification," IGARSS 2018 - 2018 IEEE International Geoscience and Remote Sensing Symposium, Valencia, 2018, pp. 7145-7148. doi: 10.1109/IGARSS.2018.8517855](https://ieeexplore.ieee.org/document/8517855)
