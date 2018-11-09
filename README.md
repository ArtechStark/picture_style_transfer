# picture_style_transfer

An implementation of [neural style][paper] in TensorFlow.


## How to run

`python picture_style_transfer.py --content example1/content.jpg --styles ./example1/style.jpg --output ./example1/output.jpg>`

Run `python picture_style_transfer.py --help` to see a list of all options.

Use `--iterations` to change the number of iterations (default 1000).  

Using a GPU is highly recommended due to the huge speedup.
