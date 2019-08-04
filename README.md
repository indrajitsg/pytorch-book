This is the corresponding code for the book Deep Learning Framework PyTorch: Getting Started and Practice, but it can also be used as a stand-alone PyTorch Getting Started Guide and Tutorial.

## Release Notes
Updated to **PyTorch 1.1.0 (Not 0.4.0)**


The current version of the code is based on pytorch 1.0.1, if you want to use the old version please `git checkout v0.2` or `git checkout v0.3`. Legacy code has better python2/python3 compatibility, CPU/GPU compatibility testing. The new version of the code has not been fully tested and has been tested under GPU and Python3. But in theory there should not be too many problems in python2 and CPU.

## Content

The contents of the book (tutorial/warehouse) are as shown:
![Minding map](http://7zh43r.com2.z0.glb.clouddn.com/del/mindmap.png)

It can be seen that this tutorial can be divided into two parts:

**Basic Part ** (Top 5) Explains PyTorch content, which introduces the main modules in PyTorch and some of the tools commonly used in deep learning. For this part of the content, here using Jupyter Notebook as a teaching tool, the reader can modify the operation in conjunction with the notebook, and experiment repeatedly.

- Chapter 2 describes how to install PyTorch and configure the learning environment. It also provides a quick start tutorial, based on the official tutorial to simplify and update the content, the reader can spend about 1 to 2 hours to quickly complete the entry task, and then choose to read the relevant chapters in depth according to the needs.
- The third chapter introduces the use of multidimensional array Tensor and dynamic graph autograd/Variable in PyTorch, with examples, let the reader use Tensor and autograd to achieve linear regression, and compare the differences between the two. In addition to introducing the basic use of the two, this chapter also provides a more in-depth analysis of Tensor's underlying design and autograd's computational graph principles, hoping to enable readers to have a more comprehensive grasp of these underlying knowledge.
- The fourth chapter introduces the basic usage of the neural network module nn in PyTorch. At the same time, it explains the "layer", "loss function", "optimizer" in the neural network, and finally leads the reader to build the code with less than 50 lines of code. ResNet won the ImageNet title.
- Chapter 5 introduces PyTorch's tools for data loading, GPU acceleration, persistence, and visualization.

**The actual combat section** (Chapters 6 through 10) uses PyTorch to implement several cool and interesting applications. For this part of the content, the warehouse gives the complete implementation code and provides the pre-trained model as a demo. For the reader to test.

- Chapter 6 is a chapter on the link. The goal of this chapter is not to teach readers new functions, new knowledge, but to combine a classic game in Kaggle to achieve a relatively simple image classification problem in deep learning. In the implementation process, the reader is guided to review the knowledge of the first five chapters, and propose code specifications to organize the program and code reasonably, making the program more readable and maintainable. Chapter 6 also describes how to debug in PyTorch.
- Chapter 7 explains the current hottest generation confrontation network (GAN) for readers, and leads the reader to implement an anime avatar generator from the beginning, which can use GAN to generate a variety of anime avatars.
- Chapter 8 explains the relevant knowledge of style migration for readers, and leads the reader to realize the style migration network and turn his own photos into famous paintings on the tall.
- Chapter 9 explains the basics of natural language processing for the reader and explains the principles of CharRNN. Then, using tens of thousands of Tang poems, I trained a small program that can automatically write poetry. This small program can control the ** format of the generated poems, ** genre **, and can also generate ** 藏 藏 **.
- Chapter 10 introduces the image description task to the reader, and takes the latest AI Challenger game data as an example to lead the reader to implement a small program that can describe simple images.
- Chapter 11 (**New, Experimental**) Speech recognition written by [Diamondfan] (https://github.com/Diamondfan). This project has been improved (this project has included three examples of images, texts, and voices).


 **The text description in Notebook belongs to the first draft of this book. It is not fluent in description, please forgive me if you are wrong. I intend to delete the content described in the notebook, leaving only the code, but in order to facilitate the reader to read and learn, I finally decided to stay. I will take the time to proofread this part of the text based on the contents of the book, but I don't provide a specific point in time.

## Do you need to buy a book?

Book ** is not necessary **, this warehouse contains more than 50% of the text content of the book, more than 90% of the code, especially the introduction of the previous chapters, almost completely retain the contents of the book. Readers can use this tutorial even if they don't buy books.

~~ If you feel that the advantages of paper books attract you, you may wish to take a small fee to support the author's work for the past six months. At the same time, in order to make the reader as convenient as possible, the author also specially opened the service of Tencent Cloud to save some of the models used in the tutorial, preprocessed data and some large files. ~~
Some of the contents of the book are outdated, and the contents of the warehouse will prevail.

## Code Description

- The code is mainly tested under python3 to get the final result, python2 has not been tested yet. The v0.2 and v0.3 branch code is rigorously tested to support python2/python3
- The actual combat code is tested in both GPU and CPU environments.
- The code has been updated to be compatible with PyTorch `0.4.1`, and will be considered compatible with `v1.0`, but there is no exact time.

If you want to run under PyTorch 0.2.0 or 0.3, please
```
Git checkout v0.2 # v0.3
```

If there is any improper, or need to be improved, the reader is welcome to open an issue discussion, or submit a pull request.

## Environment Configuration

1. Install [PyTorch] (http://pytorch.org), please select the specified version from the official website to install, one-click installation (even if you use anaconda, it is recommended to use pip). Please refer to the book for more installation methods.

2. Cloning the warehouse

   ```python
   Git clone https://github.com/chenyuntc/PyTorch-book.git
   ```

3. Install third-party dependencies

   ```python
   Cd pytorch-book && pip install -r requirements.txt
   ```

## Visdom can't open and its solution
**The new version of visdom has solved this problem and only needs to be upgraded**
```
Pip install --upgrade visdom
```
Previous [solution] (https://github.com/chenyuntc/pytorch-book/blob/2c8366137b691aaa8fbeeea478cc1611c09e15f5/README.md#visdom%E6%89%93%E4%B8%8D%E5%BC%80%E5 %8F%8A%E5%85%B6%E8%A7%A3%E5%86%B3%E6%96%B9%E6%A1%88) No longer needed, has been deleted.

## ^_^

There are any bugs, unclear places or confusion, welcome to open issue

Welcome to pull requests

Happy Coding!

![](http://img14.360buyimg.com/n1/jfs/t13339/32/2463730198/217483/e8148c6b/5a41277dNbd1470c1.jpg)

- [Jingdong purchase link] (https://search.jd.com/Search?keyword=pytorch%20Getting Started & Practice&enc=utf-8&wq=pytorch%20Getting Started & Practice&pvid=8b0d91d7108845ad8cbaf596326f3eb3)
- [Dangdang Buy Link] (http://search.dangdang.com/?key=pytorch%20%C8%EB%C3%C5%D3%EB%CA%B5%BC%F9&act=input)