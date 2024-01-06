# Human Detection model


## Getting started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```
### 2. Create and activate virtual environment

```bash
python -m venv myvenv
```
On Windows:
```
.\myvenv\Scripts\Activate
```
On Linux:
```
source myvenv/bin/activate
```
Install requirements:
```
pip install -r requirements.txt
```

### 3. Download inference model
```
http://download.tensorflow.org/models/object_detection/faster_rcnn_inception_v2_coco_2018_01_28.tar.gz
```
Extract the archive into `models` folder.

### 4. Run model
Run cells from `human_detection.ipynb` notebook to test the model on example. If you want to use the model on your own examples, replace `image_path` to paths to your images.
