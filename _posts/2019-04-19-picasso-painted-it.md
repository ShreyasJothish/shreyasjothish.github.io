---
layout: post
title: Picasso Painted It
subtitle: Neural style transfer on images.
image: /img/picassopaintedit/transformed_image.png
gh-repo: ShreyasJothish/picassopaintedit
gh-badge: [star, fork, follow]
tags: [neural style transfer]
---

Neural style transfer is a deep learning technique to compose image in the style of another image. Neural style transfer is based on Leon A. Gatys’ paper, [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576).

## Project Description

* This project was carried out as part of Lambda School’s build week. Full stack developers and Data scientists worked together to support neural style transfer of images. 

* Pablo Picasso's images are used as style reference. The live application is hosted on netlify. [Picasso Painted It](https://picasso-frontend.netlify.com)

* I was responsible for developing neural style transformation APIs.

* This application supports neural style transfer on images in two modes.

> fasttransform - Using DeepAI API.

> deeptransform - Implementation of deeptransform based on [Neural Style Transfer with tf.keras](https://colab.research.google.com/github/tensorflow/models/blob/master/research/nst_blogpost/4_Neural_Style_Transfer_with_Eager_Execution.ipynb) handled asynchronously using flask_celery.

**Content Image:**

![](/img/picassopaintedit/content_image.jpg)

**Style Image:**

![](/img/picassopaintedit/style_image.jpg)

**Transformed Image:**

![](/img/picassopaintedit/transformed_image.png)

## Tools
python, celery, tensorflow, keras, DeepAI API

## Reference List

### API:

> [DeepAI Neural Style API](https://deepai.org/api-docs/#neural-style)

### Code:

> [Neural Style Transfer with tf.keras](https://colab.research.google.com/github/tensorflow/models/blob/master/research/nst_blogpost/4_Neural_Style_Transfer_with_Eager_Execution.ipynb) and is handled asynchronously using flask_celery.


