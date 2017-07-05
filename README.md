# SynthText of Mandarin Chinese

## Proposal
Since there is too less dataset of Mandarin OCR for deep learning, we adapt the code from https://github.com/ankush-me/SynthText which is SynthText in English to create our own Mandarin version of SynthText.

## Rendering
![](https://raw.githubusercontent.com/Oliver-Q/Oliver-Q.github.io/master/Posts/Caffe/SynthText_1.png)
![](https://raw.githubusercontent.com/Oliver-Q/Oliver-Q.github.io/master/Posts/Caffe/SynthText_2.png)

As shown above, different colors and fonts custom Chinese text can be embedded into pictures based on Syntext_Chinese_version. 

## Code
From modifying the original [Ankush’s github repository](https://github.com/ankush-me/SynthText), we can generate our own English text and change background picture arbitrarily, including detecting depth with one single picture, segmenting the picture into different geometries. 

![](https://raw.githubusercontent.com/Oliver-Q/Oliver-Q.github.io/master/Posts/Caffe/SynthText_3.png)

In order to plant the Mandarin text in to our own picture, more codes will be modified to suit in.
Thanks to [SynthText_Chinese_version](https://github.com/JarveeLee/SynthText_Chinese_version) and after fixing some [problems](https://github.com/JarveeLee/SynthText_Chinese_version/issues/1)
This repository works actually good now.
