
# Image Caption Generation using External

Team Members:

    Adish Rajendra Kerkar (211IT04)
    Chikkeri Chinmaya (211IT017)
    Manjunath Harale (211IT023)

Knowledge

This project aims to generate meaningful captions for images using external knowledge to enhance the performance of traditional image captioning models. The dataset used for training and evaluation is the Flickr8k Dataset, which contains 8,000 images with accompanying captions.

The project leverages the transformer-based architecture and incorporates external data to improve the contextual understanding of images.


## Dataset

The dataset includes:

    8,000 images.
    5 captions per image.

[Kaggle Link](https://www.kaggle.com/datasets/adityajn105/flickr8k)


## Running Tests

To run tests, run the following command

```bash
  pip install -r requirements.txt

```

Setup:

    Install all required dependencies

Run the Notebook:

    Open Caption_Transformer.ipynb in Jupyter Notebook and execute the cells step by step.

Input Data:

    Place the Flickr8k dataset in the /data directory, ensuring the structure matches the required format.

Execution Workflow:

    Step 1: Data Loading and Preprocessing.
        Resize and normalize images.
        Prepare captions for training with tokenization and encoding.
    Step 2: Model Training.
        Train the transformer-based model with image features extracted using CNN (e.g., VGG16/ResNet).
        Include external knowledge for enhanced learning.
    Step 3: Evaluation.
        Evaluate model performance using BLEU, ROUGE, and other metrics.
    Step 4: Caption Generation.
        Use the trained model to generate captions for unseen images.   