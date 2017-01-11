### I2T2I: LEARNING TEXT TO IMAGE SYNTHESIS WITH TEXTURAL DATA AUGMENTATION


## File
* `model_im2txt.py` model for Image Captioning
* `train_im2txt2im_coco_64.py` for training I2T2I
* `utils.py` utility functions

## Usage
* 1. Download
 * image captioning model
 * MSCOCO dataset
* 2. Set directories
 * in `train_im2txt2im_coco_64.py` 
 * config your image directory here
`images_train_dir = '/home/.../mscoco/raw-data/train2014/'`
 * config the vocabulary and model of you image captioning module `DIR = "/home/..."`
 * directory containing model checkpoints.
`CHECKPOINT_DIR = DIR + "/model/train"`
 * vocabulary file generated by the preprocessing script.
`VOCAB_FILE = DIR + "/data/mscoco/word_counts.txt"`

## Results