# Computer Vision & Deep Learning Notebooks

Hands-on Google Colab notebooks from my computer vision and deep-learning studies: image processing with OpenCV, PyTorch fundamentals, dataset collection and a transfer-learning food classifier.

## Notebooks
| Notebook | What it covers |
|---|---|
| [`menu_detector_model.ipynb`](menu_detector_model.ipynb) | **Food / menu image classifier.** Transfer learning with a pretrained **MobileNetV2** (ImageNet weights) in PyTorch, a custom `Dataset` and `DataLoader`, image transforms, Adam optimizer, training on GPU. Classes include hamburger, hot dog, cheesecake, chocolate cake, kebab and pilaf (~3,300 images). |
| [`data_scraping.ipynb`](data_scraping.ipynb) | **Dataset collection** for the classifier: downloads selected classes from the Food-101 dataset via `kagglehub`, and scrapes extra images (e.g. local dishes) with DuckDuckGo image search, then validates them with Pillow and saves to Google Drive. |
| [`cv_opencv.ipynb`](cv_opencv.ipynb) | **OpenCV basics:** reading and saving images, BGR channels and pixel access, grayscale, resize, rotate and flip, Gaussian blur, Canny edge detection, Haar-cascade face detection with bounding boxes, and webcam video streaming. |
| [`pytorch.ipynb`](pytorch.ipynb) | **PyTorch fundamentals:** tensors, tensor operations, matrix multiplication, devices (CPU/CUDA) and a first neural network. |
| [`matplotlib.ipynb`](matplotlib.ipynb) | **Data visualisation:** line plots, styles, multiple series, bar charts and more with Matplotlib and NumPy. |

## Tech
Python · PyTorch · torchvision · OpenCV · NumPy · Matplotlib · Pillow · kagglehub · Google Colab (GPU)

## Run
Each notebook has an **Open in Colab** badge at the top. The classifier notebooks expect the dataset folder on Google Drive (`/content/drive/MyDrive/food101_dataset`), which `data_scraping.ipynb` creates.
