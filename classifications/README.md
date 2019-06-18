# Classification Results

This directory contains classification results (as .csv files; packed as .tgz for each video separately) obtained with GoogLeNet (i.e., Inception v3) that was trained on all 21k ImageNet classes. 

## Format

The format of the .csv files is as follows:
- the content is decreasingly ordered by classification confidence
- for each detected class/concept, the zero-based line number of the [synset file](synset.txt) is followed by the softmax/confidence value. Please note that the line number is zero-based, e.g., if the label is 11 it means 'French bulldog' (line 12 in the synset file).  This way, every second (uneven) value in the file is a class label, while every other (even) value is a confidence value.
