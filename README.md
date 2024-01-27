<img width=“600” height="600" alt="Screenshot 2022-10-25 at 09 06 31" src=https://www.shutterstock.com/shutterstock/photos/1483138139/display_1500/stock-photo-dangerous-malaria-infected-mosquito-skin-bite-leishmaniasis-encephalitis-yellow-fever-dengue-1483138139.jpg


# Malaria Classification using Convolutional Neural Networks (CNN)
## Overview
The classification of malaria cases using thin blood smears is a critical aspect of accurate diagnosis. Our project aims to provide an effective approach to this classification task through the implementation of a Convolutional Neural Network (CNN).

## Methodology
1. Baseline Selection:

After considering various pre-trained models, VGG16 with batch normalization (vgg_bn) was identified as the most suitable baseline model for our project.

2. Training Process:

The training process utilized vgg_bn as the baseline, achieving an initial accuracy of 97.187%.
Base Learning Rate:

Experimentation with different base learning rates was conducted to optimize model performance. The optimal learning rate, determined by plotting the loss against various learning rates, was identified. The achieved accuracy was not as high as the baseline.

3. Unfreezing the Model:

Unfreezing the model proved to be a highly effective strategy, resulting in a significant accuracy boost to 97.282%.

4. Discriminative Learning Rates:

Implementation of discriminative learning rates, where different learning rates are applied to different parts of the model, was considered. This approach demonstrated slightly lower accuracy compared to model unfreezing.

## Conclusion
The comprehensive analysis and optimization steps led to the achievement of our best model accuracy at 97.82%. The choice of the vgg_bn baseline, coupled with unfreezing the model, played crucial roles in enhancing the accuracy of malaria case classification. Our findings suggest that leveraging deep learning techniques, along with strategic model adjustments, can provide a valuable and effective approach for accurate malaria diagnosis using thin blood smears.
