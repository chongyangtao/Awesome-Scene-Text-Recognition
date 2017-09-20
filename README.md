[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

# Scene Text Localization & Recognition Resources
A curated list of resources dedicated to scene text localization and recognition. Any suggestions and pull requests are welcome.

## Papers & Code

### Overview
- [2015-PAMI] Text Detection and Recognition in Imagery: A Survey [`paper`](http://lampsrv02.umiacs.umd.edu/pubs/Papers/qixiangye-14/qixiangye-14.pdf)
- [2014-Front.Comput.Sci] Scene Text Detection and Recognition: Recent Advances and Future Trends [`paper`](http://mc.eistar.net/uploadfiles/Papers/FCS_TextSurvey_2015.pdf)


### Visual Geometry Group, University of Oxford
- [2016-IJCV, [M. Jaderberg](http://www.maxjaderberg.com)] Reading Text in the Wild with Convolutional Neural Networks  [`paper`](http://arxiv.org/abs/1412.1842) [`demo`](http://zeus.robots.ox.ac.uk/textsearch/#/search/)  [`homepage`](http://www.robots.ox.ac.uk/~vgg/research/text/)
- [2016-CVPR, [A Gupta](http://www.robots.ox.ac.uk/~ankush/)] Synthetic Data for Text Localisation in Natural Images [`paper`](http://www.robots.ox.ac.uk/~vgg/data/scenetext/gupta16.pdf) [`code`](https://github.com/ankush-me/SynthText) [`data`](http://www.robots.ox.ac.uk/~vgg/data/scenetext/)
- [2015-ICLR, [M. Jaderberg](http://www.maxjaderberg.com)] Deep structured output learning for unconstrained text recognition [`paper`](http://arxiv.org/abs/1412.5903)
- [2015-D.Phil Thesis, [M. Jaderberg](http://www.maxjaderberg.com)] Deep Learning for Text Spotting
 [`paper`](http://www.robots.ox.ac.uk/~vgg/publications/2015/Jaderberg15b/jaderberg15b.pdf)
- [2014-ECCV, [M. Jaderberg](http://www.maxjaderberg.com)] Deep Features for Text Spotting [`paper`](http://www.robots.ox.ac.uk/~vgg/publications/2014/Jaderberg14/jaderberg14.pdf) [`code`](https://bitbucket.org/jaderberg/eccv2014_textspotting) [`model`](https://bitbucket.org/jaderberg/eccv2014_textspotting) [`GitXiv`](http://gitxiv.com/posts/uB4y7QdD5XquEJ69c/deep-features-for-text-spotting)
- [2014-NIPS, [M. Jaderberg](http://www.maxjaderberg.com)] Synthetic Data and Artificial Neural Networks for Natural Scene Text Recognition [`paper`](http://www.robots.ox.ac.uk/~vgg/publications/2014/Jaderberg14c/jaderberg14c.pdf)  [`homepage`](http://www.robots.ox.ac.uk/~vgg/publications/2014/Jaderberg14c/) [`model`](http://www.robots.ox.ac.uk/~vgg/research/text/model_release.tar.gz)

### CUHK & SIAT
- [2016-arXiv] Accurate Text Localization in Natural Image with Cascaded Convolutional Text Network
 [`paper`](http://arxiv.org/abs/1603.09423)
- [2016-AAAI] Reading Scene Text in Deep Convolutional Sequences [`paper`](http://whuang.org/papers/phe2016_aaai.pdf)
- [2016-TIP] Text-Attentional Convolutional Neural Networks for Scene Text Detection [`paper`](http://whuang.org/papers/the2016_tip.pdf)
- [2014-ECCV] Robust Scene Text Detection with Convolution Neural Network Induced MSER Trees [`paper`](http://www.whuang.org/papers/whuang2014_eccv.pdf)

### Media and Communication Lab, HUST
- [2016-CVPR] Robust scene text recognition with automatic rectification [`paper`](http://arxiv.org/pdf/1603.03915v2.pdf)
- [2016-CVPR] Multi-oriented text detection with fully convolutional networks    [`paper`](http://mclab.eic.hust.edu.cn/UpLoadFiles/Papers/TextDectionFCN_CVPR16.pdf)
- [2015-CoRR] An End-to-End Trainable Neural Network for Image-based Sequence Recognition and Its Application to Scene Text Recognition [`paper`](http://arxiv.org/pdf/1507.05717v1.pdf) [`code`](http://mclab.eic.hust.edu.cn/~xbai/CRNN/crnn_code.zip) [`github`](https://github.com/bgshih/crnn)

### AI Lab, Stanford
- [2012-ICPR, [Wang](http://cs.stanford.edu/people/twangcat/)] End-to-End Text Recognition with Convolutional Neural Networks [`paper`](http://www.cs.stanford.edu/~acoates/papers/wangwucoatesng_icpr2012.pdf) [`code`](http://cs.stanford.edu/people/twangcat/ICPR2012_code/SceneTextCNN_demo.tar) [`SVHN Dataset`](http://ufldl.stanford.edu/housenumbers/)
- [2012-PhD thesis, [David Wu](https://crypto.stanford.edu/people/dwu4/)] End-to-End Text Recognition with Convolutional Neural Networks [`paper`](http://cs.stanford.edu/people/dwu4/HonorThesis.pdf)

### Others
- [2014-TPAMI] Word Spotting and Recognition with Embedded Attributes	 [`paper`](http://www.cvc.uab.es/~afornes/publi/journals/2014_PAMI_Almazan.pdf) [`homepage`](http://www.cvc.uab.es/~almazan/index/projects/words-att/index.html) [`code`](https://github.com/almazan/watts)
- [2016-CVPR] Recursive Recurrent Nets with Attention Modeling for OCR in the Wild [`paper`](http://arxiv.org/pdf/1603.03101v1.pdf)
- [2016-arXiv] COCO-Text: Dataset and Benchmark for Text Detection and Recognition in Natural Images [`paper`](http://vision.cornell.edu/se3/wp-content/uploads/2016/01/1601.07140v1.pdf)
- [2016-arXiv] DeepText:A Unified Framework for Text Proposal Generation and Text Detection in Natural Images [`paper`](http://arxiv.org/abs/1605.07314)
- [2015 ICDAR] Object Proposals for Text Extraction in the Wild [`paper`](http://arxiv.org/abs/1509.02317) [`code`](https://github.com/lluisgomez/TextProposals)

## Datasets
- [`COCO-Text (Computer Vision Group, Cornell)`](http://vision.cornell.edu/se3/coco-text/)   `2016`
  - 63,686 images, 173,589 text instances, 3 fine-grained text attributes.
  - Task: text location and recognition
  - [`COCO-Text API`](https://github.com/andreasveit/coco-text)

- [`Synthetic Word Dataset (Oxford, VGG)`](http://www.robots.ox.ac.uk/~vgg/data/text/)   `2014`
  - 9 million images covering 90k English words
  - Task: text recognition, segmantation
  - [`download`](http://www.robots.ox.ac.uk/~vgg/data/text/mjsynth.tar.gz)

- [`IIIT 5K-Words`](http://cvit.iiit.ac.in/projects/SceneTextUnderstanding/IIIT5K.html)   `2012`
  - 5000 images from Scene Texts and born-digital (2k training and 3k testing images)
  - Each image is a cropped word image of scene text with case-insensitive labels
  - Task: text recognition
  - [`download`](http://cvit.iiit.ac.in/projects/SceneTextUnderstanding/IIIT5K-Word_V3.0.tar.gz)

- [`StanfordSynth(Stanford, AI Group)`](http://cs.stanford.edu/people/twangcat/#research)   `2012`
  - Small single-character images of 62 characters (0-9, a-z, A-Z)
  - Task: text recognition
  - [`download`](http://cs.stanford.edu/people/twangcat/ICPR2012_code/syntheticData.tar)

- [`MSRA Text Detection 500 Database (MSRA-TD500)`](http://www.iapr-tc11.org/mediawiki/index.php/MSRA_Text_Detection_500_Database_(MSRA-TD500))   `2012`
  - 500 natural images(resolutions of the images vary from 1296x864 to 1920x1280)
  - Chinese, English or mixture of both
  - Task: text detection

- [`Street View Text (SVT)`](http://tc11.cvc.uab.es/datasets/SVT_1)   `2010`
  - 350 high resolution images (average size 1260 × 860) (100 images for training and 250 images for testing)
  - Only word level bounding boxes are provided with case-insensitive labels
  - Task: text location

- [`KAIST Scene_Text Database`](http://www.iapr-tc11.org/mediawiki/index.php/KAIST_Scene_Text_Database)   `2010`
  - 3000 images of indoor and outdoor scenes containing text
  - Korean, English (Number), and Mixed (Korean + English + Number)
  - Task: text location, segmantation and recognition

- [`Chars74k`](http://www.ee.surrey.ac.uk/CVSSP/demos/chars74k/)   `2009`
  - Over 74K images from natural images, as well as a set of synthetically generated characters 
  - Small single-character images of 62 characters (0-9, a-z, A-Z)
  - Task: text recognition



- `ICDAR Benchmark Datasets`

|Dataset| Discription | Competition Paper |
|---|---|----
|[ICDAR 2015](http://rrc.cvc.uab.es/)| 1000 training images and 500 testing images|`paper`  [![link](https://www.lds.org/bc/content/shared/content/images/gospel-library/manual/10735/paper-icon_1150845_tmb.jpg)](http://rrc.cvc.uab.es/files/Robust-Reading-Competition-Karatzas.pdf)|
|[ICDAR 2013](http://dagdata.cvc.uab.es/icdar2013competition/)| 229 training images and 233 testing images |`paper`  [![link](https://www.lds.org/bc/content/shared/content/images/gospel-library/manual/10735/paper-icon_1150845_tmb.jpg)](http://dagdata.cvc.uab.es/icdar2013competition/files/icdar2013_competition_report.pdf)|
|[ICDAR 2011](http://robustreading.opendfki.de/trac/)| 229 training images and 255 testing images |`paper`  [![link](https://www.lds.org/bc/content/shared/content/images/gospel-library/manual/10735/paper-icon_1150845_tmb.jpg)](http://www.iapr-tc11.org/archive/icdar2011/fileup/PDF/4520b491.pdf)|
|[ICDAR 2005](http://www.iapr-tc11.org/mediawiki/index.php/ICDAR_2005_Robust_Reading_Competitions)| 1001 training images and 489 testing images |`paper`  [![link](https://www.lds.org/bc/content/shared/content/images/gospel-library/manual/10735/paper-icon_1150845_tmb.jpg)](http://www.academia.edu/download/30700479/10.1.1.96.4332.pdf)|
|[ICDAR 2003](http://www.iapr-tc11.org/mediawiki/index.php/ICDAR_2003_Robust_Reading_Competitions)| 181 training images and 251 testing images(word level and character level) |`paper`  [![link](https://www.lds.org/bc/content/shared/content/images/gospel-library/manual/10735/paper-icon_1150845_tmb.jpg)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.332.3461&rep=rep1&type=pdf)|



## Blogs

- [Scene Text Detection with OpenCV 3](http://docs.opencv.org/3.0-beta/modules/text/doc/erfilter.html)
- [Handwritten numbers detection and recognition](https://medium.com/@o.kroeger/recognize-your-handwritten-numbers-3f007cbe46ff#.8hg7vl6mo)
- [Applying OCR Technology for Receipt Recognition](http://rnd.azoft.com/applying-ocr-technology-receipt-recognition/)
- [Convolutional Neural Networks for Object(Car License) Detection](http://rnd.azoft.com/convolutional-neural-networks-object-detection/)
- [Extracting text from an image using Ocropus](http://www.danvk.org/2015/01/09/extracting-text-from-an-image-using-ocropus.html)
- [Number plate recognition with Tensorflow](http://matthewearl.github.io/2016/05/06/cnn-anpr/) [`github`](https://github.com/matthewearl/deep-anpr)
- [Using deep learning to break a Captcha system](https://deepmlblog.wordpress.com/2016/01/03/how-to-break-a-captcha-system/) [`report`](http://web.stanford.edu/~jurafsky/burszstein_2010_captcha.pdf) [`github`](https://github.com/arunpatala/captcha)
- [Breaking reddit captcha with 96% accuracy](https://deepmlblog.wordpress.com/2016/01/05/breaking-reddit-captcha-with-96-accuracy/) [`github`](https://github.com/arunpatala/reddit.captcha)
