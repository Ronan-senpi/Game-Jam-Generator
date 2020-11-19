**Installation on windows**
**Required**

python 3.6.8 
https://www.python.org/downloads/release/python-368/
add python to environment variables

**Install TensorFlow GPU**

When using this code GPU acceleration is highlight recommended.  If you are using Ubuntu or similar use pip to install tensorflow GPU , something like this. 

`pip3 install tensorflow-gpu==1.15`

**Install GPT2 Simple**
Installing this library is as easy as 

`pip3 install gpt_2_simple`

Here is a link to the GitHub repo for those interested

https://github.com/minimaxir/gpt-2-simple

**Usage**
`python train.py`

Please note this will download a 3.1GB pre-trained GPT2 model, so that takes a while.

You can change GPT-2 model at `line 8` : 
- 124M
- 335M (3.1GB)
- 774M
- 1558M

You can change number of step at `line 9`
