# Cat VS Dog Dataset Classification

# Data:

[Kaggle: Cat VS Dog Dataset](https://www.kaggle.com/datasets/karakaggle/kaggle-cat-vs-dog-dataset)

# TensorFlow Model:

```
Model: "sequential_2"
_________________________________________________________________
 Layer (type)                Output Shape              Param #
=================================================================
 rescaling_4 (Rescaling)     (None, 180, 180, 3)       0

 conv2d_6 (Conv2D)           (None, 180, 180, 16)      448

 max_pooling2d_6 (MaxPooling  (None, 90, 90, 16)       0
 2D)

 conv2d_7 (Conv2D)           (None, 90, 90, 32)        4640

 max_pooling2d_7 (MaxPooling  (None, 45, 45, 32)       0
 2D)

 conv2d_8 (Conv2D)           (None, 45, 45, 64)        18496

 max_pooling2d_8 (MaxPooling  (None, 22, 22, 64)       0
 2D)

 flatten (Flatten)           (None, 30976)             0

 dense_2 (Dense)             (None, 128)               3965056

 dense_3 (Dense)             (None, 2)                 258

=================================================================
Total params: 3,988,898
Trainable params: 3,988,898
Non-trainable params: 0
_________________________________________________________________
```

# Credits:

## Johann Pineda:

[theonejohann - Overview](https://github.com/theonejohann)

[https://www.linkedin.com/feed/](https://www.linkedin.com/feed/)