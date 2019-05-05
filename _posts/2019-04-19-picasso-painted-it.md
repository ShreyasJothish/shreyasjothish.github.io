---
layout: post
title: Picasso Painted It
subtitle: Neural style transfer on images.
image: /img/picassopaintedit/newyork_skyline_picasso_version.png
gh-repo: ShreyasJothish/picassopaintedit
gh-badge: [star, fork, follow]
tags: [data analysis, data visualization]
---

Neural style transfer is a deep learning technique to compose images in the style of another image. This outlined in Leon A. Gatys’ paper, A Neural Algorithm of Artistic Style.

## Project Description

* This project was carried out as part of Lambda School’s build week. Full stack developers and Data Scientists worked together to support neural style transfer of images.
Here we used Pablo Picasso's images are used as style reference.

* I was responsible for supporting neural style transformation API to be used by web team.

* This application supports neural style transfer on images in two modes.

> fasttransform - Using DeepAI API.

> deeptransform - Implementation of deeptransform based on [Neural Style Transfer with tf.keras](https://colab.research.google.com/github/tensorflow/models/blob/master/research/nst_blogpost/4_Neural_Style_Transfer_with_Eager_Execution.ipynb) and is handled asynchronously using flask_celery.

**Original Image:**

![](/img/picassopaintedit/newyork_skyline.png)

**Transformed Image:**

![](/img/picassopaintedit/newyork_skyline_picasso_version.png)

## Tools
python, celery, tensorflow, keras, DeepAI API

## Reference List

### API:

> [DeepAI Neural Style API](https://deepai.org/api-docs/#neural-style)

### Reference:

> [Neural Style Transfer with tf.keras](https://colab.research.google.com/github/tensorflow/models/blob/master/research/nst_blogpost/4_Neural_Style_Transfer_with_Eager_Execution.ipynb) and is handled asynchronously using flask_celery.


