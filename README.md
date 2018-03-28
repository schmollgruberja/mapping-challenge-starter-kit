# mapping-challenge-starter-kit
![CrowdAI-Logo](https://github.com/crowdAI/crowdai/raw/master/app/assets/images/misc/crowdai-logo-smile.svg?sanitize=true)

# Installation
```
git clone git@github.com:crowdAI/mapping-challenge-starter-kit.git
cd mapping-challenge-starter-kit
pip install -r requirements.txt
```

# Dataset
Please download the datasets from [https://www.crowdai.org/challenges/mapping-challenge/dataset_files](https://www.crowdai.org/challenges/mapping-challenge/dataset_files), and untar them to have the following directory structure :

```bash
|-- data/
|   |-- test_images/ (has all images for prediction)
|   |-- train/
|   |   `-- images (has all the images for training)
|   |   |__ annotation.json : Annotation of the data in MS COCO format
|   |   |__ annotation-small.json : Smaller version of the previous dataset
|   `-- val/
|   |   `-- images (has all the images for training)
|   |   |__ annotation.json : Annotation of the data in MS COCO format
|   |   |__ annotation-small.json : Smaller version of the previous dataset
```

# Usage
Now you can refer to the list of Jupyter Notebooks for different aspects of the challenge and the datasets.
You can access all of them by :
```bash
jupyter-notebook
```
## Available Notebooks

* [Dataset Utils](Dataset%20Utils.ipynb)
  * [Import Dependencies](https://render.githubusercontent.com/view/ipynb?commit=a278ab9e505fb136b2eca31cd33487ede51746b2&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f63726f776441492f6d617070696e672d6368616c6c656e67652d737461727465722d6b69742f613237386162396535303566623133366232656361333163643333343837656465353137343662322f446174617365742532305574696c732e6970796e623f746f6b656e3d41426768414a4f714861747a6e5a73744d566176645a7077584d6c495a5f6c2d6b733561757972577741253344253344&nwo=crowdAI%2Fmapping-challenge-starter-kit&path=Dataset%20Utils.ipynb#Import-dependencies)
  * [Configuration Variables](https://render.githubusercontent.com/view/ipynb?commit=a278ab9e505fb136b2eca31cd33487ede51746b2&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f63726f776441492f6d617070696e672d6368616c6c656e67652d737461727465722d6b69742f613237386162396535303566623133366232656361333163643333343837656465353137343662322f446174617365742532305574696c732e6970796e623f746f6b656e3d41426768414a4f714861747a6e5a73744d566176645a7077584d6c495a5f6c2d6b733561757972577741253344253344&nwo=crowdAI%2Fmapping-challenge-starter-kit&path=Dataset%20Utils.ipynb#Configuration-Variables)
  * [Parsing Annotations](https://render.githubusercontent.com/view/ipynb?commit=a278ab9e505fb136b2eca31cd33487ede51746b2&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f63726f776441492f6d617070696e672d6368616c6c656e67652d737461727465722d6b69742f613237386162396535303566623133366232656361333163643333343837656465353137343662322f446174617365742532305574696c732e6970796e623f746f6b656e3d41426768414a4f714861747a6e5a73744d566176645a7077584d6c495a5f6c2d6b733561757972577741253344253344&nwo=crowdAI%2Fmapping-challenge-starter-kit&path=Dataset%20Utils.ipynb#Parsing-the-annotations)
  * [Collecting and Visualizing Images](https://render.githubusercontent.com/view/ipynb?commit=a278ab9e505fb136b2eca31cd33487ede51746b2&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f63726f776441492f6d617070696e672d6368616c6c656e67652d737461727465722d6b69742f613237386162396535303566623133366232656361333163643333343837656465353137343662322f446174617365742532305574696c732e6970796e623f746f6b656e3d41426768414a4f714861747a6e5a73744d566176645a7077584d6c495a5f6c2d6b733561757972577741253344253344&nwo=crowdAI%2Fmapping-challenge-starter-kit&path=Dataset%20Utils.ipynb#Collecting-and-Visualizing-Images)
  * [Understanding Annotations](https://render.githubusercontent.com/view/ipynb?commit=a278ab9e505fb136b2eca31cd33487ede51746b2&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f63726f776441492f6d617070696e672d6368616c6c656e67652d737461727465722d6b69742f613237386162396535303566623133366232656361333163643333343837656465353137343662322f446174617365742532305574696c732e6970796e623f746f6b656e3d41426768414a4f714861747a6e5a73744d566176645a7077584d6c495a5f6c2d6b733561757972577741253344253344&nwo=crowdAI%2Fmapping-challenge-starter-kit&path=Dataset%20Utils.ipynb#Understanding-Annotations)
  * [Visualizing Annotations](https://render.githubusercontent.com/view/ipynb?commit=a278ab9e505fb136b2eca31cd33487ede51746b2&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f63726f776441492f6d617070696e672d6368616c6c656e67652d737461727465722d6b69742f613237386162396535303566623133366232656361333163643333343837656465353137343662322f446174617365742532305574696c732e6970796e623f746f6b656e3d41426768414a4f714861747a6e5a73744d566176645a7077584d6c495a5f6c2d6b733561757972577741253344253344&nwo=crowdAI%2Fmapping-challenge-starter-kit&path=Dataset%20Utils.ipynb#Visualizing-Annotations)
  * [Advanced](https://render.githubusercontent.com/view/ipynb?commit=a278ab9e505fb136b2eca31cd33487ede51746b2&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f63726f776441492f6d617070696e672d6368616c6c656e67652d737461727465722d6b69742f613237386162396535303566623133366232656361333163643333343837656465353137343662322f446174617365742532305574696c732e6970796e623f746f6b656e3d41426768414a4f714861747a6e5a73744d566176645a7077584d6c495a5f6c2d6b733561757972577741253344253344&nwo=crowdAI%2Fmapping-challenge-starter-kit&path=Dataset%20Utils.ipynb#Advanced)
    * [Convert poly segmentation to rle](https://render.githubusercontent.com/view/ipynb?commit=a278ab9e505fb136b2eca31cd33487ede51746b2&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f63726f776441492f6d617070696e672d6368616c6c656e67652d737461727465722d6b69742f613237386162396535303566623133366232656361333163643333343837656465353137343662322f446174617365742532305574696c732e6970796e623f746f6b656e3d41426768414a4f714861747a6e5a73744d566176645a7077584d6c495a5f6c2d6b733561757972577741253344253344&nwo=crowdAI%2Fmapping-challenge-starter-kit&path=Dataset%20Utils.ipynb#1.-Convert-poly-segmentation-to-rle)
    * [Convert segmentation to pixel level masks](https://render.githubusercontent.com/view/ipynb?commit=a278ab9e505fb136b2eca31cd33487ede51746b2&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f63726f776441492f6d617070696e672d6368616c6c656e67652d737461727465722d6b69742f613237386162396535303566623133366232656361333163643333343837656465353137343662322f446174617365742532305574696c732e6970796e623f746f6b656e3d41426768414a4f714861747a6e5a73744d566176645a7077584d6c495a5f6c2d6b733561757972577741253344253344&nwo=crowdAI%2Fmapping-challenge-starter-kit&path=Dataset%20Utils.ipynb#2.-Convert-segmentation-to-pixel-level-masks)
* [Random Submission](Random%20Submission.ipynb)
  * [Submission Format](https://render.githubusercontent.com/view/ipynb?commit=a278ab9e505fb136b2eca31cd33487ede51746b2&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f63726f776441492f6d617070696e672d6368616c6c656e67652d737461727465722d6b69742f613237386162396535303566623133366232656361333163643333343837656465353137343662322f446174617365742532305574696c732e6970796e623f746f6b656e3d41426768414a4f714861747a6e5a73744d566176645a7077584d6c495a5f6c2d6b733561757972577741253344253344&nwo=crowdAI%2Fmapping-challenge-starter-kit&path=Random%20Submission.ipynb#Submission-Format)
  * [Generating a Random Segmentation](https://render.githubusercontent.com/view/ipynb?commit=a278ab9e505fb136b2eca31cd33487ede51746b2&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f63726f776441492f6d617070696e672d6368616c6c656e67652d737461727465722d6b69742f613237386162396535303566623133366232656361333163643333343837656465353137343662322f446174617365742532305574696c732e6970796e623f746f6b656e3d41426768414a4f714861747a6e5a73744d566176645a7077584d6c495a5f6c2d6b733561757972577741253344253344&nwo=crowdAI%2Fmapping-challenge-starter-kit&path=Random%20Submission.ipynb#Generate-a-random-segmentation)
  * [Generating a Random Annotation Object](https://render.githubusercontent.com/view/ipynb?commit=a278ab9e505fb136b2eca31cd33487ede51746b2&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f63726f776441492f6d617070696e672d6368616c6c656e67652d737461727465722d6b69742f613237386162396535303566623133366232656361333163643333343837656465353137343662322f446174617365742532305574696c732e6970796e623f746f6b656e3d41426768414a4f714861747a6e5a73744d566176645a7077584d6c495a5f6c2d6b733561757972577741253344253344&nwo=crowdAI%2Fmapping-challenge-starter-kit&path=Random%20Submission.ipynb#Generate-a-random-annotation-object)
  * [Generating a Random Results Object](https://render.githubusercontent.com/view/ipynb?commit=a278ab9e505fb136b2eca31cd33487ede51746b2&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f63726f776441492f6d617070696e672d6368616c6c656e67652d737461727465722d6b69742f613237386162396535303566623133366232656361333163643333343837656465353137343662322f446174617365742532305574696c732e6970796e623f746f6b656e3d41426768414a4f714861747a6e5a73744d566176645a7077584d6c495a5f6c2d6b733561757972577741253344253344&nwo=crowdAI%2Fmapping-challenge-starter-kit&path=Random%20Submission.ipynb#Generate-a-results-object)
  * [Submit to crowdAI for grading](https://render.githubusercontent.com/view/ipynb?commit=a278ab9e505fb136b2eca31cd33487ede51746b2&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f63726f776441492f6d617070696e672d6368616c6c656e67652d737461727465722d6b69742f613237386162396535303566623133366232656361333163643333343837656465353137343662322f446174617365742532305574696c732e6970796e623f746f6b656e3d41426768414a4f714861747a6e5a73744d566176645a7077584d6c495a5f6c2d6b733561757972577741253344253344&nwo=crowdAI%2Fmapping-challenge-starter-kit&path=Random%20Submission.ipynb#Submit-to-crowdAI-for-grading)

* [Locally test the evaluation function](#Local Evaluation)   

* Train [Mask-RCNN](https://arxiv.org/abs/1703.06870) : `Coming Soon`

## Miscelaneous Resources
* [Convert Annotations from MS COCO format to PascalVOC format](https://github.com/CasiaFan/Dataset_to_VOC_converter/blob/master/anno_coco2voc.py)

# Author   
Sharada Mohanty <sharada.mohanty@epfl.ch>
