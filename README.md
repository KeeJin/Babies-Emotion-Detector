# Babies Emotion Detector
Image classifier that classifies a baby's emotion into 'happy', 'sad' or 'angry' based on their facial expressions

##### Dataset source
Images of babies were scraped from google images using the "Fatkun Batch Download Image" Google Chrome extension. The search queries "happy baby", "sad baby" and "angry baby" were used.

##### Methodology
I implemented transfer learning of the VGG16 model with pretrained imagenet weights, then finetuned it by adding extra hidden layers, and unfreezing a few additional top layers for further training. The data pipeline and training was constructed with Tensorflow 2.

##### Results
The model achieved validation loss of 0.0211.

##### What can be improved
1. Should put in more effort in increasing the size of a dataset, as this would greatly improve training.
2. The curated dataset was unbalanced: there were a lot more images of "happy" babies than "sad" or "angry" babies available on the internet.
3. The difference in facial expressions between a "sad" and "angry" baby may not be very distinct.
