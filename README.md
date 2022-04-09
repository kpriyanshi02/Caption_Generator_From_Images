# Caption_Generation_From_Images
This project is built to predict and generate captions for the input image. 
The dataset contains more than 8k images and 5 captions for each image.
Feature extraction has been done for both images and captions for input. The features are then concatenated to predict the next word of the caption.
>•	CNN: To extract features from images. A pre-trained VGG16 Architecture has been used.

>•	LSTM: To generate descriptions from extracted information of images.

>•	BLEU Score is used as a metric to evaluate the performance of the trained model.
