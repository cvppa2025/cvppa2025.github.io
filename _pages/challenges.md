---
layout: single
title: Challenges
permalink: /challenges/
sidebar:
    nav: "sidebar"
---

This year, we are running the following challenges:
- [Shape Completion and Reconstruction of Sweet Peppers Challenge](#shape-completion-and-reconstruction-of-sweet-peppers-challenge)
- [Multi-object Tracking of Sweet Peppers Challenge](#multi-object-tracking-of-sweet-peppers-challenge)


For participating in the competitions, you have to provide your predictions via the respective CodaLab competitions (details below).

After conclusion of the competitions (as indicated on CodaLab), Challenge Organisers will notify the CodaLab participants with at least a single submission. 
Every participant can provide a short technical report (please follow the instructrions in the [Call for Paper](/cfp/#challenge-technical-report) page) of their technical solution, which will be published on the workshop website.

The top-3 ranked participants who provide a technical report will get a certificate and can present their approach at the workshop (if the participants attend ECCV). 
Details of the submission process will be provided via email after conclusion of the competitions.

During the workshop, we will announce the winners and plan to award a certificate for winning entries that have provided a short description of their technical approach.

[Feng Chen](mailto:feng.chen@ed.ac.uk) is the challenges lead. Please contact with questions and/or concerns. Please also contact the competition organisers with specific questions regarding the competition.


## Shape Completion and Reconstruction of Sweet Peppers Challenge

| **Challenge Organisers** |
| [Federico Magistri](http://www.ipb.uni-bonn.de/people/federico-magistri/index.html) | Photogrammetry and Robotics Lab, Center for Robotics, University of Bonn | [Email](mailto:federico.magistri@igg.uni-bonn.de) |
| [Jens Behley](http://jbehley.github.io) | Photogrammetry and Robotics Lab, Center for Robotics, University of Bonn | [Email](mailto:jens.behley@igg.uni-bonn.de) |

In this challenge, you are tasked to provide a complete 3D mesh given a partial RGB-D observation of sweet peppers. You are provided with RGB-D frames with corresponding instance masks and poses where sweet peppers are only partially visible. We ask the participants to predict a 3D mesh representing the complete fruit. Obtaining such information is a fundamental building block for agricultural autonomous systems across different downstream tasks, such as harvesting and yield estimation.

More details about this challenge can be found in our <a href="https://arxiv.org/abs/2407.13304">technical report</a> (<a href="https://arxiv.org/pdf/2407.13304">PDF</a>)  and on our dataset website at [https://www.ipb.uni-bonn.de/data/shape_completion](https://www.ipb.uni-bonn.de/data/shape_completion).

For participating in this challenge, we setup a CodaLab competition: [https://codalab.lisn.upsaclay.fr/competitions/18987](https://codalab.lisn.upsaclay.fr/competitions/18987)

Please contact [Federico Magistri](mailto:federico.magistri@uni-bonn.de) if you have questions about this competition and concerns regarding the submission on CodaLab.


## Multi-object Tracking of Sweet Peppers Challenge

| **Challenge Organisers** |
| [Chris McCool](http://agrobotics.uni-bonn.de/chris-mccool/index.html) | Institute of Agricultural Engineering, University of Bonn, Germany | [Email](mailto:cmccool@uni-bonn.de) |
| [Esra Güçlü](http://agrobotics.uni-bonn.de/esra-guclu/index.html) | Institute of Agricultural Engineering, University of Bonn, Germany | [Email](mailto:egueclue@uni-bonn.de) |

In this challenge, you need to make use of weakly labelled data to perform detection and tracking of small objects in a cluttered agricultural environment. With this information we can obtain the current state of the field (glasshouse) as well as the amount of harvestable crop, this is because it also includes a coarse estimate of the ripeness of the crop.  The weak labels that we provide are instance-based semantic segmentation masks along with an estimated unique ID for each instance in the short video sequences. 

For more information and for participating in the Codalab competition, please refer to [https://codalab.lisn.upsaclay.fr/competitions/19278](https://codalab.lisn.upsaclay.fr/competitions/19278). For more information about the data, see: [https://codalab.lisn.upsaclay.fr/competitions/19278#participate-get_data](https://codalab.lisn.upsaclay.fr/competitions/19278#participate-get_data).


Please contact [Esra Güçlü](mailto:egueclue@uni-bonn.de) if you have specific questions about this competition.
