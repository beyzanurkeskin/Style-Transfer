
# Neural Style Transfer with Contrastive Learning

This project implements Neural Style Transfer (NST) using VGG19 as the feature extractor and a logistic regression classifier trained with contrastive learning to distinguish between stylized images generated from the same content image with different styles and stylized images generated from different content images.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- scikit-learn

You can install the required packages using the following command:

```
pip install -r requirements.txt
```

## Usage

1. Clone this repository:

```
git clone https://github.com/your-username/neural-style-transfer.git
```

2. Navigate to the project directory:

```
cd neural-style-transfer
```

3. Place your content images in the `content_images` directory and your style images in the `style_images` directory.

4. Run the ipynb notebook to perform style transfer and contrastive learning:



5. The stylized images will be saved in the `output_stylized_images` directory.

