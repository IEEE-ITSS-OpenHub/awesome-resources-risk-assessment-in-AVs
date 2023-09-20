
# Awesome resources for risk assessment in Automated vehicles
![Awesome Resources](https://img.shields.io/badge/Awesome-Resources-green)
 ![Version](https://img.shields.io/badge/Version-2.0-ff69b4.svg) ![LastUpdated](https://img.shields.io/badge/LastUpdated-2023.08-lightgrey.svg) ![Topic](https://img.shields.io/badge/Topic-risk--assessment-yellow.svg?logo=github)

The rapid advancement of automated vehicle technology has brought with it a host of challenges, one of the most critical being risk assessment. Accurately assessing the risks associated with automated vehicles is crucial for ensuring the safety of passengers, pedestrians, and other road users. This repository is a curated collection of resources, including research papers, datasets, and projects, that aims to provide researchers, practitioners, and enthusiasts with valuable insights and tools to advance the field of risk assessment in automated vehicles. Whether you are a seasoned researcher or just starting in the field, this repository is a valuable starting point to understand the current landscape, challenges, and future directions of risk assessment in automated vehicles.

**Maintainers**: [**Zirui Li**](https://lzrbit.github.io) (TU Dresden, Beijing Institute of Technology)

## Index

- [New updates](#new-updates)
- [Online Perceived Risk Project](#online-perceived-risk-project)
- [Research papers collection](#research-papers-collection)
- [Dataset collection](#dataset-collection)


## New updates

- **2023.09.02** Update for the Online Preceived Risk project.
- **2023.09.01** Welcome to this project. Feel free to pull request and submit issues.


## Online Perceived Risk Project
This project is funded by TU Delft and TU Dresden. Maintainers: [**Xiaolin He**](https://www.tudelft.nl/staff/x.he-2/?cHash=2fbe05085aeb77871f1e94aa863ab055), [**Zirui Li**](https://lzrbit.github.io),  [**Xinwei Wang**](https://www.sems.qmul.ac.uk/staff/x.wang), [**Riender Happee**](https://www.tudelft.nl/staff/r.happee/?cHash=9843426844a532fc7285bdaa4f6e92b0), [**Meng Wang**](https://tu-dresden.de/bu/verkehr/vis/vpa/die-professur/head-of-chair).
### Goals
- A novel method to collect perceived risk ratings and generate continuous perceived risk data.
- Give recommendations on the parameters of typical perceived risk models.
- A new assessment method of different perceived risk models.
- perceived risk dynamics in various scenarios.
- A perceived risk dataset.

### Questionnaire
The online questionnaire was developed using the Qualtrics XM. The whole questionnaire will take around 30 mins. Welcome to contribute as the participants of questionnaires. Here is the [link](TBD).


## Research papers collection

### Survey

### Subjective risk assessment
<!-- [[Paper]]() -->
<!-- [[Code]]() -->
- A multimodal psychological, physiological and behavioural dataset for human emotions in driving tasks. Nature Scientific Data. [[Paper]](https://www.nature.com/articles/s41597-022-01557-2)[[Code]](https://www.nature.com/articles/s41597-022-01557-2#Sec25)
- The Moral Machine experiment, Nature.  [[Paper]](https://www.nature.com/articles/s41586-018-0637-6)[[Code]](https://osf.io/3hvt2/?view_only=4bb49492edee4a8eb1758552a362a2cf)


### Objective risk assessment
- Differentiable Integrated Motion Prediction and Planning with Learnable Cost Function for Autonomous Driving, IEEE T-NNLS. [[Paper]](https://ieeexplore.ieee.org/abstract/document/10154577)[[Code]](https://github.com/MCZhi/DIPP)


## Dataset collection

### Vehicles

|                           Dataset                            |            Agents            |         Scenarios         |        Sensors         |
| :----------------------------------------------------------: | :--------------------------: | :-----------------------: | :--------------------: |
|      [Waymo Open Dataset](https://waymo.com/open/)           | vehicles / cyclists / people |				urban / highway     |	LiDAR / camera / Radar |
|      [Argoverse](https://www.argoverse.org/)           | vehicles / cyclists / people |				urban / highway     |	LiDAR / camera / Radar |
|            [nuScenes](https://www.nuscenes.org/)             |           vehicles           |           urban           | camera / LiDAR / Radar |
|           [highD](https://www.highd-dataset.com/)            |           vehicles           |          highway          |         camera         |
|           [inD](https://www.ind-dataset.com/)            |           vehicles           |          highway          |         camera         |
|           [roundD](https://www.round-dataset.com/)            |           vehicles           |          highway          |         camera         |
|          [BDD100k](https://bdd-data.berkeley.edu/)           | vehicles / cyclists / people |      highway / urban      |         camera         |
|        [KITTI](http://www.cvlibs.net/datasets/kitti/)        | vehicles / cyclists / people |   highway / rural areas   |     camera / LiDAR     |
| [NGSIM](https://ops.fhwa.dot.gov/trafficanalysistools/ngsim.htm) |           vehicles           |          highway          |         camera         |
|      [INTERACTION](http://www.interaction-dataset.com/)      | vehicles / cyclists / people | roundabout / intersection |     camera     |
| [Cyclists](http://www.gavrila.net/Datasets/Daimler_Pedestrian_Benchmark_D/Tsinghua-Daimler_Cyclist_Detec/tsinghua-daimler_cyclist_detec.html) |           cyclists           |           urban           |         camera         |
| [Apolloscapes](http://apolloscape.auto/?source=post_page---------------------------) | vehicles / cyclists / people |           urban           |         camera         |
| [Udacity](https://github.com/udacity/self-driving-car/tree/master/datasets) |           vehicles           |           urban           |         camera         |
|      [Cityscapes](https://www.cityscapes-dataset.com/)       |       vehicles / people       |           urban           |         camera         |
| [Stanford Drone](http://cvgl.stanford.edu/projects/uav_data/) | vehicles / cyclists / people |           urban           |         camera         |
|           [Argoverse](https://www.argoverse.org/)            |      vehicles / people       |           urban           |     camera / LiDAR     |
| [TRAF](https://gamma.umd.edu/researchdirections/autonomousdriving/trafdataset)            |      vehicles / buses / cyclists / bikes / people / animals       |           urban           |     camera      |
|[Aschaffenburg Pose Dataset](https://doi.org/10.5281/zenodo.5724486)               |    cyclists / people     |           urban           |         camera         |
### Pedestrians
|                           Dataset                            |           Agents            |       Scenarios       |    Sensors     |
| :----------------------------------------------------------: | :-------------------------: | :-------------------: | :------------: |
| [UCY](https://graphics.cs.ucy.ac.cy/research/downloads/crowd-data) |           people           |    zara / students    |     camera     |
|       [ETH (ICCV09)](https://icu.ee.ethz.ch/research/datsets.html)       |           people           |         urban         |     camera     |
|              [VIRAT](http://www.viratdata.org/)              |      people / vehicles      |         urban         |     camera     |
|        [KITTI](http://www.cvlibs.net/datasets/kitti/)        | vehicles / cyclists / people | highway / rural areas | camera / LiDAR |
|     [ATC](https://irc.atr.jp/crest2010_HRI/ATC_dataset/)     |           people           |    shopping center    |  Range sensor  |
| [Daimler](http://www.gavrila.net/Datasets/Daimler_Pedestrian_Benchmark_D/daimler_pedestrian_benchmark_d.html) |           people           |  from moving vehicle  |     camera     |
| [Central Station](http://www.ee.cuhk.edu.hk/~xgwang/grandcentral.html) |           people           |    inside station    |     camera     |
| [Town Center](http://www.robots.ox.ac.uk/ActiveVision/Research/Projects/2009bbenfold_headpose/project.html#datasets) |           people           |     urban street     |     camera     |
| [Edinburgh](http://homepages.inf.ed.ac.uk/rbf/FORUMTRACKING/) |           people           |         urban         |     camera     |
|   [Cityscapes](https://www.cityscapes-dataset.com/login/)    |      vehicles / people      |         urban         |     camera     |
|           [Argoverse](https://www.argoverse.org/)            |      vehicles / people      |         urban         | camera / LiDAR |
| [Stanford Drone](http://cvgl.stanford.edu/projects/uav_data/) | vehicles / cyclists / people |         urban         |     camera     |
|           [TrajNet](http://trajnet.stanford.edu/)            |           people           |         urban         |     camera     |
|           [PIE](http://data.nvision2.eecs.yorku.ca/PIE_dataset/)            |           people           |         urban         |     camera     |
|           [ForkingPaths](https://next.cs.cmu.edu/multiverse/index.html)            |           people           |         urban / simulation         |     camera     |
|           [TrajNet++](https://www.aicrowd.com/challenges/trajnet-a-trajectory-forecasting-challenge)            |           people           |         urban         |     camera     |
|[Aschaffenburg Pose Dataset](https://doi.org/10.5281/zenodo.5724486)               |    cyclists / people    |           urban           |         camera         |

