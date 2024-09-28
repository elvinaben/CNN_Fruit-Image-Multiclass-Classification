## Project Overview
This project aims to develop a convolutional neural network (CNN) for the multiclass classification of fruit images. The objective is to accurately categorize images into one of four classes: **Banana**, **Betel Nut**, **Bitter Gourd**, and **Blackberry**. The dataset consists of labeled images of these fruits, which serve as the foundation for training the model to distinguish between the different classes effectively.

## Models Implemented
- **VGG16**: A pre-trained CNN model that achieved an accuracy of 24%, demonstrating limited effectiveness for this specific task.
- **EfficientNetB0**: A more efficient CNN architecture that significantly enhanced the accuracy to 96%.
- **EfficientNetB0 with Hyperparameter Tuning**: This model reached an impressive accuracy of 98%, making it the top performer.

### Training Process of the Best Model (EfficientNetB0 with Hyperparameter Tuning)
The training process employed early stopping with a patience of 10 epochs. The graphs below illustrate how the EfficientNetB0 model, after hyperparameter tuning, offers a robust fit for the data.

#### Training and Validation Loss Graph
<img src="https://github.com/user-attachments/assets/e6e29928-4ade-47fd-9927-092bf21042ae" alt="Training and Validation Loss Graph" width="400">

#### Training and Validation Accuracy Graph
<img src="https://github.com/user-attachments/assets/6bb90411-0976-4f28-b700-0511db32ecc6" alt="Training and Validation Accuracy Graph" width="400">

## Classification Metrics
The hyperparameter-tuned model achieved a remarkable 98% accuracy, accurately classifying all images of Betel Nut and Bitter Gourd. However, one Banana image was misclassified as Betel Nut, and two Blackberry images were incorrectly identified as Bitter Gourd. This outcome indicates that the EfficientNet backbone and the selected parameters were well-suited to tackle the complexities present in the image dataset.

<img width="508" alt="image" src="https://github.com/user-attachments/assets/5457d84c-d067-4ac3-9ca9-58f26369dc54">

### Sample Evaluation
#### A random sample of 40 images was evaluated, and the model successfully identified all images correctly.
<img width="184" alt="image" src="https://github.com/user-attachments/assets/25107754-0533-4eab-a16f-182e1b84c63e">
<img width="189" alt="image" src="https://github.com/user-attachments/assets/9ff2e059-cee5-4bcc-8a06-fe7b82a78e08">
<img width="187" alt="image" src="https://github.com/user-attachments/assets/8edbb721-50ee-4a98-8191-87fbd4e466a9">
<img width="184" alt="image" src="https://github.com/user-attachments/assets/6e2573f6-6f9a-45fd-b819-ff4fa342a31f">
<img width="186" alt="image" src="https://github.com/user-attachments/assets/e8abe0f7-6a85-4f54-bc06-e44f2ea54d99">
<img width="184" alt="image" src="https://github.com/user-attachments/assets/ea0b97dd-b050-4b19-9324-ddd2a9576813">
<img width="187" alt="image" src="https://github.com/user-attachments/assets/1b382936-b2ea-4ff5-bcd0-59bcf3bcc863">
<img width="184" alt="image" src="https://github.com/user-attachments/assets/8e119b87-1551-4078-a5f6-ed0f44376557">
<img width="191" alt="image" src="https://github.com/user-attachments/assets/1ecf8341-bcc5-434f-a452-4f9a48edef5e">
<img width="183" alt="image" src="https://github.com/user-attachments/assets/792fc037-4df2-4b47-aaef-37b8e43f2ed8">


## Dataset
The dataset used in this project can be accessed at the following link: [Fruit Image Dataset](https://drive.google.com/drive/folders/1j_XbnWYvs4iwlShM7EpkJljhsVjjA82v?usp=sharing)
