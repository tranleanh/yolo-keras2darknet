# Weight Conversion between Darknet & Keras

This repo contains Python code to convert weight files from Darknet to Keras and vice versa.


## Dependencies

- Tensorflow 1.13.1
- Keras 2.1.4

## Darknet to Keras

Converting Darknet model (*.weights) to Keras model (.h5):

```bashrc
$ python dark2keras.py -cfg_path {cfg_file_name}.cfg \
                       -weights_path {darknet_file_name}.weights \
                       -output_path {keras_file_name}.h5
```

## Keras to Darknet

Converting Keras model (.h5) to Darknet model (*.weights):

```bashrc
$ python keras2dark.py -cfg_path {cfg_file_name}.cfg \
                       -h5_path {keras_file_name}.h5 \
                       -output_path {darknet_file_name}.weights
```

## Citation

Please cite this repo if it's helpful for your study. 

```bibtex
@misc{tran2024keras2darknet,
  author = {Tran, Le-Anh},
  title = {Weight Conversion between Darknet and Keras},
  year = {2024},
  publisher = {GitHub},
  journal = {GitHub repository}
}
```

## References

[1] https://github.com/qqwweee/keras-yolo3

[2] https://www.cnblogs.com/shouhuxianjian/p/10567201.html
 
Have fun!


LA Tran

Jan. 2024
