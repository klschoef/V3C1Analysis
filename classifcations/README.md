# Classification Results

This directory contains classification results (as .csv files; packed as .tgz for each video separately) obtained with GoogLeNet (i.e., Inception v3) that was trained on all 21k ImageNet classes. 

## Format

The format of the .csv files is as follows:
- the content is decreasingly ordered by classification confidence
- for each detected class/concept, the line number of the [synset file](synset.txt) is followed by the softmax/confidence value. This way, every second (uneven) value in the file is a class label, while every other (even) value is a confidence value.
