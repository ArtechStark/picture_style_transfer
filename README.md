# picture_style_transfer

An implementation of paper 'A Neural Algorithm of Artistic Style' in TensorFlow.
Transfer the style of one picture to another


## How to run

`python picture_style_transfer.py --content example1/content.jpg --styles ./example1/style.jpg --output ./example1/output.jpg`

Run `python picture_style_transfer.py --help` to see a list of all options.

Use `--iterations` to change the number of iterations (default 1000).  

Using a GPU is highly recommended due to the huge speedup.

## Pretrained network
Pretrained network is [VGG19](http://www.vlfeat.org/matconvnet/models/beta16/imagenet-vgg-verydeep-19.mat) or [VGG19](https://pan.baidu.com/s/10Q9xc3c9y7QOqF-QM4Xi4A) (Baidu net disk link). Before you run the code, please download it into the top level of this repository
The structure of VGG19
![title]('VGG19 model structure.png')
