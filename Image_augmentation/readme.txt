Image Augmentation:

Image augmentation technique is a great way to expand the size of dataset. We can come up with new transformed images from original dataset.
When working with deep learning models, not having much data to train the model is one of the most common issues.
Keras ImageDataGenerator lets us to augment images in real-time while the model is still training. We can apply any random transformations on each training image as it is passed to the model. This will not only make the model robust but also save up on the overhead memory.

Keras ImageDataGenerator:

tf.keras.preprocessing.image.ImageDataGenerator(
    rotation_range=0,
    width_shift_range=0.0,
    height_shift_range=0.0,
    shear_range=0.0,
    zoom_range=0.0,
    fill_mode='nearest',
    cval=0.0,
    horizontal_flip=False,
    vertical_flip=False,
    rescale=None,
)
