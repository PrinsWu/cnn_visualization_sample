# CNN Visualization Sample

When I study the CNN in AIND of udacity, it say a [Keras blog post](https://blog.keras.io/how-convolutional-neural-networks-see-the-world.html) has a sample to visualize CNN. I got the code from [Github](https://github.com/keras-team/keras/blob/master/examples/conv_filter_visualization.py) but it is not work.  
If you follow the process of the guide of the course, you will get some error about save_img. The main cause is **version of keras of anaconda is 2.1.6 but this sample have to use 2.2.0.**.  
The second error is on transfer layer block2_conv1 since the size of it is 128 but the code write 200 in for loop.
Since I do some change in the code and let it can transfer the layers from 1 to 5.

## Getting Started

This sample run on anaconda if you do not have it then install it.

### Installing

Create a new environment in anaconda that install correct version and can run this sample well.
```
conda env create -f environment.yml
```

Get code from git repository.
```
git clone https://github.com/PrinsWu/cnn_visualization_sample.git
```

## Running the sample

Run jupyter notebook to display the result or you can use it to load another model to produce images of filters.
```
source activate keras_vis
jupyter notebook
```


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details




