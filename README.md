# Caffe implementation of "Perceptual Losses for Real-Time Style Transfer and Super-Resolution"
Fast artistic style transfer by using feed forward network.




## Requirement
- [Caffe](https://github.com/BVLC/caffe)


## Convert
```
python caffe_style_transfer.py <input_image_path> -m <model_path> -o <output_image_path> -g <use_gpu ? gpu_id : 0>
```

This repo has pretrained models as an example in model_caffe.

- example:
```
python caffe_style_transfer.py sample_images/HKU.jpg -m model_caffe/japan.caffemodel -o sample_images/output.jpg
```
or
```
python caffe_style_transfer.py sample_images/HKU.jpg -m model_caffe/modern.caffemodel -o sample_images/output.jpg
```

<img src="https://github.com/jizhuoran/caffe_style_transfer/blob/master/sample_images/HKU.jpg" height="256px">
<img src="https://github.com/jizhuoran/caffe_style_transfer/blob/master/sample_images/japon.jpg" height="256px">
<img src="https://github.com/jizhuoran/caffe_style_transfer/blob/master/sample_images/o11.png" height="256px">
<img src="https://github.com/jizhuoran/caffe_style_transfer/blob/master/sample_images/modern.jpg" height="256px">
<img src="https://github.com/jizhuoran/caffe_style_transfer/blob/master/sample_images/o12.png" height="256px">
