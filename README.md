# deeplearning4jtest
deeplearning4j学习

1.异或测试例子

2.MNIST手写数字识别（基于LENET）

# 下载 MNIST database of handwritten digits

[MNIST database](http://yann.lecun.com/exdb/mnist/)

Four files are available on this site:

train-images-idx3-ubyte.gz:  training set images (9912422 bytes) 
train-labels-idx1-ubyte.gz:  training set labels (28881 bytes) 
t10k-images-idx3-ubyte.gz:   test set images (1648877 bytes) 
t10k-labels-idx1-ubyte.gz:   test set labels (4542 bytes)

# 将下载后的文件复制到 D:/doc/ 文件下，加压这些文件

D:\doc>dir
 驱动器 D 中的卷是 DataDisk
 卷的序列号是 D8B3-0120

 D:\doc 的目录

2018/12/06  15:37    <DIR>          .
2018/12/06  15:37    <DIR>          ..
2018/12/06  15:01         1,648,877 t10k-images-idx3-ubyte.gz
1998/01/26  23:07         7,840,016 t10k-images.idx3-ubyte
2018/12/06  15:01             4,542 t10k-labels-idx1-ubyte.gz
1998/01/26  23:07            10,008 t10k-labels.idx1-ubyte
2018/12/06  15:38    <DIR>          test
2018/12/06  15:00         9,912,422 train-images-idx3-ubyte.gz
1996/11/18  23:36        47,040,016 train-images.idx3-ubyte
2018/12/06  15:01            28,881 train-labels-idx1-ubyte.gz
1996/11/18  23:36            60,008 train-labels.idx1-ubyte
               8 个文件     66,544,770 字节
               3 个目录 158,651,867,136 可用字节
  
 
