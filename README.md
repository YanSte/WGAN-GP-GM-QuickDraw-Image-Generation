# | WGAN-GP | GM | QuickDraw | Image Generation |

## WGAN-GP (Wasserstein GAN with Gradient Penalty) and GM (Generative Models) for QuickDraw Image Generation

# <b>1 <span style='color:#78D118'>|</span> Introduction</b>

This project is an exploration of Generative Models (GM) and its capabilities, focusing on the generation of bicycle images using Wasserstein Generative Adversarial Networks (WGAN-GP) in conjunction with estimators and generators.

WGAN-GP (Wasserstein GAN with Gradient Penalty) is a specific type of generative adversarial network (GAN) utilized for generating realistic data, particularly images.

- **Architecture**:
   - **WGAN-GP**: WGAN-GP represents a variant of the GAN framework that places significant emphasis on enhancing training stability and the quality of generated outputs. It leverages the concept of Wasserstein divergence, a metric measuring the dissimilarity between two probability distributions. WGAN-GP introduces a gradient penalty mechanism to control the gradient norms of the discriminator, thereby fostering more stable training and smoother gradients.

- **Loss Function**:
   - **WGAN-GP**: In contrast to traditional GANs, WGAN-GP employs the Wasserstein divergence loss, also referred to as the Earth-Mover (EM) loss. This loss measures the dissimilarity between probability distributions and is considered advantageous for improving the quality of generated data. In addition to this loss, WGAN-GP incorporates a gradient penalty component to enhance training stability further.

- **Training Stability**:
   - **WGAN-GP**: The primary objective of WGAN-GP is to enhance training stability. By incorporating a gradient penalty, it mitigates issues that can affect some conventional GANs, such as mode collapse, where the generator tends to produce similar-looking samples.

In summary, WGAN-GP is a specialized GAN variant tailored to enhance the training stability and output quality, particularly when generating images.

## Objectives :
 - Develop and train a powerful WGAN-GP model using the expansive QuickDraw dataset.
 - Cultivate a deep understanding of the cutting-edge WGAN-GP architecture and Generative AI techniques.

## The QuickDraw Dataset:
The [Quick Draw dataset](https://quickdraw.withgoogle.com/data) is a treasure trove of approximately 50 million drawings, contributed by real artists. For our endeavor, we have curated a subset consisting of 117,555 meticulously crafted bicycle drawings.

**Access the QuickDraw Dataset:**
 - Dataset Repository: [https://github.com/googlecreativelab/quickdraw-dataset](https://github.com/googlecreativelab/quickdraw-dataset)
 - Numpy Bitmap Files: [https://console.cloud.google.com/storage/quickdraw_dataset/full/numpy_bitmap](https://console.cloud.google.com/storage/quickdraw_dataset/full/numpy_bitmap)
 - Bicycle Dataset: [https://storage.googleapis.com/quickdraw_dataset/full/numpy_bitmap/bicycle.npy](https://storage.googleapis.com/quickdraw_dataset/full/numpy_bitmap/bicycle.npy)

## Project Workflow:

- **Setup**: Imports and Parameters.
-  **Data Exploration**: Discovering bicycle drawings in the Dataset.
-  **Model Architecture**: Designing a WGAN-GP (Wasserstein Generative Adversarial Network with Gradient Penalty).
-  **Model Building**: Creating the GAN Model.
-  **Model Training**: Feed data to the model and watch as it learns to generate bicycles.
-  **Artistic Analysis**: Delving into the generated Bicycles.

[| View on Kaggle |](https://www.kaggle.com/yannicksteph/wgan-gp-gm-quickdraw-image-generation/)
