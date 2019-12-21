# SimBA
[![License: LGPL v3](https://img.shields.io/badge/License-LGPL%20v3-pink.svg)](https://www.gnu.org/licenses/lgpl-3.0)
[![Gitter chat](https://badges.gitter.im/USER/REPO.png)](https://gitter.im/SimBA-Resource/community)
[![Download: Weights](https://img.shields.io/badge/Download-Weights-orange.svg)](https://osf.io/5t4y9/)


Several excellent computational frameworks exist that enable high-throughput, consistent, and unbiased scoring of freely moving animals. We attempt to distribute a plug-and play pipeline and system that enabled users in preclinical social neuroscience to feed in pose-estimation data and images of variables qualities to automatically segment and analyse behavior. SimBA does not require computer science and programing experience, and SimBA is optimized for any video recording quality. We may be able to provide support and advice for specific use instances, especially if it benefits multiple users and advances the scope of SimBA. Feel free to post issues and bugs here or contact us directly and we'll work on squashing them as they appear.

- The SimBA pipeline requires no programing knowledge 
- Specialized commercial or custom-made equipment is not required
- Extensive annotations are not required
- The pipeline is flexible and can be used to create and validate classifiers for different behaviors and environments 

SimBA currently does not support analysis of video recordings of multiple similarly coat-colored animals, and is vaidated using videos filmed from above at 90° angle using pose-estimation data from 8 body parts per animal. However we and others are working hard on getting multi-animal tracking of similarly coat colored animals going, and multiple recording angles supported! :muscle: 

#### Mouse
![](https://github.com/sgoldenlab/simba/blob/master/images/mouse_videos.gif)

#### Rat
![](https://github.com/sgoldenlab/simba/blob/master/images/rat_videos.gif)

#### SimBA GUI workflow
![](https://github.com/sgoldenlab/simba/blob/master/images/SimBA_tkinter.png)


## Pipeline 👷
![](https://github.com/sgoldenlab/simba/blob/master/images/overallflow.PNG)

### Step 1: [Pre-process videos](docs/tutorial_process_videos.md) 

### Step 2: [Create tracking model](docs/Tutorial_DLC.md) 

### Step 3: [Building classfier(s)](docs/tutorial.md) 

### Step 4: [Analysis/Visualization](https://github.com/sgoldenlab/simba/blob/master/docs/tutorial.md#step-9-analyze-machine-results)

## Installation ⚙️

- [Install SimBA](docs/installation.md)

## Tutorial 📚


- [Process video using tools](docs/Tutorial_tools.md) 🔨
- [Batch pre-process video](docs/tutorial_process_videos.md) 🏭
- [Using DeepLabCut through SimBA](docs/Tutorial_DLC.md) 📗
- [SimBA](docs/tutorial.md) 📘
- [Label behavior](docs/labelling_aggression_tutorial.md) 🏷️



## Resource 💾

### Models
Below is a link to download trained models to apply it on your dataset
- [Random forest models](https://osf.io/d69jt/) 🌲

### SimBA visualization examples
- [YouTube playlist](https://www.youtube.com/playlist?list=PLi5Vwf0hhy1R6NDQJ3U28MOUJPfl2YWYl) 📺

### Labelled images
- [DeepLabCut labelled images](https://osf.io/uhjzf/) 📷

### Tracking weights
- [DeepLabCut tracking weights](https://osf.io/5t4y9/) 🏋️

### Golden Lab webpage
- [Sam Golden Lab UW](https://goldenneurolab.com/) 🧪🧫🐁

## License 📃
This project is licensed under the GNU Lesser General Public License v3.0. Note that the software is provided "as is", without warranty of any kind, express or implied. If you use the code or data, please cite us :)

## References 📜

[![Foo](https://github.com/sgoldenlab/simba/blob/master/images/cos_center_logo_small.original.png)](https://osf.io/d69jt/) [![Foo](https://github.com/sgoldenlab/simba/blob/master/images/twitter.png)](https://twitter.com/GoldenNeuron?s=20)

## Contributors 🤼
- [Simon Nilsson](https://github.com/sronilsson)
- [Jia Jie Choong](https://github.com/inoejj)
- [Sophia Hwang](https://github.com/sophihwang26)
- [Xiaoyu Tong](https://github.com/Xiaoyu-Tong)


