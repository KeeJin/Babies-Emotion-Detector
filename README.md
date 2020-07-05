# Babies Emotion Detector
Image classifier that classifies a baby's emotion into 'happy', 'sad' or 'angry' based on their facial expressions

##### Dataset source
Images of babies were scraped from google images using the "Fatkun Batch Download Image" Google Chrome extension. The search queries "happy baby", "sad baby" and "angry baby" were used.

##### Results
The model achieved validation loss of 0.0211.

##### What can be improved
> Should put in more effort in increasing the size of a dataset, as this would greatly improve training.
> The curated dataset was unbalanced: there were a lot more images of "happy" babies than "sad" or "angry" babies available on the internet.
> The difference in facial expressions between a "sad" and "angry" baby may not be very distinct.
